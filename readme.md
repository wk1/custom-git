These are just some minor shortcuts I use for git to make my life easier.

## Usage

Download the repo and permanently add the commands to your path with (for zsh):

`echo -n '\nexport PATH=$PATH:[Repo Directory]' >> ~/.zshrc`

e.g.

`echo -n '\nexport PATH=$PATH:~/Developer/CustomGit' >> ~/.zshrc`

Afterwards you can use theses commands just like normal git commands like

  `git finish`

  or

  `git publish`

...

## Adding custom commands

Just create a new file `git-commandname` add your desired code to the file and make it executable with `chmod +x git-commandname`
