# Contribute

## Introduction

First of all, thank you for considering contributing to GrapesJS!

We welcome any type of contribution, not only code. Like for example:

- **QA**: file bug reports, the more details you can give the better (e.g. screenshots with the console open)
- **Marketing**: writing blog posts, howto's, tutorials, etc.
- **Community**: presenting the project at meetups, organizing a dedicated meetup for the local community, etc.
- **Money**: We welcome financial contributions in full transparency on our [Open Collective].

## Setting up the repository

This is a Node.js project and you need to have Node.js installed on your machine. You can download it from [here](https://nodejs.org/). We test versions 14 and 16 of Node in the CI, so it's recommended to use one of these versions, or the latest of: 16.20.2

```bash
nvm use 16.20.2
```

You will then use `yarn` to manage the dependencies and run the scripts. You can install it by running:

```bash
npm install -g yarn
```

Then you can clone the repository and install the dependencies:

```bash
git clone __YOUR_FORK__
cd grapesjs
yarn
```

Finally, you can run the development server:

```bash
yarn start
```

Navigate to `http://localhost:8080/` to see the editor in action. The development server will watch for changes in the code and automatically reload the page.

## Your First Contribution

Working on your first Pull Request? You can learn how from this **free** series, [How to Contribute to an Open Source Project on GitHub](https://app.egghead.io/playlists/how-to-contribute-to-an-open-source-project-on-github).

## Submitting code

Any code change should be submitted as a pull request. Before start working on something make always a search in opened issues and pull requests, this might help you to avoid wasting time.

A pull request could be a bug fix, new feature and much more, but in all cases, **open a new issue** and talk about what you want to do. Often happens to work on something already fixed (ready to release) or in progress.

The title should be brief but comprehensive, the description contains a link to the opened issue and the proposed solution. The pull request should contain tests whenever possible. Keep in mind that the bigger is the pull request, the longer it will take to review and merge. Try to break down large pull requests in smaller chunks that are easier to review and merge.

## Styleguide

The code is auto formatted with [prettier](https://github.com/prettier/prettier) on any commit, therefore you can write in any style you prefer

## Expenses

Anyone can file an expense (code, marketing, etc.) via our [Open Collective]. If the expense makes sense for the development of the community, it will be "merged" in the ledger of our open collective by the core contributors and the person who filed the expense will be reimbursed.

Before submitting an expense contact core contributors via the current active chat room ([Discord](https://discord.gg/QAbgGXq)) and explain your intents

## Questions

If you have any questions, create an [issue](https://github.com/GrapesJS/grapesjs/issues) (protip: do a quick search first to see if someone else didn't ask the same question before!).

## Credits

Thank you to all the people who have already contributed to GrapesJS!
<a href="/GrapesJS/grapesjs/graphs/contributors"><img src="https://opencollective.com/grapesjs/contributors.svg?width=890" /></a>

[Open Collective]: https://opencollective.com/grapesjs
