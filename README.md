[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)

Assignment: GitHub and Visual Studio Instructions: Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
 Introduction to GitHub:
What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.
GitHub is a version control system that stores files and folders associated with a project and enables the tracking of changes made to the project where any version of the project can be accessed.
GitHub functions include;
Storage of files and folders
Tracking of changes in the project 
GitHub features include repositories. Each repository has its tools to help a code be run and hosted easily. Shared repositories allow people to work together on the same project making their contribution visible to the rest.
Easy project management enables project managers in GitHub to manage and coordinate projects easily and effectively.
Pull requests feature enables users to add changes to the code and to notify the owner of the code of the changes that have been made to the project.
Safety features enable users to publish their code safely even with the choice of publishing privately if one is not willing to share their code with others.
GitHub Copilot provides suggestions for full lines of coding. This makes the coding experience on the platform easier and faster.
Code scanning helps the owner of the code to scan new additions to the code of viruses that could jeopardize the code making the repository safe from vulnerabilities.


GitHub supports collaborative software development in different ways. It enables the project manager to coordinate and track changes in the code easily. 
People working on a a project can also have discussions which helps them come up with different ideas. 
GitHub enables collaboration by showing the changes that have been made, who made those changes and how those changes contribute to the project as a whole.


 Repositories on GitHub:
What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it. 
GitHub repository is a location on GitHub that allows users to store code and to add changes to existing code and files related to a project.
To create a new repository on GitHub, follow the following steps;
Go to your Github account
Click on your profile
Select “My Repositories”
Select “New Repository”
You will be directed to your repository to make additions to your repository details. 
Add a name for your repository
Add a brief description of your repository
Add a README file to explain briefly what your repository relates to
You can choose to make your repository private or public
Click on the “Create New Repository”
And you have now created a new repository.


Version Control with Git:
Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers? 
Version control is a feature in Git that allows for changes to be recorded whereby, a specific version of the code can be retrieved when needed.
Git enhances version control for developers by tracking the changes that each developer makes and allowing developers to look at each version of the code whenever they want to check which codes work best and how the changes to the code made by each developer affect the outcome of the whole project.
Branching and Merging in GitHub:
What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch. 
Branches are part of a repository that is used to work in isolation from the main branch. Branches are important in that they help developers to try out new coding ideas, to debug and develop new features which are then added to the main branch after the developer is satisfied with the code.
To create a branch, follow the following steps:
Go to the repository
Click on the branch dropdown menu
Click on New branch
Give your branch a name in the “Branch Name” box
Then choose the source of your branch
Then click on “Create Branch” to create a new branch.
To make changes in your branch, go to the code editor to make changes in the branch and then, to visualize the commits use Desktop Github until you are satisfied with the changes made.
To merge a branch to the main branch, use the following commands in the following order;
git checkout main
git pull origin main
git merge master
git push origin main


Pull Requests and Code Reviews:
What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.
Pull requests are used by developers to suggest the addition of changes from one branch to another. The pull request helps to notify other developers of the changes made and opens room for discussions about the changes which then may or may not be added to the repository. To create a pull request, follow the following steps:
Go to the main repository where changes are to be made
Click on the Branch menu and select the branch with the changes
From the area highlighted in yellow, click on Compare & Pull the request
Click the Base Branch icon to select the branch you are targeting
Click on the Compare button to choose the topic changes were made for
Give a name and description for your pull request
Click on Create Pull Request to create a pull request that is now ready for review by others
To review the pull requests, in the repository:
Click on the Pull Requests icon under the name of your repository
Click on the requests you would like to view
Then click on Files Changed
Hover over the lines of code where you wish to add comments to using the + icon.



 GitHub Actions:
Explain what GitHub Actions are and how they can be used to automate workflows. 
GitHub Actions is a continuous integration and delivery platform that allows for the automation of the pipeline used for building, testing and deploying one’s code.
A developer can use automated workflows the automated testing to test code after it has been pushed. Git Hub actions
The steps to create a workflow using GitHub Actions are as follows;
In your repository, go to the .github/workflows directory and create github-actions-demo.yml file
Copy the GitHub-provided YAML contents into the file
Then click on the Propose Changes button
Provide an example of a simple CI/CD pipeline using GitHub Actions. 
Pulling of requests-deployment of approved commits-testing- checking of results-approving of the results


Introduction to Visual Studio:
What is Visual Studio, and what are its key features? 
Visual Studio is a platform that allows the development of apps and games using different languages. Visual Studio’s key features include developing, debugging, testing and deployment features.
How does it differ from Visual Studio Code?
Visual Studio provides an IDE environment while Visual Studio Code is a text editor.




 Integrating GitHub with Visual Studio:
Describe the steps to integrate a GitHub repository with Visual Studio.
Download the suitable version of Visual Studio to your device and launch it.
Go to the website for GiHub for Visual Studio, and download the extension.
From the downloads folder, click on the downloaded files and follow the installation steps.
After installation, run the software
Go to the Tools icon and select the Online Visual Studio Gallery
Search for GitHub in the search box. Then click on the GitHub extension for Visual Studio and then download it
After the installation, reload Visual Studio and you have now integrated Visual Studio with GitHub
 How does this integration enhance the development workflow?
The integration enhances workflow among developers by enhancing cloning, branching, pulling requests and creating of enhanced workflow environment.
Debugging in Visual Studio:
Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?
Visual Studio has various debugging tools such as the ones that need to be installed in Windows. Some of the tools include;
 Kill which helps to terminate a process
Dumb CHK which helps to validate memory
GFlags helps to control various settings and the control of registry keys
 PLM Debug helps to debug the Windows application running through a process
TList helps the developer know what processes are running in the project.
Windows Debuggers help to run and debug code in the same device but at times, it may require running and debugging the code in different devices.
Command Line Debuggers help to debug lines of code at a time.


Collaborative Development using GitHub and Visual Studio:
Discuss how GitHub and Visual Studio can be used together to support collaborative development. 
GitHub and Visual Studio can be used together by installing GitHub extensions in Visual Studio. The extensions include GitHub Extension and GitHub Copilot extension. With these extensions, developers can collaborate on projects using Pull Requests to notify others of the changes they have made to the code. Git Hub also enhances a Discussions interface where developers can discuss the code and come up with different ideas.
Provide a real-world example of a project that benefits from this integration.
Visual Studio integration with GitHub can be used to develop websites, web applications as well as mobile apps.


Sources
https://docs.github.com/en/enterprise-cloud@latest/repositories/creating-and-managing-repositories/about-repositories
https://github.com/features#features-collaboration
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository
https://docs.github.com/en/desktop/making-changes-in-a-branch
https://stackoverflow.com/questions/70460220/how-to-merge-a-branch-to-main-branch-in-github
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/reviewing-proposed-changes-in-a-pull-request
https://resources.github.com/devops/ci-cd/
https://visualstudio.microsoft.com/vs/features/
https://github.com/github/VisualStudio/blob/master/docs/getting-started/installing-github-for-visual-studio.md
https://learn.microsoft.com/en-us/windows-hardware/drivers/debugger/extra-tools
https://github.com/features#features-collaboration
