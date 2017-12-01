Easily start and stop docker compose projects with captain.

## Usage

Captain searches for directories containing `docker-compose.yml` files and allows you to start and stop those services by passing a part of the parent directory name.

### Starting a project

If I have a folder called `my-project` that contains a `docker-compose.yml` file, I can start the services using:

```
captain start my-project
```

### Stopping a project

Stopping a project works similarly:

```
captain stop my-project
```
