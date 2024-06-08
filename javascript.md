# promises

### three state of promises

* Pending : 
* Fulfilled :
* Rejected :

![promise Diagram](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/promises.png)

#### NOTE : 
- promise is object

**creating the promises :**

```
const promiseOne = new Promise(function(resolve,reject){
    // do an async task
    //DB calls, cryptography ,networks call
    setTimeout(function(){
        console.log('Async task completed..')
        resolve()
    },1000)

});


promiseOne.then(function(){
    console.log("promise consumed...);
})

```