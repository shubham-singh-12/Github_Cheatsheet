# Github_Cheatsheet


<!-- To Check GIT VERSION -->
<i>To check GIT VERSION</i><br>
<code> git --version </code>



<hr><br>
<!-- Configuring Git -->
<i>Configuring GIT</i><br>
<code> git config --global user.name <b>"username"</b></code><br>
<code> git config --global user.email <b>"xyz@gmail.com"</b></code><br>
<code> git config --list</code>



<hr><br>
<!-- Clone a Repository on our Local Machine -->
<i>Clone Repository on Local Machine</i><br>
<code>git clone <b>repository_link</b></code>



<hr><br>
<!-- Check Status -->
<i>To Check Status</i><br>
<code>git status</code>



<hr><br>
<!-- Add new or Changed files in our Working directory to the git staging area -->
<i>Add</i><br>
<b>To Add a particular file: <b><code>git add <b>file_name</b></code><br> 
<b>To Add all the files: <b><code>git add .</code>



<hr><br>
<!-- It is the Record of Change -->
<i>Commit</i><br>
#Here, <b><i>-m</i></b> stands <b><i>message</i></b><br>
<code>git commit -m <b>"message"</b></code>



<hr><br>
<!-- To push the changes to the remote repository -->
<i>Push Command</i><br>
<code>git push origin main</code><br>
#Here, <i><b>origin</i></b> is <i><b>github repository</i></b><br>
#And, <i><b>main</i></b> is <i><b>branch name</i></b>



<hr><br>
<!-- It is used to create a new git repository -->
<h3>Init Command</h3><br>

<code>git init</code><br>

<code>git remote add origin <b>link</b></code><br>

<i>To Verify Remote: </i>
<code>git remote <b>-v</b></code><br>

<i>To Check Branch, (by default:main): </i>
<code>git branch</code><br>

<i>To Rename branch to Main: </i>
<code>git branch -M <b>main</b></code>

<i>Upload local branch commits to the remote repository branch</i>
<code>git push -u origin main</code><br>
OR<br>
<code>git push origin main</code>



<hr><br>