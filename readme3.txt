5.Merge a file:
To merge branches locally, use git checkoutto switch to the branch you want to merge into. 
This branch is typically the main branch. 
Next, use git mergeand specify the name of the other branch to bring into this branch. 
This example merges the jeff/feature1 branch into the main branch. Note that this is a fast-forward merge.

                 git checkout main
                 git merge jeff/feature1