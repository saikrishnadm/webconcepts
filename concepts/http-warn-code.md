---
layout:    page
title:     "HTTP Warn Codes"
permalink: /concepts/http-warn-code/
---



The following 7 HTTP Warn Code values were found in [all available `webconcepts.info` specifications](/specs). Please be advised that the table shown here is maintained and compiled from [Web Concepts](/) sources. The [official HTTP Warn Code registry](https://www.iana.org/assignments/http-warn-codes/http-warn-codes.xhtml) is maintained by the [*Internet Assigned Numbers Authority (IANA)*](http://www.iana.org/).

HTTP Warn Code | Specification
-------: | :-------
[`110 Response is Stale`](/concepts/http-warn-code/110 "A cache SHOULD generate this whenever the sent response is stale.") | [**RFC 7234**: Hypertext Transfer Protocol (HTTP/1.1): Caching](/specs/IETF/RFC/7234 "The Hypertext Transfer Protocol (HTTP) is an application-level protocol for distributed, collaborative, hypertext information systems. This document defines requirements on HTTP caches and the associated header fields that control cache behavior or indicate cacheable response messages.")
[`111 Revalidation Failed`](/concepts/http-warn-code/111 "A cache SHOULD generate this when sending a stale response because an attempt to validate the response failed, due to an inability to reach the server.") | [**RFC 7234**: Hypertext Transfer Protocol (HTTP/1.1): Caching](/specs/IETF/RFC/7234 "The Hypertext Transfer Protocol (HTTP) is an application-level protocol for distributed, collaborative, hypertext information systems. This document defines requirements on HTTP caches and the associated header fields that control cache behavior or indicate cacheable response messages.")
[`112 Disconnected Operation`](/concepts/http-warn-code/112 "A cache SHOULD generate this if it is intentionally disconnected from the rest of the network for a period of time.") | [**RFC 7234**: Hypertext Transfer Protocol (HTTP/1.1): Caching](/specs/IETF/RFC/7234 "The Hypertext Transfer Protocol (HTTP) is an application-level protocol for distributed, collaborative, hypertext information systems. This document defines requirements on HTTP caches and the associated header fields that control cache behavior or indicate cacheable response messages.")
[`113 Heuristic Expiration`](/concepts/http-warn-code/113 "A cache SHOULD generate this if it heuristically chose a freshness lifetime greater than 24 hours and the response's age is greater than 24 hours.") | [**RFC 7234**: Hypertext Transfer Protocol (HTTP/1.1): Caching](/specs/IETF/RFC/7234 "The Hypertext Transfer Protocol (HTTP) is an application-level protocol for distributed, collaborative, hypertext information systems. This document defines requirements on HTTP caches and the associated header fields that control cache behavior or indicate cacheable response messages.")
[`199 Miscellaneous Warning`](/concepts/http-warn-code/199 "The warning text can include arbitrary information to be presented to a human user or logged. A system receiving this warning MUST NOT take any automated action, besides presenting the warning to the user.") | [**RFC 7234**: Hypertext Transfer Protocol (HTTP/1.1): Caching](/specs/IETF/RFC/7234 "The Hypertext Transfer Protocol (HTTP) is an application-level protocol for distributed, collaborative, hypertext information systems. This document defines requirements on HTTP caches and the associated header fields that control cache behavior or indicate cacheable response messages.")
[`214 Transformation Applied`](/concepts/http-warn-code/214 "This Warning code MUST be added by a proxy if it applies any transformation to the representation, such as changing the content-coding, media-type, or modifying the representation data, unless this Warning code already appears in the response.") | [**RFC 7234**: Hypertext Transfer Protocol (HTTP/1.1): Caching](/specs/IETF/RFC/7234 "The Hypertext Transfer Protocol (HTTP) is an application-level protocol for distributed, collaborative, hypertext information systems. This document defines requirements on HTTP caches and the associated header fields that control cache behavior or indicate cacheable response messages.")
[`299 Miscellaneous Persistent Warning`](/concepts/http-warn-code/299 "The warning text can include arbitrary information to be presented to a human user or logged. A system receiving this warning MUST NOT take any automated action.") | [**RFC 7234**: Hypertext Transfer Protocol (HTTP/1.1): Caching](/specs/IETF/RFC/7234 "The Hypertext Transfer Protocol (HTTP) is an application-level protocol for distributed, collaborative, hypertext information systems. This document defines requirements on HTTP caches and the associated header fields that control cache behavior or indicate cacheable response messages.")

<br/>
<hr/>

<p style="float : left"><a href="../http-warn-code.json" title="JSON representing all values for this Web Concept">JSON</a></p>