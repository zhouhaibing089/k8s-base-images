go-runner
=========

Synced from [kubernetes/release][1] at commit
[2d62543e10a3bd33f9dc7114fe689058b5e93545][2].

Run the following command to build:

```console
$ cd go-runner
$ CONFIG=go1.16-buster \
  IMAGE_VERSION=v2.3.1-go1.16.15-buster.0 \
  GO_MAJOR_VERSION=1.16 \
  OS_CODENAME=buster \
  REVISION=0 \
  GO_VERSION=1.16.15 \
  DISTROLESS_IMAGE=static-debian10 \
  REGISTRY=gcr.io/k8s-staging-build-image \
  make container
```

[1]: https://github.com/kubernetes/release
[2]: https://github.com/kubernetes/release/commit/2d62543e10a3bd33f9dc7114fe689058b5e93545
