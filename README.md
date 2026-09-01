# Internal Minecraft Gate Reverse Proxy Configuration
This is the docker compose and config for my basic gate proxy

## Components

### Compose
The compose has the container and volume information, pulling the container version from a `.env` file

### Config
The `config.yml` file is the basic config file expected by the gate application. This one is configured with which domain to expect traffic on and where to route that traffic. DNS resolution is used for all of this so it can be changed remotely from my DNS provider if needed.

### .env
The `.env` file specifies any environment information needed by Docker Compose, including the version of container to use

## Contributing
1. All commits must be made to a separate branch and merged in with a pull request.

2. All commits must be signed by a GPG key
