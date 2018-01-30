# Example Fastlane Configuration

This repo contains an example configuration for Fastlane. Most of the configuration options are
read from the environment, feel free to use a `.env` file or set the values directly on your CI
server (`BUILD_NUMBER` is already set for you to use on Jenkins, other services have their own 
conventions).

## Installing Fastlane

Install Fastlane, it's plugins and dependecies using Bundler:

```
bundle install
```

## Building Your App

Run the following command to build an app:

```
bundler exec fastlane ios release
```

## Generating a Provisioning Profile for Debug Installs

```
bundler exec fastlane ios development
```
