##EmberJS

### Installed Bootstrap Cli
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


