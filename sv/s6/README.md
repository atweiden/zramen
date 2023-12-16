# zramen-s6
To create a service, create a service folder, and copy the configuration.

```sh
  mkdir -p "/etc/s6/sv/zramen"
  cp up /etc/s6/sv/zramen/up
  cp type /etc/s6/sv/zramen/type
  cp down /etc/s6/sv/zramen/down
  cp zramen.conf /etc/s6/config/zramen.conf
```
Adding zramen to autorun.
```sh
  touch /etc/s6/adminsv/default/contents.d/zramen
```
And rebuild the s6 database
```sh
  s6-db-reload
```
And we launch it.
```sh
  s6-rc -u change zramen
```
