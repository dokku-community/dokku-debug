# dokku-debug

Toggle tracing etc.

## Installation

```bash
cd /var/lib/dokku/plugins
sudo git clone git@github.com:heichblatt/dokku-debug.git debug
sudo dokku plugins-install
```

## Usage

Show current setting
```bash
debug
´´´

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