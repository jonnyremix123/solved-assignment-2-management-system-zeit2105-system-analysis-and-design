Download Link: https://assignmentchef.com/product/solved-assignment-2-management-system-zeit2105-system-analysis-and-design
<br>
<h1>Assignment Objectives</h1>

This assignment provides you with the opportunity to demonstrate your system and database design skills, as well as your skills implementing a SQLite database.

<h1>Your Task in Brief</h1>

You are working of a new cyber education start-up. They specialise in micro credentials.  The curriculum is accompanied by a system of ‘badges’ that is given out when students complete certain groups of activities. Teachers need to keep track of which students complete which activities so that they can receive their badges in a timely manner.

Currently, the start-up does this using a (paper) notebook in which it records attendance each week and jots down which activities completed. Each week we have to update the achievement record from our jottings in the attendance record book.

In this project you will <u>design</u> and <u>implement</u> an <u>attendance record system</u> that helps teachers manage student attendance and achievement records by storing details in a <u>SQLite</u> <u>database</u>.

<h1>Submission Requirements</h1>

You must submit a softcopy of your code (Task 3) by email and hardcopy of your design (Tasks 1&amp;2). You may submit your design as early as you like (week 12 recommended) up until the final due date of 4<sup>th</sup> November.

<h1>Detailed Statement of Requirements</h1>

The micro credential award scheme is fairly complex. There are loads of things people can do. Students attend weekly meetings, weekend activities, and also do work in their own time if they want to. There are Achievement Badges that let students focus on a special interest or skill and badges that focus on the core curriculum. There is also a leader board that shows those students with the highest number of credentials.

The badging system has three levels gold, diamond, and super platinum

Each badge has 14 Tests students must complete all of

Tests 1-7 and any 3 of the remaining Tests (8-14). Each Test 1-14 is broken into topics. Each topic has between 1 and 3 parts that must be completed for the topic to be considered complete. We only need to record the date that the entire topic has been completed, but sometimes we do parts of topics and we thus need to record completion of a part as well (although not necessarily the date). In some tests students do not need to complete all the topics to complete a test. Rather students or teaching staff may choose 2-3 topics of their own preference out of the test.

<strong>Key Functionality and Scope </strong>

There are a number of things that we do manually each week that we’d like to automate using an app:

<em>Marking attendance:  </em>

Each week during trimesters 1, 2, and 3, students attend an hour and a half meeting. Sometimes students are sick or otherwise unable to attend. We need to keep a record of which students attend which weeks. We’d like to be able to mark attendance using an app that stores weekly attendance data in an SQLite database. Ideally, in future it would be great if there is a single database.

<em>Recording tests </em>

At most weekly meetings, teaching staff run a program that satisfies the requirements for parts of test topics, whole topics or several topics comprising a test. Some weeks we choose not to do related work. Sometimes we hold weekend intensives and do parts, topics or tests at the intensive. We need to be able to record what we did and when.

<h1>Your Task in Detail</h1>

Your assignment comprises four sub-tasks for requirements gathering, design, implementation and administration:

<ol>

 <li><em>Requirements List:</em></li>

</ol>

<table width="346">

 <tbody>

  <tr>

   <td rowspan="2" width="7"> </td>

   <td width="110"><em>Task 1 Deliverable</em></td>

   <td rowspan="2" width="228"><em> </em>Submit a list of requirements. Prioritise the requirements to indicate, which will be covered in your system design and implementation and which will not.</td>

  </tr>

  <tr>

   <td width="110"> </td>

  </tr>

 </tbody>

</table>

<ol start="2">

 <li><em>Design:</em></li>

</ol>

<ul>

 <li>Design a <u>database</u> that can store at least information about o students o completed parts, topics and tests.</li>

 <li>Design an <u>app</u> with the following minimum functionality:

  <ul>

   <li>Add a student to the database, including <em>at least</em> their first name, last name, DOB and which group they attend.</li>

   <li>Record attendance for a weekly meeting or weekend intensives.</li>

   <li>Record parts, topics or tests completed. o Search by name for a student and display their personal details and achievements</li>

  </ul></li>

 <li>Other functionality you may like to consider: o Search for students by other criteria eg: age o Notify teaching staff when a student has</li>

</ul>

competed an entire badge (7 compulsory tests

+ 3 optional tests) o Notify or permit teaching staff to search for parts, topics or tests that have not been widely completed (and thus should be the focus of an upcoming meeting program)

<ul>

 <li>Edit details</li>

 <li>Enter a planned test and the name of the person who will run it.</li>

 <li>A schedule</li>

 <li>Any other requirements you can establish</li>

</ul>

<table width="346">

 <tbody>

  <tr>

   <td rowspan="2" width="7"> </td>

   <td width="117"><em>Task 2 Deliverables</em></td>

   <td rowspan="2" width="221"><em>: </em>showing the functionality<strong>relational database schema</strong> showing theproposed structure of the database  showing the app behaviour forshowing the app structure. Youneed only diagram your classes, not system<strong>windows navigation diagram</strong> showing how allthe screens used by the system are related and how the user moves from one to another.</td>

  </tr>

  <tr>

   <td width="117">•               A <strong>use case diagram </strong>proposed for the new system.•               A•               An <strong>activity diagram </strong>the key use cases. • A <strong>class diagram</strong>generated classes.•               A</td>

  </tr>

 </tbody>

</table>

<ol start="3">

 <li><em> Implementation:</em></li>

</ol>

<ul>

 <li>Implement an app that communicates with a local SQLite database to achieve the following minimum functionality:</li>

</ul>

<ul>

 <li>Add a student to the database, including at least their first name, last name, DOB, which colour six they are in. o Record attendance</li>

 <li>Record parts, topics or tests completed at a weekly meeting or weekend workshop.</li>

 <li>Search by name and display their personal details and achievements</li>

</ul>

<table width="346">

 <tbody>

  <tr>

   <td rowspan="2" width="7"> </td>

   <td width="117"><em>Task 3 Deliverables</em></td>

   <td rowspan="2" width="221"><em>: </em>Your App Project code by Friday 4<sup>th</sup> November,A presentation and demonstration of your app ime by appointment).</td>

  </tr>

  <tr>

   <td width="117">•2014.• functionality (t</td>

  </tr>

 </tbody>

</table>

<ol start="4">

 <li><em> Administration:</em></li>

</ol>

<table width="346">

 <tbody>

  <tr>

   <td rowspan="2" width="7"> </td>

   <td width="262"><em>Task 4 Deliverables (Individual Submission):</em></td>

   <td rowspan="2" width="76"><em> </em>.</td>

  </tr>

  <tr>

   <td width="262">• Each group member must submit a signed statement of how they would like me to divide the100 marks for the project between group participants. Eg: if you believe that every group member contributed equally, then advise me to divide marks equally. If you believe that one or more group members did not contribute equally to the project, you may advise me appropriately• Note that contributions may be made in different manners, but still weighted equally (eg: one person may contribute to design, while another contributes to implementation.</td>

  </tr>

 </tbody>

</table>


