# SRS Docker

Forked from ossrs/srs-docker

## Building
```sh
$ docker build -t mycujoo/srs:<tag> . && docker push <tag>
```

Change `tag` or `url` ARG for changing the branch or source of the repo.

## Builds
- `mycujoo/srs:3-cidr-precedence-cerevo` -> build with tag `v3.0` of the fork mycujoo/srs with CIDR and Cerevo fixes.