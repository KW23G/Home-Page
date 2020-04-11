The most important git commands (for Sven):

You can also see many of these commands on the page of an empty  Repository on github.

#########

Section 1: Creating a new Repo (I prefer using the second way, althought the first way is easier)

Way 1:

-create a new Repository on github

-clone the Repository like this: 'git clone [repo-url]'

-do something

-push your commits like this: 'git push' (Here you don't need to specify the location, that automatically happens when you're cloning the Repo)

#####

Way 2:

-create a new Repository on github

-create the project directory on your computer (not cloning, just 'mkdir [repo-name]')

-do 'git init' and 'git add .' in your project-directory

-do something

-to push your project to github, use the following commands: 'git remote add origin [repo-url]' and 'git push -u origin master'

#########

Section 2: Changes / commits (after you have done section 1 !)

-before committing, you have to stage what you want to commit: You can stage everything or just a file: 'git stage .' / 'git stage README.md'

-to create a commit with the staged content, say 'git commit -m "[commit-message]" '

-to push it, you can just say 'git push' because git already knows the location from section 1
