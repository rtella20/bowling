bowling
==============

This is a simple command line application that will track and display a user's bowling game score. The original software was built as part of a Test-Driven Development (TDD) exercise. It has been extended to use as an example for Cucumber testing.

If you have Maven configured to run on your system, run the application by navigating to the directory and issue this command:
```
    ./bowl
```

This command will compile the code, execute all the tests and run the command line application. You may need to mark it as executable like so:
```
    chmod 744 ./bowl
```

To run tests - both **JUnit** tests and **Cucumber** tests - run the following command at the command line:
```
    mvn clean test
```

Cucumber feature files are located here:
```
src/test/resources/bowling
```

Cucumber stepdef file is located here:
```
src/test/java/bowling/BowlingGameStepDefs.java
```