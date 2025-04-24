# Identity Sync

**SCIM Workflow with OAuth2 Client Integration:**

When implementing SCIM, the TF platform will create a **confidential OAuth2 client** to securely call the platform's APIs during synchronization.

#### **Example Workflow for SCIM Integration Push strategy:**

1. **HR System Updates**: The HR system updates an employee’s status (e.g., a new employee is added, or an existing employee is terminated).
2. **Push to TF Platform**: The HR system sends a **SCIM API request** to the TF platform with the updated user data, using the **confidential OAuth2 client** to authenticate and authorize the request.
3. **TF Platform Receives Data**: The TF platform processes the incoming data, ensuring the employee has the appropriate permissions or is immediately deactivated if terminated.
4. **Real-time Synchronization**: Any associated systems or applications that rely on user data are updated instantly through the exact push mechanism.

