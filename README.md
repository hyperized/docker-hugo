# Hugo docker container

* Based on latest Alpine.
* Updated monthly.
* With Sass support.

## Usage

Run like:

```shell script
docker run --rm -v $(pwd):/project hyperized/hugo new site quickstart
```

The default `WORKDIR` is set to `/project` but can be changed by adding and modifying:

```shell script
-w /project
```

https://hub.docker.com/r/hyperized/hugo