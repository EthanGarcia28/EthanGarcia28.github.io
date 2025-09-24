---
layout: essay
type: essay
title: "Breaking Bad Code: ESLint and the Power of Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2025-09-23
published: true
labels:
  - Coding Standards
  - VSCode
  - ESLint
---

<img width="200px" class="rounded float-start pe-4" src="../img/ESLintLogo.png">

## More Than Just Indentation: The Value of Coding Standards

  Coding standards are often associated with simple rules like proper indentation or bracket placement. However, I believe the concept goes far beyond that. Coding standards help developers build good habits and adopt a consistent coding style that makes their code easier to understand, not just for themselves, but for the entire programming community.
  
  Beyond formatting, these standards also cover naming conventions, avoiding anti-patterns, enforcing structural consistency, and preventing bugs. Through these lenses, coding standards can be viewed as the grammar and style guide of a programming language, resulting in readable, maintainable, and professional-quality code.

  This past week, we were introduced to an extension for VS Code called ESLint. At first, I assumed it would only help with surface-level issues like indentation or unnecessary whitespace. But as I worked through our assignments, I realized it’s much more powerful. ESLint became a helpful tool for writing better code. For example, it identified variables and functions that were declared but never used, helping me spot parts of my code that needed cleanup or correction.

## Applying ESLint and Reflecting on Learning

  In our recent “Baby-Bieber” practice WOD, we had to work with a file containing the lyrics of Justin Bieber’s “Baby” that was separate from our file containing our functions. Although I was referencing the array from another file, ESLint flagged it as “defined but never used.” To resolve this, I added a console.log statement to print the array’s length. This tool has allowed me to follow the coding standards more effectively in developing and maintaining quality code.

  Ultimately, this experience helped me understand the importance of coding standards in developing programs and how tools like ESLint can effectively support this purpose by reducing bugs, maintaining consistency, and fostering better programming habits. By following these standards, programmers can produce higher-quality code.
