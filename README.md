# dokku-ghostscript

dokku-ghostscript is an awesome plugin for [dokku][dokku] that properly installs the ghostscript into the docker instance.

## Installation

On your dokku server:
```sh
# On 0.3.x
git clone https://github.com/Zhang/dokku-ghostscript /var/lib/dokku/plugins/dokku-ghostscript

# On 0.4.x
dokku plugin:install https://github.com/Zhang/dokku-ghostscript.git ghostscript
```

All future deployments will have ghostscript installed.
