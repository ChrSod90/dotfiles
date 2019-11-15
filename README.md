Personal config. If you got suggestions I'll gladly take 'em.
# dotfiles
```
 git        > git config
 zsh        > oh-my-zsh plugins and themes
 emacs      > emacs configs/packages (TODO: improve package-management)
 
 ```
# Usage
Use [stow](https://www.gnu.org/software/stow/) to manage my dotfiles
```
git clone https://github.com/chrsod90/dotfiles.git ~/dotfiles
cd ~/dotfiles
stow zsh # ...and whatever else you want
```
## Todo
* Create a better stow for emacs
* Create stow for desktop environment (wallpapers, keyboard shortcut)
* Create stow for webadmin stuff
  * Try [Sublime-Jekyll](https://github.com/23maverick23/sublime-jekyll)
* Custom Todo script
  * show in MOTD
  * Sync with google/business calender (might be too much of a hassle)
* Create setup.sh
  * Install packages if needed
  * Save existing dotfiles (not found in previous git history?) to backup
  * Option for verbosity/user-input
  * Write to log
* Move aliases to separate file(s)
