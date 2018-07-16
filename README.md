# WHY YOU NEED GITHUB ACCOUNT
   For many purposes, but if in simple we say "MANAGING TEAM WORK" aor "UPDATING YOUR PROJECT TO AVOID ANY PROBLEM REGARDING FILE CORRUPT" or "GETTING HELP FROM OTHERS (may be you are in team, then you can see what your other members working)"

# FIRST-TIME-ON-GITHUB
   This project is for new ones on github and who are trying to know the 0th level of github (.i.e. how to pull request and make commmit )
so for this contribution you don't need any programming skills, nothing like that ...

  
You are just contributing to this project by adding your name, bio(about yourself in max 10 words), your github username

# STEPS TO FOLLOW
1. Installation of required tools:
* git
* any IDE of your choice (for ex. sublime text and atom)

here we go with 'git'

### Installing git:

- Ubuntu:    `sudo apt-get install git`
- Windows: [Download](https://git-scm.com/download/win)
- Mac: [Download](https://git-scm.com/download/mac)
<img align="right" width="300" src="https://github.com/Stupyspyy/FIRST-TIME-ON-GITHUB/blob/master/img/New%20folder/fork.png" alt="fork this repository" />

##### WHY YOU NEED THIS


kdfkj
ljfsdlj
ljflj

### 1. Fork this repository
Fork this repo by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.




### 2. Clone the repository

<img align="right" width="300" src="https://github.com/Stupyspyy/FIRST-TIME-ON-GITHUB/blob/master/img/New%20folder/clone.png" alt="clone this repository" />

Now clone this repo to your machine. Click on the clone button and then click the *copy to clipboard* icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```
where "url you just copied" (without the quote marks) is the url to this repository. See the previous steps to obtain the url.

<img align="right" width="300" src="https://github.com/Stupyspyy/FIRST-TIME-ON-GITHUB/blob/master/img/New%20folder/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:
```
git clone https://github.com/this-is-you/first-contributions.git
```
where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository in GitHub to your computer.

### 3. Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-contributions
```
Now create a branch using the `git checkout` command:
```
git checkout -b <add-your-name>
```

For example:
```
git checkout -b add-alonzo-church
```
(The name of the branch does not need to have the word *add* in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

### 4. Make necessary changes and commit those changes

Now open `Github_user.md` file in a text editor, add your name to it, and then save the file. If you go to the project directory and execute the command `git status`, you'll see there are changes. Add those changes to the branch you just created using the `git add` command:
```
git add Github_user.md
```

Now commit those changes using the `git commit` command:
```
git commit -m "Add <your-name> to Github_user list"
```
replacing `<your-name>` with your name.

### 5. Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin <add-your-name>
```
replacing `<add-your-name>` with the name of the branch you created earlier.

### 6. Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button.  Click on that button.

<img style="float: right;" src="https://github.com/Stupyspyy/FIRST-TIME-ON-GITHUB/blob/master/img/New%20folder/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://github.com/Stupyspyy/FIRST-TIME-ON-GITHUB/blob/master/img/New%20folder/submit-pull.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.
