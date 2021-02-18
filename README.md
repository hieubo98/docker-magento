<h1 align="center">nguyentrunghieu98/docker-magento</h1
  
  
  
#### For more details on how everything works, see the extended [Setup readme](https://github.com/markshust/docker-magento/blob/master/SETUP.md).  

#### Project Setup

- [Setup readme](https://github.com/nguyentrunghieu98/docker-magento/blob/master/SETUP.md)

#### Helper Scripts

- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9064258" target="_blank">Run CLI commands within containers</a>
- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9331008" target="_blank">Stop, start & restart containers</a>
- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9064269" target="_blank">Run binaries within containers</a>

#### Docker Filesystem & Volumes

- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9064334" target="_blank">Understand volumes & host bind mounts</a>
- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9064338" target="_blank">Manage files & folders on containers</a>

#### Customize Server Configuration

- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9064349" target="_blank">Customize the Nginx configuration</a>
- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9064356" target="_blank">Quickly switch PHP versions</a>
- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9064350" target="_blank">Install extensions & packages</a>
- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9064477" target="_blank">Run additional services as containers</a>
- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/14780970" target="_blank">Configure multi-store instances</a>

#### PHPStorm & Xdebug

- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9748834" target="_blank">Setup PHPStorm for a Magento Docker project</a>
- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9763893" target="_blank">Generate XML URNs for a Magento Docker project</a>
- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9064478" target="_blank">Install Xdebug browser plugin</a>
- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9064482" target="_blank">Enable, disable, & check Xdebug</a>
- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9064615" target="_blank">Configure PHPStorm for Xdebug</a>
- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9064617" target="_blank">Trigger Xdebug breakpoints with PHPStorm</a>

#### Manual Setup (Optional)

- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9064259" target="_blank">Manual setup for new Magento installs</a>
- <a href="https://courses.m.academy/courses/setup-magento-2-development-environment-docker/lectures/9283467" target="_blank">Manual setup for an existing Magento instance</a>

## Docker Hub

View Dockerfiles:

- [markoshust/magento-nginx (Docker Hub)](https://hub.docker.com/r/markoshust/magento-nginx/)
  - 1.18
      - [`1.18`, `1.18-4`](https://github.com/markshust/docker-magento/tree/master/images/nginx/1.18)
      - [`1.18-3`](https://github.com/markshust/docker-magento/tree/34.0.0/images/nginx/1.18)
      - [`1.18-2`](https://github.com/markshust/docker-magento/tree/33.0.0/images/nginx/1.18)
      - [`1.18-1`](https://github.com/markshust/docker-magento/tree/31.0.1/images/nginx/1.18)
      - [`1.18-0`](https://github.com/markshust/docker-magento/tree/31.0.0/images/nginx/1.18)
- [markoshust/magento-php (Docker Hub)](https://hub.docker.com/r/markoshust/magento-php/)
  - 7.4
      - [`7.4-fpm`, `7.4-fpm-2`](https://github.com/markshust/docker-magento/tree/master/images/php/7.4)
      - [`7.4-fpm-1`](https://github.com/markshust/docker-magento/tree/34.1.0/images/php/7.4)
      - [`7.4-fpm-0`](https://github.com/markshust/docker-magento/tree/33.0.0/images/php/7.4)
  - 7.3
      - [`7.3-fpm`, `7.3-fpm-9`](https://github.com/markshust/docker-magento/tree/master/images/php/7.3)
      - [`7.3-fpm-8`](https://github.com/markshust/docker-magento/tree/34.1.0/images/php/7.3)
      - [`7.3-fpm-7`](https://github.com/markshust/docker-magento/tree/33.0.0/images/php/7.3)
      - [`7.3-fpm-6`](https://github.com/markshust/docker-magento/tree/32.0.1/images/php/7.3)
      - [`7.3-fpm-5`](https://github.com/markshust/docker-magento/tree/30.0.0/images/php/7.3)
      - [`7.3-fpm-4`](https://github.com/markshust/docker-magento/tree/29.0.0/images/php/7.3)
      - [`7.3-fpm-3`](https://github.com/markshust/docker-magento/tree/28.0.0/images/php/7.3)
      - [`7.3-fpm-2`](https://github.com/markshust/docker-magento/tree/27.2.0/images/php/7.3)
      - [`7.3-fpm-1`](https://github.com/markshust/docker-magento/tree/26.0.0/images/php/7.3)
      - [`7.3-fpm-0`](https://github.com/markshust/docker-magento/tree/24.2.0/images/php/7.3)
- [markoshust/magento-elasticsearch (Docker Hub)](https://hub.docker.com/r/markoshust/magento-elasticsearch/)
  - 7
      - [`7.6`, `7.6.2-2`](https://github.com/markshust/docker-magento/tree/master/images/elasticsearch/7.6)
      - [`7.6.2-1`](https://github.com/markshust/docker-magento/tree/32.0.0/images/elasticsearch/7.6)
      - [`7.6.2-0`](https://github.com/markshust/docker-magento/tree/31.0.2/images/elasticsearch/7.6)

## Usage

This configuration is intended to be used as a Docker-based development environment for Magento 2.

Folders:

- `images`: Docker images for nginx and php
- `compose`: sample setups with Docker Compose

> The Magento 1 version of this development environment has been deprecated and is no longer supported. PHP 5 was used as it's base, and that version has reached end-of-life. If you still wish to use this setup, please reference [compose/magento-1 on tag 20.1.1](https://github.com/markshust/docker-magento/tree/20.1.1/compose/magento-1), but please be aware these images are no longer maintained.

## Prerequisites

This setup assumes you are running Docker on a computer with at least 4GB of allocated RAM, a dual-core, and an SSD hard drive. [Download & Install Docker Desktop](https://www.docker.com/products/docker-desktop).

This configuration has been tested on Mac & Linux. Windows is supported through the use of Docker on WSL.

## Setup

- For more details on how everything works, see the extended [Setup readme](https://github.com/markshust/docker-magento/blob/master/SETUP.md).  

## Custom CLI Commands

- `bin/bash`: Drop into the bash prompt of your Docker container. The `phpfpm` container should be mainly used to access the filesystem within Docker.
- `bin/cli`: Run any CLI command without going into the bash prompt. Ex. `bin/cli ls`
- `bin/clinotty`: Run any CLI command with no TTY. Ex. `bin/clinotty chmod u+x bin/magento`
- `bin/composer`: Run the composer binary. Ex. `bin/composer install`
- `bin/copyfromcontainer`: Copy folders or files from container to host. Ex. `bin/copyfromcontainer vendor`
- `bin/copytocontainer`: Copy folders or files from host to container. Ex. `bin/copytocontainer --all`
- `bin/dev-urn-catalog-generate`: Generate URN's for PHPStorm and remap paths to local host. Restart PHPStorm after running this command.
- `bin/devconsole`: Alias for `bin/n98-magerun2 dev:console`
- `bin/download`: Download & extract specific Magento version to the `src` directory. If the archive download fails, it will attempt to download with Composer. Ex. `bin/download 2.4.1`.
- `bin/fixowns`: This will fix filesystem ownerships within the container.
- `bin/fixperms`: This will fix filesystem permissions within the container.
- `bin/grunt`: Run the grunt binary. Ex. `bin/grunt exec`
- `bin/magento`: Run the Magento CLI. Ex: `bin/magento cache:flush`
- `bin/mysql`: Run the MySQL CLI with database config from `env/db.env`. Ex. `bin/mysql -e "EXPLAIN core_config_data"` or`bin/mysql < backups/magento.sql`
- `bin/mysqldump`: Backup the Magento database. Ex. `bin/mysqldump > backups/magento.sql`
- `bin/n98-magerun2`: Access the n98 magerun CLI. Ex: `bin/n98-magerun2 dev:console`
- `bin/node`: Run the node binary. Ex. `bin/node --version`
- `bin/npm`: Run the npm binary. Ex. `bin/npm install`
- `bin/pwa-studio`: (BETA) Start the PWA Studio server. Note that Chrome will throw SSL cert errors and not allow you to view the site, but Firefox will.
- `bin/redis`: Run a command from the redis container. Ex. `bin/redis redis-cli monitor`
- `bin/remove`: Remove all containers.
- `bin/removeall`: Remove all containers, networks, volumes, and images.
- `bin/removevolumes`: Remove all volumes.
- `bin/restart`: Stop and then start all containers.
- `bin/root`: Run any CLI command as root without going into the bash prompt. Ex `bin/root apt-get install nano`
- `bin/rootnotty`: Run any CLI command as root with no TTY. Ex `bin/rootnotty chown -R app:app /var/www/html`
- `bin/setup`: Run the Magento setup process to install Magento from the source code, with optional domain name. Defaults to `magento2.test`. Ex. `bin/setup magento2.test`
- `bin/setup-grunt`: Install and configure Grunt JavaScript task runner to compile .less files
- `bin/setup-pwa-studio`: (BETA) Install PWA Studio (requires NodeJS and Yarn to be installed on the host machine). Pass in your base site domain, otherwise the default `master-7rqtwti-mfwmkrjfqvbjk.us-4.magentosite.cloud` will be used. Ex: `bin/setup-pwa-studio magento2.test`
- `bin/setup-ssl`: Generate an SSL certificate for one or more domains. Ex. `bin/setup-ssl magento2.test magento3.test`
- `bin/setup-ssl-ca`: Generate a certificate authority and copy it to the host.
- `bin/start`: Start all containers, good practice to use this instead of `docker-compose up -d`, as it may contain additional helpers.
- `bin/status`: Check the container status.
- `bin/stop`: Stop all containers.
- `bin/update`: Update your project to the most recent version of `docker-magento`.
- `bin/xdebug`: Disable or enable Xdebug. Accepts params `disable` (default) or `enable`. Ex. `bin/xdebug enable`

## Misc Info

### Database

The hostname of each service is the name of the service within the `docker-compose.yml` file. So for example, MySQL's hostname is `db` (not `localhost`) when accessing it from within a Docker container. Elasticsearch's hostname is `elasticsearch`.

To connect to the MySQL CLI tool of the Docker instance, run:
