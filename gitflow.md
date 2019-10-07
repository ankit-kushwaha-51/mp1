## GitFlow

* Gitflow is a way to collaborate using parallel development. 
* There are 5 main types of branches

![branches](/images/branches.png)

1. **Master**: The Master branch is for production releases. The commits to Master branch are only merges from Release branch and Hotfix branch.
1. **Hotfix**: The Hotfix branch is where emergency fixes to the code can be done.
1. **Release**:The Release branch is where after the development is done, the code can be created of the Develop branch. In the Release branch, testing, fixing, and retesting can occur until the team is satisfied to release the code to customers. 
1. **Develop**: The Develop branch is where Feature branches are branched off and merged back into when the Features are ready for release. 
1. **Feature**: There can be multiple Feature branches, as needed for each Feature. The Feature branches are merged back into Develop when the team is done with their initial development (before testing takes place in the Release branch).

* The Gitflow workflow allows the team to collaborate in an orderly fashion.
