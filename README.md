# Wordpress Development

## Features

* LEMP stack for wordPress using [Trellis](https://github.com/roots/trellis)
* WP Boilerplate using [Bedrock](https://github.com/roots/bedrock)
* Manage database uplooads and migration using  [trellis-database-uploads-migration](https://github.com/valentinocossar/trellis-database-uploads-migration)

## Development Process

1. CLone this repo recursively
2. [Install](https://roots.io/trellis/docs/installing-trellis/) LEMP stack and setup WordPress
3. copy .yml files from `trellis-database-uploads-migration` into `trellis`
4. copy .sh file from `trellis-database-uploads-migration` into `trellis/bin`
4. Clone [theem boilerplate](https://github.com/ljsherlock/wp-boilerplate)

## Deployment

```sh
./bin/deploy.sh production [example.com]
```

## DB Upload and Migration
```sh
 sh./bin/database.sh [environment] [site name] [push/pull]
 ```
```sh
 ./bin/uploads.sh [environment] [site name] [push/pull]
 ```
