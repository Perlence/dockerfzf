dockerfzf
=========

*dockerfzf* is a simple script to select Docker containers and images with [fzf](https://github.com/junegunn/fzf.vim) for bulk operations.


# Usage

```
dockerfzf COMMAND... [DOCKER_ARG...]
```

* `dockerfzf {kill,pause,restart,stop,unpause,update}` Select running containers and perform an action.

* `dockerfzf {rm,start}` Select containers and perform an action.

* `dockerfzf {attach,logs,port,top}` Select a containers and perform an action.

* `dockerfzf inspect` Select and inspect a container.

* `dockerfzf rmi` Select and remove images by their ID.

* `dockerfzf rmt` Select and remove images by their tags.

* `dockerfzf image inspect` Select and inspect an image.

* `dockerfzf network inspect` Select and inspect a network.

* `dockerfzf network rm` Select and remove networks.

* `dockerfzf node {demote,promote,ps,rm,update}` Select nodes and perform an action.

* `dockerfzf node inspect` Select and inspect a node.

* `dockerfzf service create` Select an image and create a service from it.

* `dockerfzf service {logs,ps,rm,update}` Select services and perform an action.

* `dockerfzf service inspect` Select and inspect a service.

* `dockerfzf stack {ps,rm,services}` Select stacks and perform an action.

* `dockerfzf volume inspect` Select and inspect a volume.

* `dockerfzf volume rm` Select and remove volumes.


# Examples

Force remove containers:

```
dockerfzf rm -f
```
