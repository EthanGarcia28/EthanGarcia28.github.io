---
layout: project
type: project
image: img/RoomMatch.png
title: "RoomMatch UHM: A Roommate Matching Web Application"
date: 2025-12-16
published: true
labels:
  - Next.js
  - Typescript
  - PostgreSQL
  - Prisma
  - Full-Stack Development
  - GitHub
  - VS Code
summary: "A full-stack roommate matching web application developed by my team as the final project for ICS 314."
---

<div class="text-center p-4">
  <img width="1000px" src="../img/landing-page.png" class="img-thumbnail" >
</div>

## RoomMatch UHM

RoomMatch UHM is a full-stack web application developed as part of ICS 314 Software Engineering. The purpose of the project was to help University of Hawaii at Manoa students find compatible roommates by comparing lifestyle preferences such as habits, housing needs, and roommate expectations. The application allows students to create detailed profiles, view compatibility-based matches, and communicate directly with potential roommates through built-in chat and meeting features.

To promote safety and trust with the UH Manoa community, RoomMatch UHM strictly restricts user registration to verified @hawaii.edu email addresses. The user interface was designed to be easy to read and simple to navigate, so users can efficiently manage their profiles and view matches. While the application functions as a roommate-matching platform, the primary goal of the project was to practice full-stack development and collaborative software engineering in a team setting.

## Project Overview

RoomMatch UHM allows users to sign up and create a personal profile displaying their lifestyle preferences. After completing a profile, users can search for potential roommates and view a list of compatible profiles based on shared preferences. Users are able to edit and manage their profiles at any time, allowing compatibility results to update as their information changes.

In addition to matching functionality, the application includes chat and meeting features that allow users to communicate and schedule meetups with potential roommates directly within the platform. These features support clear communication and help users coordinate next steps once a potential match is found.

## Technologies Used

RoomMatch UHM was developed using Next.js as the full-stack framework, with development done in VS Code and version control managed through GitHub. A Neon PostgreSQL database was used to store application data, including user profiles, compatibility information, messages, and meetings. Prisma was used for schema design and database interaction, enabling structured data modeling and reliable local testing.

## My Contributions

My primary role on this project focused on backend development, with additional responsibilities involving database design and compatibility logic. I worked on features that supported user matching, messaging, and meetings by connecting application logic to stored user data and ensuring that information was displayed correctly throughout the application.

I designed and implemented the compatibility scoring algorithm, which compared two user profiles and returned a weighted compatibility percentage based on lifestyle preferences. This algorithm was connected to the database so users could view a list of compatible profiles sorted by compatibility score. To test the accuracy of the algorithm, I created example user profiles and mock data to verify that calculations and sorting behaved as expected.

In addition, I contributed to database schema design using Prisma by defining models for user profiles, preferences, chats, messages, and meetings. I added and maintained seed data to support development and fixed issues where fake users were not appearing correctly on the match page.

I also implemented backend logic for the messaging and meeting features, including creating chats, sending messages, retrieving chat histories, creating meetings, and fetching meetings for individual users. These contributions required working within a shared GitHub repository, coordinating with teammates, and following established coding standards through feature branches and pull requests.

## Skills and Lessons Learned

After completing this project, I gained a stronger understanding of both technical software engineering skills and collaborative development practices. I learned how to follow a structured workflow that encourages progress through milestones and how to break larger features into smaller tasks that contribute to overall project completion.

Working extensively with messaging and meeting features strengthened my ability to design and implement database-driven functionality, including securely adding, retrieving, and managing data. I became more comfortable working with Prisma schemas, database seeding, and backend authorization logic. Additionally, collaborating through GitHub issues, feature branches, and pull requests reinforced the importance of communication and coordination when working on a shared codebase.


