## Overview
[`org.apache.tomcat:tomcat-catalina`](http://search.maven.org/#search%7Cga%7C1%7Ca%3A%22tomcat-catalina%22)
Apache Tomcat 7.x before 7.0.11, when web.xml has no security constraints, does not follow ServletSecurity annotations, which allows remote attackers to bypass intended access restrictions via HTTP requests to a web application.  NOTE: this vulnerability exists because of an incomplete fix for CVE-2011-1088.

## References
- [NVD](https://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2011-1419)