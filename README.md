# random-cat
An app that shows cat gifs randomly. I made this following this Docker tutorial: [Developer - Beginner Linux Containers](http://training.docker.com/category/self-paced-online).

## Development
### Prerequisites
- [Docker](https://www.docker.com/products/overview) - software containerization platform.

### Installation
```
$ docker build -t <YOUR_USERNAME>/random-cat . // where <YOUR_USERNAME> is your username at Docker Hub (https://hub.docker.com/). This is to build the Docker image from the Dockerfile.
```

### Execution
```
$ docker run -p 8888:5000 --name random-cat <YOUR_USERNAME>/random-cat // Open http://localhost:8888/ in browser and enjoy the app
$ docker stop random-cat
$ docker rm random-cat
```
