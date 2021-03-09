# Overview

Taint vulnerabilities are a type of [security-related rules](https://docs.sonarqube.org/latest/user-guide/security-rules/), that can be raised by both SonarCloud and SonarQube (starting with Developer Edition).

Due to technical limitations, SonarLint for Eclipse can not raise such issues on local analysis.
Nevertheless, it is possible for a project to display within the IDE vulnerabilities detected by SonarCloud/SonarQube.

# Prerequisites

* You need to bind to SonarCloud or SonarQube Developer Edition (or higher) 8.6+
* For this feature to be valuable, your project needs to be analyzed frequently (ideally by your CI server when pushing new code)
* Only issues detected on the main branch will be displayed in the IDE
* Only issues detected on open files will be displayed in the IDE

# How to display taint vulnerabilities in Eclipse

1. [[Bind your project to SonarQube/SonarCloud|Connected Mode]]
2. Open _Window_ > _Show View_ > _Other..._ > _SonarLint_ > _SonarLint Taint Vulnerabilities_
3. The view should display the list of taint vulnerabilities that are present on open files.