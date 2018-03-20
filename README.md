# CustomMaven
Custom maven lib

Used to build an app faster and easier.

***

#### Add the repositories

1.Add the repository in project:
```
allprojects {
    repositories {
        maven {
            url "https://raw.githubusercontent.com/hawkWei07/CustomMaven/master"
        }
    }
}
```

2.Add the aar of lib you need:
```
implementation 'cn.hawk.projectforlibs:commonlib:0.0.1'
```

Then, enjoy your way.



### Custom libs

| module    | version | comment                |
| --------- | ------- | ---------------------- |
| commonlib | 0.0.1   | lib for common utils   |
| netlib    | 0.0.1   | lib for network issues |
|           |         |                        |

