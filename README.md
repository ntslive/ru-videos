# ru-videos

## Setup

Install the package dependencies.
```
$ npm install
```

Copy the pre-commit Git hook, to ensure the assets are compiled before you commit.
```
$ cp pre-commit .git/hooks/.
```

## Development

```
$ npm run development
```

## Deployment

This page is hosted by GitHub pages. To deploy, simply push to master.
Ensure SASS is compiled at this point. See `pre-commit` file, or run `npm run production` before finalising your commit.
