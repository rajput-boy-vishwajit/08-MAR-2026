
<h1 align="center">Git & GitHub in One Shot</h1>

<p align="center">
A quick guide to understanding Git and GitHub fundamentals.
</p>

<hr>

<h2><u>Git</u></h2>
<p>
Version Control System is a tool that helps to track changes in code Git is a <b>Version Control System (VCS)</b> it is:
</p>

<ul>
<li>Popular, free & Open Source, fast & Scalable</li>
</ul>

<hr>

<h2><u>GitHub</u></h2>

<p>
<b>Website</b> that allows developers to store and mange their code using Git.
</p>

<pre>http://github.com</pre>

<hr>

<h2><u>GitHub Account</u></h2>
<ul>
<li>Create a new repository:</li>
<li>Make our first commit</li>
</ul>

<h2><u>Setting up Git</u></h2>

<p>
Visual Studio Code <br>
Windows (Git Bash <br>
Mac (Terminal) <br>
</p>

<pre>
git --version
</pre>


<h2><u>Configuring Git</u></h2>
<pre>
git config --global user.name "My Name"
git config --global user.email "someone@email.com
git config --list
</pre>


<h2><u>Clone & Status</u></h2>
<p>
<b>Clone - </b> Cloning a repository on our local machine.
</p>

<pre>
git clone <SOME LINK>
</pre>


<p>
<b>Status - </b> displays the state of the code.
</p>

<pre>
git status
</pre>

<h4>Untracked</h4>
<p>New files that git dosen't yet track </p>

<h4>Modified</h4>
<p>Changed </p>

<h4>Staged</h4>
<p>File is ready to be committed </p>

<h4>Unmodified</h4>
<p>Unchanged </p>


<h2>Add & Commit</h2>
<p><b>add - </b> adds new or changed files in your working directory to the Git staging area.</p>
<pre>git add (FILE NAME) </pre>

<p><b>commit - </b> it is the record of change. </p>
<pre>git commit -m "SOME MESSAGE" </pre>


******************************


<pre><h2>index.html</h2>
<p><b>index.html - </b> to create index.html file.  [29:50] </p>
<p>hello world</p>
git status
git add index.html
git add .
git status
git commit -m "commit message"
git status
git push origin main

</pre>

<h2>Push Command</h2>
<p><b>push - </b> upload local repo content to remote repo  </p>
<pre>git push origin main </pre>



<h2>Init Command</h2>
<pre>
git init
git remote add origin (LINK)
git remote -v (to verify remote)
git branch (to check brank) 
git branch -M main (to rename branch)
git push origin main
</pre>




<h2>REPO: LocalRepo</h2>
<pre>
index.html
style.css
README.md
</pre>

<pre>
git init
git remote add origin <LINK>
git remote -v
</pre>

<h2>BRANCH:</h2>
<pre>
git branch
git branch -M main
git push origin main
</pre>

<h2>GIT BRANCHS:</h2>
<pre>
git branch
git branch -M main
git checkout <BRANCH_NAME>
git checkout -b <NEW_BRANCH_NAME>
git branch -d <BRANCH_NAME>
</pre>

<h4>NEW BRANCH CREATED:</h4>
<pre>
git checkout -b feature1
git checkout main
git checkout -b feature2
git checkout main
git branch -d feature2
</pre>

<h3>
main<br>
*feature<br>
</h3>
<p>
- Changes New added into <b>*feature1</b> branch <b>modified</b>
</p>
<h2>MERGING CODE With feature BRANCH:</h2>

<h2>PULL COMMAND:</h2>

<h2>RESOLVING MERGE CONFLICTS:</h2>



**************************
**************************

<h2>Features of Git</h2>

<ul>
<li>Popular among developers</li>
<li>Free and open source</li>
<li>Fast and scalable</li>
<li>Efficient tracking of code changes</li>
<li>Supports branching and merging</li>
</ul>

<hr>

<h2>Example Git Commands</h2>


<pre>
git status
</pre>

<hr>

<h2>Basic Git Workflow</h2>

<pre>
Working Directory -> Staging Area -> Repository
      git add            git commit
</pre>

<hr>

<h3>Author</h3>

<p>
Vishwajit Rajput
</p>
