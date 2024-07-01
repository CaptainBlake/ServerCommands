# ServerCommands

ServerCommands is a plugin for the game Rust, developed using the Oxide modding framework. It provides server rules and population information via chat commands.

## Features

- **!rules Command:** Displays the server rules to players.
- **!pop Command:** Shows the current number of online players.

## Permissions

- **servercommands.use:** Allows players to use the chat commands provided by ServerCommands.
- **servercommands.admin:** Allows administrators to reload the configuration of ServerCommands and manage permissions.

## Commands

- **!rules:** Displays the server rules.
- **!pop:** Shows the number of players currently online.

### Admin Command

- **/reloadservercommands:** Reloads the configuration of ServerCommands.

## Configuration

The configuration of ServerCommands can be modified to change the responses of the commands or add new ones. It uses a simple key-value pair system where the key is the command and the value is an array of responses.

## Installation

1. Download the ServerCommands.cs file.
2. Place the file into the `oxide/plugins` directory of your Rust server.
3. Start or reload your server.

### Admin Note

- Ensure to grant **servercommands.use** permission to players who should be able to use the commands provided by ServerCommands.

## Usage

Once installed, players can use the commands in the game chat:
- Type **!rules** to see the server rules.
- Type **!pop** to check the current server population.

Admins can use **/reloadservercommands** in the game chat to reload the configuration of ServerCommands.

## Support

For issues or suggestions regarding ServerCommands, please [open an issue](https://github.com/your-repository-url/issues).

## License

This plugin is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
