## PDT standalone parser##

### Description ###

This software provide a standalone version of the PHP parser used by the PDT Eclipse plugin. 
It has no dependency on Eclipse or third parties Eclipse plugins.

### Installation ###

Checkout the source code and install it with maven in your local repository.

    <dependency>
      <groupId>com.tocea</groupId>
      <artifactId>pdt-standalone-parser/artifactId>
      <version>1.0.0</version>
    </dependency>

### Usage ###

You need to a dependency on the maven project :

    <dependency>
      <groupId>com.tocea</groupId>
      <artifactId>pdt-standalone-parser/artifactId>
      <version>1.0.0</version>
    </dependency>
    
To parse a php4 file you may use the following code :

    ASTParser parser = ASTParser.newParser(PHPVersion.PHP4);
    Program parser.setSource(new File("<your file>"));
    ...

### Licence ###

Thie software is released under [EPL](http://www.eclipse.org/legal/epl-v10.html) license.

