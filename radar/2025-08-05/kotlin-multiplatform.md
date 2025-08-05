---
title: "Kotlin Multiplatform"
ring: adopt
quadrant: Android
tags: [kotlin, android, ios, cross-platform, multiplatform]
---

Kotlin Multiplatform (KMP) is a framework that allows developers to share business logic and code between multiple platforms including Android, iOS, desktop, and web applications. By leveraging Kotlin's native compilation capabilities, KMP enables teams to write common code once while maintaining platform-specific implementations where needed.

KMP works by compiling Kotlin code to native binaries for each target platform, ensuring optimal performance and seamless integration with platform-specific APIs. The framework supports expect/actual declarations for platform-specific implementations and provides excellent interoperability with existing native codebases.

### Justification for Categorization

Kotlin Multiplatform is placed in the ADOPT category because it represents a mature and production-ready solution for cross-platform development. Google's strong backing of Kotlin, combined with JetBrains' continued investment in the multiplatform ecosystem, ensures long-term viability. KMP allows teams to maintain native performance while significantly reducing code duplication, particularly for business logic, networking, and data models. The framework's gradual adoption approach means teams can start small by sharing specific modules rather than rewriting entire applications. Major companies like Netflix, VMware, and Philips have successfully adopted KMP in production, demonstrating its enterprise readiness.

### Key Benefits
- **Native Performance**: Compiles to native code for each platform
- **Gradual Adoption**: Can be integrated incrementally into existing projects
- **Type Safety**: Leverages Kotlin's strong type system across platforms
- **Shared Business Logic**: Reduces duplication of core application logic
- **Platform Interoperability**: Seamless integration with platform-specific code

### Docs
- Official Documentation: [https://kotlinlang.org/docs/multiplatform.html](https://kotlinlang.org/docs/multiplatform.html)
- Getting Started Guide: [https://kotlinlang.org/docs/multiplatform-mobile-getting-started.html](https://kotlinlang.org/docs/multiplatform-mobile-getting-started.html)
- GitHub Repository: [https://github.com/JetBrains/kotlin](https://github.com/JetBrains/kotlin)