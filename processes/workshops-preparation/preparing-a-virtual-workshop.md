# Preparing a virtual workshop



## Objective
This procedure describe the steps needed to set up a codebar virtual workshop in the Barcelona chapter.

## Overview
The process of preparing a workshop in Barcelona chapter can be divided in 3 blocks. Each of this blocks is further detailed below in this article. They are:

* **Before the workshop:** This part of the process consists on defining workshop dates, adding the date the shared google calendar, finding a sponsor if applicable.



* **Preparing a workshop:** Creating the event in the codebar.io page, announcing the event in the slack channel, sending out the mail invitations, defining the MC, pairing support and door person roles, and monitoring that enough coaches and students have signed up before the workshop begins.

* **Post event actions:** This part of the process consist of thanking sponsors if there are any, publishing the pictures in social media and engaging a possible new date.

## Tool support
Several workshop can be *under preparation* at the same time, hence, to facilitate a quick view on the status of each workshop preparation we decided to use a [Trello board](https://trello.com/b/ccJETYgH/codebario-barcelona).

In this board, you'll find **one card per workshop** transitioning through different columns. You will see that there are templates that you can use to create in-person and virtual events. Each column title represents the state of the cards in it. Along this article, the transitions from column to column will be explained.

# Before the workshop

## Defining the dates
Barcelona chapter normally has the workshops on **Thursdays**. If needed, exceptions are allowed, but when possible we prefer to keep Thursdays since our students, coaches, and hosts are used to that day. If you are thinking of having a workshop on a different date, check that there will be enough organizers available to help you during the event.

**In Trello:** To define a new workshop date, copy the card named `Virtual-Event yyyy.mm.dd` from column `TEMPLATE`. You will find a `Copy` button inside the card. When coping it, make sure you rename it replacing `yyyy.mm.dd` by the correct date. Also make sure you keep the _checklists_, the _labels_ and the _attachments_. The new card should be placed in column `Available dates - No host yet`.

**In Google Calendar:** Once you have defined a workshop date, make sure that you add the event, along with the zoom call details to the shared organizer's google calendar.

## Finding a sponsor
Virtual workshops can be sponsored. If any companies are interested in making a financial contribution to codebar to help us cover running costs please get them in touch with us [hello@codebar.io](hello@codebar.io).


### Contacting a sponsor
TBD


**In Trello:** When you offer a date(s) to a possible host, move the card(s) to `Date proposed - Waiting host confirmation`, to avoid offering the same date(s) to other hosts.
* If the **host does not accept** the date, move the card back to `Available dates - No host yet`.

* If the **host accepts** the date, set up the host logo as **card cover**, and move the card to `Host OK - No owner defined yet`.

## Preparing a workshop

### Owner definition

To ensure everyone has an equal opportunity to participate at every level of the creation of events it is key that everyone can _'take the lead'_ of an event. One way of fostering such opportunity is to have each event have an _'owner'_. By identifying a single person as the event owner, everyone, regardless of previous experience, temperament, tendencies or personality, etc., will have an equal opportunity to participate.

This does not mean that the _'owner'_ has to do everything, though they can. Instead they have to check that each activity has been done and if necessary, bring the organizer's attention to the fact that things have not yet been completed. This will allow each and every organizer to participate in the process of creating events and communicating with hosts, not simply those who are accustomed to taking the lead.

To define the _'owner'_ TBD. If no-one volunteers, the organizer that has not owned an event for longer period will be assigned as owner.

**In Trello:** Once the owner is assigned, move the card to `Owner preparing workshop`, tag the person in the card description, and assign the card to this person.

### Publishing the workshop

### In codebar.io

This is the first platform where we need to upload the event. To do so, follow the next steps:

1. **Create a New Host:** If this is the first time the sponsor hosts us, you need to add it to the platform. Otherwise jump to 2.
   1. Login to codebar.io (you must have admin rights for the channel)
   2. Click on **Menu** > **New Sponsor**
   3. Fill in the data requested. You'll need a name, logo, address, and capacity (students and coaches separately).
   4. To confirm the sponsor was correctly added you can go to https://codebar.io/sponsors and search for it.
2. **Create a New Workshop:** To do so:
   1. Login to codebar.io (you must have admin rights for the channel)
   2. Click on **Admin Menu** > **New Workshop** and fill in the requested data.
   3. **Virtual workshop check box:** Make sure that you select the checkbox so that the system knows that it is a virtual workshop.
   4. **Slack channel:** You will need to create a slack channel dedicated specifically for the virtual workshop. In slack, click the plus icon next to channels to create the channel. You can use the following convention to name the channel

   virtual-barcelona-2021-apr-08.

   Once you have created the channel, right click on the channel to get the link and add it to the form.  
   5. **Set the number of students and coaches for the workshop:** Typically we set the number to 10 students and 10 coaches. We can manually change the number of allowed students if more coaches sign up. Typically we check how many people have signed up 2-3 days before the workshop begins. If there is a long waitlist of students, or if we are short on coaches, then we ask in the slack channel or through our own networks for more coaches to join.  
   6. **Chapter:** Barcelona
   7. **Start time:** 18:30
   8. **End time:** 20:40
   9. **Host:** For virtual workshops, we don’t have a host
   10. **Sponsor:** Virtual workshops can be sponsored. If any companies are interested in making a financial contribution to codebar to help us cover running costs please get them in touch with us [hello@codebar.io](hello@codebar.io).
   11. **Default description:** Here is a sample text that you can use. The only things that need to be modified are the date and the slack channel that we will use for the workshop. The description field supports HTML, that is why the text is written with the HTML tags

   ```
   For the virtual workshop, we will use Zoom. Download <a href="https://zoom.us/download" target="_blank">zoom</a> ahead of time .
We will send the zoom login details <strong> at 6 pm on
Add Date Here </strong>, via the following <a href="Add Slack Channel Link" target="_blank">slack channel</a>.
<br>
Slack is the main place we use for updates and announcements, make sure that you have signed up and check the channel, especially on the day of the workshop.
<br>
If you cannot attend the workshop, please let us know before noon on the day of the workshop. We usually have a waitlist of students and want to give those on the waitlist a chance to attend.
<br>
It is important to keep your RSVP updated because it helps us properly pair students and coaches. To avoid spammers entering the zoom call, everyone will be in a waiting room before the call starts.
<br>
If you have any issues drop us a message on slack. Welcome to the workshop and we look forward to seeing you soon!

   ```
   12. **'Rsvp open local date'** and **'Rsvp open local time'** should be set to the day after the preceding workshop at 12:00. Once this date is reached, the platform will automatically start allowing RSVPs from people that navigate to the workshop page. **No mail invitations are sent at this date, or when clicking Save**.
   4. **Leave invitable unchecked**: When checked, people can RSVP to the event and mass mails can be sent. Experience has showed us that if more than one event has the RSVP open at the same time, people get confused and don't know which event they RSVP'd to. To avoid this, we agreed not to mark the event as **invitable** until **after** the preceding workshop has been completed.
   <kbd>![Creating a workshop in codebar.io](images/codebar-virtual.png?raw=true "Creating a worshop in codebar.io")</kbd>
   5. **Save:** If successful, you should see a blue line with the text ```codebar: The workshop has been created.```

3. **Announce it in Slack:** Once the workshop is _invitable_ (meaning that it is the next upcoming one), announce it in #barcelona-chapter. The idea is to gives a little advantage to the Barcelona community. Students and participants enrolled in the channel will have prior notice about the open RSVP in the channel. Make sure that you copy the correct link to the event (it **must not** have the word admin on it. The best way to obtain the link is by navigating from the home page > Events). Example text:
```
Hello channel: RSVP for next week (24th/January) workshop is now open. #Thoughtworks will sponsor us. :parrot:
https://codebar.io/workshops/1069 Book your spot now. Special offer for #barcelona-chapter members. We will send official mail invitations tomorrow.
```  
4. **Send mail invitations**: The day after bullet 3. send invitations by mail to all subscribers. To do so:
   1. Login to codebar.io (you must have admin rights for the channel)
   2. Click on **Menu** > **Barcelona** > **All workshops** > **Click the workshop link** > **Invite** > Click one of the options.
      * Note: Invitations are sent only once to each subscriber. If you click invite more than once, the second time, only the new subscribers to Barcelona chapter will get a mail invitation.

**In Trello:** When workshop is added in codebar.io, check the corresponding item in the `Before workshop` section.

**Global Virtual Codebar Workshop sheet:** Once the event is created, make sure you announce the vent in the global virtual codebar workshop sheet. You will find the link to the google doc in the trello board.

### Facebook

After creating the event in codebar.io, you should add it in Facebook. To do so:

1. Navigate to https://www.facebook.com/codebarBCN/. You must login with an account with _manage access_ to this page.
2. Go to **Events** > **+ Create event**
3. Fill in the required data. You'll need, an image (that you can obtain from previous events in the same host), the date and time, the host address, the Facebook page of the host (to assign it as co-host), a description (example below), a Category (use _Networking_) and _tickets URL_ (use the event url from codebar.io.).

**In Trello:** When workshop is added in Facebook, check the corresponding item in the `Before workshop` section.

#### Example description
Replace XXXXX and HOST_URL by the correct values
```
Learn to program in 2019! Join us for a free programming workshop at XXXXX

Have you already started learning, and need some help from other programmers? Are you working on a personal project and don't know how to move forward? Are you thinking of changing your career to something technology related?
Then, this event is the perfect place for you.

IMPORTANT: For this event you will need to register on the codebar page

https://codebar.io/workshops/XXXXX

We are a non-profit group of students and coaches that love technology and strongly believe that it should be accessible for everyone. For this reason, we run regular free coding meetups for women, members of the LGBTQ community, and other underrepresented groups in tech. Our goal is to enable underrepresented people to learn to program in a safe and collaborative environment and expand their career opportunities.

This time, XXXXX opens its doors again to host the event.
https://www.HOST_URL.com/

Not sure if this event is for you yet? Join our slack channel where you can get in touch with other students and coaches not only from Barcelona but also from other cities where codebar.io has events:

Join our Slack channel at: https://slack.codebar.io.
```


### In MeetUp

After creating the event in codebar.io, you should add it in Facebook. To do so:

1. Navigate to https://www.meetup.com/es/Codebar-Barcelona/. You must login with an account with _manager access_ to this page.
2. Go to **Create event**
3. **Fill in the requested data**: You'll need, an image (that you can obtain from previous events in the same host), the date and time, the host address, a description (example in Facebook section).
4. **Save**: Wait for announcing it until one day after the announcement is Slack. See `In codebar.io` section above
5. If everything was correctly done, you should get a mail from MeetUp titled: `You've scheduled: XXXXXX`

**In Trello:** When workshop is added in MeetUp, check the corresponding item in the `Before workshop` section.

### Preparing for the workshop

#### Assigning the workshop actors

* **Door person:** The door person is in charge of checking participants in as they join the zoom call. You do this by signing into the codebar.io page as an admin, and selecting the specific workshop. On the day of the event you will see that a checkbox option opens up. Click on the checkbox to verify attendance.  

* **Master of Ceremony (MC):** The MC is in charge of the introductory talk. To contribute to the safe environment, we prefer that this role is carried out by a woman. A sample script can be [found here](https://github.com/codebar/barcelona/blob/master/processes/workshops-preparation/script-presentation.md).

* **Pairing support:** This person helps the MC while pairing students and coaches.Documentation for how the pairing tool works can be found [here](https://github.com/codebar/barcelona/tree/master/tools/pairing-tool).

**In Trello:** Once assigned, check the corresponding item in the `Before workshop` section and tag each of them in the card description

**1-2 days before the workshop:** Send pairing emails to all participants that have RSVP'd for the workshop.Here is a sample email that you can send:

Hi Participant,

We wanted to confirm your attendance to the upcoming codebar virtual workshop on DATE.

To make the pairing more efficient, can you let us know what you will be working on?

Typically we have a waitlist. If you can no longer attend, make sure you update your invitation so that another person on the waitlist can attend.

We look forward to seeing you at the event.

Best,

Your name.   

* **In Trello:** Check the corresponding item in the `Before workshop` section.

**On the day of the workshop:** Prepare an icebreaker question. You will find a link to a sample of questions in the trello board.

* **In Trello:** Check the corresponding item in the `Before workshop` section.

**On the day of the workshop:** Post the zoom call details in the dedicated slack channel so that all participants can see it at 6pm.

* **In Trello:** Check the corresponding item in the `Before workshop` section.

### Post event actions
#### Uploading the photos to Social Media

Upload the pictures into a fresh new album in Facebook. To do so:
1. Go to https://www.facebook.com/pg/codebarBCN/photos/.
2. Click "Create album"
3. Upload the pictures to it.
4. Share the link in Slack #barcelona-channel within a _thank you_ message to the Students, Coaches and host. Example:
```
Here are the photos from yesterday's event. A big thanks to XXXXX for hosting us! We also want to welcome all of the new students and coaches who joined us! Finally a big shout out to our returning coaches and students! :heart:  LINK_HERE
```

+ **In Trello:** Check the corresponding item in the `After the workshop` section.

Upload pictures to slack, meetup and twitter.

#### Thanking the sponsor

If the event was sponsored send a _thank you_ e-mail to the sponsor. In this communication the link to the event pictures can be shared. Also this mail can be used to open the discussion about possible future collaborations by including the date available in the following months.

+ **In Trello:** Check the corresponding item in the `After the workshop` section.

### Sending attendance email to those who did attend.

TBD
