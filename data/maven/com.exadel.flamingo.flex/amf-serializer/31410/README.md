## Overview
[`com.exadel.flamingo.flex:amf-serializer`](http://search.maven.org/#search%7Cga%7C1%7Ca%3A%22amf-serializer%22)
Affected versions of this package are vulnerable to Arbitrary Code Execution. It uses AMF3 deserializers which allow instantiation of arbitrary classes via public parameter-less constructors. An attacker may exploit this to send a malicious AMF3 object to the system to execute arbitrary code.

## References
- [CVE](https://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2017-3202)
- [Homeland Security](https://www.kb.cert.org/vuls/id/307983)
