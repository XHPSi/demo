# demo
Initial repos construct

Create a new repository at github.com. (this is your repository)

Give it the same name as the other repository.
Don't initialize it with a README, .gitignore, or license.
Clone the other repository to your local machine. (if you haven't done so already)

git clone https://github.com/other-account/other-repository.git
Rename the local repository's current 'origin' to 'upstream'.

git remote rename origin upstream
Give the local repository an 'origin' that points to your repository.

git remote add origin https://github.com/your-account/your-repository.git
Push the local repository to your repository on github.

git push origin master
