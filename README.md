# JetLagger

Now you would like to read this stupid instruction...

## Introduction

TODO...

## Tech Stack

- React
- Redux
- React-Router
- ESLint
- Webpack
- Babel

## How To Start

Open your terminal, do

    npm install

After the installation process is done, then do

    npm start

You will see something similar to below

    > jetlagger@0.0.1 start /Users/Kulbear/Documents/jetlagger
    > node ./node_modules/webpack-dev-server/bin/webpack-dev-server.js

    http://localhost:8080/webpack-dev-server/
    webpack result is served from /
    content is served from ./
    404s will fallback to /index.html
    Hash: 0606b825054014338918
    Version: webpack 1.13.2
    Time: 1431ms
        Asset    Size  Chunks             Chunk Names
    bundle.js  741 kB       0  [emitted]  main
    chunk    {0} bundle.js (main) 704 kB [rendered]

Now open your browser (FYI: Google Chrome has a well-developed React developer tool), go visit `http://localhost:8080/webpack-dev-server/`.

Note that this page is pre-configured to be able to hot-reload. Whenever you have a code change and save it, the webpack will re-build the `bundle.js`

## Coding Style

We will use Airbnb's JavaScript style guide for our code. Make sure you install all the dependencies before you start to write the first line of your code.

The tool we used for coding style review is ESLint.

By the way, **all the indentation number should be two spaces**.

<del>我就不听你的。</del>

## Work Together?

Whenever you want to add features for the project, please do

    git pull

first on your master branch, then you should **always** create a new branch for each feature. The branch name should be `new-feature-name`.

Once you are done, you would like to push your branch and make a `Pull Request`, the title of your PR **should be** `New Feature Name`, comments are not required but could be linked with existing issue(s).

You can review and merge others PR but please **never** merge yours by yourself.

## Commit Message

Always start your commit message with a verb like `Add`, `Fix`, `Update` and so on.

A brief example and explanation can be found [here](https://robots.thoughtbot.com/5-useful-tips-for-a-better-commit-message). **READ IT.**
