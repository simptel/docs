# Data Processing Addendum (DPA)

### 1. Roles of the Parties

* **Customer as Controller** – Customer acts as the controller of personal data stored in its tenant on the TF Platform (“The Future Platform”).
* **Simptel as Processor** – Simptel acts as processor only with respect to personal data in Customer’s tenant and processes such data solely on Customer’s documented instructions.
* **Customer Responsibility** – Customer is responsible for:
  * Selecting its hosting region (Azure, AWS, or Google Cloud);
  * Managing tenants, access rights, and identity configurations;
  * Configuring and managing third-party integrations.

While the TF Platform makes integrations easy, all third-party integrations (and their API keys or credentials) remain **Customer’s sole responsibility**.

***

### 2. Subject Matter and Scope

Simptel processes Customer Personal Data only for the provision of the **TF Platform**, an identity and security platform.

***

### 3. Processing Location

* **Tenant Data** – Customer Personal Data is processed **exclusively in the region selected by Customer** (Azure, AWS, or Google Cloud). Simptel does not replicate or transfer tenant data outside the selected region.
* **DNS Services** – The TF Platform uses **Google DNS** for the `tfplatform.com` domain, which may involve processing outside the selected region.
* **TLS Certificates** – TLS certificates are issued by **Let’s Encrypt** by default. Customers may alternatively provide their own certificates.
* **Customer Organizational Data** – Data relating to Customer’s own organization (e.g., billing, invoicing, contracting, and account administration) is processed in the **Netherlands** by Simptel. For these purposes, Simptel also uses the following service providers:
  * **Bird.com** – communications;
  * **Azure Marketplace** – subscriptions and procurement;
  * **Stripe** – payments and billing;
  * **Moneybird** – bookkeeping and accounting.

This processing is separate from Customer’s tenant data.

***

### 4. Nature and Purpose of Processing

Simptel processes Customer Personal Data solely to:

* Host, encrypt, and secure tenant data in the chosen region;
* Provide the features and functionality of the TF Platform;
* Manage billing, invoicing, and contracting for Customer’s organization.

***

### 5. Categories of Data and Data Subjects

* **Categories of Data:** Identity data, authentication data, access logs, and any other information uploaded or configured by Customer.
* **Data Subjects:** End-users of Customer’s tenant, such as employees, partners, or customers.

Customer determines what data is processed.

***

### 6. Security Measures

Simptel maintains technical and organizational measures appropriate to the risk, including:

* **Encryption** – All tenant data is encrypted at rest and in transit using **AES-based best practices**;
* **TLS** – Secured by Let’s Encrypt or Customer-provided certificates;
* **Access Controls** – Strict authentication and authorization measures;
* **Logging & Monitoring** – Security and compliance monitoring;
* **Tenant Isolation** – Logical and physical separation of tenants;
* **Certifications** – Simptel is **ISO/IEC 27001:2022 certified** and maintains **SOC 2 Type II compliance**, supported by **yearly independent audits**.

***

### 7. Sub-Processors

Authorized sub-processors are limited to:

**For Tenant Data**

* **Google** – DNS services for `tfplatform.com`;
* **Let’s Encrypt** – TLS certificate authority;
* **Cloud provider chosen by Customer** – Azure, AWS, or Google Cloud, in the region selected by Customer.

**For Customer Organizational Data**

* **Bird.com** – communications;
* **Azure Marketplace** – subscription and procurement;
* **Stripe** – payments and billing;
* **Moneybird** – bookkeeping and accounting.

**Simptel Entities**

* Simptel B.V. – Netherlands;
* Simptel Services B.V. – Netherlands;&#x20;
* Simptel India Private Limited – India&#x20;

Simptel will update this list at least 30 days before engaging a new sub-processor.

***

### 8. International Data Transfers

* **Tenant Data** – Remains in the Customer-selected region, except for DNS services.
* **TLS Certificates** – Let’s Encrypt may process limited technical data (domain validation) outside the selected region.
* **Customer Organizational Data** – Processed in the Netherlands, with Stripe and Bird.com potentially involving transfers outside the EEA.
* Where transfers outside the EEA/UK occur, Simptel ensures appropriate safeguards, including Standard Contractual Clauses.

***

### 9. Assistance to Customer

Simptel will assist Customer, where reasonably possible, with:

* Responding to data subject rights requests;
* Supporting Data Protection Impact Assessments (DPIAs);
* Providing documentation to demonstrate GDPR compliance.

***

### 10. Return or Deletion of Data

Upon termination of services, Simptel will delete or return Customer Personal Data, unless retention is required by law.

***

### 11. Audit Rights

Simptel provides documentation and evidence of compliance, including ISO 27001 and SOC 2 reports. Customer may conduct audits with reasonable notice and subject to confidentiality.

***

### 12. Liability

Each party’s liability under this DPA is subject to the limitations of liability agreed in the Terms & Conditions.

***

### 13. Governing Law

This DPA is governed by the laws of the Netherlands.
