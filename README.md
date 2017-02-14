[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/gdocs_features.svg)](https://hub.docker.com/r/rubygem/gdocs_features/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/gdocs_features.svg)](https://hub.docker.com/r/rubygem/gdocs_features/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/gdocs_features.svg)](https://hub.docker.com/r/rubygem/gdocs_features/)
[![Gem Downloads](https://img.shields.io/gem/dt/gdocs_features.svg)](https://rubygems.org/gems/gdocs_features/)
# gdocs_features

Auto-Generated Docker image for gdocs_features to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/gdocs_features`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/gdocs_features`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/gdocs_features`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/gdocs_features/)
