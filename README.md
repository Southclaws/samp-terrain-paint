# SA:MP Terrain Painter Tool

A tool that allows you to paint objects into the world map - similar to common game development tools.

## Usage

To use the browser, simply clone this repo, ensure, build and run the package:

```bash
sampctl package run --forceBuild --forceEnsure
```

And connect to `localhost:7777`.

## As a Filterscript

If you want to load the tool as a filterscript, sampctl is yet to provide an easy way to work with filterscripts so the workaround is simply to build the package as normal:

```bash
sampctl package build
```

Then copy the .amx to your server and add to the `filterscripts` section in `samp.json`/`samp.yaml` - or load during runtime via `rcon loadfs terrain-paint`.
