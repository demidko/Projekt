## `Service`

Kotlin microservice template produces self-executable jar application. For brevity, double-space
formatting is used. [`Clikt`](https://ajalt.github.io/clikt/whyclikt/) is included for parsing
command line arguments. [`Ktor`](https://ktor.io/) is included to mock Digital Ocean healthy checks.

### Usage

Make sure you are signed in to your GitHub account, then just click [`here`](https://github.com/demidko/service/generate) to use template.

### Build

Run command `./gradlew clean test shadowJar`.  
<sup>Small text</sup>
_After that, the jar application will appear in the in the repository and you can start it with the `java -jar *.jar` command._

### Deploy to the cloud

[![Deploy to DigitalOcean](https://www.deploytodo.com/do-btn-blue.svg)](https://cloud.digitalocean.com/apps/new?repo=https://github.com/demidko/service/tree/main)



