---
title: "AppAuth-iOS"
ring: adopt
quadrant: tools
tags: [iOS, macOS, tvOS, Security, OAuth, OpenID Connect, Authentication, Swift, Objective-C]
---

AppAuth-iOS is a client SDK for native apps (iOS, macOS, tvOS) to communicate with OAuth 2.0 and OpenID Connect providers. It follows modern security best practices outlined in RFC 8252 (OAuth 2.0 for Native Apps), such as using external user-agents (`SFAuthenticationSession`, `SFSafariViewController`, `ASWebAuthenticationSession`) instead of WebViews. It supports Proof Key for Code Exchange (PKCE) to enhance security.

#### Should be used in a new project if:

* Your native iOS/macOS/tvOS application needs to authenticate users against an OAuth 2.0 or OpenID Connect compliant provider.
* You want to follow current security best practices for native app authentication (RFC 8252).
* You need support for features like PKCE.
* You need to interact with standard OAuth endpoints (authorization, token, discovery).

#### Should not be used in a new project if:

* Your application does not require OAuth 2.0 or OpenID Connect authentication.
* You are using a platform-specific authentication mechanism (like Sign in with Apple) exclusively and don't need general OAuth support.
* Your identity provider offers its own specific native SDK that you prefer to use.

### Docs

* [AppAuth-iOS GitHub Repository (Primary Documentation)](https://github.com/openid/AppAuth-iOS)
* [FusionAuth iOS Swift Quickstart using AppAuth (Example Usage)](https://fusionauth.io/docs/quickstarts/quickstart-swift-ios-native-appauth)
* [RFC 8252: OAuth 2.0 for Native Apps](https://tools.ietf.org/html/rfc8252)