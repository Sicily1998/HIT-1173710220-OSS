Contributor's Guide
HOW TO CONTRIBUTE TO OPEN SOURCE accepts PR's (pull requests) from newbies only, this is to help newbies get familiar with the contribution processes.

Issues can be submitted by anyone - seasoned developers or newbies.

Getting Started
If you are new to Git and GitHub, it is advisable that you go through GitHub For Beginners before moving to Step 2.

Fork the project on GitHub. Help Guide to Fork a Repository.

Illustration for How to Fork a Repository

Clone the project. Help Guide to Clone a Repository

Create a branch specific to the issue you are working on.

git checkout -b update-readme-file
For clarity, name your branch update-xxx or fix-xxx. The xxx is a short description of the changes you're making. Examples include update-readme or fix-typo-on-contribution-md.

Open up the project in your favorite text editor, select the file you want to contribute to, and make your changes.

If you are making changes to the README.md file, you would need to have Markdown knowledge. Visit here to read about GitHub Markdown and here to practice.

If you are adding a new project/organisation to the README, make sure it's listed in alphabetical order.
If you are adding a new organisation, make sure you add an organisation label to the organisation name. This would help distinguish projects from organisation projects.
Add your modified files to git, How to Add, Commit, Push, and Go.

git add path/to/filename.ext
You can also add all unstaged files using:

git add .
Note: using a git add . will automatically add all files. You can do a git status to see your changes, but do it before git add.

Commit your changes using a descriptive commit message.

git commit -m "Brief Description of Commit"
Push your commits to your GitHub Fork:

git push -u origin branch-name
Submit a pull request.

Within GitHub, visit this main repository and you should see a banner suggesting to make a pull request. While you're writing up the pull request, you can add Closes #XXX in the message body where #XXX is the issue you're fixing. So an example would be Closes #42 would close issue #42.

Submitting a Pull Request
What is a Pull Request?

If you decide to fix an issue, it's advisable to check the comment thread to see if there's somebody already working on a fix. If no one is working on it, kindly leave a comment stating that you intend to work on it. That way other people don't accidentally duplicate your effort.

In a situation whereby somebody decides to fix an issue but doesn't follow up for a particular period of time, say 2-3 weeks, it's acceptable to still pick up the issue but make sure to leave a comment.

Note: Every open-source project has a CONTRIBUTING.md file, please make sure to read this before you open up a pull request, otherwise it may be rejected. However, if you do not see any CONTRIBUTING.md file, you can send a pull request but do it in a descriptive manner.

Helpful Resources
Pro GIT Book

Try Git

Git/ Git Hub on Windows
