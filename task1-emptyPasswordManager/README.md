# Coding a simple password manager

## Learning Goals

Through this assignment, you will learn to write and test a small software program collaboratively as a group.

## Background

Develop a Python-based password manager that allows users to store and retrieve website login credentials. If possible, also implement a password strength checker to encourage users to create strong passwords. If you have additional time, add a password generator feature that allows users to generate strong and random passwords when adding new entries. You are provided with a coding template with ready-made functions for Caesar cipher encryption and decryption. Please note that Caesar cipher encryption is only for educational purposes. Real-world password managers use robust encryption algorithms and secure storage methods.

## Preparatory Actions

1. Use the contents of this folder as the starting template for the assignment.
2. Protect the main branch of your repository. In the branch protection settings, under "Branch rules", select "Require a pull request before merging". Optionally, you can also require approvals from another group member before a pull request can be merged. See [GitHub Docs: Managing a branch protection rule](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/managing-a-branch-protection-rule).
3. Optionally, use GitHub Issues to manage your work as a team and assign tasks to each group member. See [GitHub Docs: Quickstart for GitHub Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/quickstart).

## Workflow Actions

1. Implement a simple password manager on top of the provided template in main.py. Do not change function names or the provided user interface.
2. Implement the following functions: add password, retrieve password, load passwords from file, and save passwords to file. Optionally, add a password strength checker and a random password generator.
3. Follow the instructions in the coding template when implementing the functions. If you need to deviate from the instructions, explain clearly in comments why you did so.
4. Use the provided functions to encrypt and decrypt passwords instead of writing them to file as plain text, noting that this encryption method is only for educational purposes.
5. Test your password manager either manually or with the provided automated unit tests in test.py. If you want to improve the unit tests, add your own test file, for example mytest.py.
6. You may use AI tools such as Microsoft Copilot or similar tools during this assignment, provided that you use them responsibly. You remain responsible for understanding, testing, and validating any code, explanation, or suggestion produced by an AI tool.
7. Before submitting the assignment for review, make sure that all relevant code changes have been merged into the main branch of your team repository. See Canvas for submission instructions. One team member should submit the repository link in Canvas.