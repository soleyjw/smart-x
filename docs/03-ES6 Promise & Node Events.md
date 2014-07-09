# ES5 Promise & Node events

## ES5 Promise

smart-x 提供 ECMAScript 6 标准的 [Promise](https://github.com/jakearchibald/es6-promise) 机制

标准风格：

```js
var promise = new cc.Promise(function(resolve, reject){
	...
});

promise.then(function(res){
  ...
}).catch(function(err){
  ...
});
```

when.js 风格的 api：

```js
function p(){
     var deferred = cc.Defer.create();

    dosth async...
    deferred.resolve();
}
p().then(function(res){
    ....
});
```

