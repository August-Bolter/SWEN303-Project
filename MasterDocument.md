# SWEN303 Protect Part 1 - Prototype

__Ahad Rahman (300433299)__

__George Dorrington (300429785)__

__Justina Koh (300441630)__

__Daniel Pullon (300357323)__

__August Bolter (300456915)__

*Assignment Mark Weighting*
* Design Evaluation = 0%
* Prototype = 0%
* Video = 0%
* Reflection = 0%

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


## Part 6: Prototype

[Prototype](Prototype/Final-Peerwise-Designs.xd)


## Part 7: Video

Screen recordings of our mobile and desktop designs which demonstrates the functionality:

* [Staff desktop](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2020/project1/t16/swen303-project/-/blob/master/videos/staff%20desktop.mov)
* [Staff mobile](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2020/project1/t16/swen303-project/-/blob/master/videos/staff%20mobile.mov)
* [Student desktop](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2020/project1/t16/swen303-project/-/blob/master/videos/student%20desktop.mov)
* [Student mobile](https://gitlab.ecs.vuw.ac.nz/course-work/swen303/2020/project1/t16/swen303-project/-/blob/master/videos/student%20mobile.mov)

## Part 8: Group reflection
The merging of designs was actually quite a (comparatively) smooth transition. This was likely due to the way we had approached this situation. While we definitely carried out some 'mistakes’ in trying to merge our designs, it wasn’t anything too significant, and our team was still able to function quite efficiently regardless.

We have listed below the steps that we carried out to merge our designs, a description of what was done at each step, and a reflection on how effective each step was.

Steps:

| Step and Title | Description of what we did | Reflection |
| ------ | ------ | ------ |
| 1. Review our own and each other's designs | The first thing that we did was to review our own, and our teammates' designs. In this step, we gave each other access to our designs and (separately) wrote down the top three things that we thought were really good about the design, and three things that we thought weren't very good about the design.  | This was an incredibly good step to carry out. If we were to do this assignment again, we would most definitely start with this step. By carrying out this step, we were able to fully understand what each person liked and disliked about our designs, and therefore it was an incredibly good starting point to help us start planning what we wanted our combined design to look like.    |
| 2. Give feedback and discuss the main points of design | In this step, we had a zoom call where we elaborated each point that we wrote down regarding what we liked and disliked about each other's design. This allowed us to clarify any misunderstandings that we had, and also allowed us to properly voice what we liked and what didn't like.  | This was also an incredibly important step in our process. By having this process, it allowed each other to discuss, question and understand why we made certain design choices, why we liked / didn't like certain aspects of each other's design etc.  In this step, it allowed us to understand each other a bit more, and fully appreciate why certain design choices were made. |
| 3. Combine what we wanted / didn’t want in the app | This step was just an extension of the previous step. Here, we combined our thoughts, and tried to narrow down what we wanted in the app. | This step was actually much harder than we had originally thought, mostly due to the fact that each of us had already created a template app which was completely based on what we wanted so our thoughts were already quite solidly formed. Additionally, each of us had a sHowever, just like the previous steps that we had, this step was incredibly important as it allowed us to all be aligned and be on the same page as each other. If this step hadn’t been carried out, it could have resulted in some big disagreements later on in this project (or in the next parts) as everyone would still be wanting different things. |
| 4. Start designing our app again| At this stage we started to design our app together. We started on a template, and started writing down the potential pages that we might have on the app. | This step was a bit of a mistake. Since we had just all agreed on what we wanted to do (in the previous step) we had gotten too carried away, and had just ploughed straight into redesigning our app. However, we hadn’t given any thought to the personas that we might use or the use cases that we might have. Therefore we had very little idea about what our _potential users_ would want. Our design was completely ‘designer focused’. (i.e. we had designed it for ourselves, and not for our users).
If we were to do the assignment again, we would not have carried out this step  / we would have carried out this step later on in the project, after we had made the use cases / personas.|
| 5. Discuss our personas and use cases | Here, we discussed the potential personas and use cases. _Please read the  part 3: how we merged our use cases part for more detail_| This step was also incredibly important. In the previous step we hadn’t thought about / confirmed our use cases and personas, and therefore we started to lose track of what we wanted as a group, for our potential users. This step reconfirmed what we wanted, and helped us get back on track in starting to design a good app. This step was, and is, incredibly important in ensuring that the design choices that we make, are for the user, and not because we ‘feel-like’ putting something in. |
| 6. Revaluate our design choices | Due to the fact that we hadn’t thought about the personas previously, we had to rethink our choices that we had made in step 3. We looked at each of our design choices that we made, and made sure that each of them served a function. e.g. colour choices, menus, functions etc. We also realised at this point that we wanted to follow Google’s design layout - material design. This choice was made so that we would have consistency throughout each page.
In the end we ended up cutting some decisions that we had previously wanted to make on our design as it didn’t contribute anything for the user.  | This was a good step to have. Ideally, this step would have been earlier on, maybe about step 3 (after making personas and use cases).
If this step, and step 6 were done earlier, it would mean that we would have had an easier time combining our thoughts together and deciding what design choices we wanted to do. This is because, after we carried out this step, we realised that many of the original choices that we had made in step 2 were now redundant as those choices were made for us, and provided nothing additional for the user. |
|7. Started the template again | Here we started the design template again. From here on, it was rather smooth running.|


### Pros and Cons of New Prototype

**Pros**
<br>
Role Playing
<br>
Going through the program has shown that we have thought out the design for each persona.
<br>
Roleplaying as Sally showed the strength of our design for someone that will spend a long time using the app. Going through each section of the page requires minimal clicks. We know that Sally will be using all areas of the site throughout her studies therefore it is also crucial that we have a home button at the top of every page so that no matter which page she is on, she can quickly return to the homepage. This means that the highest number of clicks to get from one page to ANY other page is 4 clicks, this is a huge benefit to workflow as it doesn't matter where you are.
<br>
Roleplaying as Liam shows the strength of our breadcrumb menu system. For Liam he won't use many of the app's features as he will not be engaged until the final moments of the course, therefore we need it to be clear and easy to get to where he wants and provide the necessary information with minimal effort. Our homepage does this by clearly dividing the website into 4 sections, once in each section you only see the information related to that section, this is important for Liam as he only wants to answer quizzes and doesn't need the other sections
<br>
Roleplaying as Daniel also showed how our design only shows you the information you need at one time. When enrolling students everything else goes dark and an overlay is displayed, for busy lecturers this is important as they need to spend the minimal time possible due to their busy schedules.
<br><br>
Control
<br>
Exits are clearly marked. Using industry standards and following Google's material design helps to create an easily understandable and clear app.
<br>
Our use of buttons support this, all submission buttons are in blue, therefore you know that pressing one of these buttons will take you somewhere different, this includes things like enrolling students, submitting quizzes, creating quizzes, editing or deleting quizzes. All of these things are permanent changes and therefore it was important to make it clear that once clicked you will be changing something, this is also supported through the text on the buttons, we use words such as ADD, POST, RETURN, CREATE etc. These are all verbs which show that buttons are actions.
<br><br>
Consistency
<br>
By following a design language and staying consistent with that language we can be confident that our program follows this principle. As previously mentioned, we thought about buttons, colours and shapes so that no matter where you are in the app it remains visually consistent. This also applies to the mobile and desktop apps, when swapping between them they are slightly different but the language remains the same, therefore working cross platform is easier.
<br><br>
Preventing Errors
<br>
As discussed above, we remove errors by keeping things such as buttons consistent. This reduces errors as you know what will happen for example a blue button signifies change.
<br><br>
Minimal Design
<br>
We used minimal colours so that it wasn't overwhelming, while also being appropriate for the age group that we were aiming for. We also used the colour white as much as possible to help with clarity, this helped to contrast the black text while also drawing your eye to specific colours which contain important information.
<br><br>
Shortcuts
<br>
The breadcrumb system as previously discussed helps with this. The app has a low barrier to entry as you know that you can backtrack from anywhere and return to the homepage, this means that the app is quick to master which allows for quick traversals across the site.
<br><br>
Help
<br>
We have multiple ways for users to provide feedback and discuss. One method is commenting on the results, you can also respond to the results and send a message to the author. This gives users ways to improve their understanding, correct mistakes and clarify ambiguous information which is crucial in any learning environment.

**Cons**
<br>
Shortcuts
<br>
We don't implement specific macros that complete many tasks at once. This is a design choice as we felt it was more important to lower the barrier to entry for people who first view the site then it was to develop complicated shortcuts for heavy users. We feel that heavy users will not be too strongly impacted as there are a limited number of clicks to move through the website.
<br><br>
Consistency
<br>
We have issues with consistency between sidebars. After doing testing with users we will be better able to understand what people expect in the sidebars. This is especially apparent in the mobile app.
<br><br>
Error Recovery
<br>
We currently have not implemented many confirmation messages. This is because we still lack user testing and so we hope that our design language will provide the clarity required for people to know that when they press a button it will have an effect.
<br><br>
Status
<br>
The quiz pages can be quite long on mobile, when reading quizzes with many questions it may require a lot of scrolling. This was a design sacrifice we made because we wanted to keep the design language to be matching across the platforms. Due to the way we use white space it creates gaps that add to clarity but extend the size of pages. This is something we will revisit in testing.
<br>
It is impossible to know the complete performance of the application until it is fully implemented. Therefore it is hard to determine whether the flow of the application would have to change if for some reason there was difficulties in getting to certain pages due to load times, performance issues, etc.



