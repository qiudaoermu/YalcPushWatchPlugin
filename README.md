
Automatic execute `yalc push` if you are use yalc when your package is changed.


### install

```
npm i yalcwatch-webpack-plugin -save-dev
```

### usage



1. install yalc

```
install yalce -g
```
2. yalc push your package 
```
yalc publish
```

3. add to your webpack 


```
const YalcWatchPlugin = require('yalcwatch-webpack-plugin');
new YalcWatchPlugin({
  watchPushAction: true, // open watching Model
  linkName: "projectA", // your main package name
})
```

4.start your project

Enjoy yourslef~~~