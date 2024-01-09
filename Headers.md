# Headers

## Website Header

<b> HTTP header </b> is a field of an HTTP request/response that passes additional context and metadata about the request/response. 

For example, a request message can use headers to indicate it's preferred media formats, while a response can use header to indicate the media format of the returned body. 

Headers are case-insensitive, begin at the start of a line and are immediately followed by a ':' and a header-dependent value. 

> Headers:
<br>

### Request Headers

<b> 1. Accept </b> - media types that the client is able to accept from the server

> Accept: application/json, text/html

<b> 2. User-Agent </b> - identifies the web browser or client application that is making the request.

<b> 3. Authorization </b> - used to send the client’s credentials to the server when the client is attempting to access a protected resource

<b> 4. Content-Type </b> - identifies the media type of the content in the request body

> Content-Type: application/json

<b> 5. Cookie </b> - client use to send previously stored cookies back to the server

<br>

### Response Headers

<b> 1. Content-Type </b> - indicates the type of data that the server is sending to the client.

<b> 2. Cache-Control </b> - controls caching behavior in the client’s browser or intermediate caches

> Cache-Control: max-age=3600, public

<b> 3. Server </b> - includes the name and version of the server software & technology stack.

> Server: Apache/2.4.10 (Unix)

<b> 4. Set-Cookie </b> - instructs the client to store a cookie with the specified name, value, and additional attributes, such as expiration, domain, path, and security flags.

<b> 5. Content-Length </b> - specifies the size of the response body in bytes, can help the client anticipate how much data it is going to receive.



https://www.google.com/url?sa=i&url=https%3A%2F%2Ftech.jotform.com%2Funderstanding-http-headers-f240f215f37b&psig=AOvVaw3CIA5GFKbeiQiQB_-PiWm-&ust=1704447245975000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCPCYr_i2w4MDFQAAAAAdAAAAABAD
