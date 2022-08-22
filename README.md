<h1>Comprehensive Terminal Commands Cheatsheet</h1>
<h3> …or create a new repository on the command line </h3>
<p>
  echo "# TerminalCommandsCheatSheet" >> README.md</br>
  git init</br>
  git add README.md </br>
  git commit -m "first commit" </br>
  git branch -M main </br>
  git remote add origin https://github.com/donlevans29/TerminalCommandsCheatSheet.git </br>
  git push -u origin main </br>
</p>

…or push an existing repository from the command line
git remote add origin https://github.com/donlevans29/TerminalCommandsCheatSheet.git
git branch -M main
git push -u origin main

…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.


<h2>WINDOWS GIT BASH</h2>
<p> $ git config --global user.name example: "Javascript Don" </p>
<p> $ git config –globlal core.editor “xyzsoftware.exe” </p>
<p>$ git config --global color.ui true </p>

<h3>COMMON COMMANDS</h3>
<p>
  <ul>
    <li>pwd (present working directory)</li>
    <li>ls (list the content of the current directory)</li>
    <li>cd (change directory)</li>
    <li>mkdir (make directories)</li>
    <li>echo (prints out the privded parameters/string to the standard output)</li>
    <li>touch (changes the file access and modifications times for a provided file)</li>
    <li> vim (open specified file with vim editor)</li>
    <li>nano (lets you open the file with nano editor Pico editor)</li>
    <li>cat ( concatenate and print the contents of files)</li>
    <li>grep ( search for a pattern in the specified file and trunts all the lines that match the given file)</li>
    <li>diff (used to compare given files line by line and prints out ht lines that are different in each file)</li>
    <li>head (prints out the content of the file from the beginning of the file a per the given flags)</li>
    <li>tail (prints out the content to the file from the end of the file as per the given flags)</li>
    <li>rm (remove directory entries. deletes the files for the given filename/path. can also be used tjo delete directories</li>
    <li>based on the flags that you provide.</li>
    <li>clear command clears out the current terminal window and takes back the prompt to the top position of the terminal window. > is used to redirect the output from a command to be passed to another file. This will overwrite the content of the file. >> is used to redirect the output from a command to be passed to another file. This will append to the content of the file. </li>   
    <li>cp is used to copy files from one directory to another. </li>
    <li>scp is    the same as the cp but is used to copy files between remote servers. </li>
    <li>mv is used to move files from one directory to another. </li>
    <li>git add . (saves changes) </li>
    <li>git commit -m"message with the commit" (commit to the repository) </li>
  </ul>
</p>


<h3>INITILIZE A DIRECTORY</h3>
<ul>
  <li>git init to initialize a project on your enviroment already open and created </li>
  <li>git clone (clones a repo) </li>
  <li>cd --> changes directory  </li>
  <li> --> drag and drop folder path into terminal </li>
  <li> npm i --> another way to say install</li>
  <li> code . --> opens project into Visual Studio Code </li>
  <li> git status (shows the status of all the files) </li>
  <li> git diff [filename] will show the difference in green of the actual changes</li>
  <li> git tracks changes via the hash# </li>
  <li> every new commit of the file shows a refernce to the preceding it. </li>
  <li> if you commit without using the -m it will open a vin but when you hit enter it just keeps adding a new line </li>
  <li> it can be confusing on how to commit the message so what you do is. </li>
  <li> " Press Esc and then type :wq to save and exit." </li>
  <li> rm filename.ext (to remove a file) </li>
  <li> mv (moves the file is git's way of renaming a file. If you manually rename the file git will see it as deleted and new name as added --> if you git status it would show that the files are similar 50% sameness. If you want to user terminal to rename you use git mv filename.ext newfilename.ext. now if you do a git status it would show a rename)</li>
   <li> </li>
  
</ul>

![image](https://user-images.githubusercontent.com/18158428/148811519-4f335c94-b2c2-4e7c-bedf-65c872cf1121.png)

<h3>Node.js Commands </h3>
<ul>
  <li>git clone --bare   </li>
  <li>git clone --bool   </li>

</ul>
