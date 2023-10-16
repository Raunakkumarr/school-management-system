
# Contribution Rules📚:

- You are not allowed to make pull requests that break the rules. We just merge it ;)
- Do NOT add any build steps e.g npm install (we want to keep this a simple static site)
- Do NOT remove other content.
- Styling/code can be pretty, ugly or stupid, big or small as long as it works
- Add your name to the contributorsList file
- Try to keep pull requests small to minimize merge conflicts


## Getting Started 🤩🤗:

- Fork this repo (button on top)
- Clone on your local machine

```terminal
git clone https://github.com/Raunakkumarr/school-management-system.git
```
- Navigate to project directory.
```terminal
cd school-management-system
```

- Create a new Branch

```markdown
git checkout -b <your-branch-name>
```
- Add your Name to [`contributors.md`](contributors.md)
```markdown
git add contributors.md
```
- Commit your changes.

```markdown
git commit -m <your-message>
```
- Then push 
```markdown
git push origin -u <your-branch-name>
```


- Create a new pull request from your forked repository -- Add short description about your work and changes.

<br>

## Avoid Conflicts {Syncing your fork}

An easy way to avoid conflicts is to add an 'upstream' for your git repo, as other PR's may be merged while you're working on your branch/fork.   

```terminal
git remote add upstream https://github.com/Raunakkumarr/school-management-system.git
```

You can verify that the new remote has been added by typing
```terminal
git remote -v
```

To pull any new changes from your parent repo simply run
```terminal
git merge upstream/master
```

This will give you any eventual conflicts and allow you to easily solve them in your repo. It's a good idea to use it frequently in between your own commits to make sure that your repo is up to date with its parent.
