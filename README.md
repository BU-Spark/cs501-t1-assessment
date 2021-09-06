# Flask JWT Auth

## Quick Start

### Basics

1. Activate a virtualenv
1. Install the requirements

### Set Environment Variables

Update *project/server/config.py*, and then run:

```sh
$ export FLASK_APP=project.server
$ export APP_SETTINGS="project.server.config.DevelopmentConfig"
```

or

```sh
$ export FLASK_APP=project.server
$ export APP_SETTINGS="project.server.config.ProductionConfig"
```

Create the tables and run the migrations:

```sh
$ flask db init
$ flask db migrate
$ flask db upgrade
```

### Run the Application

```sh
$ flask run
```

So access the application at the address [http://localhost:5000/](http://localhost:5000/)

> Want to specify a different port?

> ```sh
> $ flask run --host=0.0.0.0 --port=5000
> ```
