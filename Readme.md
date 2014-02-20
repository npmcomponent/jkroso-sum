*This repository is a mirror of the [component](http://component.io) module [jkroso/sum](http://github.com/jkroso/sum). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/jkroso-sum`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# sum

  Sum utility

## Installation

    $ component install component/sum

## API

### sum(array, [fn|string])

  Sum an array of numbers:

```js
sum([1,2,3,4,5]);
```

  Sum properties with callback:

```js
var sum = sum(users, function(user){
  return user.age;
});
```

### map(array, string)

  Sum properties in `string`:

```js
sum(users, 'age');
sum(repos, 'stats.watchers');
```

# License

  MIT
