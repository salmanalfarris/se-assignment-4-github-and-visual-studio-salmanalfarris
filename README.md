[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15305476&assignment_repo_type=AssignmentRepo)
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
Introduction to GitHub:

What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.

GitHub is a developer platform that allows developers to create, store, manage and share their code.
-it allows users to create, store, change, merge and collaborate on files or code.
-allow users to make request of one another and internally discuss the iterations along the way.
-allow users to make edit or changes that other collaborators also see.
GitHub features include
-GitHub issues let you track your work on GitHub.
-Gist code is a simple way to share code snippets with others.
-GitHub Wiki is a feature on GitHub to host the documentation of the repository.
-GitHub Pages is a static site hosting website that takes HTML,CSS and JavaScript files straight from a repository on GitHub and publishes a website with them.
It support collaborative software development in that GitHub offers a card-based project management tool.
-references:wikipidia and PLP content.

Repositories on GitHub:

What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.

-GitHub repository is the most basic element of GitHub and a place where you can store your code and files.
-create new repository by clicking add new repository 
-type a short, memorable name for your repository e.g "hello-git"
-optionally add a description of your repository i.e "this is my first repository"
-choose a repository visibility.
-select initialize this repository with a README.
-finally create the repository icon that is labelled Green in colour.


Version Control with Git:

Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?

-is the practise of tracking and managing changes to source code over time i.e Git
-it enhance vesion control by leveraging git, a distributed version control system which offers various features to streamline code management.

Branching and Merging in GitHub:

What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.

-branches are a new or seperate version of the main repository.
-because they allow you to work on different parts of a project without impacting the main branch.
The process include
-open terminal and ensure that you are in your working directory and type "git branch" and name it.
-switch to the newly created branch "git check out"
-make changes in the newly created branch by using git add,commit and push.
-merge the main branch by typing git merge in the terminal.

Pull Requests and Code Reviews:

What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.

-is a proposal to merge a set of changes from one branch into another in a GitHub.
-by enabling efficient code review, facilitate knowledge sharing and improving code quality.
-on github, navigate to the main page of the repository .
-in the branch menu,choose the branch that contains your commit.
-above the list of files, in the yellow banner,click compare and pull request to create a pull request for the associated branch.
-use the base branch dropdown menu to select the branch you like to merge into,the use the compare branch drop-down menu to choose topic.
-type a litle and description for your pull request.
Source:GitHub docs.

GitHub Actions:

Explain what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub Actions.

-is a continuous integration and continuous delivery platform that allow you to automate your build, test, and deployment pipeline.
-by creating workflows that build and test every pull request to your repository or deploy merged pull request to production.

Introduction to Visual Studio:

What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?

-is a powerful developer tool that you can use to complete the entire development cycle in one place.
-contains code editing features.
-has integrated terminals.
-has git integration.
-it has debugging features.
-it contains extension.
-it has live share.
-it has task runner.

Integrating GitHub with Visual Studio:

Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?

-copy the repository link from github to git bash.
create a folder in the desired drive.
-clone the repository to git bash.
-cd the folder of the designated link.
-type code . in the gitbash to open VS Studio code.
-adit the README in the vs code and once done open gitbash terminal in the vs code.
-git add .
-then git commit -m 
-lastly gitpush and it will update automatically in the GitHub Account.
-Source: software engineering plp class content.
It easy inteconnected different account simulteniously.

Debugging in Visual Studio:

Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?

-VS Code debugger typically support launching a program in debug mode or attaching to an already running program in debug  mode.

Collaborative Development using GitHub and Visual Studio:

Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.


GitHub and Visual Studio work hand in hand such the you can run a project in GitHub by clonning to gitbash and edit the project in vs studio by directing code . in the gitbash and edit the change in README section using VS Studio code and push back to github by git add,git commit and git push, thus its perfect tool that support collaborative development of a project i.e project_Django.

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
