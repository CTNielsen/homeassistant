# Packages

A small variaty of packages I've shared with people from my own setup.

Everything here is created as packages and needs to be added in HA as so.

To configure packages add the following lines to the `configuration.yaml` file where 'packages' is a folder in the same directory as the configuration file.
```
homeassistant:
  packages: !include_dir_named packages
```
