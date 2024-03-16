# Preparing a workshops

## Objective
This procedure describes the steps needed to set up a codebar workshop in the Barcelona chapter.

## Overview
The process of preparing a workshop in the Barcelona chapter can be divided in 3 blocks. Each of these blocks is further detailed below in this article. They are:

* **Before the workshop:** This part of the process consists of defining the workshop date and finding a space that can host us.
* **Preparing a workshop:** This part of the process consists of setting up the event once the host has been found.
* **Post-event actions:** This part of the process includes thanking the host, publishing pictures on social media, and arranging a possible new date with the host.

## Tool support
Several workshop can be *under preparation* at the same time, hence, to facilitate a quick view on the status of each workshop preparation we decided to use a [Trello board](https://trello.com/b/ccJETYgH/codebario-barcelona).

In this board, you'll find **one card per workshop** transitioning through different columns. Each column title represents the state of the cards within it. Throughout this article, the transitions from one column to another will be explained.

# Before the workshop

## Defining the dates
The Barcelona chapter normally holds workshops on **Thursdays**. Exceptions are allowed if necessary, but we prefer to keep to Thursdays when possible, as our students and hosts are accustomed to this day. If you're considering scheduling a workshop on a different day, please ensure that there will be enough organizers available to assist you during the event.

**In Trello:** To define a new workshop date, copy the card named `In-Person Event YYYY-MM-DD` or `Virtual Event YYYY-MM-DD` from the `TEMPLATE` column, depending on the type of event you're planning. You will find a `Copy` button inside the card. When copying it, make sure you rename it by replacing `YYYY-MM-DD` with the correct date. Also, ensure that you keep the _checklists_, the _labels_, and the _attachments_. The new card should be placed in the `Available dates - No host yet` column.

## Finding a Host
The Barcelona chapter has a list of regular hosts and tries to rotate among them as much as possible. The criteria for selecting the next host are described in the following section.

### How to pick the next host?

(To be filled by Amalia)

### Contacting the Host
We contact our host via email. You can use [this template](https://github.com/codebar/barcelona/blob/master/chapter_assets/email-templates/1-finding-new-hosts/new-sponsor.md) or write your own email, while covering at least the following points:
* The space must accommodate around 20-30 people.
* The workshop starts at 18:30 and ends at 20:45. Organizers typically arrive around 18:00 to help set up the space.
* There must be food and drinks (not just chips) available for people coming from work.
* If the host is providing students and coaches, they must register through the codebar.io platform. This ensures they have read the code of conduct and allows us to determine the student-to-coach ratio.
* We will provide a list of participants 24 hours before the event. We need to know how strict the access to the building and office will be, especially regarding people not on the list.

Sometimes, it's good practice to split this communication into two steps. In the first step, only the first three bullet points are covered. The rest are addressed in a follow-up communication.

**In Trello:** When you offer a date(s) to a possible host, move the card(s) to `Date proposed - Waiting host confirmation`, to avoid offering the same date(s) to other hosts.
* If the **host does not accept** the date, move the card back to `Available dates - No host yet`.

* If the **host accepts** the date, set up the host logo as **card cover**, and move the card to `Host OK - No owner defined yet`.

## Preparing a workshop

### Owner definition

To ensure everyone has an equal opportunity to participate at every level of event creation, it is crucial that everyone can _'take the lead'_ on an event. One way to foster such opportunity is to assign an _'owner'_ to each event. By identifying a single person as the event owner, everyone, regardless of previous experience, temperament, tendencies, or personality, will have an equal opportunity to participate.

This does not mean that the _'owner'_ has to do everything, though they can. Instead, they need to ensure that each activity has been completed and, if necessary, bring to the organizers' attention the fact that certain tasks have not yet been completed. This will allow each and every organizer to participate in the process of creating events and communicating with hosts, not just those who are accustomed to taking the lead.

To define the _'owner'_, the person who was in contact with the host should publish a _call for owners_ in _#barcelona-org_. If no one volunteers, the organizer who has not owned an event for the longest period will be assigned as the owner.

**In Trello:** Once the owner is assigned, move the card to `Owner preparing workshop`, tag the person in the card description, and assign the card to this person.

### Publishing the workshop

### In codebar.io

This is the first platform where we need to upload the event. To do so, follow these steps:

1. **Create a New Host:** If this is the first time the sponsor is hosting us, you need to add it to the platform. Otherwise, proceed to step 2.
   1. Log in to codebar.io (you must have admin rights for the channel).
   2. Click on **Menu** > **New Sponsor**.
   3. Fill in the requested data. You'll need a name, logo, address, and capacity (students and coaches separately).
   4. To confirm that the sponsor was correctly added, you can go to https://codebar.io/sponsors and search for it.
2. **Create a New Workshop:** To do so:
   1. Log in to codebar.io (you must have admin rights for the channel).
   2. Click on **Menu** > **New Workshop**.
   3. Fill in the requested data. Pay special attention to the **date** and **time**.
      * Note: **'Rsvp open local date'** and **'Rsvp open local time'** should be filled in with the day after the preceding workshop at 12:00. Once this date is reached, the platform will automatically start allowing RSVPs from people who navigate to the workshop page. **No email invitations are sent on this date, or when clicking Save**.
   4. **Leave invitable unchecked**: When checked, people can RSVP to the event and mass emails can be sent. Experience has shown that if more than one event has the RSVP open at the same time, it creates confusion among the participants. So we agreed not to mark the event as **invitable** until **after** the preceding workshop is completed.
   <kbd>![Creating a workshop in codebar.io](images/codebar.png?raw=true "Creating a workshop in codebar.io")</kbd>
   5. **Save:** If successful, you should see a blue line with the text `codebar: The workshop has been created.`

3. **Announce it in Slack:** Once the workshop is _invitable_ (meaning that it is the next upcoming one), announce it in the #barcelona-chapter. The idea is to give a slight advantage to the Barcelona community. Students and participants enrolled in the channel will receive prior notice about the open RSVP in the channel. Make sure that you copy the correct link to the event (it **must not** contain the word 'admin'. The best way to obtain the link is by navigating from the home page > Events). Example text:
```
Hello channel: RSVP for next week (24th/January) workshop is now open. #Thoughtworks will host us. :parrot:
https://codebar.io/workshops/1069 Book your spot now. Special offer for #barcelona-chapter members. We’ll send official mail invitations tomorrow.
```  
4. **Send mail invitations**: The day after bullet 3, send invitations via email to all subscribers. To do so:
   1. Login to codebar.io (you must have admin rights for the channel)
   2. Click on **Menu** > **Barcelona** > **All workshops** > **Click the workshop link** > **Invite** > Click one of the options.
      * Note: Invitations are sent only once to each subscriber. If you click invite more than once, the second time, only the new subscribers to Barcelona chapter will receive an email invitation.

**In Trello:** When the workshop is added in codebar.io, check the corresponding item in the `Before the workshop` section.

### Facebook

After creating the event on codebar.io, you should add it to Facebook. To do so:

1. Navigate to https://www.facebook.com/codebarBCN/. You must log in with an account that has _manage access_ to this page.
2. Go to **Events** > **+ Create event**
3. Fill in the required data. You'll need an image (which you can obtain from previous events at the same host), the date and time, the host address, the Facebook page of the host (to assign it as a co-host), a description (example below), a category (use _Networking_), and a _tickets URL_ (use the event URL from codebar.io).

**In Trello:** When the workshop is added to Facebook, check the corresponding item in the `Before the workshop` section.

#### Example description
Replace XXXXX and HOST_URL by the correct values
```
Learn to program in 2024! Join us for a free programming workshop at XXXXX.

Have you already started learning and need some help from other programmers? Are you working on a personal project and don't know how to move forward? Are you thinking of changing your career to something technology-related? If so, this event is the perfect place for you.

IMPORTANT: For this event, you will need to register on the codebar page:

https://codebar.io/workshops/XXXXX

We are a non-profit group of students and coaches who love technology and strongly believe that it should be accessible to everyone. For this reason, we run regular free coding meetups for women, members of the LGBTQ community, and other underrepresented groups in tech. Our goal is to enable underrepresented people to learn to program in a safe and collaborative environment and expand their career opportunities.

This time, XXXXX is opening its doors again to host the event.
https://www.HOST_URL.com/

Not sure if this event is for you yet? Join our Slack channel where you can get in touch with other students and coaches not only from Barcelona but also from other cities where codebar.io hosts events:

Join our Slack channel at: https://slack.codebar.io.
```


### On MeetUp

After creating the event on codebar.io, you should add it to MeetUp. To do so:

1. Navigate to https://www.meetup.com/es/Codebar-Barcelona/. You must log in with an account that has _manager access_ to this page.
2. Go to **Create event**.
3. **Fill in the requested data**: You'll need an image (which you can obtain from previous events at the same host), the date and time, the host address, and a description (see the example in the Facebook section).
4. **Save**: Wait to announce it until one day after the announcement in Slack. See the `In codebar.io` section above.
5. If everything was done correctly, you should receive an email from MeetUp titled: `You've scheduled: XXXXXX`.

**In Trello:** When the workshop is added to MeetUp, check the corresponding item in the `Before the workshop` section.

### Preparing for the Workshop

#### Assigning the Workshop Roles

* **Door Person:** The door person is responsible for welcoming the participants, providing them with a name tag, and checking them in on codebar.io.

* **Master of Ceremony (MC):** The MC is responsible for the introductory talk. To contribute to a safe environment, we prefer that this role is filled by a woman.

* **Pairing Support:** This person assists the MC with pairing students and coaches.

**In Trello:** Once the roles are assigned, check the corresponding item in the `Before the workshop` section and tag each person in the card description.

#### Reminding the Host and Sending the RSVP List

**One week before the workshop:** An email should be sent to the host reminding them that we are having the workshop the following week. It's a good opportunity to remind them about the food and drinks and to have a vegan option.

+ **In Trello:** Check the corresponding item in the `Before the workshop` section.

**The day before the workshop:** Send the host the list of people who have RSVPed. You can obtain the list from the codebar.io platform. Include in the list the **accepted** participants and those on the **waiting list**. Also check **MeetUp** in case someone only RSVPed there. IMPORTANT: **Never include participants' emails** - Only the names, technologies, and Student/Coach data can be shared with the host.

* **In Trello:** Check the corresponding item in the `Before the workshop` section.

### Post-Event Actions
#### Uploading Photos to Social Media

Upload the pictures to a new album on Facebook. To do so:
1. Go to https://www.facebook.com/pg/codebarBCN/photos/.
2. Click "Create Album".
3. Upload the pictures.
4. Share the link in the Slack #barcelona-channel with a _thank you_ message to the students, coaches, and host. Example:
```
Here are the photos from yesterday's event. A big thanks to XXXXX for hosting us! We also want to welcome all the new students and coaches who joined us. Finally, a big shout-out to our returning coaches and students! :heart: LINK_HERE
```

* **In Trello:** Check the corresponding item in the `After the workshop` section.

#### Thanking the Host

This action involves sending a _thank you_ email to the host. In this communication, the link to the event pictures can be shared. This email can also be used to initiate discussions about possible future collaborations by including available dates in the following months.

* **In Trello:** Check the corresponding item in the `After the workshop` section.