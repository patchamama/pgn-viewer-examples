# TLDR

Provide some bigger examples how to use, customize and configure the pgn-viewer for different use cases.

## Motivation

The examples in the [pgn-viewer]() are numerous, but it is not easy to find them, and the user has to understand how to run them. This repository provides a location where examples can be found easily, and where the source code is there explicitly to show how things are done.

## How it works?

1. For each bigger use case provide a directory inside the deployment directory `docs`.
2. Inside that, provide an HTML page that shows that example.
3. Explain there how it works, and show it directly by doing it.

## Current Examples

### 287: Customize SVG or PGN set of pieces

See ticket [287](https://github.com/mliebelt/PgnViewerJS/issues/287) for details.

The goal here is to add different piece sets to the pgn-viewer without building it anew. The ticket contains the recipe, a real example can be [found here](http://mliebelt.github.io/pgn-viewer-examples/customize-pieces/index.html).