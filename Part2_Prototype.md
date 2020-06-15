# SWEN303 Protect Part 2 - Prototype

__Ahad Rahman (300433299)__

__George Dorrington (300429785)__

__Justina Koh (300441630)__

__Daniel Pullon (300357323)__

__August Bolter (300456915)__

*Assignment Mark Weighting*
* Design Evaluation = 30%
* Prototype = 40%
* Video = 15%
* Reflection = 15%

## Part 1: Background
### Existing Solution

Peerwise is an online learning tool created by Auckland University. It is used in addition to classes and tutorials to help further a student’s understanding of specific course content with minimal lecturer input. 
<br>

At the start of the college term or university trimester, an empty repository is created by the course coordinator. Students can then create questions, answer questions, rate questions and further discuss them.
<br>

While Peerwise has received a lot of positive user feedback, specifically relating to the opportunity to interact and engage with course material. The users also describe the UI as underwhelming, boring and 'discouraging' due to the lacklustre appearance. Many students have stated how this unintuitive UI, has caused them to be less interested in using the app, and has stopped them from using the app altogether.
<br>

Below, we have identified and listed the three main objectives of Peerwise:<br>
1. Enable students to clarify their understanding and support their learning of each course / paper
2. Engage students with course content during trimesters
3. Allow students to learn independently

However, keeping in mind the objectives listed above, there are also issues which we have found in the existing implementation of Peerwise. The top three issues have been listed below: 
<br>

1. The app is / looks outdated
2. The app is unintuitive and can be hard / finicky to use
3. The app is incredibly boring - it is incredibly off-putting to potential users

The combination of the top three issues we have listed with the project is incredibly problematic. This is due to the fact that this combination causes the app to be unusable and deters the user from using it, which defeats the very purpose of the app in the first place. 

There are a number of systems that are similar to Peerwise such as Kahoot, GoSoapBox, and Wooclap. 
<br>

All these services have a large sign up/sign in banner at the top of their home page so that it’s the first thing that you see when you first visit the website. Below this they show people that have used their service. Each persons’ demographics and occupation are shown as well. Therefore, people visiting the website find it easier to identify whether they would use it since they can see if they are similar to the user base. There are also quotes from these users explaining their positive experiences with it. This means visitors of the site will be more likely to use it. 
<br>

These services are similar to Peerwise because each one is catered for students and teachers. They all innovate traditional learning and make learning more interactive and fun for the students. They also have a much more streamlined registration page and have a tutorial on how to sign up. For example, GoSoapBox and Kahoot has a guide on how to get started right after signing up while Peerwise doesn’t. Each service also has a quicker way to register because the username, password and email fields are all on the same page. In comparison to Peerwise where you need to enter your school/institution, click on the register link and then the fields for each registration detail (username, password, course ID and identifier) are shown on separate pages. In particular, the most inconvenient aspect about Peerwise’s registration is that you can only find out your course ID and identifier from your course coordinator. 
<br>

These services also follow a minimalist design, reducing the amount of text shown on the screen to make sure the user is not overwhelmed with information. And each given text is isolated from other nearby text via a border or container which helps the user to take the information in at a good pace. This is shown in Kahoot’s homepage after you login. These services also are more preferable to Peerwise in terms of creating a question or quiz. Take Wooclap for example, their way of creating questions and quizzes gives the user more freedom to customize questions and quizzes since they can have more multiple choice answers, compared to Peerwise which only has 5 at a maximum. Wooclap, unlike Peerwise, allows questions to be in different formats such as polls, open questions, fill in the blank questions etc. These formats are presented in a drop-down list making it convenient for the user to change the format of their question.

#### Business Objectives
Peerwise is a tool instructors (secondary school teachers or university course coordinators) use to set up courses which students can join. Students can then create questions which other students can answer. Additionally, students can rate questions once they have answered them and can filter questions by their topic. They can also start quizzes which are an assortment of questions they have already answered. All these features contribute to Peerwise’s purpose which is to encourage student collaborative learning to ensure that the students have a deeper understanding of the course material

We have identified many issues with the Peerwise app. However, the most pressing concern is: 
<br>
- Peerwise has an outdated and inconvenient interface. It is not user-centric for the modern day student. Peerwise currently doesn’t follow very many design rules - in particular, material design by Google. The way that Peerwise has been designed is hard to use, not very aesthetic and therefore off-putting.

<br>
In order to solve this issue, we have decided that we need to create a modernised interface and design. We will be following the Material Design standard, which was created by Google as it is a widely used standard, and is a familiar aesthetic to people today. Therefore we can trust that by following the standard, we will be able to achieve a website that users will find aesthetically pleasing. 
<br>

By having this improvement, it will make it easier for students to use Peerwise and they will be more incentivised to continue using it in the future. They will also be more likely to recommend it to family and friends. This will lead to a larger user-base that has more returning users (users that revisit Peerwise). It will also help with the key business objectives of Peerwise (listed below):
- Instructors can facilitate collaborative student learning through course creation and activation
- Students can have a deeper understanding of topics by explaining and discussing questions and their answers
- Peerwise has an easy-to-use, convenient and modernised interface and has an aesthetically pleasing design

As mentioned above, we have identified three major issues with the current learning management systems. We believe that our app will address these issues and therefore it will make learning at university an incredibly fun, interesting and exciting experience. Which is why our app is so valuable. 
<br>
As students of the 21st century, we are becoming an increasingly diverse range of people. We now understand that there are an incredibly wide range of people, all with different learning abilities, and recognise that education should be accessible for everyone. The main issue with the current education system is that the way it is designed, it is only suited for a very specific, and minority group of people’s learning styles. Our learning system is designed to help students who may have different learning types to the one that we are used to teaching in schools. Our new, updated learning management system has been designed to help the course content be more accessible and understandable for the students. Therefore, it is obvious that our system’s main objectives is to create: 
<br>
1. An easily navigable system that is intuitive to use
2. The app is designed to be student self-generated. This means that all, or if not most of the content on the website would be made by the students. 
3. As a result, this app should support students to help pass their exams, and understand the course content better
 
Justification for the main core functions:<br>
Our learning management system is supposed to be designed in such a way that is easy and accessible for everyone. While it is easy to assume that the large majority of students are used to technology and the basic, common layout for most apps, it is also important there are also a number of postgraduate, mature students as well as lecturers who may not necessarily be used to technology. Therefore it should be intuitive to use, even for people who aren’t used to technology. 

By having the students create the content for each other (or themselves) it allows them to develop a deeper understanding of what’s going on in the course. Many issues that people often have with lecturers is that the lecturers are highly trained in their course and therefore sometimes forget that the students aren’t as well versed in the subject as they are. By having students create content for students, they are more likely to create the content and write in such a manner that the other students will understand as well. 

### Stakeholder Information
Below we have listed the possible stakeholders along with the power and interests that they hold in the app. We have defined that those with;
- high power: _a person or entity who we want to satisfy with our app functions etc._
- low power: _a person or entity who we aren't so concerned about meeting their needs with the app's functions_
- high interest: _a person or entity who would be highly interested in what the app can currently do, and the development of the app in the future_
- low interest: _a person or entity who is interested in the app, and would like to be occasionally updated as to what the app can do_

Identified stakeholders:
- Lecturers:        low power/High interest
- Students:      high power/High interest
- University:    low power/low interest

The reasoning for the above decisions are listed below: <br>
Lecturer:
- We want this app to be more student centred as it is an app that is supposed to better _student learning_ not lecturer's ability to teach / conveying information to students. Therefore, we have reduced the lecturer to a low power status.
- We would assume that lecturers would be highly interested in an app that would improve student's grades.

Students:
- As this is an app that is created for student use and to help student learning, we have made students a high power status. We care greatly about how they feel about the app, and whether they are enjoying the app or not.
- Students are also high interest individuals as they should be highly interested in what we plan to do with the app in the future etc. 

University:
- We have given the university a lower power status for the same reason we gave the lecturers a low power status. As it is an app that focuses on students, and helping students learn, we won't worry so much about how the university enjoys the app and its functions. 
- We would assume that as the app is supposed to help students learn, then the university would be interested in how the app functions, updates etc. for the app. 
 
#### Possible concerns for stakeholders: 

| Lecturers | Students | University  |
|-----------------|:-------------|:---------------:|
| Is our system better than the current learning management system? | Is our system better than the current learning management system?|Is our system better than the current learning management system?
| Can false or incorrect content be made by other students / non students?| Will incorrect information be created by users? | Will the students and lecturers use this app?|
|Will the app be easy and intuitive to use?|Will the app be easy to use?|Will it cause students to be disengaged and not go to lecture?|
|Will it cause students to be disengaged and not go to lecture?|              |             

#### Importance to StakeHolders
Peerwise is important as it gives students another way to learn course material. If students keep learning in the same way they are more likely to become demotivated and unenthusiastic about learning so they will find it harder to take in course material. This might lead them to submitting lower quality assignments/projects and/or performing worse in exams. Peerwise is also important because it allows students to learn from each other and they can give each other different views and opinions on topics which they may not have thought about. This results in a much deeper understanding of the topic.<br>
Peerwise also helps teachers because it ensures that students aren’t relying solo on the teachers perspective of the topic. Having only one perspective of the topic can potentially create biases and can limit how well students can comprehend the material. This in turn may affect the students grades therefore it should be avoided. <br>
This also alleviates some of the teachers and professors workload by getting the students to help each other on topics that they are confused about, and the teacher won’t need to spend their time helping each troubled student individually. This means that teachers will be able to teach more topics to the students and/or dive deeper into the topics they are already teaching. <br>


## Part 2: Personas

### Selected personas in order of priority (from most to least important):

* [Student Engaged - Sally](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2020/project1/t16/swen303-project/-/blob/master/Personas/Engaged_Student.pdf)
* [Student Disengaged - Liam](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2020/project1/t16/swen303-project/-/blob/master/Personas/Disengaged_Student.pdf)
* [Lecturer - Daniel](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2020/project1/t16/swen303-project/-/blob/master/Personas/Lecturer.pdf)
* [Tutor - Veronica](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2020/project1/t16/swen303-project/-/blob/master/Personas/Tutor.pdf)


### Merging of personas background
To begin each group shared their personas and the qualities associated with them. It was identified that each group had similar titles for their personas and these were:
* Course Coordinator
* Lecturer
* Tutor
* Engaged student
* Neutral student
* Disengaged student

This was followed by some constructive discussion about the number of personas the group wanted to pursue. It was recognised that the group wanted to focus on the base case personas which minimises the overlap between each persona. A specific example of this is originally there were personas for engaged, neutral and disengaged students, and it was agreed to deselect neutral students because it was difficult to differentiate how a neutral student would use the Peerwise application differently to a disengaged student. The group remained open to creating another persona later in the development of the PeerWise application if required. The group then decided on the need to identify four persona titles to use during the development stage of the prototype. This process was not as easy as the group expected because individuals had a preference for their own personas, due mainly to them having a deeper understanding of their characteristics. The group ultimately agreed on the following four personas:

* Lecturer
* Tutor
* Engaged Student
* Disengaged Student

As the group progressed through the project, it was recognised that time was a restraint, therefore the priority was to complete a prototype for testing. To mitigate the time constraint, the group decided it was unnecessary to standardise the look and feel of the personas, as the most important aspects were title and the content, and they could still be used effectively within the development stage of the prototype. There was a significant amount of commonality within the detail of the personas relating to attitude, aptitude, motivation and skills, which led to the group reaching agreement on the Persona detail relatively quickly.


## Part 3: Scenarios

1. Create Course (Personas Involved: Sarah)

This use-case describes the process of an instructor creating a course which students can then join.

2. Create Question/Quiz (Personas Involved: Sally, Liam and Veronica)

This use-case describes the process of a student or instructor creating a question/quizzes

3. Answer Question/Quiz (Personas Involved: Sally, Liam and Veronica)

This use-case describes how users answer questions/quizzes on PeerWise

4. Login (Personas Involved: Sally, Liam, Sarah and Veronica)

This use-case describes the login process

5. Modify Question/Quiz (Personas Involved: Sally, Liam and Veronica)

This use-case describes editing an existing question/quiz

6. Edit Course (Personas Involved: Sarah)

This use-case describes how instructors edit their courses

7. View Question/Quiz (Personas Involved: Sally, Liam and Veronica)

This use-case describes how a question/quiz is displayed for instructors/students to view

8. View leaderboards (with badges) (Personas Involved: Sally, Liam, Sarah and Veronica)

This use-case describes how the leaderboards/badges are displayed for instructors/students to view

##### How we merged our use-cases
First, we assigned every team member to read all the use-cases and to select the most important ones. We created an issue for this in Gitlab and all team members were assigned to it. Then in our next Zoom meeting we went over each other's documents, comparing them and looking for similarities. In our final selection of use-cases we included every use-case that was in more than one document and we included some use-cases that was only in one document if we agreed that they were important (e.g. The Edit Course use-case was only in Ahad and George’s use-cases document).

Merging personas assigned to use-cases:
After determining our final use-cases we had to merge the roles assigned for these use-cases since we had different roles for the same use-case. For example, I assigned only students to create, edit and view questions/quizzes but Justina and Daniel also assigned instructors (lecturers) to this. We discussed and resolved every role conflict our use-cases had resulting in a list of use-cases with personas/roles associated with each one.

Merging use-case rankings:
Finally, we had to merge the use-case rankings. None of our most important use-cases documents were ranked so I obtained the ranking of the use-cases from
our assignment documents. I then averaged all our rankings for each use-case and sorted the use-cases from highest average ranking to lowest average ranking.
How I calculated the rankings can be seen below.

**Ranking calculations:**

Create Question/Quiz (August: (1 - (3/14)) (78.6%), Ahad and George (1 - (4/7)) (42.86%), Justina and Daniel (1 - (1/5)) (80%) Average 67.2%)

Answer Question/Quiz (August: (1- (4/14)) (71.4%), Ahad and George (1 - (5/7)) (28.6%), Justina and Daniel (1 - (0/5)) (100%), Average 66.7%)

View Question/Quizzes (August: N/A, Ahad and George (1 - (6/7)) (14.29%), Justina and Daniel N/A, Average 14.29%)

Login (August: N/A, Ahad and George (1 - (1/7)) (85.72%), Justina and Daniel (1 - (4/5)) (20%), Average 52.86%)

View leaderboards (with badges) (August: (1 - (14/14)) (0%), Ahad and George N/A, Justina and Daniel N/A, Average 0%)

Create Course (August: (1 - (2/14)) (85.7%), Ahad and George (1 - (2/7)) (71.44%), Justina and Daniel N/A, Average 78.57%)

Edit Course (August: N/A, Ahad and Geroge (1 - (3/7)) (42.85%), Justina and Daniel N/A, Average 42.85%)

Modify Question/Quiz (August: (1 - (6/14)) (57.2%), Ahad and George (N/A), Justina and Daniel (1 - (3/5)) (40%), Average 48.6%)


## Part 4: Design ideation

[Ahad and George](Designs/Final_Peerwise_Designs.xd)


Justina and Daniel:
<br>
[Web](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2020/project1/t16/swen303-project/-/blob/master/Designs/SWEN303_Assignment_2_Justina_and_Daniel.xd)
<br>
[Mobile](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2020/project1/t16/swen303-project/-/blob/master/Designs/swen303-A2-_Mobile_-_Justina_and_Daniel.xd)

[August](Designs/Assignment_2_Information_Hierarchy_Final.xd)


## Part 5: Design review

# Ahad + George:

## Pros:

**Consistency** 

*  All pages look like they belong to the same website, even when viewing on mobile.
*  The body text has the same font in different pages (font selection is consistent)
*  The mobile design is consistent with the web (non-mobile) design

**Recognition**

*  Follows Google's guidelines, so users familiar with Google products will be able to pick up Peerwise.
*  Familiar icons and shortcuts which support an intuitive feel

**Language** 

*  Uses language that matches the user-base (university students and staff) vocabulary (e.g. Course codes)

**Minimalism**

*  Only the most important elements are shown to the user. No unnecessary controls that can be interpreted as confusing. Also a careful use of colour, to not overwhelm or distract the user.
*  Practical layout enables the user to easily interact with the site, irrespective of the frequency of use

**Status**

*  Shows the user useful status information like how many students are online

**Shortcuts**

*  Enables lecturers to add a CSV file directly to add students rather than adding them all individually

## Cons:

**Shortcuts**

*  No shortcuts currently implemented, to do frequent use cases. Have to do everything with mouse and going back to Dashboard

**Help**

*  There is no guidance for the user upon first use of the application, could look into the idea of having 'text bubbles' popping up on first interaction with system
*  Lacks advanced features such as text reading aloud, which is an important consideration for hearing-impaired students
*  Lacks a way for users to give feedback to PeerWise

# Daniel + Justina:

## Pros:

**Consistency**

*  Layout and general design style remains consistent throughout the website.
*  A bright consistent colour scheme is used throughout the website
*  A bright consistent colour scheme is used throughout the website
*  The body text has the same font in different pages (font selection is consistent)
*  The mobile app design is consistent with the website design. This allows for easy switching between the two interfaces.

**Language**
*  Uses language that matches the user-base (university students and staff) vocabulary (e.g. Course codes)
*  Buttons are self-descriptive. I know what I am expecting when clicking a button.

**Recognition**
*  Text hyperlinks are underlined and blue which is the standard style for hyperlinks meaning it is easy for users to recognise that the text is a hyperlink.
*  Icons used are very ‘typical’ and are icones that there is a global understanding of what they mean. 

**Help**
*  A colour blind mode is available, so the design accounts for colour blind people
*  The buttons and layout of the app is very clear and obvious. This means that the app is very intuitive to us and no explanation is needed
*  Students can give feedback to the lecturer

**Status**
*  Tells the user what courses they are in via a dropdown menu

**Error Prevention** 
*  The app has been made in such a simple way that there is no need for error prevention messages. 


## Cons:

**Control**

*  Users found it unintuitive that clicking the owl would go back home. Can't go back to the screen. Need to go back to the homepage.

**Minimalism**

*  I feel like it's just a bit too much colour. This can be garish to some, and it may also be problematic for others who have colour blindness.
*  Not enough space between components on the web page, this results in the components looking a bit cramped up
*  There is a tiny bit too much colour which can detract away from the overall effectiveness of the design.
*  Not enough space between components on the web page, this results in the components looking a bit cramped up

**Consistency**
*  The design is always intuitive to the creator, however it must always be tested by a sample target audience. An example would be seeing which button people click to ‘Ask a question’.

**Status**
*  Lacks status updates such as popups when the user is hovering over options. 

**Shortcuts**
*  No shortcuts currently implemented, to do frequent use cases. Have to do everything with mouse and going back to Dashboard


# August:

## Pros:

**Consistency**

*  Layout and general design style remains consistent throughout the website.

**Recognition**

*  Uses a footer to include facebook, instagram and twitter pages. Other project didn't consider this aspect 

**Control**

*  Navigation bar is always present on every screen. Users always have the ability of what they want to do from where they are.

**No errors**

*  Dialog box makes it clear to the user what will happen after the user has made a choice. Buttons are self-descriptive.
*  A confirmation dialogue appears when the user chooses to edit or delete their question, this ensures that the user doesn’t accidentally edit/delete the question.

**Minimalism**

*  Guidelines about creating questions are shown in a separate window, to reduce the amount of text on screen for the creating a question page

**Status**

*  When the user hovers over a row in the table it darkens

**Shortcuts**

*  The navigation bar allows the user to jump to different pages of the website

**Help**

*  Users can give feedback to PeerWise via a feedback form

## Cons:

**Consistency**

*  Main background colour for web pages is not consistent, i.e. dark grey, dark blue and light blue are all background colours.

**Minimalism**

*  I feel like it's just a bit too much colour. Not a huge fan of using blue as background colour.
*  Some areas are over crowded with text

**Status**

*  Lacks status ideas such as loading and progression bars, however this is a mockup design and doesn't implement all 'active' features


## Part 6: Usability Test plan

### Methodology:
The testing methodology we have decided to go with is usability testing. Usability testing is where a facilitator asks participants to perform tasks using the Peerwise website interface, whilst the participant completes each task, the facilitator will observe the participants behaviour, listen for feedback, and measure metrics we have previously defined. Usability testing can help to identify the following:

* Problems / bugs in the design
* Help discover opportunities to improve
* Learn about the target users behaviour and preferences

We are testing six users external to the group, all six users will all be tested in the same areas to ensure consistency across results but will be carried out by different testers due to time constraints. We want to test all areas of the Peerwise and will put strong focus on creating questions, asking questions, and viewing questions as these are key usecases of the website. Other functionalities such as logging in and out as student and staff, checking leaderboard progress, and adding students to repositories will be tested however will take a reduced focus.

### The Script:
The guidelines are specifically chosen in order to minimise the possibility of bias occurring due to the impression that the tester may give the testee. These guidelines are very similar to the guidelines given to researchers when carrying out experiments in a [clinical setting](https://www.racked.com/2017/6/27/15757720/therapist-outfit-uniform-patients-healing). Below is the Script given to users.

__Welcome and Purpose:__

First of all, I’d just like to thank you for coming in today and partaking in this event. Firstly, I wanted to give you some information about what you will be doing and give you some time to ask any questions before we get started.

Today we are asking you to serve as an evaluator of a website and to complete a set of tasks. Our goal is to see how easy or difficult you find the site to use.

__Test Facilitator's Role:__

I am here to record your reactions and comments on the website you will view.

During this session, I would like you to think out loud as you work to complete the tasks. If you get stuck, I can provide some minor assistance after asking you to clarify what you have said, what you are doing at that moment, what you are expecting to happen and what your reasoning is behind what you are doing.
 
Now I am going to read out loud to you what you are going to be doing today. 

__Test Participant’s Role:__

Today I will be asking you to access particular features on our site, and how easy or difficult it was to find the information. Your performance in the following tasks I will be asking you to carry out will determine how easy or difficult we have made it for people to use the site.

With these tasks there are no right or wrong answers. If you would like some clarification on the task or comments on the task, please let me know.

Please try, with the best of your ability to complete all the tasks. If you ever feel that you are unable to complete a task with the information that we have given you, please let me know. I will either put you on the right track or move you onto the next task.

When you are using this site, use it as if you were using it from your home or your office. 

Do you have any questions before we begin?

__Tasks:__

_User acting as student_

1. Can you login to our website?
2. Are you able to create a quiz?

	a) Now, can you preview the quiz?
	
	b) Now, can you edit the quiz?
	
	c) Now, can you post a quiz?
	
3. Are you able to complete a quiz?

	a) Try filter the quizzes to only show your quizzes
	
	b) Can you hide ‘Exam Prep’ quizzes?
	
	c) Can you open ‘How to find good ghostwriters’ quiz?
	
	d) Try to Submit the quiz
	
	e) Try to make a dispute for Question 2
	
	f) What percentage of students answered A for question 2?
	
	g) Try to return to the Dashboard
	
4. Can you view the Leaderboards?

	a) Try return to the Dashboard

5. Can you log out of the website?

_User acting as staff member_

1. Can you login as staff?
2. Can you create a new course?

	a) Can you enrol a student?
	
3. Can you view course info for COMP313?

	a) Can you edit the name?
	
	b) Can you delete the course?
	
### Roles:

__All Members:__

To test our prototype we decided to pair up with another group that made their prototype for a different client (different than Peerwise). Testing prototypes for different clients will result in more accurate test results for both groups as we will have no prior knowledge of the system and therefore no bias. The group we paired up with consists of the members; Caitlin Goodger, Logan Brantley, William Torkington, Rose Sharkey, Harrison Compton and Fabian Fagan. We agreed that each team member would pair up with a member from the other team and each pair would fully test each other’s prototype based on the script, metrics and usability goals we’ve written.

The pairs are as follows:
* Ahad and Caitlin
* Daniel and Logan
* George and William
* Justina and Rose
* August and Harrison
* August and Fabian

__August:__

August is in charge of creating, editing and finalizing this section of the Usability Test plan.

__Justina:__

Justina is in charge of creating, editing and finalizing the ‘Script’ section of the Usability Test plan.

__Ahad:__

Ahad is in charge of creating, editing and finalizing the ‘Tasks’ section of the Usability Test plan, and working with Justina to develop the tasks section of the Script.

__Daniel:__

Daniel will be working on the ‘Metrics’ section of the Usability Test Plan. Daniel (and Ahad) developed the prototype, so he has a good understanding of the system hence we thought it would be a good idea that he helped develop the testing metrics. He also is responsible for the ‘Usability Goals’ section since it is related to the ‘Metrics’ section.

__George:__

George is in charge of creating, editing and finalizing the ‘Methodology’ section of the Usability Test Plan.

### Tasks:
The tasks we will set out for our users while testing will cover our use cases. We described our use cases as what we believe to be the most important actions users will do with Peerwise. Our prototype covers all of the use cases outlined in part 1 of the project. The substeps show extra tasks that we expect the user to complete. Please note that this is not what we will ask the user to do (which can be found in the Script), but it is a reference for us testers to ensure they are completing the tasks correctly.

_User acting as student_

1. Login
2. Create Quiz

	a) Enter quiz name
	
	b) Add Question to quiz
	
	c) Preview quiz
	
	d) Edit quiz
	
	e) Post quiz
	
3. Answer Quiz

	a) Show only user’s quizzes
	
	b) Hide ‘Exam Prep’ quizzes
	
	c) Open ‘How to find good ghostwriters’ quiz
	
	d) Submit quiz
	
	e) Make a dispute for Question 2
	
	f) View statistics for Question 1 and 2
	
	g) Return to quizzes
	
	h) Return to Dashboard
	
4. View Leaderboards

5. Log out

_User acting as staff member_

1. Manage courses
2. Create a new course

	a) Enter course name
	
	b) Enrol a student
	
	c) Create the course
	
3. View course info for COMP313

	a) Edit course name
	
	b) Delete course


### Metrics:

* Did they complete the task?
* Did they complete all subtasks?
* How long did they take to complete the task?
* How many times did they fail the task before they completed it?
* Did they need clarification or help?
* Did they make any mistakes?
* How long did it take to undo that mistake?
* Did they need to alter the page in some way (eg. zoom in to read)?
* How many clicks did the task take?
* Are there any bugs? Did the bugs stop them progressing?


### Usability Goals:

__Successful testing of the website__

If they met all of the criteria set out by the metrics then we can be more confident that our website is robust.

__Failures found through the testing__
* If they don’t complete the task
* If it takes them longer than 60 seconds to complete any task
* If they needed help to complete the task
* If they failed the task 3 times
* If it took more than 10 seconds to undo a mistake
* If they had to change the page to complete the task (eg. zoom in, alter colours, remove things)
* If they clicked more than 15 times to complete a task (not including mistakes)
* If the bug prevented them from completing the test or caused them to restart the test


### Problem Severity:


## Part 7: Usability Test Results

__Ahad's testing on Caitlin__

|                              | Did they complete the task? | Did they complete all subtasks? | How long did they take to complete the task? | How many times did they fail the task before they completed it? | Did they need clarification or help?                                                                                                                                        | Did they make any mistakes?                                                                                                                                                                                                                                                       | How long did it take to undo that mistake? | Did they need to alter the page in some way? | How many clicks did the task take? | Are there any bugs? Did the bugs stop them progressing?                                                             |
|------------------------------|-----------------------------|---------------------------------|----------------------------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------|----------------------------------------------|------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| Login                        | Yes                         | Yes                             | 3s                                           | N/A                                                             | No                                                                                                                                                                          | No                                                                                                                                                                                                                                                                                | N/A                                        | No                                           | 1                                  | No                                                                                                                  |
| Create quiz                  | Yes                         | Yes                             | 1 min                                        | Twice                                                           | 1) Yes, had to tell them to add a quiz name first 2) After they got sent to the dashboard, they were confused if the quiz was created or not                                | Yes, tried to post question before previewing it                                                                                                                                                                                                                                  | 5s                                         | No                                           | 8                                  | Not a bug, but bad UI which doesn't indicate they need a quiz name and if the quiz was successfully posted or not.  |
| Answer quiz                  | Yes                         | Yes                             | 2 mins 30s                                   | Three                                                           | 1) Yes, had to tell them they need to click “Choose Quiz” from dashboard to answer a quiz 2) Could not find a switch to show only the user’s quizzes so I had to tell them, | 1) Yes, they couldn’t find where to find all the quizzes. 2) To try to show the user’s question, they were clicking on the author column. 3) Also thought the statistics for question 2 would be next to the question, not near the bottom, but they figured it out on their own. | 5s and 10s                                 | No                                           | 20                                 | No bugs                                                                                                             |
| View Leaderboards            | Yes                         | Yes                             | 8s                                           | N/A                                                             | No                                                                                                                                                                          | No                                                                                                                                                                                                                                                                                | N/A                                        | No                                           | 2                                  | No                                                                                                                  |
| Log Out                      | Yes                         | Yes                             | 5s                                           | None                                                            | No                                                                                                                                                                          | No                                                                                                                                                                                                                                                                                | N/A                                        | No                                           | 2                                  | No                                                                                                                  |
| Login as Staff               | Yes                         | Yes                             | 3s                                           | None                                                            | No                                                                                                                                                                          | No                                                                                                                                                                                                                                                                                | N/A                                        | No                                           | 1                                  | No                                                                                                                  |
| Create a new course          | Yes                         | Yes                             | 20s                                          | N/A                                                             | Yes                                                                                                                                                                         | No                                                                                                                                                                                                                                                                                | N/A                                        | No                                           | 5                                  | No                                                                                                                  |
| View course info for COMP313 | Yes                         | Yes                             | 15s                                          | No                                                              | No                                                                                                                                                                          | No                                                                                                                                                                                                                                                                                | N/A                                        | No                                           | 5                                  | No                                                                                                                  |

__August's testing on Harrison__

|                              | Did they complete the task? | Did they complete all subtasks? | How long did they take to complete the task? | How many times did they fail the task before they completed it? | Did they need clarification or help?                                                                         | Did they make any mistakes?                                                                                                                                                   | How long did it take to undo that mistake? | Did they need to alter the page in some way? | How many clicks did the task take? | Are there any bugs? Did the bugs stop them progressing?                                          |
|------------------------------|-----------------------------|---------------------------------|----------------------------------------------|-----------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------|----------------------------------------------|------------------------------------|--------------------------------------------------------------------------------------------------|
| Login                        | Yes                         | Yes                             | 3s                                           | Zero                                                            | No                                                                                                           | No                                                                                                                                                                            | N/A                                        | No                                           | 1                                  | No                                                                                               |
| Create quiz                  | Yes                         | Yes                             | 38s                                          | Once                                                            | Yes, I had to explain that they had missed the edit button and needed to edit the quiz before submitting it. | Yes. They submitted the quiz after previewing it instead of editing the quiz after previewing it (but before submitting it). This is because they didn’t see the edit button. | 10s                                        | No                                           | 9                                  | No                                                                                               |
| Answer quiz                  | Yes                         | Yes                             | 1min 15s                                     | Once                                                            | Yes                                                                                                          | Yes. They didn’t realize you had to filter quizzes to see your own quizzes first before filtering them by topic. So, I had to explain that to them                            | 15s                                        | No                                           | 13                                 | Yes (quizzes should be able to be filtered without having to first only be viewing your quizzes) |
| View Leaderboards            | Yes                         | Yes                             | 4s                                           | Zero                                                            | No                                                                                                           | No                                                                                                                                                                            | N/A                                        | No                                           | 2                                  | No                                                                                               |
| Log Out                      | Yes                         | Yes                             | 3s                                           | Zero                                                            | No                                                                                                           | No                                                                                                                                                                            | N/A                                        | No                                           | 2                                  | No                                                                                               |
| Login as Staff               | Yes                         | Yes                             | 2s                                           | Zero                                                            | No                                                                                                           | No                                                                                                                                                                            | N/A                                        | No                                           | 1                                  | No                                                                                               |
| Create a new course          | Yes                         | Yes                             | 23s                                          | Zero                                                            | No                                                                                                           | No (but they did take quite a long time to realise that the manage courses section was what he needed to click)                                                               | N/A                                        | No                                           | 4                                  | No                                                                                               |
| View course info for COMP313 | Yes                         | Yes                             | 11s                                          | Zero                                                            | No                                                                                                           | No                                                                                                                                                                            | N/A                                        | No                                           | 5                                  | No                                                                                               |

__General notes:__
* Harrison said it took him a while to find the manage courses section because the admin homepage looked so similar to the student homepage (which he had just tested)
* Harrison said the edit button was also quite easy to miss

__August's testing on Fabian__

|                              | Did they complete the task? | Did they complete all subtasks? | How long did they take to complete the task? | How many times did they fail the task before they completed it?                            | Did they need clarification or help?                                   | Did they make any mistakes?                                                                   | How long did it take to undo that mistake? | Did they need to alter the page in some way? | How many clicks did the task take? | Are there any bugs? Did the bugs stop them progressing? |
|------------------------------|-----------------------------|---------------------------------|----------------------------------------------|--------------------------------------------------------------------------------------------|------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|--------------------------------------------|----------------------------------------------|------------------------------------|---------------------------------------------------------|
| Login                        | Yes                         | Yes                             | 8s                                           | Zero                                                                                       | No                                                                     | No                                                                                            | N/A                                        | No                                           | 3                                  | No                                                      |
| Create quiz                  | Yes                         | Yes                             | 52s                                          | Once (couldn’t preview quiz before adding question, so they posted quiz before previewing) | Yes, had to explain they could only preview once they added a question | Tried to post quiz before previewing it                                                       | 8s                                         | No                                           | 10                                 | No                                                      |
| Answer quiz                  | Yes                         | Yes                             | 1 min 30s                                    | Once                                                                                       | Yes, for explaining where the filter is                                | Yes, couldn’t initially find the filter that filters quizzes to only show their own quizzes.  | 7s                                         | No                                           | 10                                 | No                                                      |
| View Leaderboards            | Yes                         | Yes                             | 6s                                           | Zero                                                                                       | No                                                                     | No                                                                                            | N/A                                        | No                                           | 2                                  | No                                                      |
| Log Out                      | Yes                         | Yes                             | 6s                                           | Zero                                                                                       | No                                                                     | No                                                                                            | N/A                                        | No                                           | 2                                  | No                                                      |
| Login as Staff               | Yes                         | Yes                             | 3s                                           | Zero                                                                                       | No                                                                     | No                                                                                            | N/A                                        | No                                           | 1                                  | No                                                      |
| Create a new course          | Yes                         | Yes                             | 20s                                          | Once (tried to create course then enrol students)                                          | Yes                                                                    | One                                                                                           | 4s                                         | No                                           | 7                                  | No                                                      |
| View course info for COMP313 | Yes                         | Yes                             | 22s                                          | Zero                                                                                       | No                                                                     | No                                                                                            | N/A                                        | No                                           | 5                                  | No                                                      |


__Justina's testing on Rose__

|                              | Did they complete the task? | Did they complete all subtasks? | How long did they take to complete the task? | How many times did they fail the task before they completed it? | Did they need clarification or help?                               | Did they make any mistakes? | How long did it take to undo that mistake? | Did they need to alter the page in some way? | How many clicks did the task take? | Are there any bugs? Did the bugs stop them progressing?                                                                                                                                                      |
|------------------------------|-----------------------------|---------------------------------|----------------------------------------------|-----------------------------------------------------------------|--------------------------------------------------------------------|-----------------------------|--------------------------------------------|----------------------------------------------|------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Login                        | Yes                         | Yes                             | 1s                                           | 0                                                               | No                                                                 | No                          | N/A                                        | No                                           | 3                                  | No                                                                                                                                                                                                           |
| Create quiz                  | Yes                         | Yes                             | 1 min 2 seconds                              | 0                                                               | No                                                                 | No                          | 8s                                         | No                                           | 10                                 | No                                                                                                                                                                                                           |
| Answer quiz                  | Yes                         | Yes                             | 3mins 2 s                                    | Once                                                            | Had to explain how to find preview                                 | No                          | N/A                                        | No                                           | 20                                 | No, however she was very ‘trigger happy’ and would click around the page on things that weren't part of the task. She later clarified that it was because she was interested on all the features on the page |
| View Leaderboards            | Yes                         | Yes                             | 10s                                          | 0                                                               | No                                                                 | No                          | N/A                                        | No                                           | 2                                  | No                                                                                                                                                                                                           |
| Log Out                      | Yes                         | Yes                             | 7s                                           | 0                                                               | No                                                                 | No                          | N/A                                        | No                                           | 2                                  | No                                                                                                                                                                                                           |
| Login as Staff               | Yes                         | Yes                             | 30s                                          | 0                                                               | Had to point out that there was a staff login located on the page  | No                          | N/A                                        | No                                           | 3                                  | No                                                                                                                                                                                                           |
| Create a new course          | Yes                         | Yes                             | 50s                                          | 0                                                               | Yes                                                                | No                          | N/A                                        | No                                           | 10                                 | No                                                                                                                                                                                                           |
| View course info for COMP313 | Yes                         | Yes                             | 40s                                          | 0                                                               | No                                                                 | No                          | N/A                                        | No                                           | 9                                  | No                                                                                                                                                                                                           |

__General notes:__

* Rose found our UI and design very cool and would often click around on the page even though she knew that it wouldn’t help her on the task. She was just interested in what it was.
* A bug was found involving the staff page. When she clicked on the courses while in the staff login, you would be transported to the student’s page. 
When reading the answers, the candidate found that


__George's testing on William__

|                              | Did they complete the task? | Did they complete all subtasks? | How long did they take to complete the task? | How many times did they fail the task before they completed it? | Did they need clarification or help?                               | Did they make any mistakes? | How long did it take to undo that mistake? | Did they need to alter the page in some way? | How many clicks did the task take? | Are there any bugs? Did the bugs stop them progressing?                                                                                                                                                      |
|------------------------------|-----------------------------|---------------------------------|----------------------------------------------|-----------------------------------------------------------------|--------------------------------------------------------------------|-----------------------------|--------------------------------------------|----------------------------------------------|------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Login                        | Yes                         | Yes                             | 1s                                           | 0                                                               | No                                                                 | No                          | N/A                                        | No                                           | 3                                  | No                                                                                                                                                                                                           |
| Create quiz                  | Yes                         | Yes                             | 1 min 2 seconds                              | 0                                                               | No                                                                 | No                          | 8s                                         | No                                           | 10                                 | No                                                                                                                                                                                                           |
| Answer quiz                  | Yes                         | Yes                             | 3mins 2 s                                    | Once                                                            | Had to explain how to find preview                                 | No                          | N/A                                        | No                                           | 20                                 | No, however she was very ‘trigger happy’ and would click around the page on things that weren't part of the task. She later clarified that it was because she was interested on all the features on the page |
| View Leaderboards            | Yes                         | Yes                             | 10s                                          | 0                                                               | No                                                                 | No                          | N/A                                        | No                                           | 2                                  | No                                                                                                                                                                                                           |
| Log Out                      | Yes                         | Yes                             | 7s                                           | 0                                                               | No                                                                 | No                          | N/A                                        | No                                           | 2                                  | No                                                                                                                                                                                                           |
| Login as Staff               | Yes                         | Yes                             | 30s                                          | 0                                                               | Had to point out that there was a staff login located on the page  | No                          | N/A                                        | No                                           | 3                                  | No                                                                                                                                                                                                           |
| Create a new course          | Yes                         | Yes                             | 50s                                          | 0                                                               | Yes                                                                | No                          | N/A                                        | No                                           | 10                                 | No                                                                                                                                                                                                           |
| View course info for COMP313 | Yes                         | Yes                             | 40s                                          | 0                                                               | No                                                                 | No                          | N/A                                        | No                                           | 9                                  | No                                                                                                                                                                                                           |

__Positive Points:__

* Strong design aspects and consistency
* Good use of contrast and simple colour scheme
* Home dashboard provides ease of use and navigation

__Negative Points:__

* Staff login was hard to find
* Change ‘Choose quiz’ to ‘Answer quiz’
* Remove underlines on main dashboard
* Edit functionality is confusing to access could have a message banner across the top which tells you which view you are in


__Daniel's testing on Logan__

|                              | Did they complete the task? | Did they complete all subtasks? | How long did they take to complete the task? | How many times did they fail the task before they completed it? | Did they need clarification or help?                                                                       | Did they make any mistakes?                        | How long did it take to undo that mistake? | Did they need to alter the page in some way? | How many clicks did the task take? | Are there any bugs? Did the bugs stop them progressing? |
|------------------------------|-----------------------------|---------------------------------|----------------------------------------------|-----------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|----------------------------------------------------|--------------------------------------------|----------------------------------------------|------------------------------------|---------------------------------------------------------|
| Login                        | Yes                         | Yes                             | 3 seconds                                    | 0                                                               | No                                                                                                         | No                                                 | N/A                                        | No                                           |  1                                 |  No                                                     |
| Create quiz                  | Yes                         | Yes                             | 20 seconds                                   | 0                                                               | Yes, there was some confusion surrounding the titles of the headings Topics and Explanations               | No                                                 | N/A                                        | No                                           |  4                                 |  No                                                     |
| Answer quiz                  | Yes                         | Yes                             | 50 seconds                                   | 0                                                               | No                                                                                                         | No                                                 | N/A                                        | No                                           |  4                                 |  No                                                     |
| View Leaderboards            | Yes                         | Yes                             | 10 seconds                                   | 0                                                               | No                                                                                                         | No                                                 | N/A                                        | No                                           |  1                                 |  No                                                     |
| Log Out                      | Yes                         | Yes                             | 30 seconds                                   | 0                                                               | Yes, they clicked on the name expecting that to open the dropdown menu when currently only the arrow works | Yes, as stated they need guidance on what to click | 3 seconds                                  | No                                           |  6                                 |  No                                                     |
| Login as Staff               | Yes                         | Yes                             | 6 seconds                                    | 0                                                               | No                                                                                                         | No                                                 | N/A                                        | No                                           |  1                                 |  No                                                     |
| Create a new course          | Yes                         | Yes                             | 20 seconds                                   | 0                                                               | No                                                                                                         | No                                                 | N/A                                        | No                                           |  6                                 |  No                                                     |
| View course info for COMP313 | Yes                         | Yes                             | 40 seconds                                   | 0                                                               | No                                                                                                         | No                                                 | N/A                                        | No                                           |  2                                 |  No                                                     |


## Part 8: Usability Test Discussion

__What was the most interesting thing found from testing__

While the majority of feedback from our users were overwhelmingly positive, we found that there were many things that we hadn’t realised would be an issue or hadn’t thought about. The most interesting thing found from testing is below:

> When designing an interface it is important to consider that the design is always intuitive to the developer but might not be as intuitive to the test subjects.

While this may seem like common sense, we didn’t realise how prevalent this issue would be in our website. We assumed that these features would be intuitive but when users tested them they struggled to understand them to the same degree that we did. An example of this was the log out button. We assumed the dropdown menu to log out was intuitive for users, but some users struggled with this.

Below are some additional interesting findings from user testing.

1. Different people have different ways of navigating interfaces. E.g. Some people liked to take their time testing the interface, trying out different components whereas others rushed through it.

Each of the testers varied in the time taken, and approach they took to complete the tasks. We found that some testers got ‘competitive’ (despite us telling them to take their time, and without us revealing any other time metric) and would race through the tasks as fast as possible, and other users were more meticulous and try to read everything on the page to really make sure that they were clicking the right buttons.

2. Users become ‘trigger happy’. This was hard because we had not implemented all the features of the Peerwise website yet due to time constraints

We discovered that some of the testers would try to click on features that they knew would not help them with their assigned task.

3. Users really appreciate a consistent interface across the entire website 

By utilising the same interface throughout the website, the users were able to easily navigate the pages. It also reduced the learning curve required to be able to become “fluent” in using the website. 

4. Prioritising usability over aesthetics

While it is important to ensure that the aesthetic of the website is palatable and pleasing to the eye, usability is of greater importance, usability covers both aspects as in order to enhance usability, it is important that aesthetics are covered therefore when usability is a priority, aesthetics will be included.

5. The way language is used to describe the website is important

As developers, we have a better understanding than others who do not know the structure and therefore we had titles that were ambiguous to users. For example, on the ‘Create Quiz’ page the Explanation and Topics titles are ambiguous need clarification.

6. Users will have a different level of ability. 

We found that it was important to gather specific, quantifiable information rather than general descriptive feedback. For example it is more useful to look at things such as how many clicks it takes rather than if somebody found the program to be fast. This is because it is important for us to have objective information that can be ranked and sorted. 

One of the things that we discovered when carrying out the user testing was that when we asked people what they thought about our website and if they had any feedback for us, they would often hesitate and give very vague and/or only positive feedback to us. It was only after we asked leading questions about the statements that they gave us, that they would give us proper feedback. 

__What was the most significant result__

The most significant result we discovered from user testing is that we have a lack of status. Status trackers are pulling information, progress updates are pushing information, both can be used to track the current case of the user. When they work together effectively, users are informed and in control, potentially reducing anxiety. There were scenarios where the user was unsure what the system was conveying to them when completing tasks. This could be addressed by user interface components such as: 

1. Loading / progress bars

Progress bars inform the users how close they are to completing a set of tasks. This can be done through the use of percentages or a loading ‘circle’ as seen below.

<img src="https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2020/project1/t16/swen303-project/-/raw/master/Resources/loading.png">

2. Snack bars

Snackbars inform the user of a process that has been performed, will perform or why it wont perform. They appear temporarily, often at the top or bottom of the screen and should not impair the overall user experience.

<img src="https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2020/project1/t16/swen303-project/-/raw/master/Resources/snackbar.png">

3. Popup information boxes

A popup information box requires the user to interact with it and is designed to receive a specific response from the users. The box often contains important information where users need to make decisions.

The aforementioned components help to inform the user on the task that is currently being performed or the restrictions on why it cannot be performed. Implementing some of these components into the Peerwise website should help to reduce confusion and increase satisfaction.

<img src="https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2020/project1/t16/swen303-project/-/raw/master/Resources/snackbar.png">



