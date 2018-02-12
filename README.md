# jaspajjr.github.io

jekyll

## To generate the site locally:
```
docker run --rm \
        -v "$(pwd):/src" \
        -w /src \
        ruby:2.3 \
        sh -c '
            bundle update \
            bundle install \
            --path vendor/bundle \
            && exec jekyll build --watch'
```

## To build the docker container
```
docker build -t my-shiny-blog .
```

## To run the docker container
```
docker build -t my-shiny-blog .
```