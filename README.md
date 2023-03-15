# jkube-example

Build Steps:
mvn -DskipTests package oc:build oc:resource

Deploy Steps
mvn -DskipTests oc:deploy

ReBuild Steps:
mvn -DskipTests oc:build oc:resource oc:apply