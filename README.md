# docker-java-shaded

Shaded/Shadow/Uber/Fat/All version of the [docker-java](https://github.com/docker-java/docker-java) library

## Status

| Questions | CI | Release |
| :---: | :---: | :---: |
| [![Stack Overflow](https://img.shields.io/badge/stack-overflow-4183C4.svg)](https://stackoverflow.com/questions/tagged/docker-java-shaded) | [![Build Status](https://travis-ci.org/project-aries/docker-java-shaded.svg?branch=master)](https://travis-ci.org/project-aries/docker-java-shaded) | [![docker-java-shaded](https://api.bintray.com/packages/project-aries/libs-release-local/docker-java-shaded/images/download.svg) ](https://bintray.com/project-aries/libs-release-local/docker-java-shaded/_latestVersion) |

## Motivation

As the current maintainer of the [gradle-docker-plugin](https://github.com/bmuschko/gradle-docker-plugin) project we had a need to use a shaded version of `docker-java` to get around various `buildscript` clobberring issues. As the folks at the `docker-java` project are busy with other things, and can't immediately make this happen, I decided to go ahead and code something myself until they have the free time in which to do so.

If a new release of `docker-java` happens that I miss, and you'd like a new version of this library spun up based on it, just open an ISSUE and ask.

If a security vulnerability arises, and an internal dependency needs to be bumped, and assuming the `docker-java` can't be easily updated, then just open an ISSUE and note the library and we can spin a new point release to accommadate you and the greater community.

## Latest Release

Can be sourced from jcenter like so:
```
<dependency>
    <groupId>com.aries</groupId>
    <artifactId>docker-java-shaded</artifactId>
    <version>X.Y.Z</version>
</dependency>
```

## Additional Resources

* [Release Process](https://github.com/project-aries/docker-java-shaded/blob/master/docs/RELEASE_PROCESS.md)

