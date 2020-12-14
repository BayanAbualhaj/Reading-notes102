Many years ago, programmers created Local Version Control systems. A Local VCS entails one database on your hard disk that stores changes to files.

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project  Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of itand Git mostly relies on local operations because most necessary information can be found in local resources.

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.