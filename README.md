# course-directory
Course Directory (INFO102, Victoria University Wellington)

This project was developed in response to an assignment provocation. The project
was to be done in pairs, however, due to my partner's health issues, I made a solo
attempt at the project. As such, only lecturer side functions are complete.

I have ammended the project to remove server-side storage and retrival as the server
was provided by the university and I am no longer a student there. Only data 
permanance is affected. The functionality of the site is still intact. All JSON
has been removed.


The Scenario given was as follows (edited):


Project Introduction

Wellington School of Business and Government (WSBG or “the faculty”) has identified
that there should be a better way for students to be able to manage the courses 
they take, and the associated workshops and tutorials, throughout the study periods.
Ideally a Web application, where:
 - lecturers can put in information about their course(s), the dates and times
   they’re on, and the schedule for the workshops and tutorials.
 - students should be able to log in, and select their courses of study to their
   list of courses, see dates and times of their selected courses, and select an
   option for the workshops/tutorials.
Focus is on a trial in one school first (School of Information Management (SIM)).
The faculty have set up the Course Assignment App Board (CAAB) to manage the app’s
development.


Project Goals
- Timely and efficient information management.
- Information accessible for everyone (lecturers, and students).
- The focus is on undergraduate courses available in SIM, with a view to expanding
  it to postgraduate courses at a later date if all is going well.
- Courses can be added, and edited, with different lecturers responsible for their
  course(s).
- Courses can be added to individual student’s course feeds, where they can also
  manage their choice of workshops/tutorials.


Project Organisation

CAAB is your client. CAAB needs you to develop a Web application that fulfils their
information management requirements. CAAB does not need reports (great!). Instead, 
they want to see the project rolling from day one — that means using Agile to 
develop the software. This will help build trust that you can deliver what they 
need. You are expected to deliver an application that works from day one, and to
keep delivering functionality on a weekly basis.


System Requirements

The following requirements are non-negotiable:
- The project and resulting application will adopt a client-server architecture.
- On the server side, a web server will be provided with a fixed set of
  business-logic functions that can be accessed using HTTP and JSON. No work
  will be done on the server side. No changes can be done either.
- Since no changes can be done to the server, in this project you will develop
  only the client.
- The client will be a single-page application, i.e. running with a single page
  load on a browser.
- The client will run on modern browsers (Chrome, Firefox, Safari) and may even
  be accessed on mobile phones.
- The client will be developed with standard web technology: HTML, CSS, and using
  Python and Vue.js.


Data Requirements

For all users:
- The server maintains a user list with: login name, password, and type of user
  (lecturer, student). This will be set up for you and cannot be modified.
- Users will be of one of two types (lecturer or student) and will be discerned
  at log-in by their user name.

For lecturers:
- The course directory will be the entry point for managing all data about courses
  and associated workshops/tutorials.
- Each course has the following data: course ID, course name, course lecturer,
  course overview, year, trimester, lecture times, and options for workshops/
  tutorials.
  
For students:
- The student’s course feed will be the entry point for students to view and manage
  all data about students’ courses and the associated workshops/tutorials.
- The course directory can be viewed, where students can click through to view
  course and workshop/tutorials details.
- Courses can be added from the course directory, and deleted from their course
  feeds.
- Options for workshops/tutorials can be (optionally) selected when a course is
  added, can be selected later, and can be changed.

  
Functional requirements

- The list of courses can be viewed without logging in, but in order to make any
  changes (e.g. change a course, enrol in a course) the user will need to login.
- The lecturer can view all courses in the directory.
- The lecturer can add/modify/delete courses and the associated workshop/tutorial
  schedule.
- The student can view all courses on offer.
- The student can add courses to their directory.
- The student can delete courses from their directory.
- The student can select a workshop/tutorial option for a course they are doing
  – this can be done when the course is added, or later. The student can also
    change their workshop/tutorial selection, but cannot delete it.
- The student can display a summary of their scheduled classes, including both
  lectures and tutorials/workshops.
  
Note: This is a minimal set of functions required by the client. Other good ideas
that improve value are welcomed and will be rewarded. You are invited to add 
useful functionality to the application. Note however that you cannot change the 
server behaviour.


Other requirements

- Forms have good presentation (e.g., clean, with properly aligned fields).
- Forms are easy to use.
- Dropdown menus are preferred over empty fields.
- Forms have pre-selected options whenever possible.
- Optional challenge: Forms work well on mobile devices.
- Currently by design the use of the application is purely administrative. See
  if you can add functionality that makes the system more informative.
