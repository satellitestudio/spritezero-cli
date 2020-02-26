# @elastic/spritezero-cli

A command-line interface to [elastic/spritezero](https://github.com/elastic/spritezero).

## WTF? (Why The Fork?)
See [elastic/spritezero](https://github.com/elastic/spritezero#wtf-why-the-fork)

## Installation

    npm install -g @elastic/spritezero-cli

## Usage

    spritezero [output filename] [input directory]

      --retina      shorthand for --ratio=2
      --ratio=[n]   pixel ratio
      --unique      map identical images to multiple names
      --sdf         generate sdf sprites

Spritezero reads an input directory containing SVG files and generates a JSON
layout file and PNG spritesheet.
