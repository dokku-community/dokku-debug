# dokku-debug [![Build Status](https://img.shields.io/travis/dokku-community/dokku-debug.svg?branch=master "Build Status")](https://travis-ci.org/josegonzalez/dokku-debug)

Manage dokku trace mode

## requirements

- dokku 0.4.0+
- docker 1.8.x

## Installation

```bash
# on 0.4.x
dokku plugin:install https://github.com/josegonzalez/dokku-debug.git debug
```

## commands

```shell
dokku debug            Displays the current trace status
dokku debug:off        Deactivate trace mode
dokku debug:on         Activate trace mode
dokku debug:toggle     Toggle trace mode
```

## Usage

Show current setting

```bash
debug
```

Activate tracing

```bash
debug on
```

Deactivate tracing

```bash
debug off
```

Toggle tracing

```bash
debug toggle
```
