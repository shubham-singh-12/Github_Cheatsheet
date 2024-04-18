# Github_Cheatsheet


<!-- To Check GIT VERSION -->
<h2>To check GIT VERSION</h2><br>
<code> git --version </code>



<hr><br>
<!-- Configuring Git -->
<h2>Configuring GIT</h2><br>
<code> git config --global user.name <b>"username"</b></code><br>
<code> git config --global user.email <b>"xyz@gmail.com"</b></code><br>
<code> git config --list</code>



<hr><br>
<!-- Clone a Repository on our Local Machine -->
<h2>Clone Repository on Local Machine</h2><br>
<code>git clone <b>repository_link</b></code>



<hr><br>
<!-- Check Status -->
<h2>To Check Status</h2><br>
<code>git status</code>



<hr><br>
<!-- Add new or Changed files in our Working directory to the git staging area -->
<h2>Add</h2><br>
<b>To Add a particular file: <b><code>git add <b>file_name</b></code><br> 
<b>To Add all the files: <b><code>git add .</code>



<hr><br>
<!-- It is the Record of Change -->
<h2>Commit</h2><br>
#Here, <b><i>-m</i></b> stands <b><i>message</i></b><br>
<code>git commit -m <b>"message"</b></code>



<hr><br>
<!-- To push the changes to the remote repository -->
<h2>Push Command</h2><br>
<code>git push origin main</code><br>
#Here, <i><b>origin</i></b> is <i><b>github repository</i></b><br>
#And, <i><b>main</i></b> is <i><b>branch name</i></b>



<hr><br>
<!-- It is used to create a new git repository -->
<h2>Init Command</h2><br>

<code>git init</code><br>

<code>git remote add origin <b>link</b></code><br>

<i>To Verify Remote: </i>
<code>git remote <b>-v</b></code><br>

<i>To Check Branch, (by default:main): </i>
<code>git branch</code><br>

<i>Upload local branch commits to the remote repository branch: </i><br>
<code>git push -u origin main</code><br>
OR<br>
<code>git push origin main</code>



<hr><br>
<h2>Branch Command</h2>
<br>

<i>To Check Branch: </i>
<code>git branch</code>
<br>

<i>To Change branch name to main: </i>
<code>git branch -M <b>main</b></code>
<br>

<i>To move from one branch to another: </i>
<code>git checkout <b>branch name</b></code>
<br>

<i>Create new branch and move to that branch: </i>
<code>git checkout -b <b>branch name</b></code>
<br>

<i>To delete branch: </i>
<code>git branch -d <b>branch name</b></code>



<hr><br>