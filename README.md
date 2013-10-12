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
     config <app>                                    display the config vars for an app
     config:get <app> KEY                            display a config value for an app
     config:set <app> KEY1=VALUE1 [KEY2=VALUE2 ...]  set one or more config vars
     config:unset <app> KEY1 [KEY2 ...]              unset one or more config vars
```

TODO
----

- Restart application for each `config:set` call
- Test this against a real dokku instance
