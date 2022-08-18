# kottans-frontend
<p align="center">
<img src="https://github.com/kryvoshei/kottans-frontend/blob/main/images/photo_5454291811322411856_y.jpg" style="width: 500px; height: 500px; max-width: 100%;">
</p>

<details><summary><h2>:zero: Git Basics</h2></summary>
<h3>:white_check_mark: Coursera Introduction to Git and GitHub</h3>
<details><summary>Week 1</summary>
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_git_basics/coursera-git-week-1.png">
  </details>
  <details><summary>Week 2</summary>
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_git_basics/coursera-git-week-2.png">
  </details>
  
**Things new to me:**

I have used before a few commands, such as *git add*, *git commit*, *git push*, *git clone*, *git status*, *git merge*, so many things were actually new. They definitely should be put into practice as much as possible to solidify knowledge.

**What amazed me:**

The anatomy of a commit message was a complete discovery. So, I know now that a commit message is generally broken up into a few sections. The first line is usually kept to about 50 characters or less. The line contains a short description of what the commit changes are about. After the first line, comes an empty line, and the rest of the text is usually kept under 72 characters.

**Things to be used in the future:**

- <code>git rm</code> - deletes or removes a file;
- <code>git reset</code> - basically resets the repo, throwing away some changes;
- <code>git commit --amend</code> - is used to make changes to commits after-the-fact, which can be useful for making notes about a given commit;
- <code>git revert</code> - makes a new commit which effectively rolls back a previous commit.

<h3>:white_check_mark: learngitbranching.js.org</h3>
<details><summary>Introduction Sequence</summary>
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_git_basics/introduction-sequence.png">
  </details>
  <details><summary>Push and Pull</summary>
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_git_basics/push-pull.png">
  </details>
  
**Things new to me:**

Introduction to git commits was quite simple. But it never hurts to repeat the information.

**What amazed me:**

Practicing how to fetch data from a remote repository with the command <code>git fetch</code> was valuable.

**Things to be used in the future:**
<p>All the commands from this part of https://learngitbranching.js.org/ (namely, <code>git push</code>, <code>git pull</code>, <code>git fetch</code>, etc.) can be used in the workflow.</p>
</details>
<details><summary><h2>:one: Linux CLI, and HTTP</h2></summary>
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
  
<details><summary><h2>:two: Git Collaboration</h2></summary>
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
<p><ul>
  <li><code>git rebase</code> - to move or combine a sequence of commits to a new base commit;</li>
   <li><code>git cherry-pick</code></li>
</ul>
And only practice will show which commands are actually better to use in certain cases.
</p>
 </details>  

<details><summary><h2>:three: Intro to HTML and CSS</h2></summary>
<details><summary><h3>:thumbsup: Coursera Intro to HTML & CSS (Weeks 1-2) (screenshots)</h3></summary>
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_html_css_intro/coursera-html-css-week1.png">
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_html_css_intro/coursera-html-css-week2.png">
  </details>
  
**Things new to me:**

Relevant history of HTML. I have not heard about WHATWG (Web Hypertext Application Technology Group) and that WHATWG and W3 started working together. The result of this cooperaion is HTML5.
  
**What amazed me:**

Three characters that should be escaped to make sure they don't cause rendering issues: **<**, **>**, **&**. 

**Things to be used in the future:**

HTML and CSS basics are the core from which the profession of a front-end developer begins. I am already familiar with the information because I have learned it before, but there are always new or forgotten details. Of course, everything will be used in my future work.
  
<details><summary><h3>:thumbsup: Codecademy Learn HTML, Learn CSS (screenshots)</h3></summary>
  <img src="https://github.com/kryvoshei/kottans-frontend/blob/main/task_html_css_intro/codecademy-html-css.png">
  </details>
  
**Things new to me:**

  The <code>scope</code> attribute: <code>scope="row"</code> or <code>scope="col"</code> to specify that the heading is exactly for a row or for a col.
  
**What amazed me:**

The <code>step</code> attribute in a number input which created arrows inside the input filed to increase or decrease by the value of the <code>step</code> attribute.
  The <code>embed</code> tag which can embed any media content including videos, audio files and gifts from an external source. :exclamation: **It is deprecated.**

**Things to be used in the future:**

Everything in these courses is useful to understand the basics and prepare the ground for JS learning, to make layouts, and to better understand some common things every front-end developer should know. I will definitely use all the things.
  </details>
  
<details><summary><h2>:four: Responsive Web Design</h2></summary>
<h3>:thumbsup: <a href="https://web.dev/i18n/en/responsive-web-design-basics/" target="_blank">Responsive web design basics</a></h3>
   
**Things new to me:**

Multi-column layout (Multicol) which can create responsive numbers of columns with the column-width property.
  
**What amazed me:**

The features any-hover and any-pointer that test if the user has the capability to hover or use the type of pointer even if it is not the primary way they are interacting with the device. :exclamation: **Though we should be very careful when using them.**

**Things to be used in the future:**

Information about images is just top. To never have a problem with images causing a scrollbar, we need to use the following: 

**img {
  max-width: 100%;
  display: block;
}**

<h3>:thumbsup: <a href="https://www.youtube.com/playlist?list=PLM6XATa8CAG5mPV60dMmjMRrHVW4LmV2x" target="_blank">FLEXBOX. Вчимося верстати на флексах</a> і <a href="https://www.youtube.com/watch?v=GV92IdMGFfA&list=PLM6XATa8CAG5pXQrW_kDaeZb_uIAMNZIm">CSS Grid Layout</a></h3>
   
**Things new to me:**

Zhenya Andricanych just rocks. I have been subscribed to his YouTube channel for a year now, and I have already watched these playlists. 
  
**What amazed me:**

It is amazing how quickly you can forget the information if you do not use it on an ongoing basis. I do not usually use CSS grid layout, so it was good to rewatch the videos.

**Things to be used in the future:**

I like Flexbox more, it seems easier to me. In case the Grid layout will be required, I will be able to fulfill it.
</details>
  
