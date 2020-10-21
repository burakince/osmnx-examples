# osmnx-examples

Open Street Map data usage examples with osmnx package

## Usage

Download and install [Docker Desktop](https://www.docker.com/products/docker-desktop), then open its settings and verify your local drives are shared.

### Run the docker container

On Windows open a command prompt, change directory to location of notebook file, and run:

```
docker run --rm -it -p 8888:8888 -v "%cd%":/home/jovyan/work gboeing/osmnx:latest
```

On Mac/Linux open a terminal window, change directory to location of notebook file, and run:

```
docker run --rm -it -p 8888:8888 -v "$PWD":/home/jovyan/work gboeing/osmnx:latest
```

### Run a Jupyter notebook

Once the container is running as described above, open your computer's web browser and visit http://localhost:8888.
