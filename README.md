# ng-rnc

[![npm version](https://badge.fury.io/js/ng-rnc.svg)](https://badge.fury.io/js/ng-rnc)
![npm](https://img.shields.io/npm/dm/ng-rnc)
![GitHub](https://img.shields.io/github/license/cmiksche/ng-rn?style=flat)
[![Twitter Follow](https://img.shields.io/twitter/follow/cmiksche?style=social)](https://twitter.com/cmiksche)
[![Mastodon Follow](https://img.shields.io/mastodon/follow/106336578279256330?domain=https%3A%2F%2Fmastodon.social&style=social)](https://mastodon.social/@cmiksche)

This is a fork from the original [ng-rn](https://github.com/rechenberger/ng-rn) which wasn't maintained for the last few years and hasn't merged a fix for newer Angular Versions.

## Rename Angular Components

### One Time Usage
```
  npx ng-rnc old-button fancy-button
```

### Install
```
  npm i -g ng-rnc
```

### Usage
```
  cd /path/to/angular-project/
  ng-rnc old-button fancy-button
```

The Tool looks for the components in `src/app/`. If your components are located in a more complex path like `src/app/my-vip-components`, just change directory:
```
  cd src/app/my-vip-components
  ng-rnc old-button fancy-button
```


