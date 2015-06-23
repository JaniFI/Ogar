# Ogar with GUI
An open source Agar.io server implementation, written in Node.js.
Now with GUI to make server setup easier.

## Screenshots

![](http://i.gyazo.com/6e40fa3321951c6668e857127c5f6dcd.png?raw=true)

![](http://i.gyazo.com/0668f37938d9ba47872180fda52e51ad.png?raw=true)

## Project Status
The project is nearly complete. Here's a rough list of what's been done and what needs to be done:

- [x] Master server basic implementation
- [x] Game server basic implementation (clients can connect)
- [x] Single-cell movement
- [x] Randomly generated cells and viruses
- [x] Ejecting mass
- [x] Splitting
- [x] Multi-cell player movement
- [x] Cells eating other cells
- [x] Leaderboard
- [x] Team mode
- [x] Spectate mode

Playerbots are currently basic and for testing purposes. To use them, change "serverBots" to a value higher than zero (I like to use 50) in the config field of GameServer.js.

## Obtaining and Using
If you are on Windows, just launch Ogar_GUI.exe

Currently, Ogar listens on the following addresses and ports:
* *:80 - for the master server
* *:443 - for the game server

Please note that on some systems, you may have to run the process as root or otherwise elevate your privileges to allow the process to listen on the needed ports.

## Configuring Ogar
You can configure Ogar using the GUI.

## Contributing
Please see [CONTRIBUTING.md](https://github.com/forairan/Ogar/blob/master/CONTRIBUTING.md) for contribution guidelines.

## License
Please see [LICENSE.md](https://github.com/forairan/Ogar/blob/master/LICENSE.md).
