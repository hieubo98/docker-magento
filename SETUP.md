# Setup

## New Magento 2 Project (macOS/Linux)

1. Create the project template by going to the place you want the new project (ex. cd ~/Sites/magento2), then run
	- `curl -s https://raw.githubusercontent.com/markshust/docker-magento/master/lib/template | bash`

2. Extract the contents of your current Magento site to the `src` folder, or download a fresh copy of the Magento source code for starting a new project with:
    - `bin/download 2.3.0`

3. Add an entry to your local hosts file with your custom domain. Assuming the domain you want to setup is `magento2.test`, enter the below. Be sure to use a `.test` tld, as `.localhost` and `.dev` will present issues with domain resolution.
    - `echo "127.0.0.1 magento2.test" | sudo tee -a /etc/hosts`

4. Start your Docker containers with the provided helper script:
    - `bin/start`

5. For new projects: run Magento's setup install process with the below helper script. Feel free to edit this file to your liking; at the very least you will probably need to update the `base-url` value to the domain you setup in step 3. Also, be sure to setup [Composer Authentication](https://github.com/markshust/docker-magento#composer-authentication) before initiating the setup script.
# Magento Setup Install Commands

Starting in Magento 2.4 Elastic Search is required:
```
bin/clinotty bin/magento setup:install \
  --db-host=db \
  --db-name=magento \
  --db-user=magento \
  --db-password=magento \
  --base-url=https://magentoee241.docker/ \
  --base-url-secure=https://magentoee241.docker/ \
  --backend-frontname=admin \
  --admin-firstname=Admin \
  --admin-lastname=Admin \
  --admin-email=admin@gmail.com \
  --admin-user=admin2 \
  --admin-password=admin@123 \
  --language=en_US \
  --currency=USD \
  --timezone=America/New_York \
  --amqp-host=rabbitmq \
  --amqp-port=5672 \
  --amqp-user=guest \
  --amqp-password=guest \
  --amqp-virtualhost=/ \
  --cache-backend=redis \
  --cache-backend-redis-server=redis \
  --cache-backend-redis-db=0 \
  --page-cache=redis \
  --page-cache-redis-server=redis \
  --page-cache-redis-db=1 \
  --session-save=redis \
  --session-save-redis-host=redis \
  --session-save-redis-log-level=4 \
  --session-save-redis-db=2 \
  --search-engine=elasticsearch7 \
  --elasticsearch-host=elasticsearch \
  --use-rewrites=1
```

For Magento 2.3 installations and below the following will still work:
```
dockergento magento setup:install \
  --db-host=db \
  --db-name=magento \
  --db-user=magento \
  --db-password=magento \
  --base-url=http://magento2.lo/ \
  --admin-firstname=John \
  --admin-lastname=Smith \
  --admin-email=john.smith@gmail.com \
  --admin-user=john.smith \
  --backend-frontname=admin \
  --admin-password=password123 \
  --language=en_US \
  --currency=USD \
  --timezone=America/New_York \
  --use-rewrites=1
```

```
dockergento magento deploy:mode:set developer
```

6. You may now access your site! Check out whatever domain you setup from within a web browser.
    - `open http://magento2.test`

## New Magento 2 Project (Windows)

Works with Docker in WSL. Full instructions to follow.
