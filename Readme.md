# New Project

## Javascript

1. Copy all files and folders except package.json, package-lock.json, tsconfig.json, and tslint.json in root of your project repository.
2. Install prettier and eslint related dev dependencies by running:

```shell
npm i prettier -D
npm i eslint -D
npm i eslint-config-prettier -D
npm i eslint-config-standard -D
```

## Typescript

1. Copy files except package.json, package-lock.json, and .eslintrc.json in root of your project repository.
2. Install prettier and tslint related dev dependencies by running:

```shell
npm i prettier -D
npm i tslint -D
npm i tslint-config-prettier -D
npm i tslint-config-semistandard -D
```

## Issues

If any issues happen while using the rules set forth by this repository, please raise issues in github clearly mentioning what issues are happening and how to recreate them.

# Existing Project

If you want to use it on existing project, you can copy all the files as mentioned above but have to apply prettier on the complete project via command line.

```shell
./node_modules/.bin/prettier --write "**/*.js"
./node_modules/.bin/prettier --write "**/*.css"
./node_modules/.bin/prettier --write "**/*.scss"
```
