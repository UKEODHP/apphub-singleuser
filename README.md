# EOEPCA Application Hub - Single User Image

A single user image for running Jupyter Notebooks as part of the EOEPCA Application Hub. It is built on top of jupyter/base-notebook image.

## Build

```
docker build public.ecr.aws/n1b3o1k2/apphub-singleuser:tag .
docker push public.ecr.aws/n1b3o1k2/apphub-singleuser:tag
```

## Run

```
docker run --rm -p 8888:8888 public.ecr.aws/n1b3o1k2/apphub-singleuser:tag
```
