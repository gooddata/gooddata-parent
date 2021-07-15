# GoodData OSS Parent POM [![Build Status](https://github.com/gooddata/gooddata-parent/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/gooddata/gooddata-parent/actions/workflows/build.yml) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.gooddata/gooddata-parent/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.gooddata/gooddata-parent) [![Release](https://img.shields.io/github/v/release/gooddata/gooddata-parent.svg)](https://search.maven.org/artifact/com.gooddata/gooddata-parent)

All open source GoodData Maven projects *should* directly or indirectly inherit from `gooddata-parent` POM.

```xml
<parent>
    <groupId>com.gooddata</groupId>
    <artifactId>gooddata-parent</artifactId>
    <version>X.Y.Z</version>
    <relativePath />
</parent>
```

This module helps Maven projects to be released into the public [Central repository](http://central.sonatype.org/)
using [Sonatype's Open Source Software Repository Hosting (OSSRH) service](http://central.sonatype.org/pages/ossrh-guide.html).

## Development

See [Releasing How-To](https://github.com/gooddata/gooddata-parent/wiki/Releasing-How-To).
