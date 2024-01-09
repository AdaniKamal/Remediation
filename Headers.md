# Headers

## Website Header

HTTP header is a field of an HTTP request/response that passes additional context and metadata about the request/response. 

For example, a request message can use headers to indicate it's preferred media formats, while a response can use header to indicate the media format of the returned body. 

Headers are case-insensitive, begin at the start of a line and are immediately followed by a ':' and a header-dependent value. 

> Headers:

### Request Headers

Accept - media types that the client is able to accept from the server

> Accept: application/json, text/html

User-Agent - identifies the web browser or client application that is making the request.

Authorization - used to send the client’s credentials to the server when the client is attempting to access a protected resource

Content-Type - identifies the media type of the content in the request body

> Content-Type: application/json

Cookie - client use to send previously stored cookies back to the server

### Response Headers

Content-Type - indicates the type of data that the server is sending to the client.

Cache-Control - controls caching behavior in the client’s browser or intermediate caches

> Cache-Control: max-age=3600, public

Server - includes the name and version of the server software & technology stack.

> Server: Apache/2.4.10 (Unix)

Set-Cookie - instructs the client to store a cookie with the specified name, value, and additional attributes, such as expiration, domain, path, and security flags.

Content-Length - specifies the size of the response body in bytes, can help the client anticipate how much data it is going to receive.



https://www.google.com/url?sa=i&url=https%3A%2F%2Ftech.jotform.com%2Funderstanding-http-headers-f240f215f37b&psig=AOvVaw3CIA5GFKbeiQiQB_-PiWm-&ust=1704447245975000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCPCYr_i2w4MDFQAAAAAdAAAAABAD
