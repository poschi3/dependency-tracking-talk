# Dependency Tracking
## Maven
* mvn dependency:tree
* mvn dependency:analyze

## OWASP Plugin
* mvn org.owasp:dependency-check-maven:aggregate
* Output:
    * Console
    * Site
* Have to look / break build
* Ignoring a problem
* Sometimes slow

## SBOM / CycloneDX

* https://owasp.org/www-project-cyclonedx/
* Standard format

## Dependency Track
* Store SBOM!
* https://dependencytrack.org/
* https://github.com/DependencyTrack/dependency-track

* Additional sources (Github)

### Fix advisories
* Problem: https://github.com/advisories/GHSA-6x3v-rw2q-9gx7
* Fix: https://github.com/github/advisory-database/pull/1837

## No excuse