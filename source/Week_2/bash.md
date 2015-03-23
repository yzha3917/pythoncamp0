##Bash 

------
As the major application I'm using on a daily basis, I guess *Bash* deserves a separated section to be talked about. 

### What is Bash<sup>1</sup>?
Essentially, *Bash* is a command-line interface shell (CLI shell), contrary to a graphical user interface (GUI).  Alternatively speaking, by typing in commands on Bash, one can manipulate files and settings on the computers without touching your mouse; as for a GUI programme, a mouse is necessary to achieve any goal. 

### Why should I use it ? 
Needless to say, there are several operating systems out there, and every of them constructs utterly different GUI guideline for their platforms, which means different user experience. 

For Bash, or any CLI in general, the basic language is exact same across different platforms. Once you learnt it, it's done, lifetime, guaranteed. 

### Is it perfect ? 
Of course not. CLI programme can be considered as a replacement of Finder in OS X or Folder in Windows (with more other utilities). For any type of file other than .txt, we can only edit them through other correct softwares. 

But it is elegant, efficient, and consistent. 
### Applications on OS X<sup>2</sup>
##### Terminal 
The stack application. 
##### iTerm
The one I'm currently using, non-complains.

### Techniques<sup>3</sup>


	To create a new directory inside another new directory 
     	 	mkdir folder_name

	To go back to upper directory 
    		cd ..(/../../../..)

	To delete the directory which is empty
   		rmdir folder_name

	To delete the directory which is not empty 
    		rm -rf folder_name

	To go back to the earlier directory 
    		popd

	To create empty fils 
    		touch name.format

	To input in the empty txt file
    		cat > filename 
    		input 
     		input 
    		finish with CRTL-d

	To copy a file in the same directory
    		cp old.txt new.txt

	To copy a file in another directory 
  			cp old.txt newplace/

	To rename a file/directory
    		mv oldname newname

	To view a file in a popped up window
    		cat file.txt | less   
  			Q to quit 

	To view a file 
    		cat file.txt

	To run two commands at the same time
		cd .. && ls
		
	To change the prompt<sup>4</sup><sup>5</sup>
	      export PS1=" " 


	






------
<1> For more (and correct) information, please visit [Wikipedia](http://en.wikipedia.org/wiki/Bash_(Unix_shell)  
<2> For the complete list, please visit [Wikipedia](http://en.wikipedia.org/wiki/List_of_terminal_emulators)  
<3> For more complete command list, please visit [here](http://ss64.com/osx/)  
<4> For more details, please visit [here](http://bash.cyberciti.biz/guide/Changing_bash_prompt)  
<5> In order to permanently change the prompt, see [here](http://stackoverflow.com/questions/14416274/how-to-suppress-or-customize-mac-terminal-shell-prompt)