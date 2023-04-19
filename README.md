# Rivet Colyseus Plugin Examples

This repository provides examples of running Colyseus with the Rivet plugin.

[**Live demo**](https://colyseus.rivet.game/)

## Project setup

First, clone the project:

```
git clone https://github.com/rivet-gg/plugin-colyseus-examples.git
cd plugin-colyseus-examples
npm install
```

Set up Rivet game:

1. Create a game on the [Rivet Developer Dashboard](https://hub.rivet.gg/developer/dashboard)
1. Install the [Rivet CLI](https://github.com/rivet-gg/cli)
1. Run `rivet init --recommend` to link your game
1. Run `npm install`

## Running locally

1. Run the server in one terminal: `npm start`
1. Serve the static files in another terminal: `npm run serve`
1. Open [http://localhost:2567](http://localhost:2567) in your browser.

## Deploying to Rivet

1. Run `rivet deploy -n prod`
1. Visit the game in your browser

## License

MIT
