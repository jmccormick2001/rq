---
description: A Kubernetes operator for the rqlite database.
---

# rqlite-operator

## Getting Started

You can install the rqlite-operator as follows:

```
$ make setup
$ make install
$ make test
```

 This example above assumes you have a working k8s cluster available and you are running as a cluster-admin user.

Verify the rqlite-operator is running and a sample rqlite deployment of 3 nodes is running:

```text
$ kubectl -n rq get deployment
$ kubectl -n rq get pod
```

## Documentation
[Design](https://jmccormick2001.github.io/rqlite-operator/docs/design)
[Building from Source](https://jmccormick2001.github.io/rqlite-operator/docs/building-from-source)
