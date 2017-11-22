# Node Boilerplate Docker Image

This project defines a Dockerfile that creates a base image that would inclide the node_module dependencies in the /app directory.
This image allows to resolve issues that show up in the secure environment where docker build cannot run npm install
due to the proxy server restrictions.

The resulting image can be used then to build the node based appliaction images without running the npm install during build phase.
