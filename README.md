# dotFiles

### Notes for setting up a new dev mac env

* Update XCode 

* Install:
    * homebrew
    * Docker for Desktop
    * git
    * vscode
    * htop
    * jq
    * yq
    * iterm2
    * zshell
    * oh my zsh
    * miniconda3
    * express vpn
    * azure-cli  
    * helm
    * ripgrep
    * quicklook plugins

          brew install qlcolorcode qlstephen qlmarkdown quicklook-json qlimagesize suspicious-package apparency quicklookase qlvideo

    * Install `kubectl` to match server version 
        -  `sudo az aks install-cli --client-version 1.28.5`
    * krew
    * kubectx
    * kubens 
    * kube-ps1
    * fzf
    * poetry
    * pure
    * pyenv
    * telnet
    * tree 
    * stern
    * wget


* Configs
    * pure theme
    * tomorrow night
    * enable `locate`

* Workspace
  * Generate new ssh keypair
  * Add public key to Github 
  * Add private key into keychain and update ssh `config` file
  `ssh-add -K ~/.ssh` 
   ```
   Host *
    UseKeychain yes
    AddKeysToAgent yes
    IdentityFile ~/.ssh/id_rsa
   ```

