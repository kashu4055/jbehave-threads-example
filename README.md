# Running JBehave stories in parallel
-----------------------------

This project is a modified version of [threads example](https://github.com/jbehave/jbehave-core/tree/master/examples/threads)


## Execution

```bash
mvn clean install
```
or simply
```bash
mvn install
```


## HTML Report
after running the tests HTML report proceed to target/jbehave/view/index.html to view the report


## Running with N threads
Number of threads used to execute the stories if configurable via <threads>1</threads> property in pom.xml

Run the tests with just 1 thread and then with 2 and compare the console outputs and the HTML reports.
Latter one will overwrite the results in the report with the results from the thread that finishded the last!!!!!!!!