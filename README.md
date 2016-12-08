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

### git commands

>git status

>git checkout bower.json

>git checkout package.json

>git add *

>git commit --no-verify -m "Commit Changes"

>git push --no-verify "Message"

------------------------------------------

### Other git comments 

>git clean -f

will remove untracked files, meaning they're gone for good since they aren't in GitHub

>git reset --hard

git reset --hard will not remove untracked files

### Change fork url 

>git remote -v

>git remote set-url origin git://github.com/youruser/yourrepo

### Remove Node Modules 

>rm -rf node_modules/
