---
title: Getting Started
custom_edit_url: null
---

The Ordinals Explorer is an observability tool that helps users, developers, miners, and investors understand Ordinals. It's built with [React](https://reactjs.org/), [Next.js](https://nextjs.org/) and [Chakra UI](https://chakra-ui.com/).

## Prerequisites

To run the it locally, you must first clone the [Ordinals Explorer repository](https://github.com/hirosystems/ordinals-explorer).

You must also enusre you have installed the project dependencies listed below.

- [NodeJS](https://nodejs.dev/en/) that includes `npm`
- [PNPM](https://pnpm.io/installation/)

It is also highly recommended you install [Homebrew](https://brew.sh/).

## Installing Project Dependencies

To install project dependencies:

1. Open your terminal window and make sure you are in the `/explorer` folder.
2. Run the `pnpm i` command to install the project dependencies.

## Setting Environment Variables

The Ordinals Explorer application needs the environment variables listed below to work properly.

```
NEXT_PUBLIC_MAINNET_API_SERVER=https://api.hiro.so
NEXT_PUBLIC_TESTNET_API_SERVER=https://api.testnet.hiro.so
NEXT_PUBLIC_DEPLOYMENT_URL=https://explorer.hiro.so
NEXT_PUBLIC_MAINNET_ENABLED="true"
NEXT_PUBLIC_DEFAULT_POLLING_INTERVAL="10000"
```

> **_NOTE:_**
>
> If you are working in a macOS environment, you will need to add these variable to `/etc/paths`.
