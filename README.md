# My website

My personal website I've created using Jekyll and Github Pages - it can be viewed [here!](https://burrt.github.io/)

## Cloning

```bash
$ git clone https://github.com/burrt/burrt.github.io.git
```

## Getting Started

### Docker

```bash
$ docker-compose up
```

### Linux

You can build and host the pages locally - first setup [Jekyll](https://jekyllrb.com/docs/) in your local environment. I do recommend using Docker.

```bash
$ bundle install
$ bundle exec jekyll serve
```

## Upgrading Gems

To test upgrading of the Gems for either new features and/or security vulnerabilities:

```bash
$ bundle update github-pages
```

### Docker

Best to un-comment out the section in the `docker-compose.yml`
