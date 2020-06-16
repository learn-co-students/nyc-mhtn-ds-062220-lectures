# Lecture Notes for nyc-mhtn-ds-062220 :floppy_disk:

For any new lecture notes, duplicate the notebook you will be using and rename it to something suitable (e.g ProgrammingFundamentalsI_Notes.ipynb). 


# If you want to store your notes in a personal repository on GitHub

## Fork the repository at https://github.com/learn-co-students/nyc-mhtn-ds-062220-lectures
## Clone down your forked repository
** this step only happens once**

### From your local folder with the forked repository

* If you have set the remote skip to step :two:

1. Add the learn-co lecture notes repo as the remote, **this step only happens once**
```
git remote add upstream https://github.com/learn-co-students/nyc-mhtn-ds-062220-lectures.git
```

2. Check the remote is set and your lecture notes repo is correct.
You should see your forked repo after **origin**, and the learn-co-students repo after **upstream**

```
git remote -v
```

3. Update the changes from the upstream learn-co lecture notes repo
```
git fetch upstream master
```

4. Check that the master branch is selected
```
git branch
```

5. Merge the new changes from the upstream learn-co lecture notes repo, with a commit message
```
git merge upstream/master -m 'what you updated'
```

6. Push the changes to the forked lecture repo :raised_hands:
```
git push
```

# If you only want to save your notes locally

## Clone down this repository.

1. Check if new material is available
```
git status
```

2. If your local files are behind, pull down new changes
```
git pull origin master
```
