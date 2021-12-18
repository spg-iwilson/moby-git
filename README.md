# GitKraken How to Commit Example Repo
## Featuring Moby Dick

### Hi there and congrats on progressing with your exploration of Git and GitKraken 👋

**How to use this repository:**

(Just making a change to determine how checkouts work between remote and local. This should change the remote commit id, but not the local reference to origin\main on my local computer)

This repository contains multiple branches, each with a unique README with directions on how to perform a specific Git command with GitKraken and the CLI. 

If you are new to Git, here is an important note: each branch in this practice repo will contain unique text focused on the related Git concept. The text will change depending on which branch you have checked out.    

See the 'Next Steps' section later in this document for specific directions on changing branches.

**Contents:**

1. `main`(this branch) - Provides an example of cloning from GitHub using GitKraken and Git CLI. 
2. `git-commit` - Directions for making a [Git commit][3].
3. `git-revert` - Directions for making a [Git revert][4]. 

---

## Git Clone: 

You can follow along with the [video and guide for "What is Git Clone?" on GitKraken.com][1].


#### Set up:

If you have not already done so, you will also need to [download GitKraken.][2]

[<img src="img/gitkraken-keif-teal-sq.png" alt='GitKraken download logo' width="100" />][2]


## Git Clone with Visual Studio Code

1. From your GitHub Repository, click the Code button and copy the HTTPS URL.
2.  
3. Open Visual Studio Code.

4. Switch to the Source Control view (Ctrl+shift+G)

5. Click Clone Repository

6. Paste the URL from the first step and hit enter
   
7. Browse to the folder where you want the project set up (e.g. c:\users\myUserName\source) and select "Set Repository Location"

The code files will be downloaded locally and opened in Visual Studio Code.


**Congratulations!**  

You have successfully cloned a repository 🎉


*Now, let's try it with the CLI...*


## Git Commit a file with the Git CLI

1. Find and open the file `full-text-moby-dick.txt` with your favorite text editor.

2. Edit the file as much as you like and save your changes. 

3. Open your terminal or git-bash and navigate to the locally cloned repository containing `full-text-moby-dick.txt`.

4. Type `git status` and hit enter to show the current state of the git repository. It should show that the file you have saved is `modified` under the 'Changes not staged for commit' part of the message.

5. Type `git add full-text-moby-dick.txt` and hit enter to stage the file. By default, there is no feedback from Git if this command is successful. You can add the 'verbose' flag to the command to get a little more insight by running `git add full-text-moby-dick.txt -v` to get additional details.

6. Again type `git status` and hit enter. You will now see the file listed under the 'Changes to be committed' part of the message.

7. You are now ready to commit your changes and enter your commit message. To do this as a single step, type `git commit -m 'YOUR COMMIT MESSAGE GOES HERE'` and hit enter. 

Note: If you run only `git commit`, Git will open the commit message to be edited by the default text editor in your terminal. This is typically a program called `vim`. While this a powerful editor, it is tricky to navigate for new users. If you find yourself in this unfamiliar editor, type `i` to go into 'insert mode', which will allow you to navigate and type as you like. Then hit the `esc` key and type `:wq` to tell the editor to write (save) your changes and quit the application. You can read more about `vim` at [https://www.vim.org/](https://www.vim.org/).


**Congratulations!** 

You have successfully committed a file with the Git CLI. 👏


## Next Steps

You are reading this on the `main` branch of this repository. 

Keep going! To practice making commits you can switch to the `git-commit` branch. 

To switch branches on GitHub, click the `branches` option towards the top left of the code view and select the branch you want to navigate to. 

To checkout the branch locally and pull from the online branch in the command line type `git checkout -b git-commit origin/git-commit`.

To checkout the branch locally using GitKraken, simply click on the `git-commit` branch in the Remote menu on the left hand side. 


### Working with remotes in GitKraken

You are now set up to work locally and push your changes to GitHub, or work on GitHub and pull those changes locally. 
You are reading this on the `git-commit` branch of this repository. 

To continue on to practice reverting commits you can switch to the `git-revert` branch. 

To switch branches on GitHub, click the `branches` option towards the top left of the code view and select the branch you want to navigate to. 

To checkout the branch locally and pull from the online branch in the command line type `git checkout -b git-revert origin/git-revert`.

To checkout the branch locally using GitKraken, simply click on the `git revert` branch in the Remote menu on the right hand side. 


When using GitKraken, you will see the "Remotes" pane on the left will populate with the name of Remote and its branches. Now you can make your changes and [push them up to your remote](https://gitkraken.com/learn/git/problems/pull-remote-git-branch) so team members can access your updates.

[2]: https://www.gitkraken.com/download?utm_source=learn%20git%20practice%20repo&utm_medium=README%20gk%20download%20link&utm_campaign=git%20commit%20practice%20repo

[3]: https://support.gitkraken.com/start-here/preferences/#external-editor

[4]: https://www.gitkraken.com/learn/git/tutorials/what-is-git-clone?utm_source=learn%20gi[…]20tutorial%20link&utm_campaign=git%20commit%20practice%20repo

[5]: https://www.gitkraken.com/learn/git/problems/revert-git-commit?utm_source=learn%20git%20practice%20repo&utm_medium=README%20revert%20git%20commit%20link&utm_campaign=revert%20git%20commit%20practice%20repo


#### *Moby-Dick, or, The Whale* 
##### by Herman Melville. 

It's a book about a giant whale...and so much more.  

The text in this project is written entirely in [Markdown](http://daringfireball.net/projects/markdown/) ([Github flavor](https://help.github.com/articles/github-flavored-markdown)). 

Plain-text source file is `full-text-moby-dick.txt`. Chapters converted to Markdown are in the `/chapters/` directory. 

Based on the [Project Gutenberg](http://www.gutenberg.org/ebooks/2701) [Plain Text UTF-8 file](http://www.gutenberg.org/cache/epub/2701/pg2701.txt).



-----

[1]: https://www.gitkraken.com/learn/git/tutorials/what-is-git-clone?utm_source=learn%20gi[…]20tutorial%20link&utm_campaign=git%20clone%20practice%20repo

[2]: https://www.gitkraken.com/download?utm_source=learn%20git%20practice%20repo&utm_medium=README%20gk%20download%20link&utm_campaign=git%20clone%20practice%20repo

[3]: https://www.gitkraken.com/learn/git/tutorials/how-to-git-commit?utm_source=learn%20gi%5B%E2%80%A6%5D20tutorial%20link&utm_campaign=git%20commit%20practice%20repo

[4]: https://www.gitkraken.com/learn/git/problems/revert-git-commit?utm_source=learn%20git%20practice%20repo&utm_medium=README%20revert%20git%20commit%20link&utm_campaign=revert%20git%20commit%20practice%20repo
