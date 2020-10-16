## Quick Installation

SonarLint for Eclipse is a plugin that can be installed in most Eclipse based IDEs (including Spring Tool Suite, PyDev, ...)

1.  In your Eclipse based IDE, open the Marketplace client

[[images/install/open_marketplace_client.png|alt=Open Marketplace Client]]

2. Search for SonarLint, and click _Install_

[[images/install/marketplace_install.png|alt=Install from Marketplace]]

3. Restart your IDE

For more installation methods, look for the advanced [installation](Installation) documentation.

## First taste of SonarLint

Now that you have SonarLint installed, open or create a new project containing source files in a programming language SonarLint can analyze out of the box: Java, PHP, Python, JavaScript or HTML.

For example in Java, you can copy paste this code snippet, with a typical bug when copy/pasting `for` loops:

```java
package org.mycompany;

import java.util.logging.Level;
import java.util.logging.Logger;

public class Main {

  private static final Logger LOGGER = Logger.getLogger(Main.class.getName());

  public static void main(String[] args) {
    for (int left = 0; left < 10; left++) {
      for (int right = 0; right < 10; left++) {
        LOGGER.log(Level.INFO, "Pair: ({0},{1})", new Object[] {left, right});
      }
    }
  }

}
```

If you open this Java file within the Eclipse Java editor, you should see SonarLint reporting the issue:

[[images/analysis/first_time_analysis.png|alt=First time analysis]]

To get more details about the issue, you can simply hover on the issue location, and a popup will display the issue message:

[[images/analysis/sonarlint_java_problem_hover.png|alt=Hover]]

There is also the possibility to use the SonarLint `On-The-Fly` view to display the list of issues found by SonarLint. Simply open the view from the menu Windows -> Show View -> Other...

[[images/views/open_on_the_fly_view.png|alt=Open On-The-Fly view]]
[[images/views/on_the_fly_view.png|alt=On-The-Fly view]]