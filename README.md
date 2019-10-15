# Spectral Workshop

## Getting Started with Spectral

1. NPM install with `npm install -g @stoplight/spectral`
  - [alternative install instructions](https://stoplight.io/p/docs/gh/stoplightio/spectral/docs/getting-started/installation.md)

2. Download some files to lint, like... [the petstore](https://raw.githubusercontent.com/OAI/OpenAPI-Specification/master/examples/v3.0/petstore-expanded.yaml)

```
wget https://raw.githubusercontent.com/OAI/OpenAPI-Specification/master/examples/v3.0/petstore-expanded.yaml
```

3. lint that file! `spectral lint petstore.yaml`

4. Take a look at `--format json` and `--format=junit`

## Getting Started with Studio

1. Download [Stoplight Studio](http://stoplight.io/studio)

2. Get Spectral running in there

3. Make `.spectral.yaml` and disable some rules

4. Let's write [some Custom Rules](https://stoplight.io/p/docs/gh/stoplightio/spectral/docs/getting-started/rulesets.md)

5. Ideas for custom rules on [openapi-community/style-guide](https://github.com/openapi-community/style-guide)

## Super Advanced

1. Custom functions: https://stoplight.io/p/docs/gh/stoplightio/spectral/docs/guides/custom-functions.md

2. GitHub Action: https://github.com/stoplightio/spectral-action
