# HTTP
**Learn:** request/response anatomy, methods and idempotency, status codes, headers (caching, content negotiation), HTTP/1.1 vs 2, TLS, cookies, CORS.
**Build:** parse an HTTP request from a raw TCP socket and return a response; add keep-alive.
**Test:** curl with `-v`; send malformed requests; test large bodies.
**Deploy:** put it behind a reverse proxy with TLS.
**Interview:** What's the difference between PUT and PATCH? What makes a method idempotent? What happens when you type a URL in a browser?
**Pitfalls:** missing timeouts · trusting `X-Forwarded-For` · unbounded request size · wrong status codes for errors.
