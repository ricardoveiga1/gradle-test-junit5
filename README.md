- gradle clean test -DincludeTags='contract'
- https://docs.gradle.org/current/userguide/java_testing.html
- https://junit.org/junit5/docs/current/user-guide/#writing-tests-tagging-and-filtering
- https://javabydeveloper.com/run-tag-specific-junit-5-tests-from-gradle-command/
- https://www.jenkins.io/download/weekly/macos/
- https://www.jenkins.io/download/

















/*
- import org.junit.jupiter.api.MethodOrderer.OrderAnnotation;
  import org.junit.jupiter.api.Order;
  import org.junit.jupiter.api.Test;
  import org.junit.jupiter.api.TestMethodOrder;

@TestMethodOrder(OrderAnnotation.class)
class OrderedTestsDemo {

    @Test
    @Order(1)
    void nullValues() {
        // perform assertions against null values
    }

    @Test
    @Order(2)
    void emptyValues() {
        // perform assertions against empty values
    }

    @Test
    @Order(3)
    void validValues() {
        // perform assertions against valid values
    }

}
*/