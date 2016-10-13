##EmberJS

### Installing Bootstrap Cli
>ember install ember-bootstrap

###Generated login route
>ember generate route about

>ember destroy model empdetails

###Defining routes

```javascript
App.Router.map(function() {
  this.route('about', { path: '/about' });
  this.route('favorites', { path: '/favs' });
});
```

### Conditional Statement 

[Conditional Example Link](http://www.tutorialspoint.com/emberjs/temp_conditon_if.htm)

### Form Example in EmberJS

```html

<form {{action "doSomething" on="submit"}}>
    {{input type="text" value=foobar}}
    <button type="submit">Save</button>
</form>

```

### EmberJS Data Model

[ Example ] (https://www.sitepoint.com/fixture-adapters-ember-js-server/)

### Create component in EmberJS

```
ember g component name-of-the-component
```


