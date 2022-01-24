# workshop-selenium-java

Welcome to Java Selenium workshop. This workshop has a brief introduction to automation test with Selenium and Java

1. Create a empty Java Project using Gradle
    1. Include gitignore
1. Create a basic test with Selenium and TestNG
    1. Use [Web Driver Manager](https://github.com/bonigarcia/webdrivermanager)
1. Add Continuous Integration (CI) with Github Actions including a step to execute the tests
    1. Avoid the `chmod +x gradlew` into CI script, instead of use [git permissions](https://www.jerriepelser.com/blog/execute-permissions-with-git/)
1. Add a report to show the results of the test (passed, failed, skipped)
    1. Can use any report but we suggest that EnricoMi/publish-unit-test-result-action
1. Add code style (suggestions: nikitasavinov/checkstyle-action@master, <https://github.com/github/super-linter>)
1. Create a test to buy a T-shirt in http://saucedemo.com/
1. Refactor the test using POM (page object model)
