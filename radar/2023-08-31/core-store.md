---
title: "CoreStore"
ring: hold
quadrant: iOS
tags: [Database, iOS]
---

CoreStore is a Swift-based framework that provides a layer of abstraction on top of CoreData, Apple's persistence framework for iOS and macOS applications. It aims to simplify the usage of CoreData by offering a more modern and Swifty API.

With CoreStore, developers can perform common CoreData operations such as creating, fetching, updating, and deleting objects in a more intuitive and type-safe manner. It also provides features like automatic migration, thread-safety, and transaction management to simplify CoreData usage and reduce boilerplate code.

While CoreStore offers convenience and additional features, there are reasons why it may be preferable to rely on CoreData directly:

1. **Learning Curve**: CoreStore introduces its own concepts and API, which may require developers to learn additional frameworks and paradigms beyond CoreData.

2. **Dependency**: Adding CoreStore as a dependency introduces another layer of complexity and potential points of failure in the project.

3. **Maintenance**: CoreStore is a third-party framework, so developers rely on its maintainers to keep it up-to-date with the latest Swift and CoreData changes. Depending directly on CoreData ensures compatibility with future iOS and macOS updates.

4. **Flexibility**: CoreData is a powerful framework with extensive features and customization options. Relying on it directly allows developers to leverage its full capabilities and tailor solutions to specific project requirements without being constrained by a higher-level abstraction.

While CoreStore may provide convenience for certain projects, in many cases, relying on CoreData directly offers more control, flexibility, and long-term stability for iOS and macOS applications.

### When to use? When not to use?

We strongly recommend to use the native `CoreData` when possible. Relying on a third-party library can be a security and/or maintenance issue when native functionality can easily be the go-to solution.

### Docs

- [Github Repository](https://github.com/JohnEstropia/CoreStore)
- [Apple Documentation for CoreData](https://developer.apple.com/documentation/coredata)
