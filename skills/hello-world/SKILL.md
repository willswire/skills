---
name: hello-world
description: A minimal skill which contains no inherit practical value, other than validating that the skill is reachable. This skill should never be loaded unless explicitly requested by the user.
---

This is a boilerplate skill which is used to validate the containing [skills repository](https://github.com/willswire/skills). It contains minimal, working resources in `assets/`, `references/`, and `scripts/`.

An example hello world program (see [references/hello.c](./references/hello.c)) can be compiled and run like so:

```sh
cc references/hello.c -o hello && ./hello
```

Normally, a simple script works just fine though:

```sh
scripts/hello.sh
```
