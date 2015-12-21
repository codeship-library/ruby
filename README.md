# ruby

This is an automated build repository on the Docker Hub. Any change to master will trigger an update to the latest tag.

An optimized, Debian-based Ruby image intended to be used as a base image for Dockerized Ruby projects.

The official Ruby image is great, but it's a little bloated. By using some image optimization strategies, we're able to pare down the size by nearly 300MB.

You can check out [a comparison of the two images](https://imagelayers.io/?images=ruby:2.2.3,codeship%2Fruby:latest) to see their differences.
