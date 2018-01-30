# Example Fastlane Configuration

This repo contains an example configuration for Fastlane. Most of the configuration options are
read from the environment, feel free to use a `.env` file or set the values directly on your CI
server (`BUILD_NUMBER` is usually already set for you to use on Jenkins).

## Building An App

Run the following command to build an app:

```
bundler exec fastlane ios release
```

## Generating A Provisioning Profile For Debug Installs

```
bundler exec fastlane ios development
```