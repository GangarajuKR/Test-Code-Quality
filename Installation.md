SonarLint is an Eclipse plugin, provided as an update site.

First be sure to check the [requirements](Requirements).

## Online installation using the Eclipse Marketplace client

The simplest way to install SonarLint is to use the Eclipse Marketplace client. See the [Getting Started](Getting-Started) tutorial for more details.

:information_source: By using this method, you will be automatically notified of new updates of SonarLint (assuming you have allowed Eclipse to check for updates).

## Online installation using the Eclipse _Install New Software_ wizard

[Official Eclipse documentation](https://help.eclipse.org/?topic=%2Forg.eclipse.platform.doc.user%2Ftasks%2Ftasks-124.htm)

If you can't use the Eclipse Marketplace client, you can still use directly the SonarLint update site.

1. Open _Install New Software_

[TODO]

2. Click on the _Add..._ button to add a new update site pointing to https://eclipse-uc.sonarlint.org. Give the update site a meaningful name.<br>Don't worry if you can't open this URL in your web browser, Eclipse will automatically look for files [compositeContent.xml](https://eclipse-uc.sonarlint.org/compositeContent.xml) and [compositeArtifacts.xml](https://eclipse-uc.sonarlint.org/compositeArtifacts.xml)

[TODO]

3. Select the just added _SonarLint_ update site, and tick the _SonarLint for Eclipse_ feature

[TODO]

4. Review the features about to be installed, and click _Finish_

[TODO]

5. When requested, restart you IDE

:information_source: By using this method, you will be automatically notified of new updates of SonarLint (assuming you have allowed Eclipse to check for updates).

## Offline installation using the Eclipse _Install New Software_ wizard

If you can't perform an online installation, you can use a SonarLint update site archive.

1. Manually download the latest archive of the SonarLint update site from https://binaries.sonarsource.com/SonarLint-for-Eclipse/releases/

2. Open _Install New Software_

[TODO]

3. Click on the _Add..._ button to add a new archive update site. Click on the _Archive..._ button to select the zip file you have downloaded. Give the update site a meaningful name.

[TODO]

4. Select the just added _SonarLint_ update site, and tick the _SonarLint for Eclipse_ feature

[TODO]

5. Review the features about to be installed, and click _Finish_

[TODO]

6. When requested, restart you IDE

:warning: When using this method, you will *not* be notified for new updates of SonarLint.