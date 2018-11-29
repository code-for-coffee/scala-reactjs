# scala-reactjs

[![Build Status](https://travis-ci.org/code-for-coffee/scala-reactjs.svg?branch=master)](https://travis-ci.org/code-for-coffee/scala-reactjs)

Simple Scala binding for ReactTraining/react-stdio

## Getting Started

> You will need `nvm` (which installs `node` & `npm`), `java`, `scala`, and `gradle` for this project. Use your favourite package manager to install these.

1. `nvm install --lts` the version specific in the _.nvrmc_ file.
2. `npm ci` to install the locked dependencies to this repository. Then run `npm run build` to build **react-stdio** locally.
3. `./gradlew build --stacktrace` to build the Scala library.
4. `./gradlew test --stacktrace` to run the tests for the Scala library.

## Based on

- [Gradle Guide to building Scala packages](https://guides.gradle.org/building-scala-libraries/)
