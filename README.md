See https://issues.apache.org/jira/browse/MNG-8041

Execute `mvn provisio:provision` and obseve `target/lib` directory, that should contain all the runtime dependencies. It is incomplete.

The Guice IS runtime, but Guava is not present but should be.
