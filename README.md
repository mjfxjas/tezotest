# Taquito boilerplate

> Personal sandbox for playing with Taquito + Parcel. I use it when I need to stand up a quick Tezos demo without scaffolding a full framework project.

![Built with Taquito][logo]

A minimal framework-agnostic setup for starting developing Tezos DApps quickly with Taquito.

> If you are looking for the React template, please follow [this link](https://github.com/ecadlabs/taquito-react-template).

## Dependencies
1. jQuery - for simple manipulation and traversal of HTML documents.
2. parcel-bundler - for packaging web applications quickly.

## Repo Status

- Last sanity check: Nov 2025 (`npm install && npm run watch`).
- Networks tested: Ghostnet.
- Next steps: swap jQuery for vanilla helpers and add wallet connect (Beacon).

## Getting Started

1. Create a new repository from taquito-boilerplate by clicking "Use this template".
2. Clone your new repository:

    `git clone <YOUR_REPOSITORY_URL>`

3. Change your current working directory to the newly cloned repository directory.
4. Install dependencies:

    `npm install`

5. Start development server:

    `npm run watch`

6. Open http://localhost:1234 in your browser to see a sample application.

[logo]: https://raw.githubusercontent.com/ecadlabs/taquito-boilerplate/master/assets/built-with-taquito.png "Built with Taquito"
