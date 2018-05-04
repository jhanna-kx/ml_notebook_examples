This project builds the Docker image.

## Related Links

 * [Docker](https://docker.com)
     * [`Dockerfile`](https://docs.docker.com/engine/reference/builder/)
     * [Automated Builds](https://docs.docker.com/docker-cloud/builds/automated-build/)
         * [Advanced options for Autobuild and Autotest](https://docs.docker.com/docker-cloud/builds/advanced/)

# Preflight

You will need [Docker installed](https://www.docker.com/community-edition) on your workstation; make sure it is a recent version.

Check out a copy of the project with:

    git clone https://github.com/KxSystems/ml_notebook_examples.git

# Build

To build locally the project you run:

    docker build -t ml_notebook_examples -f docker/Dockerfile .

**N.B.** if you wish to use an alternative source for [jupyterq](https://github.com/KxSystems/jupyterq) then you can append `--build-arg jupyterq_img=jupyterq` to your argument list.

