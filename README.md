# GoodData OSS Parent POM

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
