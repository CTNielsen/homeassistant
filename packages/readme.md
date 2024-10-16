# Packages

A small variaty of packages I've shared with people from my own setup.

Everything here is created as packages and needs to be added in HA as so.

### Usage
To configure home assistant to use packages add the following lines to the `configuration.yaml` and create the 'packages' folder in the same directory as the configuration file.
```
homeassistant:
  packages: !include_dir_named packages
```
Or see official [Packages](https://www.home-assistant.io/docs/configuration/packages/) documentation
