---
documentclass: article
title: CSUCI Email listserv Guide
author: Jason Miller
date: 2020-12-15
fontsize: 12pt
# Comment or change these if you don't have these fonts installed
mainfont: Palatino
monofont: Menlo
newtxmathoptions:
- cmintegrals
- cmbraces
colorlinks: true
linkcolor: RoyalBlue
urlcolor: RoyalBlue
---

This is a guide for using CSUCI's installation of the SYMPA email listserv.

<!---------------------------------------------------------------------------->

\tableofcontents

# User Guide 

Even though we have many online ways to communicate with colleagues and students, email continues to be an important to our community.  In fact, email is the primary way Senate communicates with Senators outside of their meetings, and its a critical tool for communication between campus administration to faculty, staff, and students.  To help make email communication more efficient and, perhaps, effective on campus, ITS is providing a new service:  an email listserv.

An email listserv is a service that provides a way to send messages to groups of email addresses using a single outgoing email address.  The campus uses the SYMPA listserv software which also stores emails that are sent to a list in a browseable web archive, sorting messaged by date sent.  

Who can send a message to a list, how people receive those messages (e.g., as they are sent or in groups called digests), and who can access the web archive of list messages are properties that vary between lists and are chosen when the list is created.

This document aims to describe how we will use the SYMPA email listserv service on campus.  It begins with instructions for using the listserv (e.g., creating a list, managing a list, being a list subscriber).  Then the document presents guidelines for the use of the listserv.  It concludes with technical information about how the SYMPA listserv service has been customized for our campus.


## Creating a New List

When a person creates a new list, they take on the responsibilities of being a `list owner` which include:

* receiving notifications when an email to a subscriber bounces,
* serving as a list moderator which is someone who approves submissios to the listserv, if necessary or who assigns that duty to others, and
* approving subscription requests (if required by the list),

When a person creates a new list, they need to provide some important information that will persist with the list throughout its lifetime and will be visible to all those who use the list (and, for some lists, the public).  This information includes:

**List name**: a short, descriptive email name for the list that avoids special characters.  Though not required, best practices in email lists recommend that the name should conform to a standard naming convention like

```
[unit name]-[group name]-[optional]
```
or 
```
[unit name]-[group name]-[optional]-L
```
as `-L` is a standard way of indicating to humans that the email is coming from a listserv.

In the above, `unit name` is the umbrella organization that will use the list (e.g., `senate` or `AS` for the School of Arts and Science or `mathematics` for the mathematics department), `group name` is a short descriptive name for the list topic (where words are separated by one hyphen), and `optional` is an optional indicator of a special function, for example `announce` or `news` for a newsletter-type list.

NOTE that the last word in the lisst name (e.g., `optional`) must **not** be any one of the following words: `request`, `editor`, `owner`, `subscribe`, or `unsubscribe` as these may cause listserv errors.

Examples of email list names could be:

* `senate-exec`
* `senate-announce`
* `senate-budget-committee`
* `senate-senators`
* `mathematics-majors`
* `mathematics-minors`
* `mathematics-announce`
* `mathematics-hiring-FY21`
* `as-staff`
* `daa-budget`

Each new list will be the responsibility of a list administrator.\marginpar{\small Not sure of the best way to do this.}  The category of the list (see Table \ref{table-listadmin} below) will determine that assignment.  When you fill out the list information form and submit it, the list will go to a listserver administrator from that category for approval.


\begin{table}[t]
\centering
\begin{tabular}{|ll|} \hline
Unit  & List Administrator \\ \hline \hline
Senate & Jeannette Edwards \\
ITS & To be determined \\
Arts and Sciences & To be determined \\
Business and Economics & To be determined \\
Education & To be determined \\
Division of Academic Affairs & To be determined \\
Division of Business and Financial Affairs & To be determined \\
Division of Student Affairs & To be determined \\
Advancement & To be determined \\
Office of the President & To be determined \\ \hline \hline
\end{tabular}
\caption{Example of list administrator assignments to list category.}\label{table-listadmin}
\end{table}


### Types of list

Lists can be configured in many ways, and there are several variations on the set-up available at the time of list creation.

**Web forum mailing list**:  This is a classic mailing list where all subscribers may post without moderation and the Archive of all posts is publicly available.

**Newsletter providing plain text**:  A public list allowing all subscribers to post, but a moderated list where all posts are reviewed by a team of one or more moderators before the message is sent on to all subscribers.  Email addresses of subscribers are not visible.  All messages are plain text.

This type of list might be apprpriate for an announcements channel to a community with a shared interest such as all students interested in undergraduate research,  or all employees interested in volunteer opportunities in the region.

**Public discussion mailing list**:  Only subscribers can post to the list, but the archives are visible to the public.

This type of list might be appropriate for a goverance committee whose deliberations should be public.

**Confidential list setup**: Only the list owner can add and remove members, the archives are private (accessible only to members), the list is visible to members only, and only list members can send messages to the list.  Emails from other addresses are discarded without notification to the sender or the list owner(s).

This type of list might be appropriate for a hiring committee, an award selection committee, or some other group that needs to communicate and make decisions behind closed doors.

**Private working group setup**: Like the 'Confidential list setup' except that the list is visible to the public, though its membership and its archives are not.  Emails from other addresses are sent to a list owner for moderation.

**Hotline mailing list**: Everyone may post to the list but the archives are private.  Subscriptions to the list are subject to approval.

This type of list might be appropriate for a 'suggestion box' list where community members can send recommendations and ideas to the list owner.  It might also be apprpriate for a maintenance committee who wants to receive notifications of problems with an area of campus or a specific facility.

**Newsletter providing both text plain and HTML formats**: A public list allowing all subscribers to post, but a moderated list where all posts are reviewed by a team of one or more moderators before the message is sent on to all subscribers.  Email addresses of subscribers are not visible.  The default reception format is HTML, but a plain text alternative is provided.

This type of list might be apprpriate for an announcements channel where authors take the time to compose messages in HTML format.  Subscribers to such a list would be a community with a shared interest such as all students interested in undergraduate research,  or all employees interested in volunteer opportunities in the region.

### List Subject

This one-line description of the list is sent to uses who request information about the lists on the server.  (Condifential lists are not reported in response to such requests.)

### List Audience

SYMPA provides you with a list of categories of audience.  The category will determine the list administrator who will approve your list creation request and who will oversee your list activity.

At present, because the listserv is being installed to support communication of Academic Senate, the categories available are:

```
Academic Senate
Academic Senate / Committees
Academic Senate / Leadership
Academic Senate / other
Academic Senate / Senators
```

As more units on campus begin to use the listserv, other categories will be added.

## List Description

A desription of the list, its purpose, the audience for which it was designed.  This description appears in the web homepage for the lists.

<!---------------------------------------------------------------------------->

# Listserv Use Guidelines

This email listserv is deplayed to facilitate communication between members of the University community in ways that enrich our sense of community, deepen our connection with one another and University programs, and strengthen the institution and its operating units.

The shakeout phase of the listserv rollout is limited to the department of Information Technology Services and the University's Academic Senate.  When the operation and administration of the listserv is tunes to the University's network infrastructure, 


https://it.arizona.edu/documentation/using-website-sympa-list-owners

## Procedure for Requesting and Approving an Email List

[https://oit.duke.edu/help/articles/kb0019135](Duke University's)

Departmental lists could use SYMPA's 'family' concept as a way to keep some/all settings consistent (e.g., loading subscribers from external file, not allowing members to unsubscribe, defaulty as digest or not, modifications to family descend to lists belonging to the family).  Can use SYMPA's 'automatic list creation' feature for structural lists like departmental mailing lists (digest and not digest)

Requestor will become the listowner for the list and be responsbile for adding and removing subscribers according to the policies they set for the list.

Official University lists may be populated from official external data sources and a semi-annual or annual basis, according to natural patterns of member eligibility.

## Procedure for Owning and Moderating an Email List

https://list.arizona.edu/sympa/help/admin

https://www.montclair.edu/media/montclairedu/oit/documentation/msuapps/sympa/faq-for-sympa-list-owners-moderators.pdf

http://www.ala.org/support/sympa

### Populating list membership from file

<!---------------------------------------------------------------------------->

# Listserv Guidelines for Academic Senate Lists

Official email listserves of the Academic Senate shall be created, administered, and maintained according to these guidelines.  In the spirit of California's open meeting laws, business of the Senate shall be conducted in public where possible.  This means that official most archives of Senate email lists should be public if they will be used to discuss matters of Senate business.

senate-announce-L
: A list for announcements from Senate.  Anyone may subscribe.  Archives are public.

senate-senators-L
: This is a discussion list for all senators.  All senators are automatically subscribed and may not unsubscribe.  All active senators may post.  Archives are public.

senate-lecturers-L
: A discussion list for all lecturer faculty.  All active lecturer faculty are subscribed and may opt out of the list at will.  Archives are private.

senate-executive-L
: This list serves the deliberation of members of the Executive Committee of the Academic Senate.  All members of Senate Exec are subscribed and may not unsubscribe.  Archives are public.

senate-officers-L
: A hotline list for communication to senate officers.  Anyone can post.  Archives are private.

senate-budget-L
: Discussion list for the Budget Committee.

senate-coc-L
: Discussion list for the Committee on Committees.

senate-appc-L
: Discussion list for the Academic Policy and Planning Committee.

senate-ge-L
: Discussion list for the General Education Committee.

senate-cci-L
: Discussion list for the Committee for Centers and institutes.

senate-facult-affairs-L
: Discussion list for the Faculty Affairs Committee.

senate-faculty-search-L
: Discussion list for the Faculty Search Coordinating Committee.

senate-admineval-L
: Discussion list for the Administrator Evaluation Committee.

senate-minigrant-L
: Discussion list for the Minigrant Review Committee.

senate-prof-leave-L
: Discussion list for the Professional Leave Committee.

senate-sap-L
: Discussion list for the Student Academic Policies and Procedures Committee.

senate-lcc-mathsci-L
: Discussion list for the Local Curriculum Committee for Mathematics and Sciences.

senate-lcc-mathsci-L
: Discussion list for the Local Curriculum Committee for Mathematics and Sciences.

senate-lcc-artshum-L
: Discussion list for the Local Curriculum Committee for Arts and Humanities.

senate-lcc-behavsoc-sci-L
: Discussion list for the Local Curriculum Committee for Behavioral and Socials Sciences.

senate-lcc-prof-stud-L
: Discussion list for the Local Curriculum Committee for Professional Studies.

senate-uavb-L
: Discussion list for the Unmanned Aerial Vehicle Board.

senate-commeng-board-L
: Discussion list for the Center for Community Engagement Advisory Board.

senate-intstu-board-L
: Discussion list for the Center for Integrated Studies Advisory Board.

senate-intaff-board-L
: Discussion list for the Center for international Affairs Advisory Board.

senate-multicultural-board-L
: Discussion list for the Center for Multicultural Engagement Advisory Board.

senate-extuniv-board-L
: Discussion list for the Extended University Advisory Board.

senate-facdev-board-L
: Discussion list for the Faculty Development Advisory Board.

senate-library-board-L
: Discussion list for the Library Advisory Board.

senate-rsp-board-L
: Discussion list for the Research and Sponsored Programs Advisory Board.

senate-its-board-L
: Discussion list for the Technology Advisory Board.

senate-srpc-L
: Discussion list for the senate members of the Strategic Resource Planning Committee.

senate-aabac-L
: Discussion list for the senate members of the Academic Affairs Budget and Advisory Committee.

<!---------------------------------------------------------------------------->

# Listserv Administration Guide


### List Categories

When you create a list, you need to choose a category for the list.  The category will determine the list administrator who will approve your list creation request and who will oversee your list activity.

At present, because the listserv is being installed to support communication in the Academic Senate, the categories available are:

```
Academic Senate
    leadership
    committees
    senators
    other
```

In the future, the following categories can be added if list administrators can be identified:

```
Staff Council
    leadership
    committees
    counselors
    other
Student Government
    leadership
    committees
    counselors
    other
Institutional Review Board
Schools
    School of Arts & Sciences
        departments
        committees
        members
        students
    School of Education
        departments
        committees
        members
        students
    Martin V. Smith School of Business and Economics
        departments
        committees
        members
        students
Divisions
    Academic Affairs
        units
        employees
    Business and Financial Affairs
        units
        employees
    Student Affairs
        units
        employees
    Advancement
        units
        employees
        alumni
```


## Templates

Site-wide message templates should contain information that associate the lists and messages that are sent through the list with CSUCI.

Templates use the Perl *Template Toolkit* (TT2) language which is described at [http://www.template-toolkit.org](http://www.template-toolkit.org).[^1]

[^1]: SYMPA documentation incorrectly identifies the home of TT2 documentation as `http://www.tt2.org`.

### Default list templates

#### unsubscribe message

```
From: [% fromlist %]
Subject: [%"Unsubscribed from %1"|loc(list.name)|qencode%]

[%|loc(user.email,list.name,domain)%]Your email address (%1) has been removed from list %2@%3[%END%]
[%|loc%]Thank you for using CSUCI's email listserv![%END%]
```

#### subscribing invitation message

```
[%# invite.tt2 ~%]
From: [% requested_by %]
Reply-To: [% conf.email %]@[% domain %]
Subject: [%"Invitation to join list %1"|loc(list.name)|qencode%]

[%|loc(list.subject)%]This list is about %1, so you are probably interested.[%END%]

[%|loc%]To subscribe, click the following URL:[%END%]
[% IF conf.wwsympa_url -%]
  [% 'auth' | url_abs([keyauth,'subscribe',list.name],{email=>user.email}) %]
[%~ ELSE -%]
  [% "${conf.email}@${domain}" | mailtourl({subject => "AUTH ${keyauth} ${cmd}"}) %]

[%|loc(conf.email,domain)%]Or send a message to %1@%2 with the following subject:[%END%]
  AUTH [% keyauth %] [% cmd %]
[%~ END -%]

[%|loc%]If you don't want to subscribe just ignore this message.[%END%]
```

#### message footer


#### message header


#### moderator rejection message

```
[%# reject.tt2 ~%]
From: [% fromlist %]
Subject: [%"Your message has been rejected"|loc|qencode%]

[%|loc(list.name,domain,rejected_by)%]Your message for list %1@%2 has been rejected by the moderator (%3).[%END%]

[%|loc(subject)%](Subject of your mail: %1)[%END%]

[% IF conf.wwsympa_url -%]
[%|loc(list.name)%]Check %1 list usage:[%END%]
[% 'info' | url_abs([list.name]) %]
[% END -%]
```

#### remind message

```
[%# remind.tt2 ~%]
From: [% fromlist %]
Subject: [%"Reminder of your subscription to %1"|loc(list.name)|qencode%]

[%|loc(list.name,domain,user.email,user.password)%]You are receiving this mail because you are subscribed to the mailing list %1@%2 with email address %3.[%END%]

[%|loc%]It is important that we not send email to people that do not want to receive it. If you do not want to be on this mailing list, please follow the instructions below to remove yourself.[%END%]

[% IF conf.wwsympa_url -%]
[%|loc%]List information: [%END ~%]
  [% 'info' | url_abs([list.name]) %]
[%|loc%]To unsubscribe:[%END%] [%""~%]
  [% 'signoff' | url_abs([list.name]) %]
[% ELSE -%]
[%|loc%]List information: [%END ~%]
  [% "${conf.email}@${domain}" | mailtourl({subject => "info ${list.name}"}) %]
[%|loc%]To unsubscribe:[%END%] [%""~%]
  [% "${conf.email}@${domain}" | mailtourl({subject => "sig ${list.name} ${user.email}"}) %]
[% END -%]
```


#### deletion message

```
From: [% fromlist %]
Subject: [%"Removed from %1"|loc(list.name)|qencode%]

[%|loc(user.email,list.name,domain)%]Your email address (%1) has been removed from list %2@%3[%END%]

[%|loc%]You can subscribe again:[%END%]
[% | mailtourl({subject => "sub ${list.name}"}) ~%]
  [% conf.email %]@[% domain %]
[%~ END %]
```


#### welcome message

```
[%# welcome.tt2 ~%]
From: [% fromlist %]
Subject: [%"Welcome to list %1"|loc(list.name)|qencode%]

[%|loc(list.name,domain)%]Welcome to list %1@%2[%END%]
[%|loc(user.email)%]Your subscription email is %1[%END%]

[% TRY %]
[% INSERT "info" %]
[% CATCH %]
[% END %]

[% IF conf.wwsympa_url -%]
[%|loc%]The list homepage:[%END%] [% 'info' | url_abs([list.name]) %]
[%|loc%]General information about mailing lists:[%END%] [% 'help' | url_abs(['introduction.html']) %]
[% END -%]
```


#### virus infection message

```
Subject: [%"A virus in your email"|loc|qencode%]

    [%|loc%]***** V I R U S    A L E R T *****[%END%]

[%|loc(virus_name,recipient,sender)%]A campus viruschecker found a virus named %1 in a message addressed to %2 and that seems to be yours (From: %3).[%END%]

[%|loc%]Delivery of this message has been blocked.[%END%]

[%|loc%]It may be useful to check your system for viruses.

Note, however, that many viruses fake sender's e-mail address, so it is possible that the virus didn't come from your computer. In that case, please disregard this message.[%END%]
```


### Site-wide templates

#### list creation request message

#### global reminder message

```
Subject: [%"Subscription summary"|loc|qencode%]
X-Sympa-NoWrap: yes

[%|wrap -%]
[%|loc(user.email)%]Summary of your subscription (using the e-mail %1).[%END%]
[%|loc%]If you want to unsubscribe from some list, please save this mail.[%END%]

[%|loc%]For each list here is a mail address to use if you want to unsubscribe.[%END%]
[%- END#wrap%]

-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
[% FOREACH l = lists -%]
[% l %] [% | mailtourl({subject => "sig ${l} ${user.email}"}) ~%]
  [% conf.email %]@[% domain %]
[%~ END %]
[% END -%]
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
```


#### help file

```
Subject: [%"User guide"|loc|qencode%]

              SYMPA -- Systeme de Multi-Postage Automatique
[%|loc%]                       (Automatic Mailing System)[%END%]

[%|loc%]                                User's Guide[%END%]


[%|loc%]SYMPA is an electronic mailing-list manager that automates list management functions such as subscriptions, moderation, and archive management.[%END%]

[%|loc("${conf.email}@${domain}")%]All commands must be sent to the electronic address %1.[%END%]

[%|loc%]You can put multiple commands in a message. These commands must appear in the message body and each line must contain only one command.[%END%]

[%|loc%]Available commands are:[%END%]
[%|wrap(0,39)%]
 [%|loc%]HELp                        * This help file[%END%]
 [%|loc%]INFO <list>                 * Information about a list[%END%]
 [%|loc%]LISts                       * Directory of lists managed on this node[%END%]
 [%|loc%]REView <list>               * Displays the subscribers to <list>[%END%]
 [%|loc%]WHICH                       * Displays which lists you are subscribed to[%END%]
 [%|loc%]SUBscribe <list> <name>     * To subscribe or to confirm a subscription to <list>.[%END%]

 [%|loc%]UNSubscribe <list> <EMAIL>  * To quit <list>. <EMAIL> is an optional email address, useful if different from your "From:" address.[%END%]
 [%|loc%]UNSubscribe * <EMAIL>       * To quit all lists.[%END%]

 [%|loc%]SET <list>|* NOMAIL         * To suspend the message reception for <list>[%END%]
 [%|loc%]SET <list>|* DIGEST         * Message reception in compilation mode[%END%]
 [%|loc%]SET <list>|* DIGESTPLAIN    * Message reception in compilation mode, sent as a plain text email with all attachments[%END%]
 [%|loc%]SET <list>|* SUMMARY        * Receiving the message index only[%END%]
 [%|loc%]SET <list>|* NOTICE         * Receiving message subject only[%END%]
 [%|loc%]SET <list>|* MAIL           * <list> reception in normal mode[%END%]
 [%|loc%]SET <list>|* CONCEAL        * To become unlisted (hidden subscriber address)[%END%]
 [%|loc%]SET <list>|* NOCONCEAL      * Subscriber address visible via REView[%END%]


 [%|loc%]INDex <list>                * <list> archive file list[%END%]
 [%|loc%]GET <list> <file>           * To get <file> of <list> archive[%END%]
 [%|loc%]LAST <list>                 * Used to received the last message from <list>[%END%]
 [%|loc%]INVITE <list> <email>       * Invite <email> for subscription in <list>[%END%]
 [%|loc%]CONFIRM <key>               * Confirmation for sending a message (depending on the list configuration)[%END%]
 [%|loc%]QUIT                        * Indicates the end of the commands (to ignore a signature)[%END%]
[%END#wrap%]
[% IF is_owner -%]
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-
[%|loc%]The following commands are available only for lists owners or moderators:[%END%]
[%|wrap(0,39)%]
 [%|loc%]ADD <list> user@host Full name  * To add a user to a list[%END%]
 [%|loc%]DEL <list> user@host            * To delete a user from a list[%END%]
 [%|loc%]STATS <list>                    * To consult the statistics for <list>[%END%]

 [%|loc%]REMIND <list>                   * Send a reminder message to each subscriber (this is a way to inform anyone what is their real subscribing email).[%END%]
[%END#wrap%][% END %]
[% IF is_editor -%]
[%|wrap(0,39)%]
 [%|loc%]DISTribute <list> <key>        * Moderation: to validate a message[%END%]
 [%|loc%]REJect <list> <key>            * Moderation: to reject a message[%END%]
 [%|loc%]MODINDEX <list>                 * Moderation: to view the list of messages to moderate[%END%]
[%END#wrap%][% END %]

[%|loc(conf.version)%]Powered by Sympa %1[%END%][%|loc%]:[%END%] http://www.sympa.org
```

#### list aliases template

```
#------------------------------ [% list.name %]: list alias created [% date %]
[% IF is_default_domain -%]
[% list.name %]: "| /usr/libexec/sympa/queue [% list.name %]@[% list.domain %]"
[% list.name %]-request: "| /usr/libexec/sympa/queue [% list.name %]-request@[% list.domain %]"
[% list.name %]-editor: "| /usr/libexec/sympa/queue [% list.name %]-editor@[% list.domain %]"
#[% list.name %]-subscribe: "| /usr/libexec/sympa/queue [% list.name %]-subscribe@[% list.domain %]"
[% list.name %]-unsubscribe: "| /usr/libexec/sympa/queue [% list.name %]-unsubscribe@[% list.domain %]"
[% list.name %][% return_path_suffix %]: "| /usr/libexec/sympa/bouncequeue [% list.name %]@[% list.domain %]"
[% ELSE -%]
[% list.domain %]-[% list.name %]: "| /usr/libexec/sympa/queue [% list.name %]@[% list.domain %]"
[% list.domain %]-[% list.name %]-request: "| /usr/libexec/sympa/queue [% list.name %]-request@[% list.domain %]"
[% list.domain %]-[% list.name %]-editor: "| /usr/libexec/sympa/queue [% list.name %]-editor@[% list.domain %]"
#[% list.domain %]-[% list.name %]-subscribe: "| /usr/libexec/sympa/queue [% list.name %]-subscribe@[% list.domain %]"
[% list.domain %]-[% list.name %]-unsubscribe: "| /usr/libexec/sympa/queue [% list.name %]-unsubscribe@[% list.domain %]"
[% list.domain %]-[% list.name %][% return_path_suffix %]: "| /usr/libexec/sympa/bouncequeue [% list.name %]@[% list.domain %]"
[% END -%]
```

#### list creation notification message

```
[%# list_created.tt2 ~%]
Subject: [%"%1 mailing list creation"|loc(list.name)|qencode%]

[%|loc(list.name,domain)%]%1@%2 mailing list has been activated by listmaster.[%END%]

[% IF conf.wwsympa_url -%]
[%|loc%]homepage[%END%]
[% 'info' | url_abs([list.name]) %]

[%|loc(list.name)%]%1 admin page[%END%]
[% 'admin' | url_abs([list.name]) %]
[% END -%]
```

#### directory of lists

```
Subject: [%"Public lists"|loc|qencode%]

[%|loc(conf.email,domain)%]Here is the list of lists from %1@%2[%END%]

[% FOREACH l = lists -%]
[% l.key %]@[% domain %][%|loc%]:[%END%] [% l.value.subject %]

[% END %]

-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_
mailto:[% conf.listmaster_email %]@[% domain %]
```

#### summary message

```
[%# summary.tt2 ~%]
From: [% fromlist %]
Subject: [%"%1 Summary %2"|loc(list.name,date)|qencode%]
X-Sympa-NoWrap: yes

[%|loc(list.name,date)%]%1 summary %2[%END%]

[% FOREACH m = msg_list -%]
[%|wrap(0,2)%]* [% m.id %] - [% m.subject %] - [% m.from %][%END#wrap%]
[% IF conf.wwsympa_url -%]
  [% 'arcsearch_id' | url_abs([list.name,m.month,m.message_id]) %]
[% END %]
[% END -%]
```


## Configurations

### List families

Lists might be used to create automatic distribution lists for employees based on periodic snapshots of Active Directory information.

Possible list families:

* students in a major
* all employees in a unit (department, school, division)
* all faculty (tenured, tenure-track, lecturer) in a unit (department, school, division)
* all staff in a unit (department, school, division)

Lists whose membership do not conform to an Active Directory definition should be constructed and managed by hand.

### Web Site Styles

The site CSS configuration has been edited so the color conform to the University [web style guide](https://www.csuci.edu/its/web/styleguide/color-type.htm).  Specifically, in `Listmaster Admin > Skins, CSS and colors`:

* `color_2` (Titles and buttons color) and `color_6` (text color of hovered links;
background color of buttons) set to be \#999999

* `color_10` (background color of list configuration edition and navigation edition links) set to be \#cb132a

## References


