Here are the requirements for SonarLint to work properly.

* Eclipse Platform Requirement: the minimal version of the Eclipse platform that SonarLint supports. If you are not familiar with Eclipse versioning scheme, see [here](https://en.wikipedia.org/wiki/Eclipse_(software)#Releases).
* JVM requirement: the minimal version of the JVM that is used to [run Eclipse](https://wiki.eclipse.org/Eclipse.ini#Specifying_the_JVM).
* Node.js requirement: only for JavaScript analysis
* SonarQube requirement: only if using connected mode

| SonarLint Version | Eclipse Platform Requirement | JVM Requirement | Node.js Requirement | SonarQube requirement (if using connected mode) |
| --- | --- | --- | --- | --- |
| 6.x | 4.6+ (Neon+) | 1.8+ | | 7.9+ |
| 7.x | 4.8+ (Photon+) | 11+ | | 7.9+ |
| 7.4 | 4.8+ (Photon+) | 11+ | 12.22+ | 7.9+ |

# Other requirements

* Analysis of Java code requires JDT
* Analysis of C and C++ requires CDT
* Analysis of Cobol requires specific integration provided only by some Cobol IDEs, like [IBM Developer for z Systems (IDz)](https://community.ibm.com/community/user/ibmz-and-linuxone/blogs/blog-entry1/2017/07/07/sonarlint-integration-with-developer-for-zsystems) or [BMC Compuware Topaz Workbench](https://devops.api.bmc.com/guidelines/ispw/ispw_projects.html#setting-up-usage-of-sonar-lint).
