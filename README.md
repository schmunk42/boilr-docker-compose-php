## What is this?

Boilr is a tool for generating your projects boilerplate files. This template repository provides templates for generating docker-compose.yml for PHP projects.

These templates are configued based on MY personal opinion on how docker-compose works best for PHP projects

After the YAML files are generated, you may need to tweak slightly (Node entrypoint, etc)

**These templates will get smarter when boilr advances**
see: https://github.com/tmrts/boilr/issues/9 and https://github.com/tmrts/boilr/issues/10

## Installation

### Install boilr

1. Download the latest binary from: https://github.com/tmrts/boilr/releases
2. Run `boilr init` to set it up

### Install this template

`boilr template download rawkode/boilr-docker-compose-php dockercomposephp`

## Use this template

`boilr template use dockercomposephp <project name>`

