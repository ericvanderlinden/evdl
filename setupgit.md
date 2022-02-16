
Download Git for local use.  
https://git-scm.com/download/win  
Accept all settings.  
Last question: start bash. Yes.  

Pin MINGW64 to taskbar.  
The MINGW64 Bash starts in P: (Your personal directory in Huygens infrastructure).   

type: cd Documents [enter]  (The directory in P: that hold your documents). 
type: mkdir yourDirName [enter]  (Create a directory that will hold your git dir.)   
type: cd yourDirName [enter]  


-> in CMD type: conda install -c conda-forge jupyterlab [enter]  
-> [y/n] type y  
-> when install finished type: jupyter lab [enter]  
-> jupyter lab starts in explorer / edge  
-> in the file manager go to Documents/yourDirName   
-> create a new notebook (or any other file in yourDirName)  
type: git init [enter]  
(reply: Initialized empty Git repository in .git/ ....)  
type: git add . [enter] (dot means any file.)  
type: git commit  
(Git start an editor Vim. Scroll down and type: i   
Vim now in inseert mode. Type a commit comment.)  
type: esc (stop editing)  
type: :x [enter] (to save en exit.)  

go to https://desktop.github.com/  
download GitHub Desktop for windows 64bit  

New branch (create and switch)  
git branch newBranchName  
git checkout newBranchName  

or short  
git checkout -b newBranchName  

push branch  
git push --set-upstream origin newBranchName  

switch branch: git checkout yourBranch (with check)  
switch branch: git switch yourBranch  

Pull request in Git  
A pull request is an event in Git where a contributor asks a maintainer of a Git repository to review code they want to merge into a project.

haha
