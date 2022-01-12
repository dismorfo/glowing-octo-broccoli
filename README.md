# Hugo example

#### Requirements
- [Hugo](https://gohugo.io/) (if you plan to run `hugo` command in your machine instead of the Hugo shell from the container)
- [Docker Compose](https://docs.docker.com/compose/)

### Run

Inside the project directory run `"docker-compose up"`.

To use docker-compose detached mode, run `"docker-compose up -d"` instead of `"docker-compose up"`. The app will run as a background process. 

To see the app logs when running detached mode, use `docker-compose logs -f`.

### Live 

Once the project is up and running you can visit the site using Hugo's development server (http://localhost:1313/) or Apache Server (http://localhost:8008/)

Hugo's development server has the benefit of live reload.

### Modifications

The source will be mounted in both containers, this enable the ability to make modifications in the source code and see the changes live in the container without building the image.

Site will be "render" to destination path (inside `public` directory) instead or memory.
## Hugo shell

The [Hugo shell](https://hub.docker.com/r/klakegg/hugo/) is available, see image [README.md](https://github.com/klakegg/docker-hugo) for more information.
