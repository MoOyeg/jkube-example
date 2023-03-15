# jkube-example

[Source Code Link](https://github.com/RedHatTraining/DO288-apps/tree/main/micro-java/src/main) 

Build Steps:
```bash
mvn -DskipTests package oc:build oc:resource
```

Deploy Steps
```bash
mvn -DskipTests oc:deploy
```

ReBuild Steps:
```bash
mvn -DskipTests oc:build oc:resource oc:apply
```