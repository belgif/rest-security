# REST Security Guide

## Overview
The REST Security Guide, built from these sources, will be available on https://www.belgif.be/specification/rest/security-guide/.

This guide is the result of a collaboration between several Belgian public institution and intends to raise awareness of security best practices for those involved in the development and maintenance of RESTful services.

See the [wiki](https://github.com/belgif/rest-security/wiki) for more information on the organization of the REST Security workgroup and its meeting reports.

## Guidelines for repository contributors

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in the REST Security guide are to be interpreted as described in [RFC 2119](https://datatracker.ietf.org/doc/html/rfc2119).

Rules must follow the following format:

```
[.rule, caption="Rule {counter:rule-number}: "]
.rule title
====
<the rule, using RFC 2119 key words>
====
```

Examples must follow the following format:

```
.example title
====
<example, may use nested code blocks>
====
```

## Building the guide

The guide is built with [Apache Maven](https://maven.apache.org).

With Maven installed, run `mvn site` in the root directory of the project.
The guide will be built in the `target/site/doc/` directory.
