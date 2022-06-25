● Tell me how to remove them locally and remotely.
  -> to remove locally
      #git branch -d dev

  -> to remove remotely
     #git push origin :dev

● Tell me how to list tags.
  1)Lightweight  -> git tag v1.7
  2)Annotated    -> git tag -a v1.7 -m "version v1.7"

● Tell me how to delete tag locally and remotely.
  ->locally # git tag -d v1.7
  ->remotly #git push origin --delete v1.7
