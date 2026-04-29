# Security Vulnerabilities Reporting

## Learning Goals

Through this assignment, you will learn how to read code, identify security vulnerabilities, report them, and optionally fix some of them.

## Background

You are given a small program in [main.py](main.py) with a text-based user interface that allows users to store basic information about students. The program contains several serious flaws and vulnerabilities. In this assignment, you will practice finding, reporting, and optionally fixing them. Please read the additional background information, including the assessment criteria, in Canvas.

## Preparatory Actions

1. Use the contents of this folder as the starting template for the assignment.
2. Enable private vulnerability reporting for your repository. See [GitHub Docs: Configuring private vulnerability reporting for a repository](https://docs.github.com/en/code-security/security-advisories/working-with-repository-security-advisories/configuring-private-vulnerability-reporting-for-a-repository).
3. Protect the main branch of your repository. In the branch protection settings, under "Branch rules", select "Require a pull request before merging". Optionally, you can also require approvals from another group member before a pull request can be merged. See [GitHub Docs: Managing a branch protection rule](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/managing-a-branch-protection-rule).
4. Optionally, use GitHub Issues to manage your work as a team and assign tasks to each group member. See [GitHub Docs: Quickstart for GitHub Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/quickstart).

## Workflow Actions

1. Examine the main code in [main.py](main.py) carefully and test different usage scenarios. You can test the code manually by running the program and entering values by hand, or by writing automated tests. You can find examples of simple tests in [test.py](test.py) and expand on those.
2. Search for vulnerabilities in the code and investigate common security issues such as SQL injection and directory traversal.
3. As soon as you find a security flaw, use GitHub to file a private security vulnerability report. Use [Vulnerability Report Template by GitHub Security Lab](https://github.com/github/securitylab/blob/main/docs/report-template.md) as a basis for your report. **You can use this as a template and create a file named report.md in this folder** . Although the report does not have mandatory fields, you should provide as much useful detail as possible. In particular, include exact steps to reproduce the vulnerability, including tested example input or code where relevant. Create a separate report for each vulnerability you find.
4. If you still have time, try fixing some of the identified vulnerabilities or make other well-reasoned improvements to the code. Make all code changes in a separate branch, then open a pull request and merge the approved changes into the main branch.
5. You may use AI tools such as Microsoft Copilot or other similar tools during this assignment, provided that you use them responsibly. You remain responsible for understanding, testing, and validating any code, explanation, or suggestion produced by an AI tool.
6. Before submitting the assignment for review, make sure that all relevant code changes have been merged into the main branch of your team repository. See Canvas for submission instructions. One team member should submit the link to the repository in Canvas.
    
