[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8wgCKhpZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18516737&assignment_repo_type=AssignmentRepo)
# se-day-2-git-and-github
## Explain the fundamental concepts of version control and why GitHub is a popular tool for managing versions of code. How does version control help in maintaining project integrity?

## Describe the process of setting up a new repository on GitHub. What are the key steps involved, and what are some of the important decisions you need to make during this process?

## Discuss the importance of the README file in a GitHub repository. What should be included in a well-written README, and how does it contribute to effective collaboration?

## Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects?

## Detail the steps involved in making your first commit to a GitHub repository. What are commits, and how do they help in tracking changes and managing different versions of your project?

## How does branching work in Git, and why is it an important feature for collaborative development on GitHub? Discuss the process of creating, using, and merging branches in a typical workflow.

## Explore the role of pull requests in the GitHub workflow. How do they facilitate code review and collaboration, and what are the typical steps involved in creating and merging a pull request?

## Discuss the concept of "forking" a repository on GitHub. How does forking differ from cloning, and what are some scenarios where forking would be particularly useful?

## Examine the importance of issues and project boards on GitHub. How can they be used to track bugs, manage tasks, and improve project organization? Provide examples of how these tools can enhance collaborative efforts.

## Reflect on common challenges and best practices associated with using GitHub for version control. What are some common pitfalls new users might encounter, and what strategies can be employed to overcome them and ensure smooth collaboration?

SOLUTION

ASSIGNMENT 2

Version control as the name implies is the control of different version of code. When developers collaborates on a project. There are different features done individually which may implies each version of different sections of the code.  Github hence is a collaborative hub for developers online where developers collaborate on a repository. It makes code writing faster and quicker. It allows history of code to be saved. It easily allow version control from may be v1.0 to another version. It allows other to be able to see the code if its made public.


2.
Steps in setting up a repository
a.	Login to github online
b.	Register to create an account using your email and password
c.	Login and click on repositories
d.	Add new repository by adding the unique repository name
e.	Description may be added
f.	Select public if the repository is to be made public or private
g.	Select to add READme.md or .gitignore if needed
h.	Save to create a repository


3.
README.md is a file in a repository to communicate important information about project. A README along with a repository license, citation file, contribution guidelines and a code of conduct communicated expectations for the project and helps manage contributions.

README.md typically include information on:
a.	What the project does
b.	Why the project is useful
c.	How users can get started with the project
d.	Where users can get help with the project
e.	Who maintains and contributes to the project.


4.
Repositories store project files and revision history. The key differences:
Public Repositories are opened to everyone, anyone can view, fork and clone code. Its ideal for open-source projects and collaboration
Private repositories have access restricted to owner and invited collaborators, protect as sensitive data and proprietary code. And offers more control over who can view and modify.





5.

To make a commit.
Make sure that the CLI recognizes your email and username
a.	git config –global user.name “username”
b.	git config –global user.email “email”
c.	git add filename
d.	git commit –m commit “commit message”

6.
a.	A branch is a new/separate version of the main repository. 
b.	It allows you edit code directly without impacting the main branch
c.	Emergency!!! There is an unrelated error somewhere else in the project that needs to be fixed ASAP
d.	You can fix all your errors in the branch and finally merge with the main branch


7.
PULL REQUEST
A pull request is a request to confirm the changes made in a branch to be merging along with the main branch. Many developers may collaborate on a project hence creating a branch to be able to work on. After work is done on the branch, then the merge is needed. This is when a pull request is needed. A request to a repository maintainer to pull in and merge a proposed source code or other change.

8.	When you say you are Forking a repository you are basically creating a copy of the repository under your GitHub ID. The main point to note here is that any changes made to the original repository will be reflected back to your forked repositories (you need to fetch and rebase). However, if you make any changes to your forked repository you will have to explicitly create a pull request to the original repository. If your pull request is approved by the administrator of the original repository, then your changes will be committed/merged with the existing original code-base. Until then, your changes will be reflected only in the copy you forked.

In short:
The Fork & Pull Model lets anyone fork an existing repository and push changes to their personal fork without requiring access be granted to the source repository. The changes must then be pulled into the source repository by the project maintainer.
Note that after forking you can clone your repository (the one under your name) locally on your machine. Make changes in it and push it to your forked repository. However, to reflect your changes in the original repository your pull request must be approved.

9.
Issues can be created in the repository to plan, discuss and track work. Issues are quick to create, flexible and can be used in many ways. Issues integrate with work all across Github. Mentioning an issue in another issue or pull request will create references between them and using keywords like fixes:, in the pull request will automatically close the associated issues. For example if an issue is created and a pull request is done after fixing the issue. The issue can be selected after the pull request is done and automatically the issue will show solve.

10.
a.	Make Incremental, small changes: In this case, after identifying a problem or enhancement, the best way to try something new and untested is to divide the update into small batches of value that can easily and rapidly be tested with the end user to prove the validity of the proposed solution and to roll back in case it doesn’t work without deprecating the whole new functionality. Committing code in small batches decreases the likelihood of integration conflicts.
b.	Keeps commits atomic: atomic commits are a single unit of work, involving only one task or one fix (e.g upgrade, bug fix, refactor). It makes code reviews faster and reverts easier. 
c.	Develop using branches: Using branches, developers can make changes without affecting the main code line
d.	Write descriptive commit messages: Descriptive commit message are as important as the change itself. It gives a direct description of what is done. A very good verb (present tense) in imperative mood to indication the purpose of each commit in a clear and concise manner. E.g “make xyz do frotz instead of “this patch makes xyz do frots. 
e.	Obtain feedback through code reviews
f.	Identify a branching strategy: it may be a centralized workflow, feature branching, Git flow or personal branching.

