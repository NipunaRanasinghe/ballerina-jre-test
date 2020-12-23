# Ballerina JRE Artifacts

Generates platform-specific custom Java runtime images to be bundled with Ballerina platform distributions, which
contains only the required modules for Ballerina runtime.

This custom JRE generation is currently based on AdoptOpenJdk11 binaries and can be configured to use any custom
prebuilt platform JDKs, and a set of JDK library modules which should be included for Ballerina runtime.