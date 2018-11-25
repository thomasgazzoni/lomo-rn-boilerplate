The config file (index.ts) is generated by:

- the [build-config.sh](../../scripts/build-config.sh) script called during the postinstall (after yarn or npm install) using some example data.
- the [appcenter-post-clone.sh](../../appcenter-post-clone.sh) script, when run a build using the appcenter branch custom Environment variables configuration.

Environment variable that can be shared between development and production can be added in the [common environment file](./common.ts)