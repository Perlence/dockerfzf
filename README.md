dockerfzf
=========

*dockerfzf* is a simple script to select Docker containers and images with [fzf](https://github.com/junegunn/fzf.vim) for bulk operations.


# Usage

```
dockerfzf COMMAND... [DOCKER_ARG...]
```

* `dockerfzf {stop,kill}` Select and stop/kill containers by their ID.

* `dockerfzf {start,rm,attach,logs}` Select and start/rm/attach/log containers by their ID.

* `dockerfzf inspect` Select and inspect container by its ID.

* `dockerfzf inspecti` Select and inspect image by its ID.

* `dockerfzf rmi` Select and remove images by their ID.

* `dockerfzf rmt` Select and remove images by their tags.

* `dockerfzf volume rm` Select and remove volumes by their ID.

* `dockerfzf volume inspect` Select and inspect volume by its ID.

* `dockerfzf network rm` Select and remove networks by their ID.

* `dockerfzf network inspect` Select and inspect network by its ID.


# Examples

Force remove containers:

```
dockerfzf rm -f
```
