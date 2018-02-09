# gearmand

Forked from [artefactual-labs/docker-gearmand](https://github.com/artefactual-labs/docker-gearmand) and added `Postgres` backend

`crestone/gearmand` packages recent versions of gearmand using Alpine Linux as the base image.

## Supported tags and respective `Dockerfile` links

- [`1.1.18-alpine`, `latest` (*Dockerfile*)](https://github.com/crestone/docker-gearmand/tree/1.1.18/Dockerfile)

See also the [official releases](https://github.com/gearman/gearmand/releases) page.

## Supported gearmand backends

- `builtin` (default)
- `postgres`

To be added: `libmemcached` (see related [issue](https://bugs.alpinelinux.org/issues/7065)).

## Usage

Print help:

```bash
docker run --rm -i crestone/gearmand:latest --help
```
