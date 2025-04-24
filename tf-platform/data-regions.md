---
icon: globe
cover: ../.gitbook/assets/world.png
coverY: -127.73313565604151
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Data regions

When setting up a tenant, you can select a geographic location based on data residency, processing, compliance, and performance requirements. We currently support four data regions, providing flexibility and control over your data storage needs:

*   **European Economic Area (EEA)** \
    Ideal for compliance with the **General Data Protection Regulation (GDPR)**, ensuring data residency within the region and optimal performance for use cases in the EEA.

    \
    Available on:&#x20;

    * **Google Cloud Platform (GCP)**
    * **Microsoft Azure**


*   **India** (Google Cloud Platform, Microsoft Azure):\
    Ideal for compliance with the **Personal Data Protection Bill (PDPB)**, ensuring data residency within the country and optimal performance for use cases in India.\


    Available on:&#x20;

    * **Google Cloud Platform (GCP)**
    * **Microsoft Azure**

{% hint style="success" %}
Consult legal experts to ensure compliance with applicable regulations.
{% endhint %}

***

## Failover Support

* **Intra-Regional Failover:** Failover support is available within each data region to enhance reliability while keeping data within the selected region.
* **Cross-Regional Failover:** Currently, we do not support cross-regional failover, ensuring that data does not leave the selected region.

{% hint style="info" %}
If you have any questions about how your data is stored, please email us at [support@tfplatform.com](https://sourcegraph.com/cody/chat). You can also read our [privacy policy](https://www.simptel.com/legal/privacy).
{% endhint %}

***

## On the Roadmap

We are developing a **global data residency option** to better serve tenants with worldwide needs. This feature will:

* Automatically select optimal data storage locations across regions.
* Ensure compliance with international regulations.
* Provide optimal performance for global operations.
