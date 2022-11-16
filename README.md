# sample-posts

sample-posts is the API for providing sample content for our [front-end challenge](https://github.com/Coderockr/frontend-test).

## Stack

This API is built on top of [json-serverless][] which is a [json-server][] implementation for serverless architetures.
By dependencies limtations we had to target the *already dead* [Node.js 14][].
After beign deployed it is hosted on [Amazon Lambda][].

## Getting Started

Before start make sure that you have [Node.js 14][] and [yarn][] installed and configured.

1. Clone this repository
2. Install the project dependencies `yarn install`
3. Run it `yarn start`

## Deploy

In case you want to force a deploy - which is not recommended since we have automated deploy's configured - you can use `yarn deploy`, but before that make sure that you have installed and configured the [AWS CLI][].

[json-serverless]: https://github.com/pharindoko/json-serverless
[json-server]: https://github.com/typicode/json-server
[Node.js 14]: https://nodejs.org/en
[Amazon Lambda]: https://aws.amazon.com/lambda
[yarn]: https://yarnpkg.com
[AWS CLI]: https://aws.amazon.com/cli
