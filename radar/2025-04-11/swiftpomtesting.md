---
title: "swift-pom-testing"
ring: assess
quadrant: tools
tags: [iOS, Swift, Testing, UI Testing, POM]
---

swift-pom-testing is a Swift library providing base classes to facilitate UI testing using the Page Object Model (POM) pattern. It offers `BasePage` to encapsulate UI element identification and access within a specific screen (page), and `BaseRobot` to define actions and verifications that can be performed on those elements. The goal is to create more structured, reusable, and maintainable UI tests.

#### Should be used in a new project if:

* You are writing UI tests for your iOS application using XCTest.
* You want to implement the Page Object Model (POM) pattern for better test structure and maintainability.
* You are looking for base classes to reduce boilerplate code when creating Page and Robot objects.
* You prefer identifying UI elements primarily via accessibility identifiers.

#### Should not be used in a new project if:

* You are not writing UI tests for your application.
* You are using a different UI testing framework or pattern.
* You prefer writing UI tests without the structure imposed by POM or find the abstraction unnecessary for your project's scale.

### Docs

* [swift-pom-testing GitHub Repository (Primary Documentation)](https://github.com/neopixl/swift-pom-testing)