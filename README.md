# Rivet Colyseus Plugin Examples

This repository provides examples of running Colyseus with the Rivet plugin.

[**Live demo**](https://colyseus.rivet.game/)

## Running locally

```
git clone https://github.com/rivet-gg/plugin-colyseus-examples.git
cd plugin-colyseus-examples
npm install
```

Run the server in one terminal:

```
npm start
```

Serve the static files in another terminal:

```
npm run serve
```

Open [http://localhost:2567](http://localhost:2567) in your browser.

## Deploying to Rivet

1. Create a game on the [Rivet Developer Dashboard](https://hub.rivet.gg/developer/dashboard)
1. Install the [Rivet CLI](https://github.com/rivet-gg/cli)
1. Run `rivet init` to link your game
1. Run `rivet deploy -n prod`
1. Visit the game in your browser

## License

MIT
