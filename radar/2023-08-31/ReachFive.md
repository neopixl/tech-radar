---
title: "ReachFive"
ring: hold
quadrant: tools
tags: [Database, login, iOS, React native]
---

<p>Login management framework</p>
<p><a href="https://developer.reachfive.com/sdk-ios/index.html">iOS Documentation</a> <br /> <br />
<p><a href="https://developer.reachfive.com/sdk-android/8.1.1/index.html">Android Documentation</a> <br /> <br />
<p><b>Library problems:</b><br />
- implements third-party libraries (for example for the network, can cause conflicts if we use the same lib)<br />
- infrequent update (last time, they deprecated an API, and we had to contact them to update their lib...)<br />
- doesn't really make sense (the different possible authentications are listed by the API, but they must still be declared on the mobile side for security reasons, so even if they change a config, an update of the apps is necessary) <br />
- insufficient or imprecise documentation, which complicates major version upgrades<br />
</p>
