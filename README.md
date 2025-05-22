# Nitin Prajwal's Blog

This is the repository for my personal blog, built with Hugo and the Bootstrap theme.

## About Me

I'm Nitin Prajwal, a software engineer passionate about technology and development. You can find more about my work and projects on [my website](https://nitinr.live).

## Local Development

### Develop via Docker Compose

**1.Install Dependencies**

```sh
$ docker compose run server npm ci
```

> This step is one-time task per machine, unless you deleted the __node_modules__ folder or introduce new dependencies.

**2. Start server**

```sh
$ docker compose up
```

### Develop with Native Tools

**1. Install dependencies**

```shell
$ npm ci
```

Generally, this step only needs to be performed once for each local project.

**2. Start server**

```shell
$ hugo server
```

## Deployment

The site is deployed to [https://blog.nitinr.live/](https://blog.nitinr.live/).

Make sure the `baseURL` in `config/_default/config.yaml` is set correctly before deploying.

For more details on the theme and its features, please refer to the theme documentation.
