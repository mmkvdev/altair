---
parent: Features
---

## GraphQL Subscriptions (with desktop notifications)

You can test your GraphQL subscriptions easily and also get a notification when you are away from the
app (desktop apps only). This is very handy when developing apps that use the realtime feature of
GraphQL, like chatting ang gaming applications that need realtime feedback.

Altair supports a number of subscription implementations:

### Websocket

This supports the [GraphQL over websocket](https://github.com/enisdenjo/graphql-ws/blob/master/PROTOCOL.md) protocol, which is the more common specification used for GraphQL subscriptions.

### AWS AppSync

This supports the MQTT-based subscription protocol used in [AWS AppSync](https://docs.aws.amazon.com/appsync/latest/devguide/welcome.html) which is an enterprise-level, fully managed GraphQL service with real-time data synchronization and offline programming features.

![Specifying connection parameters](https://user-images.githubusercontent.com/15103463/99538456-49d97080-29ad-11eb-9002-e744eec42780.png)

![AWS AppSync subscription](https://i.imgur.com/pDhCiBn.png)

### Rails Action Cable

[Action Cable](https://guides.rubyonrails.org/action_cable_overview.html) seamlessly integrates WebSockets with the rest of your Rails application. It allows for real-time features to be written in Ruby in the same style and form as the rest of your Rails application, while still being performant and scalable.

![Specifing action cable connection parameters](https://user-images.githubusercontent.com/3378171/99864870-e8afc980-2b73-11eb-8eb1-ff1334c4dc21.png)

![Action cable subscription](https://user-images.githubusercontent.com/3378171/99864871-ea798d00-2b73-11eb-835b-69fa6ae0726e.png)
