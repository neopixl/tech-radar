---
title: "Arkana"
ring: adopt
quadrant: tools
tags: [security, secrets, obfuscation, ios, android, swift, kotlin]
---

Arkana is a tool for managing secret keys and sensitive configuration values in iOS and Android projects. It reads secrets from environment variables at build time, encrypts them, and generates typed Swift and Kotlin accessors. This keeps credentials out of source control and avoids plain-text secrets in the codebase and the compiled binary. Configuration is handled in an `arkana.yml` file.

### Docs

* [Arkana GitHub Repository (Primary Documentation)](https://github.com/rogerluan/arkana)
* [Arkana Configuration Template (template.yml)](https://github.com/rogerluan/arkana/blob/main/template.yml)
