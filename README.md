# IntelliJ-Jenkins-DSL-Skeleton
skeleton structure for writing Jenkins DSL


this repository is a skeleton structure for writing jenkinsdsl in IntelliJ IDE.
IntelliJ is the only officially supported IDE for JenkinsDSL (as far as I know). 
However compatability is still quite tidious to achieve...

So I created this repository that includes a **gradle build**. 


### How to use this repository
------------------------------

**Pre-Requirements:**

this skeleton project assumes you have the following things already installed on your system:

* Java
* Gradle (you could us a gradle wrapper, there is one provided in here.)
* IntelliJ

all you have to do is **git clone** this skeleton and open the gradle build with intelliJ



### File structure
------------------

    .
    ├── jobs                    # DSL script files
    ├── resources               # resources for DSL scripts
    ├── src
    │   ├── main
    │   │   ├── groovy          # support classes
    │   │   └── resources
    │   │       └── idea.gdsl   # IDE support for IDEA
    │   └── test
    │       └── groovy          # specs
    └── build.gradle            # build file



**note:** this repository is a stripped down version of: https://github.com/sheehan/job-dsl-gradle-example
in that repository you will find the same code but for an older jenkins version, with example files if anything would be unclear. :) 
