## Overview
[`org.springframework:spring-web`](http://search.maven.org/#search%7Cga%7C1%7Ca%3A%22spring-web%22)
When processing user provided XML documents, the Spring Framework did not disable by default the resolution of URI references in a DTD declaration. This enabled an XXE attack.

## References

- [Pivotal Security](http://www.gopivotal.com/security/cve-2014-0225)
- [Redhat Bugzilla](https://bugzilla.redhat.com/show_bug.cgi?id=CVE-2014-0225)
