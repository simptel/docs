---
description: >-
  This article provides an overview of the rate limiting policies within the
  platform to show how many requests a tenant can sustain.
---

# Rate Limiting Policy

## How Rate Limiting Works

Each tenant is limited to **600 API requests per minute** on all **public-facing APIs**. This limit maintains fair usage and system stability. Rate limits apply **globally across all public APIs per tenant**. If the limit is exceeded, the API responds with **HTTP 429 – Too Many Requests**.

***

### Event Log Example

Rate limit details are recorded in the event log:

```json
{
  "x-ratelimit": 600,
  "x-ratelimit-remaining": 450,
  "x-ratelimit-reset": 1632425760
}
```

***

### Exceeding the Limit

If the request limit is exceeded, the API responds:

```
HTTP/1.1 429 Too Many Requests
```

The event log shows the limit, remaining requests, and reset time.

***

### Best Practices

* **Retry Logic** – If you receive an HTTP 429 response, use the reset time from the event log to determine when it is safe to retry requests.
* **Monitor Usage** – Regularly review the event log to track request volumes and avoid recurring limit breaches.

***

### Quota Increase

Higher rate limits for public APIs may be available on request based on your subscription. Contact **support@tfplatform.com** to discuss your requirements.
