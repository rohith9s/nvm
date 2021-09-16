# Node Version Manager:


Run multiple versions of NodeJs with NVM(Node Version Manager)  for Windows:

Being a full stack web developer, I use NodeJs often as part of my own projects & also professionally where I was worked. Developers working in frontend applications usaully uses NPM as part of there application development. A Node.js is comming with many versions of it released & new versions will be released in future. Applications build on one node version will not be guaranteed to work for another version of Node.js. For this reason, we not only need a way to install mutiple nodejs but also switching between Node.js versions.

NVM is available for Linux, macOS, and Windows.

Usage of Node.js
----------------

Once NVM is installed & ready to use, you can easily switch between Node.js for your current user, by running below commands:


# install multiple node version

```
	> nvm install 10.13.0
	> nvm install 11.2.0
```

# choose current node version

```
	> nvm use 10.13.0
```

## switching at project level:

```
	> cd projectName
	> echo '8.12.0' > .nvmrc
	> nvm use
```
