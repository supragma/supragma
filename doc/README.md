# Installation for OSX Development
TODO(raj): Write a script to do all this

- Check if gcc is installed on your Mac via running ```gcc``` on the terminal
- If it is not then this will prompt you to install XCode
- Install XCode
- Verify gcc was installed by running ```gcc```
- Install git (search for it online)
- Run ```git clone https://github.com/supragma/supragma.git```
- Run inserting your username and email (instead of Raj's):
```
  git config --global user.name "Navraj Chohan"
  git config --global user.email nlake44@gmail.com
```
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
