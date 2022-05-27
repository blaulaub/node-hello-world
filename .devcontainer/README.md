# Visual Studio Code Remote Containers

This folder contains configuration to configure the Remote - Containers plugin
for VSCode, see [VSCode - Developing inside a Container](https://code.visualstudio.com/docs/remote/containers).

_This is optional. The configuration provides node.js, npm and ng-cli in a container environment. If
you have these already installed in your local environment, you can work on this project also without
VSCode, Docker or Remote-Containers._

## Caveats

Following issues have been observed with `ng serve`:

- on Windows/WSL, automatic rebuild may come with a considerable delay,
  probably due to issues with the file system virtualization
- on Linux/Podman, port exposure may not work, http://localhost:4200
  may not be forwarded properly
