# Astro Embed

Welcome! This project aims to collect easy-to-use and lightweight ways to embed common media into your [Astro](https://astro.build/) site.

## 📚 Documentation

Want to get started using some embed components?

[Check out the README for the `astro-embed` package ](packages/astro-embed/README.md)

## 🚀 Project Structure

This project uses a monorepo structure with a separate workspace for each embed type. You’ll find a directory for each service in the [`/packages`](packages) directory.

The Astro site in the [`/demo`](demo) directory can be used to preview the various components and the files in [`/tests`](tests) are used to run automated testing on the components.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command       | Action                                                          |
| :------------ | :-------------------------------------------------------------- |
| `npm install` | Installs dependencies                                           |
| `npm start`   | Starts local dev server for the `demo` site at `localhost:3000` |
| `npm t`       | Run the test suite                                              |

## 🧪 Testing

You can run unit tests by running `npm t` in a terminal or run `npm start` to start a dev server for the demo project.

Because the `<Tweet />` component requires a Twitter API token, these tests will fail if you don’t add a bearer token to this repo.

1. Create a new file at `demo/.env`

2. Add your API token:

   ```
   SECRET_TWITTER_TOKEN=bearer-token-for-the-twitter-api
   ```

## ✨ Want to contribute?

This is an Astro Community project. That means YOU!

- 🛠 Want to build a missing component? [We have a guide for that.](CONTRIBUTING.md)

- 🐛 Found a bug? Open a [new issue](https://github.com/astro-community/astro-embed/issues/new/choose) to let us know.

- 💬 Want to chat? Jump into [the Astro Discord server](https://astro.build/chat).
