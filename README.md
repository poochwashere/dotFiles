# dotFiles

### Notes for setting up a new dev mac env

* Update XCode 

* Install:
    * homebrew
    * git
    * vscode
    * htop
    * jq
    * iterm2
    * zshell
    * oh my zsh
    * miniconda3
    * kubernetes-cli
    * kube-ps1
    * express vpn
    * azure cli  
<br>
* Configs
    * pure theme
    * tomorrow night
    * enable `locate`
<br>
<br>
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

