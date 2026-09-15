# Contributing

## Get started

This project is written in TypeScript and is using prettier and eslint for code formatting. You need Node.js v22.

1. Install Node.js v22. I recommend installing that with nvm: https://github.com/nvm-sh/nvm

```sh
nvm install 22
```

2. Make Node.js v22 default

```sh
nvm alias default 22
```

3. Open a new terminal and verify the Node.js version (should return v22.X.X)

```sh
node -v
```

4. Install yarn

```sh
npm install -g yarn
```

5. Fork and clone project

```sh
git clone git@github.com:<GITHUB_USERNAME>/aws-azure-login.git
cd aws-azure-login
```

6. Install dependencies

```sh
yarn install
```

7a. Start dev mode

```sh
yarn start
```

7b. Start prod mode

```sh
yarn build && node ./lib/index.js
```
