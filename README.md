Collect provided dependencies using Aether and Maven
====================================================

A sample to show how collecting all dependencies (provided, test, etc.) is done using Aether.

Collecting for

    junit:junit-dep:jar:4.10

Gives this output

    junit:junit-dep:jar:4.10 ()
      org.hamcrest:hamcrest-core:jar:1.1 (compile)
        jmock:jmock:jar:1.1.0 (provided)
        junit:junit:jar:4.0 (provided)
        org.easymock:easymock:jar:2.2 (provided)