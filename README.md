# Practice forking an assignment repository and editing its files

## A few terms of art
A **repository**, often abbreviated to **repo**, is just a fancy way of saying _folder_. It's a bunch of files. It can have subfolders inside it. You're looking at a repository right now! (See the files up above this text?)

This text is, itself, coming from a single file inside the repository, with the special name of **README.md**. Anything appearing in the README will show up here.

To **fork** a repo is to _make a copy_ of it: all the files, and – interestingly – the complete \*history\* of those files. This lets you safely play with and edit the files, without worrying that you'll overwrite someone else's work. For today, I've asked you to work in teams; for the major projects coming up, you'll each have an individual set of files.

## Your task: use the "five principles" as a lens
For this particular assignment, I'm asking you to work in groups to apply the ideas from [Sorapure's "Playing Lev Manovich"](http://kairos.technorhetoric.net/8.2/binder2.html?coverweb/sorapure/index.htm). What do the "five principles of new media" help you see?

### I. Make a copy you can edit
1. To start, the team anchor should **Fork this repository,** using the button at the top right. ![location of fork button in github](github-fork-button.png)
2. Once you have your own copy, go into your Settings...  ![location of settings button in github](github-settings.png)
3. ... and **add your groupmates as collaborators**. (You'll need to ask for their usernames or email addresses.)![add collaborators, not teams](github-add-collaborators.png)
4. Everyone else will need to check their email and accept the invitation.

### II. Do the work
1. **Create a new file**, named for one of the five principles in Sorapure: numerical-representation.md, modularity.md, automation.md, variability.md, or transcoding.md
   - Five groups, so each group will start with a different file.
   - Note that filenaming convention: all lowercase, no spaces.
   - The .md file extension lets you use ["markdown" syntax](https://guides.github.com/features/mastering-markdown/), like using asterisks to mark list items.
2. In that file, you're going to **make a list** of examples of where you've seen that principle in action.
   - What does this principle help you notice in conjunction with [Wesch's "Information R/evolution"](http://www.youtube.com/watch?v=-4CV05HyAbM) video, for example?
   - What other examples from your digital day-to-day come to mind as you think about this principle?
   - **As your first commit, put in about ten blank lines.** This should allow each member of the group to later edit simultaneously, without conflicting with each other when you merge.
3. **Take turns** adding to the file, saving as you go, so that **everyone in the group gets to make at least one commit.**
   - Use meaningful commit messages: rather than accept the default of "update modularity.md" (which tells us nothing about _how_ you've updated it), write something like "add example from news websites."
   - If you're patient enough to go one at a time, you can commit straight to the main branch without deleting each other's contributions. But to edit at the same time and _merge_ the edits, practice using _pull requests_ instead. This ensures you're always adding to the most recent version, even if it's changed since you started your edit.
   - Pull requests take more clicks, but they're worth it when working with collaborators! ![series of screenshots demonstrating the steps of a commit as branch + pull request](github-pull-request-sequence-with-arrows.png)
4. Did you know that when you fork, you can also file a pull request back to the original repository? 
   - From the home screen of the repo, click on "New pull request"... 
   - Verify that the arrow is pointing from your repo (the "head") back to the original (the "base")...
   - and click to start the merge and review process, as above!
   
EXT: All done with the main activity? Consider further: Manovich was talking about "new media," not "digital media." Is there a difference? If time allows, **make some notes.**

EXT: If you finish working on all that and are still waiting for other groups, go back to step II.1 and move on to the next "principle."
