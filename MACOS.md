# MacOs Configuration

## Settings

1. Finder

-   [ ] Remove unecessary folders and rearrange them
-   [ ] Change in View --> as List --> Increase size
-   [ ] Add folder of device owner and create folder Dev (this will contain all Development-driven files)
-   [ ] Keep all files in "Documents folder"
-   [ ] Set as default fodler in finder device owner space

2. Desktop

-   [ ] Move folders to the Finder "Documents" or "Dev"
-   [ ] Remove all folders from desktop

3. HomeBrew

-   [ ] Paste curl from Brew website [Brew](https://brew.sh/)
-   [ ] Don't forget to install plugin in Raycast to instal from there later

4. Raycast (App launcher, replacement for Spotligth)

-   [ ] a. Paste in Terminal command `brew install --cask raycast`, b. Get from [website](https://www.raycast.com/)
-   [ ] `Command + comma ","` to open settings --> `Extensions` --> `Add` --> `Install from store` --> Brew plugin

5. Browser

-   [ ] Chrome
-   [ ] Firefox dev + no-dev

6. Docker

-   [ ] install via brew --> `brew install --cask docker`

## List of remaining apps to install via brew

```
discord
notion
virtual-studio-code
hidden-bar
figma
rectangle
todoist
tg-pro
iterm2
```

-   [ ] Create file with `nano app_list.txt` and paste above list (IF SOME OF THEM WON'T BE INSTALLED DO IT SINGULARLY WITH --cask flag to install as desktop app)
-   [ ] Use command --> `xargs brew install < app_list.txt (this will install all listed apps)

7. Iterm2 will be installed after above actions

-   [ ] Use this [Tutorial](https://dev.to/immayurpanchal/unlocking-the-ultimate-productivity-mastering-iterm2-oh-my-zsh-powerlevel10k-fig-and-homebrew-1dih)
-   [ ] Adjust theme for your need (Profiles and Windows)
-   [ ] For text-editor like behavior go to the settings `Command + comma` --> `Profiles` --> `Keys` --> `Keys mapping` --> Natural text edditing

8. Setup SSH onto local machine

-   [ ] Follow this guide to setup an ssh key for github
-   [ ] Follow this guide to add the ssh key to your github account

9. NodeJS + NVM

-   [ ] Install [NodeJS + NVM](https://nodejs.org/en/download/package-manager)
