[![Gradle Build Scan](https://github.com/ajaychinthapalli/gradle-build-scan/actions/workflows/main.yaml/badge.svg)](https://github.com/ajaychinthapalli/gradle-build-scan/actions/workflows/main.yaml)

# gradle-build-scan
A sample repository to experience the Build Scan™ service of Gradle Enterprise with Gradle builds.

## Create a Build Scan™

Create and publish a Build Scan™ on `scans.gradle.com`:

1. Run `./gradlew build --scan`
```text
./gradlew build --scan

BUILD SUCCESSFUL in 9s
4 actionable tasks: 4 executed

Publishing a build scan to scans.gradle.com requires accepting the Gradle Terms of Service defined at https://gradle.com/terms-of-service. Do you accept these terms? [yes, no] yes

Gradle Terms of Service accepted.

Publishing build scan...
https://gradle.com/s/v25fieytc3o5o
```
![build-scan-summary.png](images%2Fbuild-scan-summary.png)