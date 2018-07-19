Gradle Task DoFirst DoLast Demo
===============================

The code in task but not in `doFirst/doLast` are configuration code, they will be run when parsing the `build.gradle` script.

```
./gradlew tasks
```

will show:

```
> Configure project :
----------- hello in configuration -----------
```

Run task:

```
./gradlew hello
```

will show:

```
> Task :hello
------------ doFirst ------------
------------ doLast ------------
```
