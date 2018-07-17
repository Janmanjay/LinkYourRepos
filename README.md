# LinkYourRepos
An exercise to link repos (Link Your Repos):
Perhaps you've already created some files on your local machine and you want to make a Github.com repository for them. What would you do?

* 1 Create a folder on your desktop with the sample files you want to save.
* In your terminal, navigate to that folder and type git init.
* Next, go to Github.com and create a repo for your files.
* Click on the green "clone/download" button and copy the hyperlink.
* Back in your terminal, type git remote add origin and paste the hyperlink.
* Type git status which should show you a message saying that your local and remote repos are not currently synchronized! Do you know what to do next? Note that when you add a remote to an existing local repo, when you want to push or pull, you'll need to explicitly specify the location (e.g., git push origin master).

Now let's try this
