# Git-cheat_sheet
Shortcuts of git using command prompt


•	git config --global user.name LN

•	git config --global user.email Laxmi.narayan.one@gmail.com

•	git init (initialize empty git repo)

•	ls (list of files)

•	ls -lart(condition of file)

•	git status(is there any commit or uncommited file)

•	Initial commit(after commit)

•	Press ESC and type :wq to exit

•	touch hello.py (to create file)

•	touch about.html

•	git add file_name (to add file)

•	git add -A (to add all file simultaneously)

•	git checkout ( to recover mashed single)

•	git checkout -f (to cover all files)

•	git log (tell us about files and author)

•	git log -p -3(means we can see log of 3 files only)

•	git diff (it compare working tree to staging area)

•	git diff –staged(now it compare  staging area to last commit)
	
•	git commit –a -m “Skipped staging area and fixed <”

•	git rm –cached (file removed form staging area but not from hard disk)

•	git rm file_name(removed from hard disk)

•	git status -s(file modifying in staging area)

•	git checkout contact.html(will recover previous condition)

•	touch .gitignore (will create file whre we can give file name which need to ignore during pushing and pulling form and to server)

•	touch mylogs.log(if create such file then write same thing in .gitignore file and save)

•	then git will ignore those files

•	git log -p -3 (will show 3 file changes, but)

•	YOU HAVE TO EXIT THAT LOG BY PRESSING q button in keyboard


Branching

Branch means if you are at master branch on any real time working environment so by mistake you can do any blunder mistake so you should create your own specific branch
•	git branch feature1
•	git branch(will tell feature1) and switched for that branch
•	git checkout feature1( will switch to feature1 branch)
•	but creation done by “git branch feature2”
•	If I want direct creation with switching then 
•	git checkout -b flaskIntegration (direct lotai)
•	
•	

