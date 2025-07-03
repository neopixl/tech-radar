---
title: "Arkana"
ring: assess
quadrant: tools
tags: [iOS, Kotlin, Security, Secrets, Obfuscation, Swift]
---

Arkana is a library designed to help manage and obfuscate secrets (like API keys) within application code for both iOS (Swift) and Android (Kotlin). It reads secrets from environment variables during the build process and generates obfuscated code (Swift/Kotlin files) to access these secrets, preventing them from being easily discoverable in the compiled binary. Configuration is handled via a `arkana.yml` file.

#### Should be used in a new project if:

* You need to store sensitive keys or secrets directly within your mobile application code.
* You want to add a layer of obfuscation to make it harder for secrets to be extracted from the app binary.
* You need a solution that supports both iOS (Swift) and potentially Android (Kotlin) via configuration.
* You prefer managing secrets via environment variables during the build process.

#### Should not be used in a new project if:

* Your secrets management strategy involves fetching secrets from a secure backend at runtime instead of embedding them.
* Basic storage methods (e.g., in plist or build settings) are deemed sufficient for your security needs.
* You require more robust security measures than simple obfuscation.

### Docs

* [Arkana GitHub Repository (Primary Documentation)](https://github.com/rogerluan/arkana)
* [Arkana Configuration Template (template.yml)](https://github.com/rogerluan/arkana/blob/main/template.yml)