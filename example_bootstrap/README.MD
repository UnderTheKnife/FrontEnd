## Example bootstrap

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
Http-server install:
```
     npm install http-server -g
```
### Launching
You must install packages from `package.json`. \
Run on project folder:
```
    npm install
```
Then you must start the local server:
```
    http-server
```
Now you can visit http://localhost:8080 to view your server

