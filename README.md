# Kotlin-try
Kotlinのお試し

## コマンドラインから実行

```.sh
kotlinc hello.kt -include-runtime -d hello.jar
java -jar hello.jar
```

## Gradleから実行

```.sh
gradle init --type kotlin-application
  # Select build script DSL: 1
  # Project name: [Enter]
  # Source package: [Enter]
./gradlew run
```

## 参考文献

- [OpenJDK](https://openjdk.java.net/projects/jdk/11/)
- [SDKMAN](https://sdkman.io/)
- [Kotlin](https://dogwood008.github.io/kotlin-web-site-ja/)
- [Gradle](https://gradle.org/)

### インストール

#### OpenJDK

```.sh
# もしJREがインストールされている場合
rpm -qa | grep jre
sudo rpm -e jre1.8-1.8.0_211-fcs

yum search jdk | grep "openjdk\.x86_64"
sudo yum install java-11-openjdk
```

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
