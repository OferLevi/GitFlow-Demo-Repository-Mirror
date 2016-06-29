# GitFlow Demo Project - By Ofer

This is an example of a readme file in Markdown (file extension is md).

I can use it to enter details on the project i'm working on. 
Notice that I can make the font **bold**, *italic* or even _**bold and italic**_ with simple additions to the text.

## Purpose of this repository

To show an example of how the CoSign repository is expected to look like if we use the GitFlow Workflow Properly

## Steps taken to create this repository History

### Preparing first release to QA
1. Creating **Develop** Branch
2. Branching from it to work on **Feature1**
3. Making a Pull Request and merging it back to **Develop**
4. Adding 2 more features in the same way, simultaneously (**Feature2** and **Feature3**).


### All features for the first version are ready for the QA
5. Branch out to version **1.0.0.1**


### QA found a bug that need to be fixed
6. Fixing an issue in branch **1.0.0.1** (making a pull request on that branch to simulate bug comming from QA).


### QA finished testing the release. Ready for production.
7. Merging **1.0.0.1** to the **develop** branch
8. Merging **1.0.0.1** to the **master** branch and adding a tag to mark it as a released version


### Working on the next release
9. Add a new feature by branching it from the **develop** branch (called **Feature4**).
10. Making a Pull Request and merging it back to **Develop**
11. Making another feature (called **Feature5**) and adding it to the **Develop** branch.


### All features for the second version are ready for the QA
12. Branch out to version **2.0.0.1**


### QA finished testing the release. Ready for production.
13. Merging **2.0.0.1** to the **develop** branch
14. Merging **2.0.0.1** to the **master** branch and adding a tag to mark it as a released version


### Client that uses the first version has encountered a problem and can't upgrade to the latest version.
15. A hotfix is required for a client that is working on the old version (1.0.0.1)
16. Create a Support branch (**Support/1.0.0.1.X**)
17. Branch from it to a branch called HotFix/1.0.0.1.1.
18. Implement the fix and merge it to the support branch (**Support/1.0.0.1.X).
19. Tag this branch with the new version (1.0.0.1.2). Fron now on we can build this version instead of the version tagged originally.
    This branch will remain along side the other branches.
    
### Last step - Creating this readme and adding it directly to Master
