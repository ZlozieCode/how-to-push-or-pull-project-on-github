# How-to-push-or-pull-project-on-github
# Follow the commands

 

## 1. run --> git init 
### Open git bash inside the project folder then (initialize a git instance in that)

## 2. run --> git branch -M main 
### to switch from master to main branch
## 3. run --> git status
## 4. run --> git commit -m "specify here your commit message"
## 5. run --> git remote remove origin
### In case the error "remote origin already exists
## 6. run --> git remote add origin [link of your repo]
## 7. run --> git push -m -f origin HEAD:master
### run --> git push origin HEAD:master
### run --> git push origin HEAD:main
## 8. run --> git pull origin main


# If nothing works ->
### run --> git init
### run --> git add .
### run --> git commmit -m "something here"
### run --> git remote add origin [link of your repo]
### run --> git push origin HEAD:master
### run --> git push origin HEAD:main


# Adding new file

## run --> echo " " > [File name]
## run --> git add [file name] or git add --all
## run --> git commit -m "something here"
## run --> git push origin HEAD:master
## run --> git pull origin master

# Common error main/master doesn't exist
## run --> git push origin HEAD:master [instead of] git push origin master
## run --> git push origin HEAD:main [instead of] git push origin main










