# How to deploy the Hello World Java app

## Build the application

First, use the following command to download all of the dependencies and create the application for deploying.

### Mac OS X, Unix, or Linux

```bash
./mvnw compile
./mvnw package
```

## Windows

```powershell
.\mvnw.cmd compile
.\mvnw.cmd package
```

## Deploy the application

Then follow the usual process for deploying

```bash
cf push
```

<!-- Auto-update: 2025-10-16T11:42:28.758710 -->
