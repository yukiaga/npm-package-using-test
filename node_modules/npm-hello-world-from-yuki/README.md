## npm tutorial

- ```mkdir npm-helloworld```
- ```cd npm-helloworld/```
- ```npm init```
```
{
  "name": "npm-helloworld",
  "version": "1.0.0",
  "description": "This is hello world!",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "Yuki Agatsuma",
  "license": "ISC",
  "repository": {
    "type": "git",
    "url": "git+ssh://git@github.com/yukiaga/npm-hello-world.git"
  },
  "keywords": [
    "npm",
    "npm-hello-world"
  ],
  "bugs": {
    "url": "https://github.com/yukiaga/npm-hello-world/issues"
  },
  "homepage": "https://github.com/yukiaga/npm-hello-world#readme"
}
```
- ```git init```
- ```touch README.md```
- ```git add README.md```
- ```git commit -m "first commit"```
- ```git branch -M main```
- ```git remote add origin git@github.com:yukiaga/npm-hello-world.git```
- ```git push -u origin main```
- ```npm adduser```
- ```npm login```
- ```npm whoami```
- ```npm version```
- ```npm publish```