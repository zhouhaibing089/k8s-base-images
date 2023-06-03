k8s-build-image
===============

The build images published by kubernetes community eventually are going to be
vulnerable to various of CVEs, yet it is not always obvious on how they should
be patched properly. This is an attempt to provide continuous support to fix
CVEs from unsupported kubernetes releases.

The following images are updated via automation daily:

```
ghcr.io/zhouhaibing089/k8s/build-image/go-runner:v2.3.1-go1.16.15-buster.0
ghcr.io/zhouhaibing089/k8s/build-image/debian-base:buster-v1.9.0
ghcr.io/zhouhaibing089/k8s/build-image/setcap:buster-v2.0.4
ghcr.io/zhouhaibing089/k8s/build-image/debian-iptables:buster-v1.6.7
```
