[![Travis](https://img.shields.io/travis/nikolaik/docker-python-nodejs.svg?style=flat-square)](https://travis-ci.org/nikolaik/docker-python-nodejs)
[![Pulls](https://img.shields.io/docker/pulls/nikolaik/python-nodejs.svg?style=flat-square)](https://links.shields.io/d-python-nodejs)
[![Release](https://img.shields.io/github/release/nikolaik/docker-python-nodejs.svg?style=flat-square)](https://github.com/nikolaik/docker-python-nodejs/releases)

## Python (latest) with Node.js 7.x based on [beevelop/nodejs-python](https://travis-ci.org/beevelop/docker-nodejs-python)
- npm: 3.x
- Node: v7.x
- Python: latest
- pip: latest

----
### Pull from Docker Hub
```
docker pull nikolaik/python-nodejs:latest
```

### Build from GitHub
```
docker build -t nikolaik/python-nodejs github.com/nikolaik/docker-python-nodejs
```

### Run image
```
docker run -it nikolaik/python-nodejs bash
```

### Use as base image
```Dockerfile
FROM nikolaik/python-nodejs:latest
```

## Disclaimer
> This is experimental and might break from time to time. Use at your own risk!