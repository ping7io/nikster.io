# nikster.io website

This repository holds the content for the `nikster.io` website.

## Running the website locally

```bash
$ docker build -t ping7-docs .
$ docker run -p 4000:4000 \
    -v $(pwd):/usr/src/app ping7-docs jekyll serve --watch
```
