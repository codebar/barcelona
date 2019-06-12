# Monthly meetings

## Objective

As a group we had agreed to be allowed to work on specific initiatives in small groups (which can also include people outside the organizers group). The objective of these regular meetings is to synchronize the progress of the initiatives between the organizers. Also it is the place to present new initiatives and identify other organizers that would like to contribute to it. Last but not least, it's the place to veto initiatives that we consider not aligned with codebar mission or current priorities.

## Attendance
These meetings are part of the responsibilities of being an organizers and should be respected as such. Attendance is important.

**Schedule**: First Friday of each month.

# Meeting preparation
The following bullets describe the preparation that **must happen before** each monthly meeting:
* **Define facilitator:** This person is in charge of following up the preparation of the meeting and to moderate the meeting itself. It is recommended that the facilitator is defined at the end of the previous meeting. At the current team size, it's expected that each one is facilitator twice a year.
* **Check availability**: One week before the meeting, the facilitator should check availability for the upcoming meeting. If any of the organisers of the team can not make it on the scheduled day (neither physically nor remotely), the possibility of having the meeting on a different day could be assessed. An alternative day can be chosen if the attendance would result higher **as long as the participants that could make it in the originally scheduled day can still make it in the new proposed date**. Should there not be any date in the week where the attendance would result higher, then the meeting should take place with the available participants. The facilitator is in charge of coordinating any rescheduling.
    * It is still to be defined the minimum attendance expected from organizers (75% sounds like a fair value, but this has not been discussed yet)
* **Share new initiatives**: In order to allow the facilitator to correctly moderate the meeting, the organizers that want to present new ideas (see more details below), should share them in advance with the facilitator. Should the facilitator think that there are already too many ideas to discuss in the available 30', he/she should warn the organizer that the idea may need to be deferred to the following meeting. Ideas should be discussed in a FIFO approach. The idea should only be shared with the facilitator to avoid early discussions outside the monthly meeting. The facilitator should publish the agenda in github before the meeting so everyone knows what will be discussed. See below _how to do this in Github_ for detailed instructions.
* **Foresee your absence**: If you know you'll not be able to participate, respect the participants by sharing in advance the status of your ongoing initiatives. The facilitator can share the status for you in the meeting. Absent organizers can not present _new initiatives_.

# Meeting agenda (1hr)

## Ongoing activities (30')
The first half of the meeting is for initiatives already discusses in previous monthly meetings. Each organizer should share:
  * What are the relevant latests accomplishments for the initiative?
  * What is blocking the initiative to move forward?
  * What are the planned next steps?

This block should last 30 minutes maximum. This means about 5 minutes per organizer (for our current size).

## New initiatives (30')
The second half of the meeting is to present ideas for new initiatives. Before presenting any idea, the idea owner should make sure that it is align with codebar mission statement:

> Our goal is to enable underrepresented people to learn programming in a safe and collaborative environment and expand their career opportunities. To achieve this we run free regular workshops, regular one-off events and try to create opportunities for our students making technology and coding more accessible.

Initiatives can be vetoed during the monthly meeting if any of the present organizers considers that they are not aligned with the mission above.

If the idea is accepted (not vetoed), its implementation is to be planned outside the monthly meetings. Organizers interested in collaborate with the idea should be identified at this stage.

Each initiative must have an owner who will be responsible for updating the rest of the team about the progress in the monthly meetings. It has yet to be defined a place were the team can register initiatives that are agreed but their implementation should be deferred to a later moment in time (_"Initiatives backlog"_).

# Meeting minutes
In order to share news with absent participants, to record activities and share them easily with new organizers and to make sure the initiatives were understood, the facilitator should create a Pull Request with the minutes of the meeting under directory
```
/minutes/yyyy-mm.md
```
Where _yyyy_ is the year and _mm_ is the month. Using the previous month minutes as template is advised. A template exists understood
```
/minutes/2019-00-Example.md
```

# How to do this in Git

In order to be able to upload the agenda (and the minutes after the meeting), you need to clone the Barcelona chapter git repository. To do so open a command line and run
```
git clone https://github.com/codebar/barcelona.git barcelona
```

Then enter the just created copy of the repo by typing
```
cd barcelona
```
You will now be in `master` branch. You can check that, by typing the following command and looking for the one with a `*`
```
git branch
```

Before moving forward to the next steps, make sure that the file with the minutes from the previous meeting is present. If not, there should be a pull request pending to be merged. Once it is merged, you can do `git pull` to get the latests changes into your local copy.

Now you need to create a new branch, to do so type
```
git checkout -b monthly-meeting-yyyy-mm
```
Make sure you replace `yyyy-mm` by the year and the month. What you put after `-b`is the name of the branch.

Now you can create your file `yyyy-mm-Minutes.md`. You can also copy `2019-00-Example.md` as inspiration, or the one from previous meeting.

Edit the file until you are happy with it. Don't forget to include as *ongoing initiatives* all those that were not closed in previous meeting. Then _stage_ it (mark it to be included in your next commit), with the following command
```
git add yyyy-mm-Minutes.md
```
You must do this from the folder where the file is (or use a complete path to it). If you type `git status` before the above command you can also get instructions.

If you are ready to commit and push, you can create the commit by
```
git commit -m 'Add base agenda for yyyy-mm'
```
Feel free to change the message if you want something else there. If it's the first time you do a commit in Git you will be requested to add your user and email. Follow the instructions in the screen to do so. Once that is solved, you will need to do the `commit` again as before.

Now it's time to push it. To do so you could use the following command
```
git push --set-upstream origin monthly-meeting-yyyy-mm
```
In this command `monthly-meeting-yyyy-mm` is the name of the branch in the remote repository. As the branch you created in your local repository does not exists in the remote repository you must specify it with the `--set-upstream` parameter. The subsequent push don't need it, just `git push` will do.

This is all you need to upload the draft agenda. You can check it by going to Github web and navigating to the just created branch on the repository.

**After the meeting**, get back to your local repository folder, and pull any possible change that others may have pushed to the branch using
```
git pull
```

Then do the updates to the minutes file, and commit/push by doing:
```
git add yyyy-mm-Minutes.md
git commit -m 'Add minutes for meeting yyyy-mm'
git push
```
Note that this time the `--set-upstream` is not needed anymore.
