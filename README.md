# jiakuan-gwt-gradle-plugin-sample



This is a sample GWT project that modifies a project created with the [GWT webAppCreator](https://www.gwtproject.org/doc/latest/RefCommandLineTools.html#webAppCreator) to  a Gradle project using [jiakuan/gwt-gradle-plugin](https://github.com/jiakuan/gwt-gradle-plugin).

I needed a sample project that uses a bit more updated tools and libraries than the examples from [jiakuan/gwt-gradle-plugin/tree/1.1.18/examples](https://github.com/jiakuan/gwt-gradle-plugin/tree/1.1.18/examples)

- jiakuan/get-gradle-plugin 1.1.18
- gwt 2.9.0
- JDK 11
- Gradle 7.4.2
- gretty 3.0.7

## Run Super Dev Mode

Open two separate terminals and run the following tasks

```shell
# Terminal 1
./gradlew gwtSuperDev

# Terminal 2
./gradlew draftWar appRun
```

Open the URL form terminal 1 and follow the instructions to add the bookmarklets

Open the URL from terminal 2 and click the "Dev Mode On" bookmarklet and compile the  `mywebapp` module.
