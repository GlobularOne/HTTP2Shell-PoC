Here is a PoC for HTTP2Shell. it's not a full-fledged "hack every http server you see", the server should either hang or crash (most seem to hang in my testing) if it decompresses the body.
