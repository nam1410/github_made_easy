## create .gitignore in text editor and add extensions of all files that should be ignored
1. example, 
```
*.pkl
*.zip
*.csv
*.xlsx
*.pth
```
(add such extensions in new lines)

## check if there are any submodules in the current or nested directories. go to the directory and type
1. ```rm -rf .git```

## run the following in order in command terminal (change to the directory you want to upload - cd dir_name/)
1. ```git init```
2. ```git add .```
3. ```git commit -m "Initial commit"```

## go to github.com and create a repository in your dashboard and copy its link
<link> should be like ```https://github.com/your_username/your_repository_name.git```

## come back to the command terminal
1. ```git remote add origin <link>```
2. ```git branch -M main```
3. ```git push -u origin main```


## you should see all your files in your github repository 
