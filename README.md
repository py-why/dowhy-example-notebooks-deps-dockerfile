# Dockerfile for DoWhy's example notebooks

This repository hosts the `Dockerfile` to build the [dowhy-example-notebooks-deps image](https://github.com/py-why/dowhy-example-notebooks-deps-dockerfile/pkgs/container/dowhy-example-notebooks-deps).

This image contains R dependencies and many other required packages to run most of the DoWhy example notebooks.

It turned out that the R dependencies are very experimental, and reliably rebuilding this image is not possible without continuous efforts to update the Dockerfile. The Dockerfile is therefore mainly for documentation purposes.