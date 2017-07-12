## Example bootstrap sass

### Installation
Before run this you must install `node.js` and `npm`: \
Node.js 6:
```
    curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
    sudo apt-get install -y nodejs

```
Node.js 8:
```
    curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash - 
    sudo apt-get install -y nodejs
```
### Launching
You must install packages from `package.json`. \
Run on project folder:
```
    npm install
```
For generate `styles.css` file run in project folder:
```
    npm run scss
```
Then you must start the local server:
```
    npm run start
```

### Syntax validate
For check syntax with `sass-lint` run in project folder:
```
    npm run sass-lint
```