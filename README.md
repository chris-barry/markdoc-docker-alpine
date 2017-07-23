# Markdoc Docker Alpine

A docker image for [Markdoc](http://markdoc.org/).
Markdoc is a lightweight Markdown-based wiki system. It’s been designed to allow you to create and manage wikis as quickly and easily as possible.

## Running

Run this to build your site every 5 min.
The HTML of your site will be available in /site/html.


	$ docker run -v /path/to/site:/site:rw chrisbarry/markdoc-docker-alpine:latest

## License

[Unlicense](./LICENSE]
