# AI Workshop

This repository contains instructions and supporting materials for the AI Workshop session in the Basics of Programming course.

## Purpose

The goal of this workshop is to help students:

- Understand core AI concepts in a beginner-friendly way
- Apply AI tools to programming-related tasks
- Practice responsible and effective AI usage

## Prerequisites

At this point, students should have:

- Completed all Python programming tasks
- Familiarity with the basics of Python
- Familiarity with GitHub, VS Code, and GitHub Codespaces from previous tasks

## Tools Used During the Workshop

- Microsoft Copilot for guided coding support, explanations, and iteration
- GitHub Codespaces as the cloud development environment for workshop tasks

## How Students Will Work

Students should work through the workshop in the following way:

1. Clone or fork this repository and complete the demo AI task by following the provided guidelines.
2. Form a team of 3 to 5 students and join your team in Canvas.
3. As a team, choose one of the three available tasks: Task 1, Task 2, or Task 3.
4. Decide how your team will organize the work. You may work together in a shared repository, or each student may work in their own repository and combine the final work into one team repository before submission.
5. Submit one final repository link in Canvas. If the work was done in separate repositories, one team member should collect and merge the final version into a single repository before submission.
6. If your team gives the presentation, one team member may present the work on the date shown in the timetable. The presentation should be a short 5-minute demo of the application, what you learned, how you used AI tools, and how your team organized the work.

## Responsible and Effective AI Use

Students are expected to use AI tools in a thoughtful and ethical way:

- Treat AI output as a draft, not a final answer
- Test all generated code before submission
- Verify facts and references from reliable documentation
- Avoid sharing sensitive or personal information in prompts
- Write prompts clearly and include enough context

## Tasks Overview

In this workshop, you will either analyze or develop a small-scale Python application. The work is primarily intended for groups of 3 to 5 students.

Students should choose one of the following three tasks:

1. Task 1: Software Development Project  
   Develop a simple password manager based on the provided template in [task1-emptyPasswordManager/README.md](task1-emptyPasswordManager/README.md).
2. Task 2: Software Analysis Project  
   Identify, report, and optionally fix security vulnerabilities in the sample program described in [task2-faultystudentrecord/README.md](task2-faultystudentrecord/README.md).
3. Task 3: Open AI-Assisted Application Project. You may either create a new application or continue improving the CLI application from the workshop. If you choose the CLI continuation path, each student should add at least one new feature.
   
   > Create a small Python application with the help of an AI coding assistant such as GitHub Copilot, Cursor, Codeium, ChatGPT, or a similar tool. A command-line application is recommended for GitHub Codespaces. If you work locally, you may also choose a PySide6 desktop GUI. See [workShopDemo/README.MD](workShopDemo/README.MD).

## Task 3 Requirements

If you choose Task 3, you are free to design the application yourself as long as it meets the following minimum requirements:

- Run successfully in your chosen environment (Codespaces or local machine)
- Include at least one interactive feature, such as text input and output in a command-line app, or widgets such as a button, text input, dropdown, list, or table in a GUI app
- Use AI-assisted programming for at least two parts of the implementation, such as GUI layout, event handling, or helper functions
- Include meaningful edits or adaptations to AI-generated code rather than only copying it directly

If you build a GUI with PySide6, a local environment is recommended.

Possible example ideas for Task 3 include:

- Notes application
- Simple calculator
- Unit converter
- Timer or stopwatch
- Small game such as Tic-Tac-Toe, number guessing, or memory match
- To-do list application

## Instructions

1. Choose one of the three tasks.
2. Follow the instructions in the relevant task README carefully.
3. Complete the work in your team repository.
4. Return the link to your GitHub project in Canvas. If your repository is not public, make sure the instructor has access.
5. Present your group work on the date indicated in the timetable. The presentation can be short, up to 5 minutes, and should focus on what you learned rather than only showing the final output.
6. Complete the required peer review in BuddyCheck when you receive the invitation.

## What to Submit

Please submit the repository link in Canvas.

## Assessment

Projects are evaluated on a scale of 0 to 10 points.

- Up to 8 points come from the project work itself
- Up to 2 additional points come from a strong project demonstration
- Peer review results in BuddyCheck may affect individual points

Please see Canvas and the course assessment criteria for full details about grading and weighting.

## Expected Workload

The time allocated for this work is approximately 25 to 30 hours. The actual time required depends on prior experience and how effectively the group works together.

## Suggested Reading and Sources

- GitHub Copilot documentation: https://docs.github.com/en/copilot
- GitHub Codespaces documentation: https://docs.github.com/en/codespaces
- Microsoft Responsible AI resources: https://www.microsoft.com/en-us/ai/responsible-ai
- Microsoft Learn (AI fundamentals and developer content): https://learn.microsoft.com/training/
- OWASP Top 10 (secure coding awareness): https://owasp.org/www-project-top-ten/

## Team Collaboration on GitHub

Use the following workflow to collaborate effectively in your team repository:

1. The repository owner should create the team repository (or use a repository forked or cloned during the workshop). Prefer using one shared team repository created by one team member, and add all team members as collaborators.
2. Each student creates a separate branch for their work instead of committing directly to the main branch.
3. Make small, clear commits with meaningful commit messages.
4. Open a pull request (PR) from your branch to main when your feature or fix is ready.
5. At least one teammate reviews the PR before merging.
6. Resolve comments, update the branch if needed, and merge only after checks and review are complete.
7. Delete merged branches to keep the repository clean.
8. Use GitHub Issues to plan tasks, assign ownership, and track progress.

Suggested team practices:

- Pull the latest changes from main before starting new work.
- Keep PRs focused on one change at a time.
- Discuss major design or feature changes in issues or PR comments.

Helpful GitHub reading:

- Adding collaborators to repositories: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/inviting-collaborators-to-a-personal-repository
- About branches: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches
- About pull requests: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests
- Reviewing proposed changes in a pull request: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/reviewing-proposed-changes-in-a-pull-request
- About protected branches: https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches
- GitHub Issues quickstart: https://docs.github.com/en/issues/tracking-your-work-with-issues/quickstart

