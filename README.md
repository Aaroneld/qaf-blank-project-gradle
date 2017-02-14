# qaf-blank-project-gradle

This is automation project skeleton to start with using Gradle. Please refer [documentaion](https://qmetry.github.io/qaf/) for more help.


This is sample project with Gradle directory structure:
 
The 'config' directory contains testng.xml file, and is a place holder for configuration files.

The 'resources' directory contains all required resources including properties files and data files, and is a place holder for other resources.

The 'src' directory contains all java files and is a place holder for other java files.

The 'test-results' directory contains result files.

The 'scenarios' directory is the default place holder for all the scenario files. 


To change/modify dependencies check `build.gradle`
To run the project, from command prompt go to project home and run `gradle clean test`.
Open dashboard.htm to view results.

Note: This sample project uses chrome driver and it requires chrome driver binary.
You need to download and set webdriver.chrome.driver property in application.properties file with driver binary path.

Please refer https://qmetry.github.io/qaf/ 

Thanks,
QAS Team.
