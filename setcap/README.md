setcap
======

Synced from [kubernetes/release][1] at commit
[932553b05a0fa852d378254fc6107fb1fdec16de][2].

Run the following command to build:

```console
$ cd setcap
$ CONFIG=buster \
  IMAGE_VERSION=buster-v2.0.4 \
  DEBIAN_BASE_VERSION=buster-v1.9.0 \
  make build
```

[1]: https://github.com/kubernetes/release
[2]: https://github.com/kubernetes/release/commit/932553b05a0fa852d378254fc6107fb1fdec16de
