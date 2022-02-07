# Java Template Project

This is a template project for Java. The following technologies are used in this template.

# Project Structure

```markdown

┌─── build.gradle                 (Gradle build configurations)
├─── .gitignore                   (Files ignored by Git)
├─── gradle/                      (Gradle distribution to build this project)
├─── .gradle/                     (not committed, in .gitignore)
├─── gradlew                      (Unix command for Gradle)
├─── gradlew.bat                  (Windows command for Gradle)
├─┬─ src/
│ ├─┬─ main/
│ │ ├─── java/
│ │ └─── resources/
│ └─┬─ test/
│   ├─── java/
│   └─── resources/
├─── README.md
└─── settings.gradle              (project name configuration)

```

# Decisions Log

<Details><summary>Multi Repo</summary>

The multi-repo approach uses several repositories to host the multiple libraries or services of a project

Alternatives

* Mono Repo
</details>

<Details><summary>Spring Boot</summary>

Spring Boot is an opinionated way for creating stand-alone, production-grade applications with minimum effort. It is the
most popular Framework used in Java.

Alternatives

* [Play Framework](https://www.playframework.com/)
* [Vert.x](https://vertx.io/docs/vertx-web/java/)
</details>

<Details><summary>Gradle</summary>

Gradle is a build automation tool for multi-language software development. The Gradle Wrapper is the preferred way of
starting a Gradle build.

Other Alternatives

* [Maven](https://maven.apache.org/)

</details>

<Details><summary>gitignore.io</summary>
Generates .gitignore file based on keywords. 

Alternatives

* Manually creating a .gitignore file
* https://github.com/github/gitignore

</Details>  

<Details><summary>lombok</summary>
Annotation-based Java library that allows you to reduce boilerplate code 

Alternatives

* Generate POJOs with IDE or https://www.jsonschema2pojo.org/
* [AutoValue](https://github.com/google/auto)

</Details>  