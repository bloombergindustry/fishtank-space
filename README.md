# Fish Tank Space

[Space tokens](https://medium.com/eightshapes-llc/tokens-in-design-systems-25dd82d58421) for all of the space in the Fish Tank Design System, distributed in one freestanding package.

## Installation

```sh
npm install @fishtank/space
```

## Usage

Once you've added `@fishtank/space` as a dependency, you'll be able to get the tokens in a number of different formats. We currently support:

* JSON (default)
* Common.JS module
* CSS Custom Properties
* SCSS
* LESS

More formats are available. See [`theo`](https://github.com/salesforce-ux/theo) for more information.

## Development

Tokens are encoded as YAML files consumed by Salesforce's [Theo](https://github.com/salesforce-ux/theo) design token tool, which outputs them to multiple formats.