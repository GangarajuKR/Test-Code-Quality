# Overview
You can connect SonarLint to SonarQube >= 6.7 or SonarCloud to aim at having consistent issues reported on both sides.

Features when connected mode is used:
* use the same analyzers than the server, assuming they are supported in SonarLint
* use the same quality profile (same rules activation, parameters, severity, ...)
* reuse some settings defined on the server (rule exclusions, analyzer parameters, ...)
* automatically suppress issues that are marked as _Won’t Fix_ or _False Positive_ on the server

Note: connected mode does not push issues to the server. Rather, its purpose is to configure the IDE so that it uses the same settings as the server.

# Configure a connection

A connection is a basically the informations needed to communicate with the SonarQube server or SonarCloud.

## Configure a connection to a SonarQube server

## Configure a connection to SonarCloud

# Configure project(s) binding

# Troubleshooting

## Why I have some issues reported on SonarQube/SonarCloud but not in SonarLint?

TODO: copy from the FAQ

## SSL/proxy issues