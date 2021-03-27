# Github   

## Instalation   
- `sudo apt-get install git`   

## Setup   
- Before commiting some files for the first time run the following commands to set your identity:   
  - `git config --global user.name "Name Here"`   
  - `git config --global user.email "my@email.tldr"`   
- Note:  
  - The provided email address will be publicly visible, alternatively you can use: `github-username-here@users.noreply.github.com`   

## Init a repository   
### Locally   
- `git init`   
- Later if you want to push the changes to a remote repository run:   
  -  Commit some changes here
  - `git remote add origin URI_HERE`
  - `git branch -M main`   
  - `git push origin main`   

### OR Clone a remote repository   
- using HTTPS: `git clone https://github.com/username/example.git`   
- using SSH:   `git clone git@github.com:username/example.git`   

## Usage    
- `echo "hi" >> hello.txt`   
- `git add hello.txt`   
- `git commit -m "Commit message here" `   
- `git push -u origin master`   

## Other commands
- `git status`   
- `git log`   
- ``   
