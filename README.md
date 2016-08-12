#schematron-xslt#
Compiles ISO Schematron using XSLT

**Prerequisites**

You need to have [Maven](https://maven.apache.org/) installed and available on the command line.

**Usage**

Add your Schematron file to the `src/main/resources` sub-directory of the project and then run `mvn clean install`. After this has run, if all goes well, the XSLT version of the Schematron file will be found in:

    target/generated-resources/schematron/xslt
