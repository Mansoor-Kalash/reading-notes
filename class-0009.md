# HTTP

**Hypertext Transfer Protocol (HTTP) isHTTP is a protocol for fetching resources such as HTML documents. It is the foundation of any data exchange on the Web and it is a client-server protocol, which means requests are initiated by the recipient, usually the Web browser. A complete document is reconstructed from the different sub-documents fetched, for instance, text, layout description, images, videos, scripts, and more.**

![](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview/fetching_a_page.png)

1. *Request is received by the server, the server determines the ISAPI extension to handle the request based on filename extension.*

2. *n case this is first request, it will create an app domain for maintaining isolation with this and other applications running.*

3. *then it creates hosting environment which will also create the objects like HttpContext, HttpRequest and HttpResponse.*

4. *After this the HTTPApplication object is created .*

5. *Afterwards the events in the global.asax which is the class inherited from the HTTPApplication object fires in the order defined in the link above.*