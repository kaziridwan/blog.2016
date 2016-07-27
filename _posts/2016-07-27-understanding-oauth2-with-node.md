---
published: true
layout: post
category:
  - articles
---
## Oauth2

Many a times, we might need to allow external services / additional services to be built on top of our app, and for that, they might need to be authorized to use the user information. OAuth is mainly used in those cases as a protocol, to authorize external services to get our user data, and work on their behalf.

> What Does OAuth Do?

> OAuth is basically a protocol that supports authorization workflows. What this means is that it gives you a way to ensure that a specific user has permissions to do something.

> That’s it.

> OAuth isn’t meant to do stuff like validate a user’s identity — that’s taken care of by an Authentication service. Authentication is when you validate a user’s identity (like asking for a username / password to log in), whereas authorization is when check to see what permissions an existing user already has.

> Just remember that OAuth is a protocol for authorization.

Oauth 2.0 is an authentication framework, allowing an extensible set of authorization grants to be exchanged for access tokens. Implementations are free to choose what grant types to support, by using bundled middleware to support common types or plugins to support extension types.


## References

1. [What the heck is OAuth](https://stormpath.com/blog/what-the-heck-is-oauth)
