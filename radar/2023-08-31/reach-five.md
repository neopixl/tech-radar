---
title: "ReachFive"
ring: hold
quadrant: tools
tags: [Database, login, iOS, React native]
---

Reach5 is a customer identity and access management (CIAM) platform designed to help businesses streamline user authentication, registration, and account management processes. It provides a comprehensive set of authentication methods such as social login, passwordless authentication, and multi-factor authentication (MFA), allowing businesses to offer a seamless and secure login experience for their users across web and mobile applications.

#### Should be used in a new project if:

- You need to implement user authentication and registration functionality in your application.
- You want to offer social login options (e.g., via Facebook, Google, LinkedIn) to your users.
- You require advanced features such as passwordless authentication or MFA to enhance security.
- You value a flexible and customizable CIAM solution with SDKs and APIs for easy integration into your application.

#### Should not be used in a new project if:

- Your project does not involve user authentication or registration processes.
- You already have an existing CIAM solution that meets your requirements.
- You prefer to build and manage authentication features in-house rather than using a third-party platform.

### Known Issues

- Implements third-party libraries (for example for the network, can cause conflicts if we use the same lib)
- infrequent update (last time, they deprecated an API, and we had to contact them to update their lib...)
- doesn't really make sense (the different possible authentications are listed by the API, but they must still be declared on the mobile side for security reasons, so even if they change a config, an update of the apps is necessary)
- insufficient or imprecise documentation, which complicates major version upgrades

### Docs

- [Reach5 Documentation](https://developer.reach5.co/)
- [Reach5 API Reference](https://developer.reach5.co/reference/)
- [Reach5 Developer Guides](https://developer.reach5.co/guides/)
