# New Project

1. Copy all files and folders except package.json, package-lock.json in root of your project repository.
2. Install prettier and eslint related dev dependencies by running:

```shell
npm i prettier -D
npm i eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin -D
npm i eslint-config-prettier -D

```

3. Configure TSConfig and Eslintrc as per your project.

## Issues

If any issues happen while using the rules set forth by this repository, please raise issues in github clearly mentioning what issues are happening and how to recreate them.

# Existing Project

If you want to use it on existing project, you can copy all the files as mentioned above but have to apply prettier on the complete project via command line.

```shell
./node_modules/.bin/prettier --write "**/*.js"
./node_modules/.bin/prettier --write "**/*.css"
./node_modules/.bin/prettier --write "**/*.scss"
```
