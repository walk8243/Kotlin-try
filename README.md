# Kotlin-try
Kotlinのお試し

## コマンドラインから実行

```.sh
kotlinc hello.kt -include-runtime -d hello.jar
java -jar hello.jar
```

## Gradleから実行

```.sh
gradle init
./gradlew run
```

## 参考文献

- [SDKMAN](https://sdkman.io/)
- [Kotlin](https://dogwood008.github.io/kotlin-web-site-ja/)
- [Gradle](https://gradle.org/)

### インストール

#### SDKMAN

```.sh
curl -s get.sdkman.io | bash
```

#### Kotlin

```.sh
sdk install kotlin
```

#### Gradle

```.sh
sdk install gradle
```
