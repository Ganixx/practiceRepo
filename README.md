This repo to get famillar with git

If you don't have git on your machine, install it.

Fork this repository
Fork this repository by clicking on the fork button on the top of this page. This will create a copy of this repository in your account.

Clone the repository
Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button, then on SSH tab and then click the copy url to clipboard icon.

Open a terminal and run the following git command:
git clone "url you just copied"
where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

For example:
git clone git@github.com:this-is-you/first-contributions.git
where this-is-you is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.



git add Contributors.md
Now commit those changes using the git commit command:

git commit -m "Add your-name to Contributors list"
replacing your-name with your name.

Push changes to GitHub
Push your changes using the command git push:

git push -u origin your-branch-name
replacing your-branch-name with the name of the branch you created earlier.

If you get any errors while pushing, click here:
Submit your changes for review
If you go to your repository on GitHub, you'll see a Compare & pull request button. Click on that button.

create a pull request

Now submit the pull request.

submit pull request

Soon I'll be merging all your changes into the main branch of this project. You will get a notification email once the changes have been merged.
