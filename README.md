# water-for-all

**Greetings Team.** 

My name is Steven Poulin. I studied at Bishops and now we are going to collaborate on a Nasa Project. Layachi told me times and times again, and I will tell you: Do projects like these, and coop programs. They will make the difference between being an amazon delivery driver or a programmer, afterwards. Workplaces need experience. Even more than a degree. 

This said, let's start. 

This is our repository for the Space Apps 2020 challenge. Catherine is our project manager, Ahmad and I will be your guides for the coding part. You may very well know more than we do, so we encourage you to speak up, show us what you can do and take charge of things you feel comfortable with. 

In a repository, we can work on things in parallel and separate the work. There is a master which is the project, then we pull out a clone on our own workspace, work on our part, then merge with the master, or a branch (which is a master in a parallel dimension).

Resources:  https://youtu.be/SWYqp7iY_Tc  - this is an introductory video on git
            http://try.github.io/

GIT CHEAT SHEET : https://education.github.com/git-cheat-sheet-education.pdf

First, you will need to create a github account if you do not have one. Then send your github name to Catherine or in our messenger group.

You will need to install node.js and npm : https://www.npmjs.com/get-npm     -afterwards, you will be able to use the command line to generate code, install dependencies, etc.

Download visual code studio ( it doesnt really matter which IDE you use to code, but this one is great, easy, dynamic and i can help youwith )
https://visualstudio.microsoft.com/downloads/
and then install the extensions:
            Eslint
            Prettier
            Auto Rename Tag
            Javascript Booster
                        And extra:
                                    Bracket pair colorizer
                                    Colonize

You need to install git on your computer to use it in the command line, which is standard in the industry. https://git-scm.com/downloads

The workflow is basically this: 
            -Go to command line and enter these commands
            ```
            git clone https://github.com/SpaceApps20-Water/water-for-all.git
            cd water-for-all
            npm install ``` (install all the dependencies you need to run the web-app)
            `npm start` (will start a local server for local development)

Then you can work on your part. When you are happy with the result, the command is : `git add .` (this will add the changes to the upcoming commit)
                                                                                     `git commit -m` (then a short description of your work) (this will commit the changes to your version)
                                                                                     `git push origin master` (this will push your changes to the master version)
                                                                                     
** Note: you will probably be given branches to work on (parallel versions of the master) and then we will merge these branches, it looks like `git commit origin branchname`   

*** Happily, git and github keep track of every changes and every versions. So we can always go back to working ones. Typically, the master version is always runnable. So the hardwork is done on branches, then merged after tests and approval.
                                                                                     
                                                                                  
For our design and website team, you can use (codepen.io). There you can code in html, css and javascript and see the results all in a browser. Perfect to design a button, menus, transitions, etc. 

Since we don't learn everything at Bishop's, online tutorial and online courses are great. 

Brad Traversy on youtube is pretty awesome. To learn html, css, javascript, frameworks like react and vue, and much else. He is now in a sabatical and has hired helpers, so dig down in his videos to find him.

We will update this readme to concern only the web app use and the code afterwards, as README files are meant for this.
