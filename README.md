# Ghost on Render

This is a template repository for running [Ghost](https://ghost.org) on Render.

* It uses the official [Ghost Docker image](https://hub.docker.com/_/ghost).

* It uses [Render Disks](https://render.com/docs/disks) for permanent SSD storage for uploaded files and content.

* It supports [MySQL](https://render.com/docs/deploy-mysql) as the backing database for Ghost.

**Note**: As of Ghost 5.0, MySQL 8 is the only supported database, according to the [Ghost changelog](https://ghost.org/docs/changes/). SQLite is only supported in development environments, NOT in production.


## Deployment

See https://render.com/docs/deploy-ghost.
