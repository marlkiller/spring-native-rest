# introduce
Spring boot native sample project
Build with maven/gradle


# env
- graalvm-jdk-17 (https://github.com/graalvm/graalvm-ce-builds/releases)
- native-image (gu install native-image) 
- maven|gradle

# build run
## mvn
```jshelllanguage
mvn clean -Pnative -DskipTests package
./target/spring-native-rest
```

## gradle
```jshelllanguage
gradle -x test clean build nativeCompile
./build/native/nativeCompile/spring-native-rest
```


