# ITCSS tools layer
Reusable tools layer for my (and your) itcss stack

### Install using Bower

```
$ bower install --save foo-itcss-tools
```

### Install as a Git Submodule

```
$ git submodule add git@github.com:foo-itcss/tools.git
```
Once installed, @import into your project in its tools layer:
```
@import "tools/tools";
````
Alternatively you can import only needed files, e.g.:
```
@import "tools/tools.position";
```

#### Pull requests are welcome
But avoid to "break" the behaviour of current rules, since they're shared with others projects.

###### Thanks
To [Harry Roberts](http://csswizardry.com/) for the great idea of ITCSS
