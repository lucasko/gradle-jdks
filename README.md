

```
./gradlew clean compileJava6 jar6 

# check version of compiled file
javap -v ./build/classes/App.class | grep major
```

```
45.3 = Java 1.1
46 = Java 1.2
47 = Java 1.3
48 = Java 1.4
49 = Java 5
50 = Java 6
51 = Java 7
52 = Java 8
53 = Java 9
54 = Java 10
55 = Java 11
56 = Java 12
57 = Java 13
58 = Java 14
```