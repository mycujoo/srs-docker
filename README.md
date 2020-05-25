# SRS Docker

Forked from ossrs/srs-docker

## Building
```sh
$ docker build -t mycujoo/srs:<tag> . && docker push <tag>
```

Change `tag` or `url` ARG for changing the branch or source of the repo.

## Builds
- `mycujoo/srs:3-cidr-cerevo` -> build with branch 3.0release of the fork mycujoo/srs with CIDR and Cerevo fixes.