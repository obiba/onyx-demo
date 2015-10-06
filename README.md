Onyx Demo Project
=================

Onyx demo project can be used as a starting point to build your own Onyx project.

## Based on a Onyx release

1. Select [one of the tag](https://github.com/obiba/onyx-demo/tags)
2. Download project as a zip file
3. Unzip
4. From project base directory, build your onyx web application and launch server: `mvn jetty:run-war`
5. Connect to [http://localhost:8080](http://localhost:8080) and test your onyx webapp
6. Change settings (see [Onyx Customization & Configuration Guide](http://wiki.obiba.org/display/ONYXDOC))
7. Build and test again
8. When done, copy war file from target directory to your favorite servlet container

## Based on a Onyx snapshot

1. Clone onyx-demo project: `git clone https://github.com/obiba/onyx-demo.git`
2. From project base directory, build your onyx demo web application and launch server: `mvn jetty:run-war`
3. Connect to [http://localhost:8080](http://localhost:8080) and test your onyx webapp
4. Change settings (see [Onyx Customization & Configuration Guide](http://wiki.obiba.org/display/ONYXDOC))
5. Build and test again
6. When done, copy war file from target directory to your favorite servlet container

## Requirements

Requirements are: 
* [Maven 3.x](http://maven.apache.org)
* Java JDK 1.7.x or higher
