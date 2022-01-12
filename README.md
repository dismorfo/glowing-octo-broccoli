# Hugo example

#### Requirements
- [Hugo](https://gohugo.io/)
- [Docker Compose](https://docs.docker.com/compose/)

### Run

Inside the project directory run `docker-compose up`.

### Live 

Once the project is up and running you can visit the site using Hugo's development server (http://localhost:1313/) or Apache Server (http://localhost:8008/)

Hugo's development server has the benefit the live reload and browser changes updates.

### Modifications

The source will be mounted to both containers, this enable the avility to make modifications in the source code and see the changes live in the container without building the image.

## Hugo shell

The [Hugo shell](https://hub.docker.com/r/klakegg/hugo/) is available, see image [README.md](https://github.com/klakegg/docker-hugo) for more information.
