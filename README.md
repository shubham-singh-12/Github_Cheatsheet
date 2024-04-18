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
<h2>Merging Code (branch)</h2>
<br>

<h4>WAY - 1</h4>
<br>
<i>To compare commits, branches, files & more: </i>
<code>git diff <b>branch name</b></code>
<br>

<i>To merge 2 branches: </i>
<code>git merge <b>branch name</b></code>
<br>

<h4>WAY - 2</h4>
<br>
<i>Create a <b>PR</b> (Pull Request)</i>
<br>
<b>PR: </b>It let us tell other's about changes we've pushed to a branch in a repository on Github.
<br>



<hr><br>
<h2>Pull Command</h2>
<br>

<i>It is used to fetch and download content from a remote repository and immediately update the local repository to match that content.</i>
<br>
<code>git pull origin <b>main</b></code>
<br>
OR
<br>
<code>git pull <b>link</b></code>



<hr><br>
<h2>Merge Conflicts OR Resolving Merge Conflicts</h2>
<br>

<i>An Event that takes place when git isunable to automatically resolve differences in code between 2 commits.</i>



<hr><br>
<h2>Undoing Changes</h2>
<br><br>

<b>CASE 1:</b>
<br>
<i>Changes that were <b>add</b> but not <b>commit: </b></i>
<code>Staged changes</code>
<br>
<i>For single file: </i>
<code>git reset <b>file_name</b></code>
<br>
<i>For multi file: </i>
<code>git reset</code>
<br><br>

<b>CASE 2:</b>
<br>
<i>For One Commit: </b></i>
<code>commited changes</code>
<br>
<i>HEAD is the latest changed occurs: </i>
<code>git reset HEAD~1</b></code>
<br><br>

<b>CASE 3:</b>
<br>
<i>For many commits: </i>
<code>commited changes</code>
<br>
<i>Commit Hash: </i>
<code>git reset <b>commit_name</b></code>
<br>
<i>Commit Hash: </i>
<code>git reset --hard</code>
<br>



<hr><br>
<h2>Fork</h2>
<br>
<i>A fork is a new repository that shares code and visibility settings with the original "upstream" repository.</i>
<br>
<i>Fork is a rough copy.</i>



<hr><br>
<h2>Managing Commits</h2>
<br><br>

<i>Modify the last commit: </b></i>
<code>git commit --amend</code>
<br>

<i>Modify the last commit without changing the commit message: </i>
<code>git commit --amend --no-edit</code>
<br>

<i>Displays a condensed commit history: </i>
<code>git log --oneline</code>
<br>

<i>Shows the commit history in graphical form: </b></i>
<code>git log --graph</code>
<br>

<i>Reapplies changes on top of another base tip: </i>
<code>git rebase <b>[branch]</b></code>
<br>

<i>Create a new commit that undoes the specified changes: </i>
<code>git revert <b>[commit]</b></code>
<br>



<hr><br>
<h2>Branches and Merging</h2>
<br><br>

<i>Lista all Branches in the repository: </b></i>
<code>git branch</code>
<br>

<i>Create a new branch: </i>
<code>git branch <b>[branch_name]</b></code>
<br>

<i>Switches to the specified branch: </i>
<code>git checkout <b>[branch_name]</b></code>
<br>

<i>Merging the specified branch's history into the current branch: </b></i>
<code>git merge <b>[branch]</b></code>
<br>

<i>Delete the specified branch: </i>
<code>git branch -d <b>[branch_name]</b></code>
<br>



<hr><br>
<h2>Sharing and Updating Projects</h2>
<br><br>

<i>Uploads local branch commits to the remote repository branch: </b></i>
<code>git push <b>[alias] [branch]</b></code>
<br>

<i>Integrates remote branch changes into the current local branch: </i>
<code>git pull</code>
<br>



<hr><br>
<h2>Inspecting and Comparision</h2>
<br><br>

<i>Display the version history for the current branch: </b></i>
<code>git log</code>
<br>

<i>Shows changes to a specific file: </i>
<code>git log --follow <b>[file]</b></code>
<br>

<i>Shows content differences between 2 branches: </i>
<code>git diff <b>[brancheB]</b></code>
<br>



<hr><br>
<h2>Working with Specific Commits</h2>
<br><br>

<i>Shows metadata and content changes of the specified commit: </b></i>
<code>git show <b>[commit]</b></code>
<br>

<i>Applies the changes introduced by the specified commit on the current branch: </i>
<code>git cherry-pick <b>[commit]</b></code>
<br>

<i>Moves the current branch tip backward to the specified commit, leaving the changes in staging: </i>
<code>git reset --soft <b>[commit]</b></code>
<br>

<i>Moves the current branch tip backward to the specified commit, leaving the changes unstaged: </i>
<code>git reset <b>[commit]</b></code>
<br>

<i>Reset the working directory to the specified commit, discarding all changes: </i>
<code>git reset --hard <b>[commit]</b></code>
<br>



<hr><br>
<h2>Undoing Changes</h2>
<br><br>

<i>Undoes all commits after [commit], preserving changes locally: </b></i>
<code>git reset <b>[commit]</b></code>
<br>

<i>Eraseall changes after the specified commit: </i>
<code>git reset --hard <b>[commit]</b></code>
<br>