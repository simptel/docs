# SCIM Push Model



**Setting Up SCIM**

1. Create SCIM Push application.
2. Shows the under-the-hood points. It will automatically make OAuth2 client creation
3. wait for the first sync...
4. After successfully synced, it will show a green check (Reference **Integration** **Health Status** in Fleans his design)

To securely authenticate and authorize SCIM API requests, the OAuth2 Confidential client requires the following scopes:

* **`users:read`** – Read user data (e.g., profiles, attributes).
* **`users:write`** – Create, update, or delete user accounts.
* **`groups:read`** – Read group data.
* **`groups:write`** – Create, update, or manage groups.
* **`scim:read`** – Read SCIM resources (users and groups).
* **`scim:write`** – Update SCIM resources (users and groups).
* **`scim:admin`** (Optional) – Admin-level access for managing SCIM resources.

### **Push Model Workflow:**

1. **HR System Updates:** The HR system updates user data (e.g., new hire, role change, termination).
2. **HR System Pushes Data to TF Platform:** The HR system sends SCIM API requests with updated data, authenticated via OAuth2 client with the necessary scopes.
3. **TF Platform Receives Data:** TF platform processes the update, applying changes to user profiles and group memberships.
4. **Real-Time Synchronization:** Associated systems are updated immediately.
