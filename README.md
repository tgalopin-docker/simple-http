# Simple HTTP

Expose simple text content over HTTP using a single environment variable (useful for maintenance process, etc.).

Usage:

```
docker run -p 80:80 -e HTML_CONTENT='The HTML content to display' tgalopin-docker/simple-http
```

Based on nginx and alpine.