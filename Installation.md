SonarLint is an Eclipse plugin, provided as an update site.

First be sure to check the [requirements](Requirements).

## Online installation using the Eclipse Marketplace client

The simplest way to install SonarLint is to use the Eclipse Marketplace client. See the [Getting Started](Getting-Started) tutorial for more details.

:information_source: By using this method, you will be automatically notified of new updates of SonarLint (assuming you have allowed Eclipse to check for updates).

## Online installation using the Eclipse _Install New Software_ wizard

[Official Eclipse documentation](https://help.eclipse.org/?topic=%2Forg.eclipse.platform.doc.user%2Ftasks%2Ftasks-124.htm)

If you can't use the Eclipse Marketplace client, you can still use directly the SonarLint update site.

1. Open _Install New Software_

[[images/install/open_install_new_software_wizard.png|alt=Install new software]]

2. Click on the _Add..._ button to add a new repository pointing to https://eclipse-uc.sonarlint.org. Give the repository a meaningful name.<br>Don't worry if you can't open this URL in your web browser, Eclipse will automatically look for files [compositeContent.xml](https://eclipse-uc.sonarlint.org/compositeContent.xml) and [compositeArtifacts.xml](https://eclipse-uc.sonarlint.org/compositeArtifacts.xml)

[[images/install/add_software_site.png|alt=Add Update Site]]
[[images/install/add_software_site_online.png|alt=Add Update Site Online]]

3. Select the just added _SonarLint_ repository, and tick the _SonarLint for Eclipse_ feature

[[images/install/p2_install_online.png|alt=Select feature online]]

4. Review the features about to be installed, and click _Finish_

[[images/install/p2_install_confirm.png|alt=Confirm feature]]

5. When requested, restart you IDE

:information_source: By using this method, you will be automatically notified of new updates of SonarLint (assuming you have allowed Eclipse to check for updates).

## Offline installation using the Eclipse _Install New Software_ wizard

If you can't perform an online installation, you can use a SonarLint repository archive.

1. Manually download the latest archive (.zip) of the SonarLint repository from https://binaries.sonarsource.com/?prefix=SonarLint-for-Eclipse/releases/

2. Open _Install New Software_

[[images/install/open_install_new_software_wizard.png|alt=Install new software]]

3. Click on the _Add..._ button to add a new repository. Click on the _Archive..._ button to select the zip file you have downloaded. Give the repository a meaningful name.

[[images/install/add_software_site.png|alt=Add Update Site]]
[[images/install/add_software_site_archive.png|alt=Add Update Site Archive]]

4. Select the just added repository, and tick the _SonarLint for Eclipse_ feature

[[images/install/p2_install_offline.png|alt=Select feature offline]]

5. Review the features about to be installed, and click _Finish_

[[images/install/p2_install_confirm.png|alt=Confirm feature]]

6. When requested, restart you IDE

:warning: When using this method, you will *not* be notified for new updates of SonarLint.