<!--
SPDX-FileCopyrightText: NOI Techpark <digital@noi.bz.it>

SPDX-License-Identifier: CC0-1.0
-->

Replace all `ToDo` notes with the appropriate names, descriptions and commands.

# ToDo: Project Name

ToDo: Description of the project.

ToDO: Replace hugo-boilerplate with your project name in the badge links

![REUSE Compliance](https://github.com/noi-techpark/hugo-boilerplate/actions/workflows/reuse.yml/badge.svg)
[![CI/CD](https://github.com/noi-techpark/hugo-boilerplate/actions/workflows/main.yml/badge.svg)](https://github.com/noi-techpark/hugo-boilerplate/actions/workflows/main.yml)

## Table of contents

- [Gettings started](#getting-started)
- [Deployment](#deployment)
- [Docker environment](#docker-environment)
- [Information](#information)

## Getting started

These instructions will get you a copy of the project up and running
on your local machine for development and testing purposes.

### Prerequisites

To build the project, the following prerequisites must be met:

- [Hugo](https://gohugo.io/)

If you don't want to install all prerequisites directly on your machine and instead use a Docker environment with all prerequisites already installed and configured, you can check out the [Docker environment](#docker-environment) section.

### Source code

Get a copy of the repository:

```bash
ToDo: git clone git@github.com:noi-techpark/hugo-boilerplate.git
```

Change directory:

```bash
ToDo: cd hugo-boilerplate
```

### Development

To start a local webserver that serves the project, simply run the following command:

```bash
hugo server -s src
```

The website will be available at [http://127.0.0.1:1313](http://127.0.0.1:1313). It also recompiles automatically if you make any change to the source code.

## Deployment

To deploy the website, simply run the command `hugo -s src -d ../target` from the root folder of the project. The final version of the website will then be generate inside the `target` folder.

## Docker environment

For the project a Docker environment is already prepared and ready to use with all necessary prerequisites.

These Docker containers are the same as used by the continuous integration servers.

### Installation

Install [Docker](https://docs.docker.com/install/) (with Docker Compose) locally on your machine.

### Start and stop the containers

Before start working you have to start the Docker containers:

```
docker-compose up --build --detach
```

The website will be available at [http://127.0.0.1:1313](http://127.0.0.1:1313). It also recompiles automatically if you make any change to the source code.

After finished working you can stop the Docker containers:

```
docker-compose stop
```

## Information

### Support

ToDo: For support, please contact [info@opendatahub.bz.it](mailto:info@opendatahub.bz.it).

### Contributing

If you'd like to contribute, please follow the following instructions:

https://docs.opendatahub.bz.it/en/latest/guidelines/contributors.html

### Documentation

More documentation can be found at [https://opendatahub.readthedocs.io/en/latest/index.html](https://opendatahub.readthedocs.io/en/latest/index.html).

### Boilerplate

The project uses this boilerplate: [https://github.com/noi-techpark/hugo-boilerplate](https://github.com/noi-techpark/hugo-boilerplate).

### License

The code in this project is licensed under the GNU AFFERO GENERAL PUBLIC LICENSE Version 3 license. See the [LICENSE.md](LICENSE.md) file for more information.
