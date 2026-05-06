# distilled-spec-polar

A git mirror of Polar's API spec. The spec is fetched and committed as a JSON file so the repo serves as a versioned snapshot.

The mirror is updated every 24 hours and is designed to be used as a stable git submodule.

## Spec source(s)

- https://api.polar.sh/openapi.json

## Usage as a submodule

```sh
git submodule add https://github.com/alchemy-run/distilled-spec-polar.git
```

## Updating specs

From `.meta/`:

```sh
bun install
bun run fetch-specs
```
