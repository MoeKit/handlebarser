# little demo
---


````javascript
seajs.use('index',function(Handlebars){
    window.console && console.log(Handlebars.compile('{{hello}}')({hello:'world'}));
});
````