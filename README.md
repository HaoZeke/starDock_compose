# Star Dock [![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg?style=for-the-badge)](https://www.paypal.me/HaoZeke/) 

> Copyright (C) 2017-Present  Rohit Goswami <rohit1995@mail.ru>

## Introduction

A `docker-compose` setup for my dockerized media services.

## Components

Currently should be running:

* Airsonic for music streaming
* Calibre-web for library [ebook] delivery
* Plex for transcoding and delivering videos
* Traefik to rewrite to locations on a single domain
* Watchtower to update your images every 12 hours with email notifications

## Setup

```bash
# Get the repo
git clone http://github.com/HaoZeke/starDock_compose
# Copy and edit the sample .env file
cp .env.sample .env
vim .env
# Run the thing
docker-compose up -d
# Profit
```

## Inspiration

This setup was inspired by:

* [vaeyo's Mediaserver files](https://github.com/vaeyo/MediaServer-DockerComposeFiles)
* [Portrainer docker-compose](https://github.com/portainer/portainer-compose)
* [Linuxserver.io templates](https://github.com/linuxserver/docker-templates)
* [evertamos' dockerportainer with letsencrypt](https://github.com/evertramos/docker-portainer-letsencrypt)

## Licenses

This is technically under the MIT license.
However evertamos' repo is under the GPLv3.