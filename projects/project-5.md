---
layout: project
type: project
image: images/panda.png
title: UH Code Submissions
permalink: projects/uhcodesubmissions
# All dates must be YYYY-MM-DD format!
date: 2021-05-12
labels:
  - Meteor
  - Semantic UI
  - MongoDB
summary: A web application made for ICS students at UH Manoa, specifically members of the Programming and Algorithms (PANDA) SIG of ACM Manoa, to assist them in solving problems and storing solutions.
---

## Overview

I learned several concepts and aspects of software engineering in my ICS 314: Software Engineering I class. A month before the end of the semester, students were assigned to complete a working web application in groups of 3-5 people that will serve the UH community in some way. My group was selected to create a web application that will allow UHM students, specifically the ones in computer science, who either want to improve their skills in algorithms or are preparing for technical interviews. An alternate to websites such as LeetCode, UH Code Submissions serves mainly for members of PANDA (Programming and Algorithms) SIG of ACM Manoa as an efficient, comprehensive location to submit and store problems and solutions.

<img class="ui rounded image" src="../images/uhcode.png">

#### This application includes:
- New Problem Page (admin): a page where only admins can add new problems.
- Problems Page (admin): a page with published problems by the admin. The admin is able to edit problems on the problems page. Each problem includes a brief overview of the problem and a tag for its category.
- Problems Page (user): a page with published problems by the admin. A user is able to submit a solution to a selected problem. Similar to the admin's side, each problem includes a brief overview of the problem and a tag for its category.
- Solutions Page (user): the user is directed here after selecting to submit a solution to a problem.
- Profile Page (admin and user): admins and users have their own profile page where they are able to write (and edit) a short bio about themselves.

## Development Process

I contributed to the project through various means in front-end design and back-end development. I helped with the overall UI design and look of the pages, and came up with the idea of having a dark, simple theme for the entire application. I helped contribute to the navigation bar, landing page, add/edit problems portion for admins, creating the problems page, and adding a portion of submitted problems and new problems added to the user and admin pages on the Profile pages respectively. I also led the process for creating, updating, and maintaining our project homepage.

<div class="ui two column grid">
  <div class="column">
    <div class="ui segment"><img class="ui large image" alt="uhcode-new" src="../images/new.png"></div>
  </div>
  <div class="column">
    <div class="ui segment"><img class="ui large image" alt="uhcode-problems" src="../images/page.png"></div>
  </div>
</div>
</br>

I started the process by working on the landing page, and creating the navigation bar options for the users and admins. Since the admin had an additional tab contributing to adding a new problem, I had to create a separate admin-protected tab solely for the admins. After completing the navigation bar (which actually underwent several changes over the course of three milestones), I created the original default landing page with three features of the website and the signin and signup options. I implemented a few additional parts to the signup page, such as Name, Image, and Bio. After that, I worked mainly on the portions required for the admin, and implemented the Add New Problem page, and Edit Problem page that would only be accessible on the admin side. I had to make sure both matched, and they were able to submit (or update) on the Problems page. The most difficult portion on the overall development for my contribution was creating the Problems page as it was mainly back-end development that I was less confident on. I had to make sure that the problems appeared in the database, that new problems could be added and updated (in the database), and that it was possible to add a new problem from the Add New Problem page to the Problems page.

## Accomplishments

Throughout the project, I grew my understanding of Meteor, Semantic UI (with React), JavaScript, MongoDB, the deployment process, and maintaining a clean and organized project homepage. I was able to learn new aspects of front-end design and development using Semantic UI (with React), and start to appreciate the development that takes place more on the back-end side. Originally, I had not realized how crucial databases and a proper understanding of them were necessary for web development, but I was able to get a better grasp of both throughout the project. I believe I also learned several soft skills alongside programming.

Since my team weren't able to meet in-person and regularly, we had to rely on communication through Discord and collaboration through GitHub in order for our project to be successful. I learned how invaluable effective communication and proper planning is when it comes to projects such as this. My group worked on implementing an Agile Project Management approach so that we would be able to complete tasks efficiently. I also learned specifically from this experience that it is important (maybe even necessary) to have a project head or lead when it comes to challenging and intense projects such as this one. I imagine this is what was most impactful for me, because there were times when I felt that with better initiative or direction from one of the members (such as myself), the development of the application would not have been as stressful as it was. This is not something I can do easily, but it is a skill I desire to improve on when I choose to venture into management.

Through the process, I learned there was so much more that goes into software development that I was previously unaware of, but that in no means discouraged me, but only helped me grow my passion and interest in software engineering, and especially, web development. This was a group project managed by the following members: Chad Oshiro, Kanai Gooding, Tristan DeAguiar, and Kiran Datwani (myself). To learn more about this project, please visit our project page or our github repository:

<a href="https://uh-code-submissions.github.io/"><i class="large github icon"></i>UH Code Submissions Project Page</a> - <a href="https://github.com/uh-code-submissions"><i class="large github icon"></i>UH Code Submissions GitHub Repository</a>
