## Tutorial 1: Proofread the Getting Started topic 

1. Open a terminal.
2. Navigate to your __Home__ folder (under Users > find folder with your user name).
3. Create a folder in your __Home__ folder. Name the folder as `Github-Step1`
4. Clone the repo into the folder you just created.
    - To clone , run `git clone git@github.com:puchki-chat07/Howdy.git` to clone the repo. 
    - Learn more about the [`git clone` command](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository). More details [on how clone works](https://stackoverflow.com/questions/16427600/how-git-clone-actually-works). More like "behind-the-scene-effect" of the git clone command.
    - You can also copy the above clone command from GitHub. See this [screenshot](https://thoughtspot.atlassian.net/wiki/spaces/TC/pages/323977243/Create+a+repository+clone+on+your+local+machine?preview=/323977243/323878920/image2018-6-4_17-24-24.png).
5. Create a branch. The branch you create is associated to the folder you are in. Git will now track all changes you make to the files/folders stored under `Github-Step1`.
    - To create a new branch (and switch to the branch at the same time), run `git checkout -b <branch_name>`. 
    - Learn more about [git checkout](https://www.atlassian.com/git/tutorials/using-branches/git-checkout) command.
6. Run `git branch` to verify that you are on the branch you just created.
7. Run `git status` to verify that there are no uncommitted changes and your branch is up to date.
8. Run `git push origin <branch_name>` to create a remote copy of your branch on GitHub.

### Edit Content and commit the changes
1. In your terminal run `atom .` to open atom and start proofediting and structuring the content following the Technical Writing best practices. See MSTP for reference. 
2. Run `git add .` to add the changes to your branch.
3. Run `git commit -a` to add a brief details of the changes you made and that are ready to be committed.
4. Run `git push origin <branch_name>`.
5. Go to Github and click __Create a pull request__. [See this screenshot for more instruction](https://thoughtspot.atlassian.net/wiki/spaces/TC/pages/373817352/Create+personal+named+branches+to+separate+work+into+multiple+pull+requests?preview=/373817352/374603777/personal-branch-create-PR.png).
6. Verify both the origin (master) and your branch that you want to merge. This merges your fork to master.
7. Add comment.
8. Click __Merge Pull request__.
9. Click __Confirm Merge__ to apply the changes to the repo.

 
## Tutorial 2: Change the location of the Getting Started topic. 
Once you are done, move the Getting Started to a new folder.
