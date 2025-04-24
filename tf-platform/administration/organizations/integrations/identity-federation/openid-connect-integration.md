# OpenId Connect integration

To enable secure authentication and authorization using OpenID Connect to outsource User Authentication, the external OAuth2 client requires the following **OIDC-specific scopes**:

* **`openid`** – Grants permission for basic authentication (essential for OIDC).
* **`profile`** – Access to the user’s basic profile information (e.g., name, email).
* **`email`** – Access to the user’s email address.
* **`groups`** (optional) – Access to group membership information.
* **`offline_access`** (optional) – Allows the client to refresh the user’s session.

Interface to register this external OAuth2 client.]



This happens at the external Identity Provider (the above points)

