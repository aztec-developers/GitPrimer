# GitPrimer
Learn how to use git: clone, add, commit, branch, checkout, diff, clean, push, and pull


## Guide
It's important to have a basic understanding of source control before jumping into big projects. Source control is
what allows teams to work on large, complex projects at the same time. Aztec Developer's source control of choice
is Git, with all of our projects being stored on GitHub. Before editing or starting on a project with the club it'd
be a good idea to go over this Git Primer to obtain a basic understanding. Just follow these steps and you should b
good to go!

## Steps

1. First clone this repo onto your local machine by using `git clone https://github.com/aztec-developers/GitPrimer.git`
2. cd into the folder created and then create your own branch. Branching allows multiple developers work on the samefiles at the same time without stepping on each other's toes. Do this by using the command: `git checkout -b <branch name>`. To make everything easy just name the branch your github username
3. Now lets edit the text file! Open the file with your favorite text-editor and add your github username to the file. After you've made your edit you'll want to make a commit, this can be done in a series of steps. First add all the files by using `git add .` (The period is just a shortcut to add everything in the directory), then use the command `git commit -m "<commit message here>". It's extremely important to have a descriptive commit message detailing what you worked on.
4. Before pushing your changes we can take a quick look at the diff command. By using the command `git diff <filename>` you'll be able to see all of the changes you've made to the file.
5. Now you can push your changes to your branch. Do this by running `git push origin <branch name>`.
6. To merge your changes with the master branch you'll need to execute a pull request. Do 
