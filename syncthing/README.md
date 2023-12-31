Create a [Syncthing](https://syncthing.net/) jail, exposing the service on the host.

e.g., assuming these templates are in your `/usr/local/bastille/templates` dir
```sh
$ sudo bastille create syncthing 14.0-RELEASE 10.0.1.200
$ sudo bastille template syncthing dcreemer/syncthing
```
