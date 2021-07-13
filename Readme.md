## New Project

# Javascript

1. Copy all files and folders except package.json and package-lock.json in root of your project repository.
2. Install prettier as a dev dependency by running: npm i prettier -D
3. Install Eslint related dev dependencies since you are writing your code in Javascript

# Typescript

1. Copy files except package.json and package-lock.json in your project repository.
2. Install prettier as a dev dependency by running: npm i prettier -D
3. Install Tslint related dev dependencies since you are writing your code in Typescript

## Issues

If any issues happen while using the rules set forth by this repository, please raise issues in github clearly mentioning what issues are happening and how to recreate them.

## Existing Project

If you want to use it on existing project, you can copy all the files as mentioned above but have to apply prettier on the complete project via command line.

```shell
./node_modules/.bin/prettier --write "**/*.js"
./node_modules/.bin/prettier --write "**/*.css"
./node_modules/.bin/prettier --write "**/*.scss"
```
