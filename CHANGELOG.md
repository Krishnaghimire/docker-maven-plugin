Change Log
===
2.6.0

* Upgraded to docker-java-orchestration 2.6.0 ([changelog](https://github.com/alexec/docker-java-orchestration/blob/master/CHANGELOG.md)).
* Exclude containers using `-Ddocker.exclude=app,other`, or `<exclude>app,other</exclude>`.

2.5.0

* Reduced logging of properties to debug level.
* Do not treat files in `src/main/docker` as containers, only directories.
* Made validation more tolerant to property filtering.
* Fixed bug so that images are no longer removed by default.
* Added ability to "quiet" builds.
* Fixed bug where images were always rebuilt.
* Added ability to sleep on starting a container.

2.4.0

* Added the ability to verify the body of a ping health-check.
* [DJO Issue 17](https://github.com/alexec/docker-java-orchestration/issues/17) Can disable filtering on "added" properties.
* [DMP Pull 42](https://github.com/alexec/docker-maven-plugin/pull/42) Added ability to configure certificates from plugin configuration.

* Fix splitting of tag name when tag contains port declaration for non-default registry.

2.3.0

* [DMP Pull 38](https://github.com/alexec/docker-maven-plugin/pull/38) Expose container IP address as Maven properties .
* Changed to Apache 2.0 licence.
* [DMP Issue 34](https://github.com/alexec/docker-maven-plugin/issues/34) Problem with configuration of host URI is some environments.
* [DMP Issue 28](https://github.com/alexec/docker-maven-plugin/issues/28) Added support for private repositories.

2.2.0

* Used docker-java-orchestrator 2.2.0. See [Changelog](https://github.com/alexec/docker-java-orchestration/)

2.1.0

* Fixed bug preventing correct linking of containers.
* [DMP Issue 26](https://github.com/alexec/docker-maven-plugin/issues/26) Support for link alias.
* Forcibly delete images.

2.0.2

* [DMP Pull 27](https://github.com/alexec/docker-maven-plugin/pull/27) Added environment and system properties.

2.0.1

* [DJO Pull 10](https://github.com/alexec/docker-java-orchestration/pull/10) Correctly preserve line endings on Windows. 
* [DJO Pull 11](https://github.com/alexec/docker-java-orchestration/pull/11) Use docker-java 0.10.2.
* [DJO Pull 12](https://github.com/alexec/docker-java-orchestration/pull/12) Correctly stop containers.

2.0.0

* Updated to use port 2375 by default.
* [DJO Issue 2](https://github.com/alexec/docker-java-orchestration/issues/2) Support for volumes.
* [DMP Issue 8](https://github.com/alexec/docker-maven-plugin/issues/8) Correct incorrect tag names.
* [DMP Issue 22](https://github.com/alexec/docker-maven-plugin/issues/22) Use docker-java.

1.4.0

* [DMP Issue 15](https://github.com/alexec/docker-maven-plugin/issues/15) - support `cache` parameter

1.3.1

* Issue 5 - removed logging of binary to console 

1.3.0

* Issue 8 - support removal of intermediate containers
* Issue 11 - correct spelling in README.md
* Issue 12 - added skip option
