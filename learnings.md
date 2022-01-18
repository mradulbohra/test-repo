/**Few of the major Git commands I learnt**/



/**this adds the file to staging area**/
git add fileName.txt / git add *.txt

/**this commits the file**/
git commit -m "Message"

/**it tells about the status of files in staging area**/
git status

/**it creates a new branch**/
git checkout -b new-branch

/**it checkouts another branch**/
git checkout another-branch , //one can also use switch command

/**it resets the locally committed branch a commit backward**/
git reset HEAD~1

/**it reverts the commit remotely by creating a new revert commits**/
git revert HEAD
