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

## Bootstrap

1. npm i bootstrap -S
2. add in Index.html 
``
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
  </head>
  <body>
    <h1>Hello, world!</h1>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2" crossorigin="anonymous"></script>
  </body>
</html>
``