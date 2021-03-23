# Windows virtual desktop sandbox

This repo contains an example how to run a Windows virtual desktop on Instruqt.

This track uses a Windows Server 2019 VM: [`instruqt/windows-server`](https://github.com/instruqt/packer-windows-server), and an Alpine container that is used as a proxy for running challenge lifecycle scripts and terminal access.

## RDP via Guacamole

This track uses a Guacamole container (`gcr.io/instruqt/guacamole`, see [`config.yml`](config.yml)) to provide RDP access to the windows host. In the [setup script](sandbox/setup-guac) it injects the necessary Guacamole configuration. And the RDP session is exposed through a service tab in the `track.yml`:

```
slug: windows-desktop
...
challenges:
  ...
  tabs:
  - title: RDP
    type: service
    hostname: guac
    path: /#/client/c/windows?username=instruqt&password=Passw0rd!
    port: 8080
...
```
