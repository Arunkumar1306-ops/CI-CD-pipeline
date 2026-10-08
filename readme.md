git init
git remote add origin https://github.com/username/repo-name.git
git pull origin main


what is unit tests?

Unit tests are the smallest level of automated testing in software development. They focus on verifying that individual pieces of code (units) — usually methods or functions — work correctly in isolation.






mvn clean install

mvn clean install

Runs the full build lifecycle:

clean → wipes old build artifacts.

compile → compiles source code.

test → runs unit tests.

package → creates .jar/.war.

install → puts the artifact in your local Maven repo (~/.m2).

This is the standard way to build a Java project with Maven.



mvn test

Runs all unit tests (JUnit/TestNG) defined in your project.

If tests fail, the pipeline stops — ensuring only working code moves forward.




