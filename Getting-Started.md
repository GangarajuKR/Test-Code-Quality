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

For example in Java, you can copy paste this code snippet:

```java
package org.mycompany;

import java.util.logging.Level;
import java.util.logging.Logger;

public class Main {

  private static final Logger LOGGER = Logger.getLogger(Main.class.getName());

  public static void main(String[] args) {
    for (int i = 0; i < 10; i++) {
      for (int j = 0; j < 10; i++) {
        LOGGER.log(Level.INFO, "Pair: ({0},{1})", new Object[] {i, j});
      }
    }
  }

}
```

If you open this Java file with the Eclipse Java editor, you should see SonarLint underlining an issue:


:construction: 

* On-the-fly view
* code snippets for all languages
* rule description
* analyze all files
