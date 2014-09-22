# node-pressure-test

a simple nodejs pressure test app

## how to use

1. get it ready

```Batchfile
git clone git@github.com:zxdong262/node-pressure-test.git
cd node-pressure-test
cp options-sample.js options.js
sudo npm install
```

2. edit options.js

```javascript
module.exports = {

    // edit this section
    // for more options, 
    // visit https://www.npmjs.org/package/request#request-options-callback-

    options: {
        url: 'http://www.baidu.com'
        ,timeout: 600000
    }

    //concurrent request number
    ,concurrent: 150
    
}
```

3. run it

```Batchfile
node app
```

## license

mit