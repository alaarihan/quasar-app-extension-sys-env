# System Environment Variables (quasar-app-extension-system-environment-variables)

[![npm version](https://badge.fury.io/js/quasar-app-extension-sys-env.svg)](https://badge.fury.io/js/quasar-app-extension-sys-env)

====
> Load environment variables from the system and makes them available through process.env. Works best for building on CI/CD environments

In some scenarios like when working in a CI environment where we might want to load environment variables from the system variables instead of an .env file. This plugin will handle loading system variables as long as they are present in the .env.example file.


## Install

```bash
quasar ext add sys-env
```

Quasar CLI will retrieve it from NPM and install the extension.

## Uninstall

```bash
quasar ext remove sys-env
```

## Info

You need to setup a `.env.example` file which can work as a dictionary so the plugin knows which variables to look for and load from the system environment, plus it works as a guide for other users letting them know which variables are available.
