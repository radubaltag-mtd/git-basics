git push --force:
  Overwrites the remote branch no mather what.
  If someone else pushed work to the same branch , their commits will be deleted.
git push --force-with-lease:
  It only overwrites the branch if nobody else added new commits since my last pull.
