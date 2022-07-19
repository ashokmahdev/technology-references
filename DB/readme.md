## Visualizing Postgres Database Schemas

### Purpose

This repository contains the necessary JAR files to utilize [SchemaSpy](http://schemaspy.org/) in creating an [Entity-relationship diagram](https://en.wikipedia.org/wiki/Entity%E2%80%93relationship_model) of a PostgreSQL database.

### Setup

- SchemaSpy relies upon Java and (optionally) Graphviz.
  - Java comes pre-installed on a Mac. One could use Brew to [install a specific version](https://medium.com/w-logs/installing-java-11-on-macos-with-homebrew-7f73c1e9fadf).
  - [Installing Graphviz](http://www.graphviz.org/download/) on a Mac: `brew install graphviz`
- If you are not using PostgreSQL, you will need to download the relevant JDB Driver file for your preferred flavor of DB.


### Steps

1. After cloning repository, copy [example file](./schemaspy.properties.example) into a file called `schemaspy.properties`, and update with your preferred configuration.
    - Alternatively, when executing, specify the file path using the command flag `-configFile filePath`.
    - Complete list of [SchemaSpy command line arguments](https://schemaspy.readthedocs.io/en/latest/configuration/commandline.html#commandline)
1. Ensure that your target database is running.
1. Execute `java -jar schemaspy-6.1.0.jar` within your local clone of this repository.
1. Open output/index.html within your preferred browser or HTML application.