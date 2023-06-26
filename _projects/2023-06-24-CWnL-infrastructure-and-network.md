---
title: "Condueit Weak & Leak: Technology Infrastructure and Network Segementation"
subtitle: ''
date: 2023-06-24 06:00:00
description: "Overview of Weak & Leak Infrastructure"
featured_image: '/images/techsmith/line-pipe-shutterstock_1037473621.jpg'
---

![](/images/techsmith/line-pipe-shutterstock_1037473621.jpg)

**Technology Infrastructure and Network Segmentation:**

CW&L began its operations with a relatively simple flat network infrastructure. In its initial years, due to the smaller scale of operations, this flat network with limited segmentation adequately served its needs. All devices - from corporate servers to end-user devices - were on the same network, presenting a significant risk. This risk became apparent when the data breach occurred in 2018, as the attackers were able to move laterally within the network, accessing critical resources such as cardholder data.

**The Journey to Network Segmentation:**

Post the 2018 data breach, CW&L recognized the need to implement network segmentation to increase security and reduce the risk of lateral movement in case of a breach. The new CISO, appointed in 2019, spearheaded the transition from a flat network to a segmented network architecture.

The segmented network now includes a Cardholder Data Environment (CDE), an administrative network supporting the CDE, a corporate network, and a guest wireless network.

- **CDE**: This is where all cardholder data is processed, stored, and transmitted. It is the most sensitive part of the network and is equipped with the highest level of security controls. The CDE is further segmented to separate processing and storage, reducing the risk of a single point of compromise.

- **Administrative Network**: This network is used for managing the systems within the CDE. Access to this network is restricted to specific individuals who need to administer the systems within the CDE. It is segregated from the CDE with firewall rules and access control lists, ensuring that if this network is compromised, the attacker can't directly access the CDE.

- **Corporate Network**: This network is used for general business operations such as email, file storage, and other non-payment-related applications. This network is kept entirely separate from the CDE, limiting exposure of cardholder data to a minimum number of systems and users.

- **Guest Wireless Network**: This network provides internet access to visitors and is completely isolated from all other networks, ensuring that guest devices cannot access sensitive company data.

**Dataflow Overview:**

The payment data flow starts when customers enter their card information on CW&L's secure online portal to purchase a product. The data is immediately tokenized and transmitted through a secure, encrypted connection to the CDE. The CDE communicates with payment gateways to authorize the transaction.

When transactions are successful, CW&L's billing systems within the CDE generate an invoice. All communication to the billing systems is also done through secure, encrypted connections. Once the invoice is generated, the system sends a notification to the customer, without including any sensitive cardholder data.

For refunds, the process is somewhat similar. The refund request is sent to the CDE, where the original transaction is looked up using the token, and a refund is initiated if the criteria are met.

Fraud detection is handled by specialized systems within the CDE that use advanced algorithms to flag potentially fraudulent transactions. When a transaction is flagged, it is manually reviewed by a team within the administrative network before a decision is made.

For each of these processes, the CDE interfaces with the administrative network, which provides management and support functions. Both networks are segregated from the corporate network and the guest network, where non-cardholder data is processed and transmitted.

This comprehensive network segmentation and data flow strategy significantly improved CW&L's security posture and was a key aspect of achieving their PCI DSS compliance. This data flow description can be translated into a detailed diagram, providing a visual representation of how cardholder data moves within CW&L's networks.
