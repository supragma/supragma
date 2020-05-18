# Installation for OSX Development
TODO(raj): Containerize the project
- Install gcc on your Mac via running ```gcc``` on the terminal
- This will prompt you to install XCode
- Install XCode
- Verify gcc was installed by running ```gcc```
- Install git (search for it online)
- Run ```git clone https://github.com/supragma/supragma.git```
- Run inserting your username and email (instead of Raj's):
```
  git config --global user.name "Navraj Chohan"
  git config --global user.email nlake44@gmail.com
```
See for more information: https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration
- Set up an ssh key with github (search for it online)
- Change your git to use ssh using the following command:
``` git remote set-url origin git@github.com:supragma/supragma.git ```

You're done.

# Main git commands
You can run ```man git``` to learn about git.
Some commands you should know by heart:
- git clone
- git diff
- git checkout
- git push
- git stash
- git status
See official documentation here: https://git-scm.com/book/en/v2/
