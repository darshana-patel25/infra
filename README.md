# J!NX Website

Shopify website on [slate v0](https://shopify.github.io/slate/)

## Requirements

## Install

```
yarn install
```

## Shopify Credentials

Copy the `config.yml.default` local and update the `password` fields from [private app in Shopify](https://jinxinc-dev.myshopify.com/admin/apps/private/83787382847) `Password`.

```
cp config.yml.default config.yml
```

## Development

Sync changes to the dev theme with live preview.

```
slate watch
```

## Deploy

Get the latest theme updates and clean assets directory.

```
yarn run download
```

Deploy current files to production theme.

```
slate deploy -e production
```