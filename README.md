# project_for_new_projects
___This project is made for creating and edditing new project___
## In order to use this tool you can:
1. Go to the folder with this tool in the terminal:
`cd your/path/to/project_for_new_projects`
2. Add execute permission for the file owner of init:
`chmod +x ./.init`
3. Make an empty directory where you want all your projects
4. Run the program ./.init
`./.init`
5. Follow directions
	
	a. Enter path/to/your/dir from home dir whithout ~
	
	For example if you want to have all your projects in directory ~/projects you need to enter "projects"
	
	Example 2:  if you want to have all your projects in directory ~/studies/projects you need to enter "studies/projects"
	
	b. Make directory hierarchi following directions
## What you can do with this 
### Making new project
Then if you want to make new project you can run: `./.new_project` while you are in each folder from home path (~) to ~/path/where/you/want/to/make/it and follow directions, __but only at home folder or somewhere in folder you maded in init__

__If you are making project from some folder, you can make it only in this folder or folders inside this!!!__

if you want to make project you can use ./.new_project following the rules described above

while following directions you can add readme file, add git-repository, add to your github-repository or clone it and choose language of your project
### Making new folder
if you want to make folder you can use ./.new_folder following the rules described above
### Making new file
if you want to make file you can use ./.new_file following the rules described above

## featches of python projects:
__if you chose python project it will add venv to your project and add commands below__ 
### Make requirements.txt
if you want to make requirements.txt automaticly you can run `./.make_reqs`, and you don't even need to install all libraries it will install it automaticly, but it can workwith bugs
### Run program
If you want to run program you can run `./.run`, but you need to write in main file bash script:
```python3 <file> <function>```
and if you need not only one function to run program you can write more then one line, but first line is need to be `source venv/bin/activate`

