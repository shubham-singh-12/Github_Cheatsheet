# Github_Cheatsheet


<!-- To Check GIT VERSION -->
<i>To check GIT VERSION</i><br>
<code> git --version </code>



<hr><br>
<!-- Configuring Git -->
<i>Configuring GIT</i>
<br>
<code> git config --global user.name <b>"username"</b></code>
<br>
<code> git config --global user.email <b>"xyz@gmail.com"</b></code>
<br>
<code> git config --list</code>



<hr><br>
<!-- Clone a Repository on our Local Machine -->
<i>Clone Repository on Local Machine</i>
<br>
<code>git clone <b>repository_link</b></code>



<hr><br>
<!-- Check Status -->
<i>To Check Status</i>
<br>
<code>git status</code>



<hr><br>
<!-- Add new or Changed files in our Working directory to the git staging area -->
<i>Add</i>
<br>
#To Add a particular file.
<br>
<code>git add <b>file_name</b></code>
<br> 
#To Add all the files.
<br>
<code>git add .</code>



<hr><br>
<!-- It is the Record of Change -->
<i>Commit</i>
<br>
#Here, <b><i>-m</i></b> stands <b><i>message</i></b>
<br>
<code>git commit -m <b>"message"</b></code>



<hr><br>
<!-- To push the changes to the remote repository -->
<i>Push Command</i>
<br>
<code>git push origin main</code>
<br>
#Here, <i><b>origin</i></b> is <i><b>github repository</i></b>
<br>
#And, <i><b>main</i></b> is <i><b>branch name</i></b>



<hr><br>
<!-- It is used to create a new git repository -->
<i>Init Command</i>
<br>
<code>git init</code>
<br>
<code>git remote add origin <strong>link</strong></code>