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
donle@DESKTOP-KE0S180 MINGW64 /
$ git config --global user.name "Javascript Don"


donle@DESKTOP-KE0S180 MINGW64 /
$ git config --global user.email "donlevans29@gmail.com"


$ git config –globlal core.editor “xyzsoftware.exe”

donle@DESKTOP-KE0S180 MINGW64 /
$ git config --global color.ui true

<h3>COMMON COMMANDS</h3>
pwd (present working directory)
ls (list the content of the current directory)
cd (change directory)
chmod (change mode and accessiblity)
mkdir (make directories)
echo (prints out the privded parameters/string to the standard output)
touch (changes the file access and modifications times for a provided file)
vim (open specified file with vim editor)
nano (lets yo uopen the file with nano editor Pico editor)
cat ( concatenate and print the contents of files)
grep ( search for a pattern in the specified file and trunts all the lines that match the given file)
diff (used to comparie given files line by line and print sout ht lines that are different in each file)
head (prints out the content of the file from the beginning of the file a per the given flags)
tail (print sout the conten to the file fromt he end of the file as per the given flags)
rm (remove directory entries. deletes the files for the given filename/path. can also be used tjo delete directories based on the flags that you provide.
clear command clears out the current terminal window and takes back the prompt to the top position of the terminal window.
> is used to redirect the output from a command to be passed to another file. This will overwrite the content of the file.
>> is used to redirect the output from a command to be passed to another file. This will append to the content of the file.
cp is used to copy files from one directory to another.
scp is the same as the cp but is used to copy files between remote servers.
mv is used to move files from one directory to another.
git add . (saves changes)
git commit -m"message with the commit" (commit to the repository)

<h3>INITILIZE A DIRECTORY</h3>
git init to initialize a project on your enviroment already open and created
git clone (clones a repo)
cd --> changes directory
   --> drag and drop folder path into terminal
npm i --> another way to say install
code . --> opens project into Visual Studio Code

git status (shows the status of all the files)
git diff [filename] will show the difference in green of the actual changes
git tracks changes via the hash#
every new commit of the file shows a refernce to the preceding it.
if you commit without using the -m it will open a vin but when you hit enter it just keeps adding a new line
 it can be confusing on how to commit the message so what you do is.
  " Press Esc and then type :wq to save and exit."

