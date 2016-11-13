docker-crosstool-ng
========================
[![License: MIT](http://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/hnw/docker-openwrt-buildroot/blob/master/LICENSE)

This is a docker container for the [crosstool-NG](http://crosstool-ng.org/).

Because the build system requires that its command are not executed by root,
the user `ct-ng` was created.

To run a shell in the crosstool-NG, execute the following command:

```sh
docker run -i -t -u ct-ng yhnw/crosstool-ng:baremetal-rpi2 /bin/bash
```



