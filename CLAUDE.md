# CLAUDE.md

Jenkins plugin for uploading Android, iOS, and macOS apps to Microsoft AppCenter.

## Stack
- Java 8
- Kotlin 1.4.10
- Maven
- Jenkins plugin framework (2.222.3+)
- Retrofit2 for API communication
- Azure Storage SDK for artifact uploads

## Build & Test
```bash
mvn clean verify
mvn hpi:run  # local Jenkins instance on http://localhost:8080/jenkins
```

## Notes
- Uses Dagger for dependency injection
- Kotlin-based implementation with Java interop
- Supports both pipeline and freestyle jobs
- AppCenter API token required for authentication
