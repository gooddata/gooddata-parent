# Release notes

## 3.0.0
* Simplify license headers.
** No need to update year on change.
* Include only files under src/ for license check.
** Maven should not check files which are not part of the build check of child modules is ensured using multimodule build (we don't use aggregate setting in license plugin).
* Add Kotlin source files to license header includes.

## 2.0.3
* Set only build to require java 11 the release target switched back to 8

## 2.0.2
* Set target Java release to 11

## 2.0.1
* Do not use doclint even on java 11

## 2.0.0
* Support java 11 build. Enforces target java 8 by default. Expects java 8 javadoc (no modules).

## 1.0.0
* Initial version derived from [org.sonatype.oss:oss-parent:9](http://repo1.maven.org/maven2/org/sonatype/oss/oss-parent/9/oss-parent-9.pom).
* Add GoodData basic stuff
