# first-contribution
a repository where people new to open source can make their first contribution and learn about git and github

## How Do I Make My First Contribution?

Follow this guide to learn how to use git/github and make your first open source contribution!

### Install git
https://git-scm.com/downloads

### Configure git
In terminal (MacOS) or Powershell (Windows), run the following commands, replacing ```first_name``` with your first name, ```last_name``` with your last name, and ```email_address``` with the email address you use for Github.

```git config --global user.name "first_name last_name"```

```git config --global user.email email_address```

### Star and fork this repository
Towards the top right of the screen of the repo, click, "Star" (to help us reach more open source contributors), then click "Fork". Then another page will show up, where you should click "Create Fork". You will now be redirected to your fork of the code.

### Clone the repository
In the repository on Github, click the green <> Code button, then copy the link that shows up

On the terminal (MacOS) or Powershell (Windows) run the git command ```git clone paste_copied_url_here``` (to paste into terminal/powershell, you should right click, then click paste)

### Enter the local repository

In terminal or powershell, run ```cd first-contribution```

### Make changes

In a text editor, open ```contributors.md```

Add the following code to a new line at the bottom of file, replacing ```username``` with your Github username, and save the file

``` - [username](https://github.com/username)```

### Add and commit changes to git

In the terminal/powershell window where you are in the ```first_contributions``` directory, run the following commands, replacing ```username``` with your Github username

```git add contributors.md```

```git commit -m "username - first open source contribution"```

### Push the changes to Github

```git push -u origin main```

If you get an authentication error and are not given the option to authenticate Github in your browser, follow the instructions to add an ssh key to your computer/github for authentication at https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

### Submit changes for review

Now that you have pushed changes to your fork (which is essentially a copy of the first-contribution repository), you must request your changes to be merged into the repository.

If you go to your fork of this repository, click the button that says "compare and pull request", then submit the pull request by clicking "create pull request".

Now, once I review the pull request, your contribution will be merged into the first-contribution repository.
