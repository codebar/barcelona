# Preparing a workshops



## Objective
This procedure describe the steps needed to set up a codebar workshop in Barcelona chapter.

## Overview
The process of preparing a workshop in Barcelona chapter can be divided in 3 blocks. Each of this blocks is further detailed below in this article. They are:

* **Before the workshop:** This part of the process consists on defining workshop dates and finding a space that can host us on each of them.
* **Preparing a workshop:** This part of the process consist in setting up the event once the host has been decided.
* **Post event actions:** This part of the process consist of thanking the host, publishing the pictures in social media and engaging a possible new date with the host.

## Tool support
Several workshop can be *under preparation* at the same time, hence, to facilitate a quick view on the status of each workshop preparation we decided to use a [Trello board](https://trello.com/b/ccJETYgH/codebario-barcelona).

In this board, you'll find **one card per workshop** transitioning through different columns. Each column title represents the state of the cards in it. Along this article, the transitions from column to column will be explained.

# Before the workshop

## Defining the dates
Barcelona chapter normally has the workshops on **Thursdays**. If needed, exceptions are allowed, but when possible we prefer to keep Thursdays since our students and hosts are used to that day. If you are thinking of having a workshop in a different date, check that there will be enough organizers available to help you during the event.

**In Trello:** To define a new workshop date, copy the card named `Event yyyy.mm.dd` from column `TEMPLATE`. You will find a `Copy` button inside the card. When coping it, make sure you rename it replacing `yyyy.mm.dd` by the correct date. Also make sure you keep the _checklists_, the _labels_ and the _attachments_. The new card should be placed in column `Available dates - No host yet`.

## Finding a host
Barcelona chapter has a list of regular hosts and tries to rotate through them as much as possible. The criteria for picking up a next host is described in next section.

### How to pick the next host?

(To be filled by Amalia)

### Contacting the host
We contact our host by mail. There is not a fixed template to reach them out, but there are a few points that **must be covered** in the communication with them. Those are:
* There must be space for around 30 people,
* The workshop starts at 18:30 and ends 20:45. Organizers normally arrive around 18:00 to help up setting up the space,
* There must be food and drinks (not just chips) for people coming from work,
* If they will provide student and coaches, they have to subscribe through the codebar.io platform (so we know they have read the code of conduct and to allow us to know the students/coaches ratio),
* We will provide a list with participants 24 hours before the event. We need to know how strict the access to the building and to the office will be. Specially regarding people not in the list.

It's sometimes a good practice to do this communication in two steps. In a first one only the first 3 bullets are covered, and in a follow up the rest.

**In Trello:** When you offer a date(s) to a possible host, move the card(s) to `Date proposed - Waiting host confirmation`, to avoid offering the same date(s) to other hosts.
* If the **host does not accept** the date, move the card back to `Available dates - No host yet`.

* If the **host accepts** the date, set up the host logo as **card cover**, and move the card to `Host OK - No owner defined yet`.

#### Mail example
First bullets covered only:

```
Hi XXXXX,

My name is YYYY. ZZZZ told me to get in touch with you about this. I'm one of the organizers of codebar in Barcelona. codebar is an organization that started in the UK 4 years ago, which goal is to enable underrepresented people to learn programming in a safe and collaborative environment to expand their career opportunities.

We do this by pairing students with volunteer developers who work at different companies throughout Barcelona. We started a chapter in Barcelona in 2017, and we host workshops every two weeks. https://www.meetup.com/Codebar-Barcelona/

Some of our students want to become full-time developers, and others are interested in learning the basics in a welcoming environment. Since our community is expanding, **we are looking for more companies to host our workshops**.

If you are interested in hosting a workshop, our hosts must provide space with some tables to work at, an internet connection, and since people are coming to the workshops after work, some drinks and food. The number of people that we open up the workshop to is 30 people and the workshop runs from 18:30-20:45.

These workshops are a great opportunity for companies hosting us to make their company visible in the IT world. Also to network with developers than can power your business.

Right now we are looking for hosts for the following dates:

XXXXX
YYYYY

Thanks a lot for helping us in this cause,

looking forward to hear from you.

YYYY
```
## Preparing a workshop

### Owner definition

To ensure everyone an equal opportunity to participate at every level of the creation of events it is key that everyone can _'take the lead'_ of an event. One way of fostering such opportunity is to have each event have an _'owner'_. By identifying a single person as the event owner, everyone, regardless of previous experience, temperament, tendencies or personality, etc, will have an equal opportunity to participate.

This does not mean that the _'owner'_ has to do everything, though they can. Instead they have to check that each activity has been done and if necessary, bring organizers attention to the fact that things have not yet been completed. This will allow each and every organizer to participate in the process of creating events and communicating with hosts, not simple those who are accustomed to taking the lead.

To define the _'owner'_ the person that was in contact with the host, should publish in _#barcelona-org_ the _call for owners_. If no-one volunteers, the organizer that has not owned an event for longer period will be assigned as owner.

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
   2. Click on **Menu** > **New Workshop**
   3. Fill in the data requested. Pay special attention to the **date** and **time**
      * Note: **'Rsvp open local date'** and **'Rsvp open local time'** should be filled in with the day after the preceding workshop at 12:00. Once this date is reached, the platform will automatically start allowing RSVPs from people that navigates to the workshop page. **No mail invitations are sent at this date, or when clicking Save**.
   4. **Leave invitable unchecked**: When checked, people can RSVP to the event and mass mails can be sent. Experience showed that if more than one event has the RSVP open at the same time, it creates confusion to the participants. So we agreed not to mark the event as **invitable** until **after** the preceding workshop is completed.
   <kbd>![Creating a workshop in codebar.io](images/codebar.png?raw=true "Creating a worshop in codebar.io")</kbd>
   5. **Save:** If successful, you should see a blue line with the text `codebar: The workshop has been created.``

3. **Announce it in Slack:** Once the workshop is _invitable_ (meaning that it is the next upcoming one), announce it in #barcelona-chapter. The idea is to give a little advantage to the Barcelona community. Students and participants enrolled in the channel will have prior notice about the open RSVP in the channel. Make sure that you copy the correct link to the event (it **must not** have the word admin on it. The best way to obtain the link is by navigating from the home page > Events). Example text:
```
Hello channel: RSVP for next week (24th/January) workshop is now open. #Thoughtworks will host us. :parrot:
https://codebar.io/workshops/1069 Book your spot now. Special offer for #barcelona-chapter members. We’ll send official mail invitations tomorrow.
```  
4. **Send mail invitations**: The day after bullet 3. send invitations by mail to all subscribers. To do so:
   1. Login to codebar.io (you must have admin rights for the channel)
   2. Click on **Menu** > **Barcelona** > **All workshops** > **Click the workshop link** > **Invite** > Click one of the options.
      * Note: Invitations are sent only once to each subscriber. If you click invite more than once, the second time, only the new subscribers to Barcelona chapter will get a mail invitation.

**In Trello:** When workshop is added in codebar.io, check the corresponding item in the `Before workshop` section.

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

* **Door person:** The door person is in charge of receiving the participants, giving them a name tag and checking them in at codebar.io.

* **Master of Ceremony (MC):** The MC is in charge of the introductory talk. To contribute to the safe environment, we prefer that this role is carried out by a woman.

* **Pairing support:** This person helps the MC while pairing students and coaches.

**In Trello:** Once assigned, check the corresponding item in the `Before workshop` section and tag each of them in the card description

#### Reminding the host and sending the RSVP list.

**One week before the workshop:** A mail must be send to the host remembering them that we are having the workshop the week after. It's a good opportunity to remind them about the food and drinks and to have a vegan option.

+ **In Trello:** Check the corresponding item in the `Before workshop` section.

**The day before the workshop:** Send to the host the list of person that RSVP. You can obtain the list from the codebar.io platform. Include in the list the **accepted** participants and those in the **waiting list**. Check also **meetUp** in case someone only RSVPed there. IMPORTANT: **never include participants emails** - Only the names, techs and Student/Coach data can be shared with the host

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

#### Thanking the host

This action consists in sending a _thank you_ e-mail to the host. In this communication the link to the event pictures can be shared. Also this mail can be used to open the discussion about possible future collaborations by including the date available in the following months.

+ **In Trello:** Check the corresponding item in the `After the workshop` section.
