# Week 1

## Git
implementation Git 
1. mkdir <name directory>
2. git init
3. git checkout -b <name branch>
4. git add .
5. git commit -m <message>
6. git remote add origin <repository>
7. git push --set-upstream origin <branch>

## NPM

1. npm init
2. do a commit add package.json
3. install lite-server lite-server -D
    3.1 --save-dev is used to save the package for develoment purpose. Example: unit test, minification
    3.2 --save is used to save the package required for the application to run
    -D = --save-dev
    -S = --save
4. Inside package.json 
    "scripts": {
    "dev": "lite-server"
  }
5. add new file .gitignore
6. /node_modules