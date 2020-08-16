# My website

My personal website I've created using Jekyll and Github Pages! It can be viewed at [here](https://burrt.github.io/).

## Cloning

```bash
$ git clone https://github.com/burrt/burrt.github.io.git
```

## Building

You can build and host the pages locally - first setup [Jekyll](https://jekyllrb.com/docs/) in your local environment.

### Linux

```bash
$ bundle install
$ bundle exec jekyll serve
```

### Windows

#### Docker

```powershell
# Powershell
PS> docker run `
    --rm `
    --label=jekyll `
    --volume=${pwd}:/srv/jekyll `
    -it -p 4000:4000 jekyll/jekyll `
    jekyll serve `
        --force_polling `
        --config _config.yml,_config_development.yml
```

Or alternatively, run the Powershell script `.\RunDocker.ps1`.
