# My OSS Project

An open-source project bootstrapped using the [ModiTect OSS Quickstart](https://github.com/moditect/oss-quickstart) archetype.

## Build

This project requires Java 17 or newer for building.
It comes with the Apache [Maven wrapper](https://github.com/takari/maven-wrapper),
i.e. a Maven distribution will be downloaded automatically, if needed.

Run the following command to build this project:

```shell
./mvnw clean verify
```

On Windows, run the following command:

```shell
mvnw.cmd clean verify
```

Pass the `-Dquick` option to skip all non-essential plug-ins and create the output artifact as quickly as possible:

```shell
./mvnw clean verify -Dquick
```

Run the following command to format the source code and organize the imports as per the project's conventions:

```shell
./mvnw process-sources
```

In accordance to the post [Maven Release Plugin: Dead and Buried](https://axelfontaine.com/blog/dead-burried.html) from Axel Fontaine
Run the following command to tag and deploy a version based on revision.

```shell
./mvnw deploy -Ddeploy -Drevision=1
```

## License

This code base is available under the Apache License, version 2.
