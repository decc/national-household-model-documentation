# Synopsis
This project is linked to [National Household Model Core Components] (https://github.com/decc/national-household-model-core-components), in that it takes the compiled jar files for nhm-language-documentation and nhm-stock-documentation which contain reference documentation for those files in the form of XML and converts them into four formats, docbook, eclipse, pdf and webhelp. The eclipse format is then used within the [National Household Model IDE] (https://github.com/decc/tbd) to provide a refrence guide.


# Installation
Requires installation of Java 1.7 JRE in order to run executable JAR file. Uses Maven to build exectutable. Your local maven repository should include both the nhm-language-documentation and nhm-stock-documentation jars at the correct version. These can be added to your local repository by cloning [National Household Model Core Components] (https://github.com/decc/national-household-model-core-components) and running '/gradlew install'.

# License
[Open Government License] (http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) 
