# rz_verified_linux_package

This is a documentation sources for [rz_verified_linux_package](https://renesas-rz.github.io/rz_verified_linux_package) website (github.io).

## Prepare environment

Python3 and pip3 are required.

In some case you may need to make a `symlink` to pip (of python3).

### Setup from script

Working directory should be `rz_verified_linux_package/`.

```
. work/setup.sh
```

### Serve local server

Working directory should be `rz_verified_linux_package/`.

```
. serve.sh
```

## Test versioning with `mike`

By default, versioning is unused in this project.

To use versioning properly,
please un-comment below config ([mkdocs.yml](mkdocs.yml) > `extra:`) first.

```
  # version:
  #   provider: mike
```

Working directory should be `rz_verified_linux_package/`.

### Deploy

This will generate a static website into `local/gh-pages` branch.

`dev` will be used as version.

```
. mike/deploy.sh
```

### Serve

You must deploy first.

```
. mike/serve.sh
```

### Clean-up

This step is not mandatory.

After you complete checking your website, you may want to remove `local/gh-pages` branch.

```
. mike/remove.sh
```
