### ctrace
---
https://github.com/Nordstrom/ctrace

```
{
  "traceId": "xxxxxxxxxx",
  "spanId": "xxxxxxxxx",
  "parentId": "xxxxxxxxxxxx",
  "service": "ProductService",
  "operation": "CreateProduct",
  "start": xxxxxxxxx,
  "duration": 738,
  "tags": {
    "component": "ProductUpdater",
    "span.kind": "service",
    "http.url": "https://api.nordstorm.com/v1/products",
    "http.method": "POST",
    "http.user_agent": "Mozilla/5.0 (X11; Linux x86_64; rv:12.0) Gecko/20100101 Firefox/21.0"
    "http.status_code": 200,
    "http.status_addr": "192.168.1.2",
    "styleId": "xxxx",
    "sku": "xxxxx",
    "label": "NewPump"
  },
  "logs": [
    "timestamp": xxxxxxxxxx,
    "event": "Finish-Span"
  ],
  "baggage": {
    "origin": "xxxxxxxxx",
    "agent": "xxxxxx",
    "user": "xxxxxxxxxxxx"
  }
}
```

```
```

```
```


