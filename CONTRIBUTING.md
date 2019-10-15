## How to contribute to openfloodai.github.io?

### Fork the repository
Click on the Fork button at the top of the Github page in https://github.com/OpenFloodAI/openfloodai.github.io

This creates a copy(fork) of the repository in your Github account.

### Clone the repository
To make your own local copy of the repository you would like to contribute to, type in the terminal:

```
git clone https://github.com/<your-username>/openfloodai.github.io.git
```

where you replace <your-username> by your Github username. You can find this link on clicking the green "Clone or download" button in your repo (in your account).


### Create a New Branch
```
cd openfloodai.github.io
git branch <newbranch>
git checkout <newbranch>
```
Where you can replace <newbranch> by the name of the branch you'd like to create.
This checks you out to the new branch.

### Make your changes
Fix the issues or contribute as you would like to, by making appropriate changes.
Once you have made your changes, commit them as:
```
git add .
git commit -m "<a suitable message for the commit>"
```


## Push your changes to your repo
```
git push --set-upstream origin new-branch
```


## Create pull request
Once you have pushed your branch, navigate to the forked repository on your GitHub webpage and toggle to the branch you just pushed to see the changes you have made in-browser.

At this point, it is possible to make a pull request to the original repository. Click on the Pull Request button which shows up at the top of your repo. Make sure your branch is mergeable.

# How to Contribute to this Project

You can contribute to this project for:
1. Resolving issues
2. Feature suggestion


## Working on Issues ##

- If you want to contribute by working on resolving issues, please state the same as a comment for the Issue.
- Wait for repo maintainers to assign that issue to you.
- Do not start working on the issue unless the issue is assigned to you.
- PRs for the issue will only be accepted by the contributors who were assigned to it. This prevents other contributors from hijacking others' issues.

<hr/>

## Basics ##
1. Create an account on GitHub

2. Fork this repository to your own GitHub by clicking on the 'Fork' button (on the right)

3. Now you have your own remote copy of the project! Clone this remote repository to your machine so you'll have a local copy:

   'https://github.com/<Your_User_Name>/openfloodai.github.io'

4. Open up the code in a code editor (e.g Atom, Visual Studio Code, Sublime Text, Notepad... ;-> ). Resolve issue -> Add your meaningful
   contribution!

5. Commit your changes from the root directory of the project (openfloodai.github.io):
   `git add .`
   `git commit -m "[Write a message that briefly explains the change you've made]"`

6. Push your changes from the local repository on your machine to the forked remote repository on your GitHub:
   `git push`

7. Make a pull request to ask for your changes to be integrated (merged) into the original openfloodai.github.io that you forked
   from OpenFloodA back in step 2. On your GitHub, click the 'Pull Request' button and ensure that the base fork is 'base
   fork: OpenFloodAI/openfloodai.github.io' and the head fork is '[your GitHub name]/openfloodai.github.io'.

8. I will review your contribution and merge it into the original master branch!


<hr/>
=======
# List of contributors:
 

## More Help

- How to make a pull request on GitHub: https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github
- GitHub git flow: https://guides.github.com/introduction/flow/
- Git cheat sheet: https://www.git-tower.com/blog/git-cheat-sheet/

# Happy coding!
