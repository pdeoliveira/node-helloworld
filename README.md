# node-helloworld

A simple Node.js Hello World web page running within a Docker container.

If you want to test it using Docker:
```
docker pull pdeoliveira/node-helloworld
docker run --name node-helloworld -p 8080:8080 -d pdeoliveira/node-helloworld
```