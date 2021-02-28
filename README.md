# fedeconomy
Game Economy As a Service

**State of the project:** Unstable and in active development

# Economy Service

Service that allows you to control your game's economy as a standalone module.
API development is in progress.

- [What is the economy service?](#what-is-the-economy-service)
- [Requirements](#requirements)
- [Setup](#setup)
- [Contributing](#contributing)
- [License](#license)

## What is the economy service?

A virtual service that takes care of the in-game economy: population, player/npc inventory, game markets, trading, game industry, politics, social, etc.
On top of the CORE functionality, features can be enabled or disabled per hosted game instance service. This means that you can have a game service that could potentially serve multiple game servers that share the same economy so you could benefit from cross-server (background) interactions. These settings can be controlled via a web ui that connects to the API.

## Requirements
TO DO - Not yet available

## Self-Hosted Setup - Docker;
1. Clone this repo;
2. Edit the .env and .config files as per your system requirements;
3. Edit docker-compose as per your system requirements;
4. Start the containers (ex. docker-comose up -d);
5. Access the WebUI and configure your client.

## Contributing

We welcome contributions. Read our [Contribution guidelines](CONTRIBUTING.md) for more information


## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
