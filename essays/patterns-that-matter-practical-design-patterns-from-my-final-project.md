---
layout: essay
type: essay
title: "Blueprints of Logic: How Design Patterns Shaped My Roommate App"
date: 2025-12-03
published: true
labels:
  - Design Patterns
  - Software Engineering
  - Roommatch
---

# <img width="220px" class="rounded float-start pe-4" src="../img/design-patterns-logo-2.png">

When building software, the structure of your codebase plays a similar role to the structure of a home. Without organization, your project becomes messy, harder to understand, and difficult to maintain. With the right blueprints, however, the entire system becomes clearer and more stable. These blueprints are known as design patterns, which help developers solve recurring problems while keeping code clean and predictable. During the development of my final project, Roommatch, I learned how essential these patterns are in creating a well-structured application.

## The Role of Design Patterns in Software Engineering

Design patterns are important because they act as reusable solutions to common challenges that engineers face. They help create an environment where developers can write code that is easier to test, reuse, and extend later on. Since software projects often involve teamwork, consistent patterns improve communication and prevent confusion, especially as features grow more complex. In my project, several design patterns naturally appeared as I organized the logic for matching users, handling chats, and managing stored information.

## Layered Architecture: Keeping Each Part of the App Organized

One of the most influential patterns in Roommatch was the use of a layered architecture. This pattern separates a project into different sections, each with a specific responsibility. For example, the user interface is responsible for displaying information, the server routes handle requests and decisions, and the database layer manages stored data. Keeping these layers distinct made the project much easier to navigate and understand.

This organization also made debugging more manageable. When messages stopped appearing in the chat at one point, I could check each layer separately to find out where the issue started. Because the responsibilities were clearly divided, I quickly discovered that the problem came from an incorrect value being passed through the server route. Without this structure, identifying the issue would have taken much longer. Overall, the layered architecture pattern kept different parts of the project from interfering with one another and maintained clarity in the codebase.

## Repository Pattern: Centralizing How Data Is Accessed

Another helpful pattern was the Repository pattern, which centralizes all database interactions in one place. Instead of having database queries scattered across different parts of the project, Roommatch collects all data-related operations in a single file. This makes the project much easier to maintain and update, especially when the structure of the database changes.

For example, when I separated user information into two different tables, I only had to adjust the functions inside this centralized file. The rest of the system continued working without any major changes. This pattern also encouraged consistency throughout the project, preventing small differences in database calls from causing bugs. By keeping all data access in one place, the Repository pattern improved organization and made future modifications much easier.

## Transactions / Unit of Work: Preventing Data Problems

One of the more challenging bugs I encountered happened when two users tried to open a chat at the same time. Occasionally, the app would accidentally create duplicate chat rooms or place a user’s message into the wrong chat. This happened because the system allowed both actions to happen at once, resulting in mixed or duplicated data.

To solve this, I used the concept of transactions, which follow the Unit of Work design pattern. This pattern ensures that multiple related operations are treated as one complete action. If everything succeeds, the changes are saved, but if something goes wrong, nothing is saved at all. After applying this pattern, Roommatch no longer created duplicate chats, and the messages consistently appeared where they belonged. The system became more reliable, especially when users performed actions at the same time.

## Conclusion

Throughout the development of Roommatch, design patterns played a major role in helping me write organized, understandable, and reliable code. Patterns such as the Layered Architecture, Repository, and Unit of Work helped the project avoid confusion, stay consistent, and prevent difficult bugs. These patterns provided structure during the entire development process and made the application easier to maintain and grow.

Ultimately, design patterns act as guides for solving common problems in software. They help engineers write code that makes sense not only today but also in the future. By learning and applying these patterns, developers can create applications that are cleaner, more stable, and easier for others to understand—qualities that are essential in becoming a strong and effective software engineer.
