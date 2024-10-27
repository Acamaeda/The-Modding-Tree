# Getting started

Welcome to The Modding Tree!

Using the Modding Tree, at its simplest level, just requires getting a copy of it onto your computer. However, if you do it the right way, it will help in many ways.

Don't let the word "Github" scare you away. It's actually much easier to use than most people think, especially because most people use it the hard way. The key is Github Desktop, which lets you do everything you need to, without even touching the command line.

The benefits of using Github:

- It makes it much, much easier to update The Modding Tree.
- You can share your work without any extra effort using githack, or with a bit more effort, set up a github.io site.
- It lets you undo changes to your code, and to have multiple versions of it.
- It lets you collaborate with other people, if you want to.

## Getting set up with Github Desktop, Visual Studio Code, and The Modding Tree:

1. Install [Github Desktop](https://desktop.github.com/) and [Visual Studio Code](https://code.visualstudio.com/).

2. Make a Github account. You can handle this on your own.

3. Log in on your browser, and go back to [The Modding Tree page](https://github.com/Acamaeda/The-Modding-Tree). At the top right, there should be a button that says "fork". Click on it, and then on your username. You now have your own fork, or copy, of The Modding Tree.

4. Open Github Desktop and log in. Ignore everything else and choose "clone a repository". A "repository" is basically a "Github project", like The Modding Tree. "Cloning" is downloading a copy of the repository to your computer.

5. Look for The Modding Tree in the list of repositiories (it should be the only one) and click "clone".

6. Select that you're using it for your own purposes, and click continue. It will download the files and handle everything.

### Using your repository

1. Click on "show in explorer/finder" to the right, and then open the index.html file in the folder. The page should open up on your browser. This will let you view and test your project locally!

2. To edit your project, click "open in VSCode" in Github Desktop.

3. Open [mod.js](/js/mod.js) in VSCode, and look at the top part where it has a "modInfo" object. Fill in your mod's name to whatever you want, and change the id as well. (It can be any string value, and it's used to determine where the savefile is. Make it something that's probably unique, and don't change it again later or else it'll effectively wipe existing saves)

4. Save [mod.js](/js/mod.js), and then reload [index.html](/index.html) in your browser. The title on the tab, as well as on the info page, will now be updated! **You can reload the page every time you change the code to test it quickly and easily.**

5. Go back to Github Desktop. It's time to save your changes into the git system by making a "commit". This basically saves your work and creates a snapshot of what your code looks like at this moment, allowing you to look back at it later.

6. At the bottom right corner, add a summary of your changes, and then click "commit to master".

7. Finally, at the top middle, click "push origin" to push your changes out onto the online repository.

8. You can view your project online, or share it with others, by going to https://raw.githack.com/[YOUR-GITHUB-USERNAME]/The-Modding-Tree/master/index.html. **You do NOT need to do this to test your mod locally.**

And now, you have successfully used Github! You can look at the next tutorial on [making a mod](making-a-mod.md), or look at the [documentation](../!general-info.md) to see how The Modding Tree's system works and to make your mod a reality.
