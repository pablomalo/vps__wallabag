# vps__wallabag

Save applications for later reading, on the model of Pocket. See https://github.com/wallabag/wallabag

This repo is intended to work in conjunction with https://github.com/pablomalo/vps

## Installation

> Prerequisite: install Traefik using https://github.com/pablomalo/vps

1. Init the submodule from within the parent repo.

2. Copy `.env.dist` to `.env` and `.dbroot.env.dist` to `.dbroot`. Set the environment variables, paying particular attention to those bearing the "Set me" comment.

3. `docker-compose up -d`

## Documentation

* List of available commands: https://symfony.com/doc/current/console.html#running-commands
* Docker: https://github.com/wallabag/docker