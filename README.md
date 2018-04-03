# Awesome React GraphQL [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated collection of resources, clients and tools that make working with `GraphQL and React/React Native` awesome.

## Contents

- [General Resources](#general-resources)
- [Clients](#clients)
- [Developer Tools](#developer-tools)
- [Tutorials](#tutorials)
- [Boilerplates](#boilerplates-and-example-apps)
- [Advanced Use Cases](#advanced-use-cases)
- [GraphQL BaaS Providers](#graphql-baas-providers)
- [Articles and Videos](#articles-and-videos)
- [Stories](#stories)

## General Resources

- [GraphQL](http://graphql.org/learn/)
- [ReactJS](https://reactjs.org/docs/hello-world.html)
- [React Native](https://facebook.github.io/react-native/docs/getting-started.html)
- [Redux](https://redux.js.org/)

## Clients

> React and React Native clients for GraphQL

- [Apollo](https://www.apollographql.com/): Apollo Client is a community-driven GraphQL client for React, JavaScript, and native platforms
  - [Docs](https://www.apollographql.com/docs/react/)
  - [Github](https://github.com/apollographql)
  - [Slack](https://www.apollographql.com/slack)
- [Relay Modern](https://facebook.github.io/relay/): A JavaScript framework for building data-driven React applications
  - [Docs](https://facebook.github.io/relay/docs/en/introduction-to-relay.html)
  - [Github](https://github.com/facebook/relay)
  - [Discord](https://discord.gg/0ZcbPKXt5bX40xsQ)
- [AppSync](https://github.com/awslabs/aws-mobile-appsync-sdk-js): JavaScript GraphQL library for Offline, Sync, Sigv4. includes support for React Native
  - [Docs](https://docs.aws.amazon.com/appsync/latest/devguide/welcome.html)

## Developer Tools

> Tools for better development (debugging, linting, validation etc)

- Code generators:
  - [apollo-codegen](https://github.com/apollographql/apollo-codegen): Generate API code or type annotations based on a GraphQL schema and query documents
  - [graphql-code-generator](https://github.com/dotansimha/graphql-code-generator): GraphQL code generator with flexible support for custom templates
- Linters:
  - [eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql): Check your GraphQL query strings against a schema
- ReactJS Debugging Tools
  - [Apollo Client Developer Tools](https://chrome.google.com/webstore/detail/apollo-client-developer-t/jdkknkkbebbapilgoeccciglkfbmbnfm): Chrome extension for Apollo Client developer tools
  - [Relay DevTools](https://chrome.google.com/webstore/detail/relay-devtools/oppikflppfjfdpjimpdadhelffjpciba): A Chrome Extension that creates a Relay tab in the developer tools interface for debugging apps in Chrome
  - [Relay Devtools Electron](https://www.npmjs.com/package/relay-devtools): StandAlone Relay DevTools App for debugging Relay outside Chrome
- React Native Debugging Tools
  - [Relay Devtools Electron](https://www.npmjs.com/package/relay-devtools): StandAlone Relay DevTools App for debugging Relay outside Chrome

## Tutorials

> Awesome tutorials for using GraphQL with React and React Native

- ReactJS
  - [React + Relay Tutorial](https://www.howtographql.com/react-relay/0-introduction/)
  - [(Video) Using GraphQL, ReactJS and Apollo to Create Amazing Apps](https://youtu.be/kXH2dbnHYA0)
  - [React + Apollo Tutorial](https://www.howtographql.com/react-apollo/0-introduction/)
  - [(Video) Getting Started with Relay Modern, React & GraphQL](https://www.youtube.com/watch?v=XeALXh37WeU)
  - [Building a Real Time React Application with GraphQL & AWS AppSync](https://www.youtube.com/watch?v=qNkkPoq9D3k&t=10s)
- React Native
  - [(Video series) Build a Twitter Clone with Apollo Graphql & React-Native  ](https://www.youtube.com/watch?v=33qP1QMmjv8)
  - [How to setup React Native + GraphQL + Relay Modern](https://codeburst.io/how-to-setup-a-react-native-graphql-relay-modern-a6a5f6c18353)
  - [Building Chatty](https://medium.com/react-native-training/building-chatty-a-whatsapp-clone-with-react-native-and-apollo-part-1-setup-68a02f7e11): A WhatsApp clone with React Native and Apollo
  - [Code an App With GraphQL, React Native, and AWS AppSync: The API](https://code.tutsplus.com/tutorials/code-an-app-with-graphql-and-react-native--cms-30511)
  - [Code an App With GraphQL, React Native and AWS AppSync: The App](https://code.tutsplus.com/tutorials/code-an-app-with-graphql-react-native-and-aws-appsync-the-app--cms-30569)
- Vue
  - [Full Stack Vue with GraphQL & AWS AppSync](https://hackernoon.com/full-stack-vue-with-graphql-aws-appsync-adc5af474dc9)
- Miscellaneous
  - [A cartoon intro to facebook's Relay](https://code-cartoons.com/a-cartoon-intro-to-facebook-s-relay-part-1-3ec1a127bca5)

## Boilerplates and Example Apps

> Boilerplates and examples for a headstart in development

- ReactJS
  - [ReactQL](https://reactql.org/): Universal React+GraphQL starter kit
    - [Docs](https://reactql.org/docs/)
    - [Github](https://github.com/reactql/cli)
  - [UniversalRelayBoilerplate](https://github.com/codefoundries/UniversalRelayBoilerplate)
  - [React Todo App using Apollo Client](https://hasura.io/hub/projects/hasura/react-apollo-todo-app)
  - [React AppSync Starter App](https://github.com/aws-samples/aws-mobile-appsync-events-starter-react)
  Boilerplate + examples for React Native (iOS, Android), React (isomorphic, Material-UI), Relay, GraphQL, JWT, Node.js, Apache Cassandra.
  - [Relay Skeleton](https://github.com/fortruce/relay-skeleton) - Relay project skeleton.
  - [Next.js With Apollo](https://github.com/zeit/next.js/tree/master/examples/with-apollo) - Boilerplate for building Next.js apps with Apollo.
  - [Universal React Apollo](https://github.com/WeLikeGraphQL/universal-react-apollo-example) - Universal React Apollo Example App with Webpack, Recompose, CSS Modules, and other cool stuff.
  - [GitHunt React](https://github.com/apollographql/GitHunt-React)
  - [Extensive React + Apollo + GraphQL GitHub Client](https://github.com/rwieruch/react-graphql-github-apollo)
- React Native
  - [WhatsApp Clone](https://github.com/srtucker22/chatty)
  - [React Native Todo App using Apollo Client](https://hasura.io/hub/projects/hasura/react-native-apollo-todo)
  - [frontpage-react-native-app](https://github.com/apollographql/frontpage-react-native-app): Apollo "hello world" app, for React Native
  - [pokedex-react-native](https://github.com/learnapollo/pokedex-react-native)
  - [GraphQL starter application with Realtime and Offline functionality using AWS AppSync](https://github.com/aws-samples/aws-mobile-appsync-events-starter-react-native)

## Advanced Use Cases

- Server-side Rendering
  - [(Video) React NYC- Server-side Rendering with GraphQL](https://www.youtube.com/watch?v=YMuigDra88M)
  - [Understanding Server-side rendering with Apollo](https://dev-blog.apollodata.com/how-server-side-rendering-works-with-react-apollo-20f31b0c7348)
- Offline apps
  - [Offline GraphQL Queries with Redux Offline and Apollo](http://www.petecorey.com/blog/2017/07/24/offline-graphql-queries-with-redux-offline-and-apollo/)
- Realtime
  - [(Video) Robert Zhu - Realtime React Apps with GraphQL - React Conf 2017](https://www.youtube.com/watch?v=AYbVMNtO-ro)
  - [Polling](https://dev-blog.apollodata.com/dynamic-graphql-polling-with-react-and-apollo-client-fb36e390d250): Dynamic GraphQL polling with React and Apollo Client
  - [Subscriptions with Relay Modern](https://facebook.github.io/relay/docs/en/subscriptions.html)
  - [Subscriptions with Apollo Client](https://www.apollographql.com/docs/react/advanced/subscriptions.html): Learn how to achieve realtime data with GraphQL subscriptions using Apollo Client.
- [Gatsby](https://www.gatsbyjs.org/): Blazing-fast static site generator for React

## GraphQL BaaS Providers

> Get a GraphQL backend for your applications using these service providers

- [GraphCool](https://www.graph.cool):
Self-Hosted GraphQL BaaS
- [Hasura](https://hasura.io): Instant GraphQL APIs on Postgres
- [Scaphold](https://scaphold.io): GraphQL Backend As A Service
- [AWS AppSync](https://aws.amazon.com/appsync/): Build data-driven apps with real-time and offline capabilities

## Articles and Videos

### Articles

- [So what’s this GraphQL thing I keep hearing about?](https://medium.freecodecamp.org/so-whats-this-graphql-thing-i-keep-hearing-about-baf4d36c20cf)
- [Thinking in Graphs](http://graphql.org/learn/thinking-in-graphs/)
- [What are the benefits of using GraphQL and why it surpasses REST](https://blog.hellocomet.co/graphql-benefits-api/)

### Videos

- [From REST to GraphQL](https://www.youtube.com/watch?v=ntBU5UXGbM8)
- [Data fetching for React Applications at Facebook](https://www.youtube.com/watch?v=9sc8Pyc51uU)

## Stories

> Good and bad experiences

- [The Evolution of React and GraphQL at Facebook and Beyond](https://developers.facebook.com/videos/f8-2017/the-evolution-of-react-and-graphql-at-facebook-and-beyond/)
- [(Video) Lessons from 4 Years of GraphQL](https://www.youtube.com/watch?v=zVNrqo9XGOs)
- [React, Relay and GraphQL: Under the Hood of The Times Website Redesign](https://open.nytimes.com/react-relay-and-graphql-under-the-hood-of-the-times-website-redesign-22fb62ea9764)
- [2017: The year in GraphQL](https://dev-blog.apollodata.com/2017-the-year-in-graphql-124a050d04c6)
- [Harry Wolf: Experiences with GraphQL](http://hswolff.com/blog/experiences-with-graphql/)
- [JetRuby: Our experience with GraphQL](https://expertise.jetruby.com/our-experience-with-node-js-react-graphql-c40007ad4373)
