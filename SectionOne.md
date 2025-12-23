## Learn Git Branching
It is understand  about git commands and practice problems

## Level 1:Introduction to Git Commits
A commit in a git repository records a snapshot of all the (tracked) files in your directory.
<img width="1920" height="966" alt="Screenshot 2025-12-23 072232" src="https://github.com/user-attachments/assets/689108b6-0b83-456b-9dd3-b708e42ba17a" />
The goal shows there are three commits -- the first inital commit -C0,second commit after that C1,third commit after C2, that might have some meaningful changes.
To complete this problem use below command two times.
~~~
$ git commit
~~~
<img width="1920" height="955" alt="Screenshot 2025-12-18 081658" src="https://github.com/user-attachments/assets/47c0c7da-6f4a-4d44-91d1-11c276a44dc1" />

## Level 2:Git Branches
Branches in Git are very lightweight because they are just pointers to specific commits.
Since they don’t use extra storage, developers can create many branches to organize work easily.<br>
For Example:

<img width="215" height="290" align="left" alt="Screenshot 2025-12-23 075056" src="https://github.com/user-attachments/assets/12254a46-9485-4abf-aea9-f2b29ddbb93e" /><br><br><br><br><br><br><br><br><br><br><br><br><br>
There is main branch.If we want to create new branch then use below command.
~~~
$ git branch newImage
~~~
The branch newImage now refers to commit C1.<br>
<img width="215" height="290" align ="left" alt="Screenshot 2025-12-23 075133" src="https://github.com/user-attachments/assets/4667a2b7-d0e1-4e48-90b7-f98673fd1c58" /><br><br><br><br><br><br><br><br><br><br>
Let's tell git we want to checkout the branch with
git checkout <name>
This will put us on the new branch before committing our changes.
~~~
$ git checkout newImage; git commit
~~~
<img width="196" height="300" align="left" alt="Screenshot 2025-12-23 110101" src="https://github.com/user-attachments/assets/72afb014-d59f-4dc3-af56-5c6e0bdb9a3d" /><br><br><br><br><br><br><br><br><br><br><br><br><br>
Lets practice problem on git branching
<img width="1920" height="978" alt="Screenshot 2025-12-23 110622" src="https://github.com/user-attachments/assets/9fd6df74-331d-4d4c-9a61-35d606190981" />
The goal shows the create new branchname is bugfix & checkout the branch for bugfix for solving the problem use below commands.
~~~
$ git branch bugfix
$ git checkout bugfix
~~~
<img width="1920" height="968" alt="Screenshot 2025-12-23 111933" src="https://github.com/user-attachments/assets/908907c5-c315-4597-ac73-a64fdb9f119a" />

## Level 3:Git Merge
Git merge helps us do this by creating a special commit that joins the history of two branches into one.<br>
For Example:<br>
Here we have two branches; each has one commit that's unique.
<img width="403" height="469" align="left" alt="Screenshot 2025-12-23 120926" src="https://github.com/user-attachments/assets/e2c526da-685f-40ea-904a-5f08ef0860ed" /><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
If we want to merge the branch with bugfix then use below command:
~~~
$ git merge bugfix
~~~



