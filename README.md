# How to fail

```
gradlew build
```

```
gradlew jar
```

```
java -jar app/build/libs/app.jar
```
The above produces:

```
no main manifest attribute, in app/build/libs/app.jar
```

Which I can confirm when I run:

```
jar xf app/build/libs/app.jar META-INF/MANIFEST.MF
```
