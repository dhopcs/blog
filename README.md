# blog

This is the source for my personal blog: [dhopcs.org](https://dhopcs.org) and [posts.dhopcs.org](https://posts.dhopcs.org). It is built with [Zola](https://www.getzola.org/).

## Building

To build the site, you need to have [Zola installed](https://www.getzola.org/documentation/getting-started/installation/) then run:

```
zola build
```
which will build the static files into the `public` directory.

I use [nginx](https://www.nginx.com/) to serve the static files. The `nginx.conf` file contains the configuration used for the server.
