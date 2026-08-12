# Multi-Module Maven Project

This repository contains two Maven projects created in Eclipse:

## 1. Maven Java Project (root)
A simple Java application built with Maven (`maven-archetype-quickstart` style).

- `src/main/java/com/example/App.java` — prints `Hello World!`
- `src/test/java/com/example/AppTest.java` — JUnit test
- Run: **Run As → Java Application**
- Build: `clean install test` → BUILD SUCCESS

## 2. Maven Web Project (`mavenweb/`)
A Java web application (WAR) that displays a "Hello World" web page on Apache Tomcat.

- `mavenweb/src/main/webapp/index.jsp` — Hello World page
- `mavenweb/src/main/webapp/WEB-INF/web.xml` — deployment descriptor
- Run: **Run As → Run on Server** (Tomcat v9)

## Tech
- Java 17
- Maven
- JUnit 4
- Servlet API / JSP
- Apache Tomcat 9
