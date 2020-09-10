# React Personal Resume with Material UI Theme

## Introduction

An CV website written in React, featuring mordern material UI design, for building personal resume website. Integrated with create-react-app and gh-pages, easy to build and deploy.

### 1. Set up local environment

Since this app is bootstrapped with _creat-react-app_, you’ll need to have Node 8.10.0 or later on your local development machine. Install dependencies. For more information: ([create-react-app](https://github.com/facebook/create-react-app))

Install dependencies

```
npm install
```

Run the app

```
npm start
```

Now you should see the app is running in http://localhost:3000

### 2. Customize with your data

To customize it with your perosnal information, all you need to do is modify the json file in `./src/data/profile.json` and upload your profile picture to `./src/img/self.jpeg`

### 3. Publish your website

Currently only github page is supported. To host your website with Github.
Edit website path in `package.json`. This will normally be `https://[your account].github.io/[repo name]/`.

Publish

```
npm deploy
```
