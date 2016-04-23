# New Machine Setup

Welcome my son, to the machine.

## OS X Applications
* iTerm2 https://www.iterm2.com
* Atom https://atom.io/
* FlyCut http://itunes.apple.com/us/app/flycut-clipboard-manager/id442160987?mt=12
* ShiftIt https://github.com/fikovnik/ShiftIt/releases
* Karabiner https://pqrs.org/osx/karabiner/
* RubyMine https://www.jetbrains.com/ruby/

## SSH Key

Just follow along https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/

Add the public key to Github `cat ~/.ssh/id_rsa.pub | pbcopy`

## CLI Tools

* Homebrew http://brew.sh/
* Oh My Zsh https://github.com/robbyrussell/oh-my-zsh
* tig `brew install tig`
* git `brew install git`
* rbenv https://github.com/rbenv/rbenv#installation

## Configuration

### Oh My Zsh

* Install Powerline fonts https://github.com/powerline/fonts

  ```
  git clone git@github.com:powerline/fonts.git ~/powerline-fonts
  (cd ~/powerline-fonts && ./install.sh)
  ```

### OS X Settings

* Enable three finger drag http://osxdaily.com/2016/01/06/enable-three-finger-drag-gesture-mac-trackpad-os-x/

### Karabiner

Default key-repeat is way too slow on OS X, Karabiner will fix that.

| Delay until repeat | Key Repeat |
| --- | --- |
| 250 | 25 |
