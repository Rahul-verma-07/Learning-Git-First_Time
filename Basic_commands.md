# Basic_commands
1. <b>CLONE</b> :- Cloning a repository on our local machine.<br>
<pre>              => <b>git clone <-Some Link-></b>   </pre><br>
2. <b>STATUS</b> :- Displays the state of the code.<br>
<pre>              => <b>git status</b>   </pre>
<p1>Status Types :-</p1><br>
a. UNTRACKED : New files that git doesn't get track.<br>
b. MODIFIED : Changes occured in a file.<br>
c. STAGED : Files are ready to Commit.<br>
d. UNMODIFIED : Unchanged file.<br><br>

3. <b>ADD</b> :- To add new files and changed files in the working directory to the git staging area.<br>
<pre>              => <b>git add <-File Name-></b>   </pre><br>
4. <b>COMMIT</b> :- It is the record of the changes we've done in the file.<br>
<pre>              => <b>git commit <-File Name-></b>   </pre><br>
5. <b>PUSH</b> :- To upload local repository content to the remote repository.<br>
<pre>              => <b>git push origin main</b>   </pre><br>
6. <b>TOUCH</b> :- To add a new file to our repository branch.<br>
<pre>              => <b>touch <-New file name-></b>   </pre><br>
7. <b>INIT</b> :- It's used to create a new Git repository.<br>
<pre>              => <b>git init</b>   </pre><br>
8. <b>GIT BRANCHES</b> :- To provide another copy of the repository and code to allow others modify new changes.<br><br>
<p2><b>COMMANDS :-</b></p2><br><br>
=> To check branch :
<pre>              => <b>git branch</b>   </pre><br>
=> To rename branch :
<pre>              => <b>git branch -m</b>   </pre><br>
=> To navigate branch :
<pre>              => <b>git checkout <-Branch name-></b>   </pre><br>
=> To create new branch :
<pre>              => <b>git checkout -b <-New branch name-></b>   </pre><br>
=> To delete branch :
<pre>              => <b>git branch -d <-Branch name-></b>   </pre><br>
9. <b>GIT IGNORE</b> :- A file which is not made for commit, used for personal purpose. we can add extra unwanted files in git ignore.
<pre>              => <b>touch .gitignore</b>   </pre><br>
# <b>UNSTAGE</b> :- To unstage any file or changes.
<pre>              => <b>git restore --staged <-File Name-></b>   </pre><br>
# <b>REMOTE</b> :- To PUSH all commits from our local machine to remote repository.
<pre>              => <b>git remote add origin <-Some Link-></b>   </pre><br>
<pre>              => <b>git push origin main</b>   </pre><br>