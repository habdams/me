### fixup! Old commit message
- to make it easier to squash commits that belong together. E.g you made a typo, discovered a bug while still working on the story, ...
### wip: Commit message
- only if you are committing something that does not work by itself, i.e. it throws errors, warnings, is incomplete, requires feedback, ... I like to use this for my last commit on top of things that I might still split up into more logical units.
- Follow the commit message guide I sent you (example message: Fix onChange handler in <Button />)
- Only commit working states
- Split up into chunks: Did you just develop a component that consists of 3 other components that might be used elsewhere? Split it up into different commits! Check out any of my branches -- there's a bunch of commits going on.
- If you have a bigger story and a chunk that is already working and is not only relevant to the story you're working on -- open a PR just for that chunk. Keeping your PRs small makes it easier to review. For the JSON import right now, you could already open a PR for the drag & drop component if that's done and collect feedback already.
- Always, always rebase. Try to rebase daily. And not merge, but rebase. Your commits will be put on top of the master branch, which keeps the Git history flat and prevents future merge conflicts. For this to not become a pain it is important to really do it regularly so your branch isn't 100s of commits behind with no easy way to know which change is up-to-date.
- Right now, the Git history on your branch is pretty cluttered and everything has a wip:. You'll need to heavily update this so it's ready for the PR. If I have a messed up Git history, I like to rename the branch and create a fresh branch. Then, I cherry-pick commits and chunk and squash them into logical commits so the history becomes easier to follow.
- The Git history should not track your development progress 1:1. Your PR could consist of 4-5 commits.