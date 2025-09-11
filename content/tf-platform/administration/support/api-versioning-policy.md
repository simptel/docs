---
description: This article describes how we incorporate versioning of the services.
---

# API Versioning Policy

## API Versioning

TF Platform uses **header-based versioning**. You specify the API version in the request header without altering the URL structure.

```http
TF-API-Version: 1.0.0
```

If no version header is provided, the **latest stable major version** will be used by default.

***

### Semantic Versioning

TF Platform follows **semantic versioning (semver)** in the format **{major}.{minor}.{patch}**:

* **Major (X.0.0)** – breaking changes, not backward-compatible.
* **Minor (X.Y.0)** – backward-compatible new features.
* **Patch (X.Y.Z)** – bug fixes and minor improvements.

**Examples:** v1.2.0, v2.0.3, v3.1.1.

***

### API Request Example

```http
GET https://your-domain.com/api/resource
Host: your-domain.com
TF-API-Version: 1.2.3
```

***

### Best Practices

* Always specify the **full version (X.Y.Z)** in production to avoid unexpected changes.
* Test against new minor versions before upgrading.
* Refer to the **Service Level Agreement (SLA)** for details on version support windows and deprecation notice periods.

***

### Version Tags

All TF Platform open-source components use semantic versioning and are tagged in repositories with a **v** prefix (e.g., `v2.3.1`).
