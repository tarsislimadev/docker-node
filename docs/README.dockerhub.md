# Quick reference

Maintained by:
[github.com/brtmvdl](https://github.com/brtmvdl/docker-node)

Where to get help:
[Official Repository](https://github.com/brtmvdl/docker-node/issues)

# Supported tags and respective Dockerfile links

* [angular](https://github.com/brtmvdl/docker-node/blob/main/src/angular/Dockerfile)

* [heroku](https://github.com/brtmvdl/docker-node/blob/main/src/heroku/Dockerfile)

* [nestjs](https://github.com/brtmvdl/docker-node/blob/main/src/nestjs/Dockerfile)

* [nextjs](https://github.com/brtmvdl/docker-node/blob/main/src/nextjs/Dockerfile)

* [surge](https://github.com/brtmvdl/docker-node/blob/main/src/surge/Dockerfile)

* [vercel](https://github.com/brtmvdl/docker-node/blob/main/src/vercel/Dockerfile)

# Quick reference (cont.)

Where to file issues:
https://github.com/brtmvdl/docker-node/issues

# What is Node.js?
Node.js is a software platform for scalable server-side and networking applications. Node.js applications are written in JavaScript and can be run within the Node.js runtime on Mac OS X, Windows, and Linux without changes.

Node.js applications are designed to maximize throughput and efficiency, using non-blocking I/O and asynchronous events. Node.js applications run single-threaded, although Node.js uses multiple threads for file and network events. Node.js is commonly used for real-time applications due to its asynchronous nature.

Node.js internally uses the Google V8 JavaScript engine to execute code; a large percentage of the basic modules are written in JavaScript. Node.js contains a built-in, asynchronous I/O library for file, socket, and HTTP communication. The HTTP and socket support allows Node.js to act as a web server without additional software such as Apache.

![https://nodejs.org/static/images/logo.svg](https://nodejs.org/static/images/logo.svg)

## How to use this image

### Usage

Use like you would any other base image:

```Dockerfile
# Dockerfile
FROM tmvdl/node:angular

WORKDIR /app

COPY . .

CMD npm start
```

# License

[MIT]()
