# WHY YOU NEED GITHUB ACCOUNT
   For many purposes, but if in simple we say "MANAGING TEAM WORK" aor "UPDATING YOUR PROJECT TO AVOID ANY PROBLEM REGARDING FILE CORRUPT" or "GETTING HELP FROM OTHERS (may be you are in team, then you can see what your other members working)"

# FIRST-TIME-ON-GITHUB
   This project is beneficial for new one and who are trying to know the 0th level of github (.i.e. how to pull request and make commmit )  
   
   Using this, you can take help from others through their profile in which mutual interest are same and helping others through HIGHLIGHTING_YOUR_PROFILE so start contributing :-}
   
Newbies don't need to worry because for this contribution you don't need any programming skills...
You are just contributing to this project by adding your name, bio(about yourself in max 10 words), your github username

# STEPS TO FOLLOW
1. Installation of required tools:
* git
* any IDE of your choice (for ex. sublime text and atom)

here we go with 'git'


### Installing git:

<img align="right" width="300" src="https://github.com/Stupyspyy/FIRST-TIME-ON-GITHUB/blob/master/img/New%20folder/fork.png" alt="fork this repository" />


- Ubuntu:    `sudo apt-get install git`
- Windows: [Download](https://git-scm.com/download/win)
- Mac: [Download](https://git-scm.com/download/mac)





### 1. Fork the repository
Fork this repo by clicking on the fork button on the top-right of this page.
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
git checkout -b <add-branch-name>
```

For example:
```
git checkout -b newbranch
```


### 4. Make changes and commit those changes

Now open `Github_user.md` file in a text editor and enter details in the following format  
```
   Name: "Your name here"    
   Bio: "Enter about yourself here"  
   Github: [Github username](github profile url)  
   Other: "Any other platform like facebook,sololearn,your own websites,linked in,etc"
```
   * make sure to give 2 whitespaces after each colon.  
   * make sure to give username in [] and url in () with no spaces in between username and url


If you go to the project directory and execute the command `git status`, you'll see there are changes. Add those changes to the branch you just created using the `git add` command:
```
git add Github_user.md
```
 
Now commit those changes using the `git commit` command and meaningful commit message like "Added to Github_user list":
```
git commit -m "Commit message here"
```
(include double quotes)

For example:
```
git commit -m "Added to Github_user list"
```

### 5. Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin "branch name"
```
replacing `<branch name>` with the name of the branch you created earlier.

For example:
```
git push origin newbranch
```

### 6. Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button.  Click on that button.

<img style="float: right;" src="https://github.com/Stupyspyy/FIRST-TIME-ON-GITHUB/blob/master/img/New%20folder/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://github.com/Stupyspyy/FIRST-TIME-ON-GITHUB/blob/master/img/New%20folder/submit-pull.png" alt="submit pull request" />

Sit back and relax while your pull request is reviewed and merged.
