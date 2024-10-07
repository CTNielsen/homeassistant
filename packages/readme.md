# Packages

A small variaty of packages I've shared with people from my own setup.

Everything here is created as packages and needs to be added in HA as so.

Configuration example with a folder named 'packages' in the same directory as `configuration.yaml`
```
homeassistant:
  packages: !include_dir_named packages
```
