to check status /: git status
to create file : touch (filename).txt/md etc

If you have made a project and in that there are many files and we want to make it trackable with git then : git init

After using the previous command we see that there is one hidden folder .init which will make our files traceble

4> Now again if we type : git status we will see there are untracked files
"""
kushal@kushal:~/Desktop/demo$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	readme.txt

nothing added to commit but untracked files present (use "git add" to track """

Untracked files means whatever commands are not tracked by the git so we haven't added to the git source control i.e git doesn't understand what is there 
5> So if we want to make it track use : git add readme.txt (it will only track this file)
   if we want everthing to add whater=ver is there inside untrackable or modified files so we can use this command : git add .

6>to make any files untrackable use git rm --cached "filename"

7>to make commit use git commit

then write something a message and then exit and save

8> git log will show all the commits made by others too.

9>If we want to change the commit message  the changes which we havent pushed use : git commit --amend
	It will open the text editor write the message and just save and to check write git log

10> if we want to check what is there in our github/gitlab etc use : git remote
