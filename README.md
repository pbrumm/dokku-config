dokku-config
============

heroku-like configuration handling for dokku

Project: https://github.com/progrium/dokku

Installation
------------
```
cd /var/lib/dokku/plugins
git clone https://github.com/josegonzalez/dokku-config config
dokku plugins-install
```


Commands
--------
```
$ dokku help
     config <app>                    List all environment variables
     config:get <app>                List a specific environment variable
     config:set <app> <key> <value>  Set an environment variable
     config:unset <app> <key>        Unset an environment variable
```

TODO
----

- Add support for `config:set key=value` calls
- Add support for setting multiple values via `config:set`
- Properly restart dokku instances after setting/unsetting environment variables
- Test this against a real dokku instance
