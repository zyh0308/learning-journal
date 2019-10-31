# Revisions and the Cloud#

#### What is Vision Control#### 

- "Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified."

- Local Version Control : programmers created Local Version Control systems. A Local VCS entails one database on your hard disk that stores changes to files.

- Centralized Version Control : This streamlined the collaboration process (by eliminating the need to involve all local databases), allowed programmers to have more knowledge of team members’ activities with certain files, and gave administrators much more control over divvying up revision privileges.

- Distributed Version Control : A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure. A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure. So that programmers working in teams can collaborate with each other in various ways to complete a joint project. 


#### What is Git####

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

* Git mostly relies on local operations because most necessary information can be found in local resources. 

* Every single change applied to any file or directory is tracked by Git.

* Files in Git can reside in three main states: committed, modified and staged.

* The local Git repository has three components:

  1. Working Directory: The actual files reside here.
  2. Index: The area used for staging
  3. Head: Points to the most recent commit





