# docker-http-env-dump
Dumps container env over http


```
$ docker run -d -p 127.0.0.1:8080:8080 -e HELLO=hello hasnat/http-env-dump

$ curl http://127.0.0.1:8080
HOSTNAME=614ce010390a
SHLVL=1
HOME=/root
PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
PWD=/
HELLO=hello

```
