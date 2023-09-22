# Dependency Tracking
## Maven Central OSS Index
* https://central.sonatype.com/
* com.microsoft.graph:microsoft-graph:5.30.0

## Maven
* mvn dependency:analyze
* mvn dependency:tree

## OWASP Plugin
* https://jeremylong.github.io/DependencyCheck/index.html
* mvn org.owasp:dependency-check-maven:aggregate
* Output:
    * Console
    * Site
* Have to look / break build
* Ignoring a problem
* Sometimes slow
* When to run?

## SBOM / CycloneDX

* https://owasp.org/www-project-cyclonedx/
* Standard format

## Dependency Track
* Store SBOM!
* https://dependencytrack.org/
* https://github.com/DependencyTrack/dependency-track
* http://localhost:8080/

* Additional sources (Github)

### Fix advisories
* Problem: https://github.com/advisories/GHSA-6x3v-rw2q-9gx7
* Fix: https://github.com/github/advisory-database/pull/1837

## No excuse