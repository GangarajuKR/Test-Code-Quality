# Overview
You can connect SonarLint to SonarQube >= 7.9 or SonarCloud to aim at having consistent issues reported on both sides.

Features when connected mode is used:
* use the same analyzers than the server, assuming they are supported in SonarLint
* use the same quality profile (same rules activation, parameters, severity, ...)
* reuse some settings defined on the server (rule exclusions, analyzer parameters, ...)
* automatically suppress issues that are marked as _Won’t Fix_ or _False Positive_ on the server

Note: connected mode does not push issues to the server. Rather, its purpose is to configure the IDE so that it uses the same settings as the server.

# Configure a connection

A connection is the set of informations needed to communicate with the SonarQube server or SonarCloud (URL, credentials, ...).

## Configure a connection to a SonarQube server

1. Open the connection wizard, for example using menu _File_ -> _New_-> _Other..._ and then _SonarQube/SonarCloud Connection_:
[[images/connected/file_new_connection.png|alt=New Connection]]

2. Select _SonarQube_ and click on the _Next_ button:

[[images/connected/wizard_select_sonarqube.png|alt=Select SonarQube]]

3. Enter your SonarQube server URL:

[[images/connected/wizard_set_url.png|alt=Set URL]]

4. Choose the authentication method:
* Token: generate a token on [SonarQube](https://docs.sonarqube.org/latest/user-guide/user-token/), to be used by SonarLint as authentication method. This is the preferred way to avoid the risk to compromise your username/password.
* Username + Password: use directly your SonarQube credentials (not recommended)

[[images/connected/wizard_choose_auth.png|alt=Choose auth]]

5. Enter your token or username/password

6. Give your connection a name

## Configure a connection to SonarCloud

4. Generate a token on [SonarCloud](https://sonarcloud.io/documentation/user-guide/user-token/), to be used by SonarLint as authentication method.

# View configured connections

Configured connections can be retrieved from the Bindings view (Window > Show View > Other... > SonarLint > SonarLint Bindings).

This should open a view at the bottom, listing all connections:

[[images/connected/bindings_view.png|alt=Bindings View]]

A right-click on a connection will open a contextual menu to remove or edit the connection. It can be useful for example to update the credentials if they have changed.

# Configure project(s) binding

# Troubleshooting

## Why I have some issues reported on SonarQube/SonarCloud but not in SonarLint?

TODO: copy from the FAQ

## SSL/proxy issues
