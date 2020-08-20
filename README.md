⚠️ https://pulsar.dedis.ch has been discontinued. The project has now its own website and organization: https://drand.love/, https://github.com/drand.

# Sources of the Pulsar Website
See [https://pulsar.dedis.ch](https://pulsar.dedis.ch).

## Requirements

- [golang](https://golang.org/)
- [hugo](https://gohugo.io/)
- [make](https://www.gnu.org/software/make/)
- [rsync](https://rsync.samba.org/)

## Development and Deployment

Run a local server at [http://127.0.0.1:1313](http://127.0.0.1:1313):

```
make server
```

Build the site:

```
make build
```

Deploy the site:

```
make deploy
```
