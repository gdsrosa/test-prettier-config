# `@gdsrosa/my-prettier-config`

> My personal [prettier](https://prettier.io) config.

## Usage

**Install**:

```sh
npm install --save-dev @gdsrosa/my-prettier-config
```

**Edit `package.json`**:

```jsonc
{
  // ...
  "prettier": "@gdsrosa/my-prettier-config
}
```

## Release a new package

This project uses [sementic versioning](https://semver.org/). A new version will be published to both npm and GitHub Package Registry when a new tag is pushed. Please make sure an entry is added to [CHANGELOG.md](CHANGELOG.md)

```
git checkout master
npm version <major|minor|patch>
git push --follow-tags
```
