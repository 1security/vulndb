## Overview
[`io.netty:netty`](http://search.maven.org/#search%7Cga%7C1%7Ca%3A%22netty%22)
WebSocket08FrameDecoder in Netty 3.6.x before 3.6.9, 3.7.x before 3.7.1, 3.8.x before 3.8.2, 3.9.x before 3.9.1, and 4.0.x before 4.0.19 allows remote attackers to cause a denial of service (memory consumption) via a TextWebSocketFrame followed by a long stream of ContinuationWebSocketFrames.

## References
- [NVD](https://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2014-0193)
- [Netty Release Notes](http://netty.io/news/2014/04/30/release-day.html)
- [Guthub Issue](https://github.com/netty/netty/issues/2441)
