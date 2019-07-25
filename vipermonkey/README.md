Introduction
============
Docker file to run vipermonkey (https://github.com/decalage2/ViperMonkey) from a Docker

Build
=====
$ docker build -t vipermonkey/latest .

Usage
=====
$ docker run --run -v /local/path:/malware vipermonkey/latest [options] <maliciousfile> ...
