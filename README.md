# project1

Imports [project2](https://github.com/brianyu0717/project2/) and uses [git submodules](http://blog.joncairns.com/2011/10/how-to-use-git-submodules/) to manage this dependency.

Uses Gradle to build this and import this project.

Looks like IntelliJ has [decent support](https://www.jetbrains.com/help/idea/2016.2/git-branches-in-multirooted-projects.html) for this.

## Dev

Run ```git clone``` then

```
git submodule init
git submodule update --recursive
```

Now open this project in IntelliJ and it should all just be configured.
