Git clone command : 

	git clone https://github.com/robpragmawork/demo.git
	

Set a git user:	
	
	git config --global user.email "rob.pragmawork@gmail.com"
	
	git config --global user.name "robpragmawork"
	
	
	
Solve "LF will be replaced by CRLF in git" worrning : 

	git config --global core.safecrlf false
	
	
	
Existing project add on git : 	
	
	git init
	
	git add .
	
	git commit -m "First commit"
	
	git remote add origin remote repository URL
	
	git push origin master
	
	
Create git ignore file :	
	
	ren example.gitignore .gitignore