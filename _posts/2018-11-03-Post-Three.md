---
layout: post
title: Benchmarking online security scans part 2
permalink: /:year/:month/:day/:title
---

Spent about 3hrs trying to setup and get Dagda running... huge pain... Next I found [this resource](https://github.com/veggiemonk/awesome-docker) of docket tools with a [security](https://github.com/veggiemonk/awesome-docker#security) section. Tried [cis-socker-bench](https://github.com/dev-sec/cis-docker-benchmark) ~~no luck getting that to run either.~~ it generated a huge very difficult to read report it mainly audited the engine but It did flag some security issues with the contained that are running. Next up was [OpenSCAP](https://github.com/OpenSCAP/openscap) a well know security scanning tool for VMs... socker support however is limited to REHL hosts and im running Ubuntu so did not get very far.
