git init
git remote add origin https://github.com/username/repo-name.git
git pull origin main


what is unit tests?

Unit tests are the smallest level of automated testing in software development. They focus on verifying that individual pieces of code (units) — usually methods or functions — work correctly in isolation.




mvn clean install

clean → deletes old compiled files (ensures a fresh build).

install → compiles the code, runs tests, packages the app (like a .jar or .war), and installs it into your local Maven repository (~/.m2).

This is the standard way to build a Java project with Maven.

mvn test

Runs all unit tests (JUnit/TestNG) defined in your project.

If tests fail, the pipeline stops — ensuring only working code moves forward.




