# Git External exam
# Commands to Stash changes, switch branches, and then apply the stashed message.
<p>
  <h> <b> Syntax </b> </h>
  <ol>
  <li> git config --global user.name "username"</li> 
  <li> git config --global user.email "useremail"</li>
  <li> git clone <repo-url></li>
  <li> cd repo_name</li>
  <li> git status</li>
  <li> git checkout -b branch_name</li>
  <li> nano file_name</li>
  <li> git add .</li>
  <li> git stash -m "Message" </li>
  <li> git checkout -b new_branch_name</li>
  <li> git stash apply</li>
  <li> git push origin new_branch_name</li>
  <li> git stash list</li>
  <li> git push origin branch_name</li>
  </ol>
</p>

<p>
  <h> <b> Execution </b> </h>
  <ol>
  <li> git config --global user.name "subhangidutta23"</li> 
  <li> git config --global user.email "subhangidutta23@gmail.com"</li>
  <li> git clone https://github.com/subhangidutta23-ship-it/git_exam.git
  <li> cd git_exam</li>
  <li> git status</li>
  <li> git checkout -b master</li>
  <li> nano main.py</li>
  <li> git add .</li>
  <li> git stash -m "Stashed Message" </li>
  <li> git checkout -b feature-branch</li>
  <li> git stash apply</li>
  <li> git push origin feature-branch</li>
  <li> git stash list</li>
  <li> git push origin master</li>
  </ol>
</p>
