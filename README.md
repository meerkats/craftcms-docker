[![Docker Hub; wyveo/craftcms-docker](https://img.shields.io/badge/docker%20hub-wyveo%2Fcraftcms--docker-blue.svg?&logo=docker&style=for-the-badge)](https://hub.docker.com/r/wyveo/craftcms-docker/) [![License MIT](https://img.shields.io/badge/license-MIT-blue.svg?&style=for-the-badge)](https://github.com/wyveo/nginx-php-fpm/blob/master/LICENSE)

## Introduction

This is a [Craft 3](https://craftcms.com/3) base running on the [nginx-php-fpm](https://hub.docker.com/r/wyveo/nginx-php-fpm/) docker image.

#### Versioning

| Docker Tag | Git Branch | Craft Release | Database        | Caching     |
| ---------- | ---------- | ------------- | --------------- | ----------- |
| latest     | craft3     | 3.3.15        | PostgreSQL 11.5 | Redis 5.0.6 |

Features:

- Nginx 1.17.x, PHP-FPM 7.3.x, Git 2.11.0
- imageMagick image manipulation library

## Clone repo and run

#### [![version craft3](https://img.shields.io/badge/version-Craft%203-red.svg?&style=for-the-badge)](https://craftcms.com/3) [![](https://img.shields.io/microbadger/image-size/wyveo/craftcms-docker/craft3.svg?&style=for-the-badge)](https://microbadger.com/images/wyveo/craftcms-docker) [![](https://img.shields.io/microbadger/layers/wyveo/craftcms-docker/craft3.svg?&style=for-the-badge)](https://microbadger.com/images/wyveo/craftcms-docker)

```
$ git clone https://github.com/wyveo/craftcms-docker.git
$ cd craftcms-docker
$ docker-sync-stack start
```

navigate to `http://<HOSTNAME>/index.php?p=admin` to begin installing Craft 3.
NOTE: if the above url doesn't work, try navigating to `http://<HOSTNAME>/admin/install` instead.
