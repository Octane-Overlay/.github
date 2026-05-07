## Hi there 👋

Octane Overlay is an open source toolkit for building Rocket League broadcast overlays. It connects to Rocket League's native game stats feed and exposes the data as a clean WebSocket API, a typed JavaScript client, and a set of React hooks, so you can build a custom overlay for your stream, tournament, or org in minutes not days or weeks.

### What's in the box:

- [x] Bridge - a small Windows binary that talks to Rocket League and exposes a local WebSocket
- [x] Core - typed JS/TS package that wraps the WebSocket and gives you all game state as plain objects
- [x] Admin - an admin panel that allows you to set team names, logos, and series length. Connects to the local bridge. 
- [x] React - drop-in hooks like usePlayers(), useSeriesScore(), useBoost() for building overlays as React components
- [x] React Example - An example application written in React that uses the React package

### How to use:

- Enable the game stats api, see: [Manual](https://www.rocketleague.com/en/developer/stats-api#configuration)
- Download the latest release of the Bridge here: [Bridge Releases](https://github.com/Octane-Overlay/Octane-Bridge/releases)
- Open the admin panel, either via [Website](https://octane-rl.app), or by cloning and running the admin panel yourself
- Run the React Example, or build your own overlay from scratch and add it as a browser source in your streaming software
- Start streaming
