# kottans-frontend
<p align="center">
<img src="https://github.com/kryvoshei/kottans-frontend/blob/main/images/photo_5454291811322411856_y.jpg" style="width: 500px; height: 500px; max-width: 100%;">
</p>

## General
<details><summary><h2>Git Basics</h2></summary>
<h3>:white_check_mark: Coursera Introduction to Git and GitHub</h3>
<details><summary>Week 1</summary>
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_git_basics/coursera-git-week-1.png">
  </details>
  <details><summary>Week 2</summary>
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_git_basics/coursera-git-week-2.png">
  </details>
  
**Things new to me:**
<p>I have used before a few commands, such as *git add*, *git commit*, *git push*, *git clone*, *git status*, *git merge* so many things were actually new. They definitely should be put into practice as much as possible to solidify knowledge.</p>

**What amazed me:**
<p>The anatomy of a commit message was a complete discovery. So, I know now that a commit message is generally broken up into a few sections. The first line is usually kept to about 50 characters or less. The line contains a short description of what the commit changes are about. After the first line, comes an empty line, and the rest of the text is usually kept under 72 characters.</p>

**Things to be used in the future:**

- <code>git rm</code> - deletes or removes a file;
- <code>git reset</code> - basically resets the repo, throwing away some changes;
- <code>git commit</code> --amend - is used to make changes to commits after-the-fact, which can be useful for making notes about a given commit;
- <code>git revert</code> - makes a new commit which effectively rolls back a previous commit.

<h3>:white_check_mark: learngitbranching.js.org</h3>
<details><summary>Introduction Sequence</summary>
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_git_basics/introduction-sequence.png">
  </details>
  <details><summary>Push and Pull</summary>
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_git_basics/push-pull.png">
  </details>
  
**Things new to me:**
<p>Introduction to git commits was quite simple. But it never hurts to repeat the information.</p>

**What amazed me:**
<p>Practicing how to fetch data from a remote repository with the command <code>git fetch</code> was valuable.</p>

**Things to be used in the future:**
<p>All the commands from this part of https://learngitbranching.js.org/ (namely, <code>git push</code>, <code>git pull</code>, <code>git fetch</code>, etc.) can be used in the workflow.</p>
</details>
<details><summary><h2>Linux CLI and Networking</h2></summary>
  <details><summary><h3>:white_check_mark: Linux Survival (4 modules) (watch screenshots here)</h3></summary>
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_linux_cli/linux-quiz-1.png">
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_linux_cli/linux-quiz-2.png">
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_linux_cli/linux-quiz-3.png">
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_linux_cli/linux-quiz-4.png">
 </details>  

**Things new to me:**
<p>This is my first time working with Linux, or better said - with a simulated Linux terminal. When you face something for the first time, everything is an unexplored territory.</p>

**What amazed me:**
<p>
<ul>
<li><code>ps aux</code> - to list all the processes;</li>
<li><code>chmod</code> - to change mode, change security permissions (for u - user, g - group, o - other);</li>
<li><code>man</code> (stands for manual) - displays portions of online documentation;</li>
<li><code>man man</code> - allows to search for commands which partain to a particular subject.</li>
  </ul>
  </p>

**Things to be used in the future:**
<p>I am pretty sure that I will use Linux in practice someday and the studied material will come to the rescue. If all the commands exist, then they are used, hopefully, I will use all of them.</p>

  <h3>:white_check_mark: HTTP: The Protocol Every Web Developer Must Know—Part 1</h3>
  
**Things new to me:**
<p>HTTP verbs in a request that are though less used: <strong>HEAD</strong>, <strong>TRACE</strong>, <strong>OPTIONS</strong>.</p>

**What amazed me:**
<p>Number of general headers are shared by both the request and response messages: <code>Cache-Control</code>, <code>Connection</code>, <code>Connection</code>, <code>Pragma</code>, <code>Trailer</code>, <code>Transfer-encoding</code>, <code>Via</code>, <code>Upgrade</code>.
</p>

**Things to be used in the future:**
<p>How to send an HTTP Request With the Fetch API and choose the right HTTP verbs and headers for my use-case.</p>

<h3>:white_check_mark: HTTP: The Protocol Every Web Developer Must Know—Part 2</h3>
  
**Things new to me:**
<p>Existence of digest authentication that does not transfer a password to the server, instead, the client takes the password and the username.</p>

**What amazed me:**
<p>If the server does not send any Cache-Control headers, the client is free to use its own heuristic expiration algorithm to determine freshness.
</p>

**Things to be used in the future:**
<p>Now I know all the cache processing which will definitely be useful in my future work.</p>
  </details>
  
<details><summary><h2>Git Collaboration</h2></summary>
  <details><summary><h3>:white_check_mark:  Introduction to Git and GitHub Weeks 3 and 4 (watch screenshots here)</h3></summary>
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_git_collaboration/coursera-git-week-3.png">
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_git_collaboration/coursera-git-week-4.png">
   </details> 
   
**Things new to me:**
<p>We have two options for combining commits, <i>squash</i> and <i>fix up</i>. In both cases, the contents of the selected commit are merged into the previous commit in the list. </p>

**What amazed me:**
<p>There is an option of auto-merge. People with write permissions to a repository can enable auto-merge for a pull request.
</p>

**Things to be used in the future:**
<p>As advided, I will not rebase changes that have been pushed to remote repos.</p>
  
  <details><summary><h3>:white_check_mark: learngitbranching.js.org (watch screenshots here)</h3></summary>
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_git_collaboration/git-1.png">
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_git_collaboration/git-2.png">
   </details> 
  
  **Things new to me:**
  <p>Well, this part was a bit challenging, among new things I can pick 
  <ul>
    <li><code>git stash</code> - to stash the changes in a dirty working directory away;</li>
    <li><code>git cherry-pick</code> - enables arbitrary Git commits to be picked by reference and appended to the current working HEAD.</li>
  </ul>
  </p>

**What amazed me:**
<p>
  <ul>
  <li><code>git pull --rebase</code> - when we pull remote changes with the flag --rebase, then our local changes are reapplied on top of the remote changes;</li>
  <li><code>git pull --merge</code> - when we pull remote changes with the flag --merge, then our local changes are merged with the remote changes.</li>
</ul>
</p>

**Things to be used in the future:**
<p>As advided, I will not rebase changes that have been pushed to remote repos.</p>
 </details>  

