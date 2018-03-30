# Awesome React GraphQL

## Contents

- [General Resources](#general-resources)
- [Clients](#clients)
- [Developer Tools](#developer-tools)
- [Tutorials](#tutorials)
- [Boilerplates](#boilerplates-and-example-apps)
- [Advanced Use Cases](#advanced-use-cases)
- [GraphQL BAaS](#graphql-baas)
- [Articles](#articles)
- [Stories](#stories)

## General Resources

- [GraphQL](http://graphql.org/learn/)
- [ReactJS](https://reactjs.org/docs/hello-world.html)
- [React Native](https://facebook.github.io/react-native/docs/getting-started.html)
- [Redux](https://redux.js.org/)

## Clients

> React clients for GraphQL

- [Relay Modern](https://facebook.github.io/relay/): A JavaScript framework for building data-driven React applications
  - [Docs](https://facebook.github.io/relay/docs/en/introduction-to-relay.html)
  - [Github](https://github.com/facebook/relay)
  - [Discord](https://discord.gg/0ZcbPKXt5bX40xsQ)
- [Apollo](https://www.apollographql.com/): Apollo Client is a community-driven GraphQL client for React, JavaScript, and native platforms
  - [Docs](https://www.apollographql.com/docs/react/)
  - [Github](https://github.com/apollographql)
  - [Slack](https://www.apollographql.com/slack)

## Developer Tools

> Tools for better development (Debugging, Linting, Validating)

- Code generators:
  - [apollo-codegen](https://github.com/apollographql/apollo-codegen): Generate API code or type annotations based on a GraphQL schema and query documents
  - [graphql-code-generator](https://github.com/dotansimha/graphql-code-generator): GraphQL code generator with flexible support for custom templates
- Linters:
  - [eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql): Check your GraphQL query strings against a schema
- React Debugging Tools
  - [Apollo Client Developer Tools](https://chrome.google.com/webstore/detail/apollo-client-developer-t/jdkknkkbebbapilgoeccciglkfbmbnfm): Chrome extension for Apollo Client developer tools
  - [Relay DevTools](https://chrome.google.com/webstore/detail/relay-devtools/oppikflppfjfdpjimpdadhelffjpciba): A Chrome Extension that creates a Relay tab in the developer tools interface for debugging apps in Chrome
  - [Relay Devtools Electron](https://www.npmjs.com/package/relay-devtools): StandAlone Relay DevTools App for debugging Relay outside Chrome
- React Native Debugging Tools
  - [Relay Devtools Electron](https://www.npmjs.com/package/relay-devtools): StandAlone Relay DevTools App for debugging Relay outside Chrome

## Tutorials

> Awesome tutorials for using GraphQL with React and React Native

- React
  - [React + Relay Tutorial](https://www.howtographql.com/react-relay/0-introduction/)
  - [(Video) Using GraphQL, ReactJS and Apollo to Create Amazing Apps](https://youtu.be/kXH2dbnHYA0)
  - [React + Apollo Tutorial](https://www.howtographql.com/react-apollo/0-introduction/)
  - [(Video) Getting Started with Relay Modern, React & GraphQL](https://www.youtube.com/watch?v=XeALXh37WeU)
- React Native
  - [(Video series) Build a Twitter Clone with Apollo Graphql & React-Native  ](https://www.youtube.com/watch?v=33qP1QMmjv8)
  - [How to setup React Native + GraphQL + Relay Modern](https://codeburst.io/how-to-setup-a-react-native-graphql-relay-modern-a6a5f6c18353)
  - [Building Chatty](https://medium.com/react-native-training/building-chatty-a-whatsapp-clone-with-react-native-and-apollo-part-1-setup-68a02f7e11): A WhatsApp clone with React Native and Apollo
- Miscellaneous
  - [A cartoon intro to facebook's Relay](https://code-cartoons.com/a-cartoon-intro-to-facebook-s-relay-part-1-3ec1a127bca5)

## Boilerplates and Example Apps

> Boilerplates and examples for a headstart in development

- React
  - [ReactQL](https://reactql.org/): Universal React+GraphQL starter kit
    - [Docs](https://reactql.org/docs/)
    - [Github](https://github.com/reactql)
  - [UniversalRelayBoilerplate](https://github.com/codefoundries/UniversalRelayBoilerplate)
  Boilerplate + examples for React Native (iOS, Android), React (isomorphic, Material-UI), Relay, GraphQL, JWT, Node.js, Apache Cassandra.
  - [Relay Skeleton](https://github.com/fortruce/relay-skeleton) - Relay project skeleton.
  - [Next.js With Apollo](https://github.com/zeit/next.js/tree/master/examples/with-apollo) - Boilerplate for building Next.js apps with Apollo.
  - [Universal React Apollo](https://github.com/WeLikeGraphQL/universal-react-apollo-example) - Universal React Apollo Example App with Webpack, Recompose, CSS Modules, and other cool stuff.
  - [GitHunt React](https://github.com/apollographql/GitHunt-React)
- React Native
  - [WhatsApp Clone](https://github.com/srtucker22/chatty)
  - [frontpage-react-native-app](https://github.com/apollographql/frontpage-react-native-app): Apollo "hello world" app, for React Native
  - [pokedex-react-native](https://github.com/learnapollo/pokedex-react-native)

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
- Multiple Mutations
  - [Multiple Mutations with Apollo](https://www.learnapollo.com/tutorial-react/react-06/)
  - [Multiple Mutations with Relay Modern](https://stackoverflow.com/questions/40328992/how-to-call-multiple-mutations-at-the-same-time)


# GraphQL BAaS Providers

> Get a GraphQL backend for your applications using these service providers

- [GraphCool](https://www.graph.cool):
Self-Hosted GraphQL BaaS
- [Hasura](https://hasura.io): Get GraphQL APIs over Postgres instantly
- [Meldio](https://meldio.com): Open source GraphQL backend for building delightful mobile and web apps
- [Prisma](https://www.prismagraphql.com): Turn your database into a GraphQL API
- [Scaphold](https://scaphold.io): GraphQL Backend As A Service


## Articles

> Awesome articles and videos

- [So what’s this GraphQL thing I keep hearing about?](https://medium.freecodecamp.org/so-whats-this-graphql-thing-i-keep-hearing-about-baf4d36c20cf)
- [Thinking in Graphs](http://graphql.org/learn/thinking-in-graphs/)
- [What are the benefits of using GraphQL and why it surpasses REST](https://blog.hellocomet.co/graphql-benefits-api/)

## Stories

- [The Evolution of React and GraphQL at Facebook and Beyond](https://developers.facebook.com/videos/f8-2017/the-evolution-of-react-and-graphql-at-facebook-and-beyond/)
- [(Video) Lessons from 4 Years of GraphQL](https://www.youtube.com/watch?v=zVNrqo9XGOs)
- [React, Relay and GraphQL: Under the Hood of The Times Website Redesign](https://open.nytimes.com/react-relay-and-graphql-under-the-hood-of-the-times-website-redesign-22fb62ea9764)
- [2017: The year in GraphQL](https://dev-blog.apollodata.com/2017-the-year-in-graphql-124a050d04c6)
- [Harry Wolf: Experiences with GraphQL](http://hswolff.com/blog/experiences-with-graphql/)
- [JetRuby: Our experience with GraphQL](https://expertise.jetruby.com/our-experience-with-node-js-react-graphql-c40007ad4373)
