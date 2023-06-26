---
title: "Condueit Weak & Leak: Open Card Data in a Flat Network"
subtitle: ''
date: 2023-06-25 06:00:00
description: "Overview of Weak & Leak Infrastructure"
featured_image: '/images/techsmith/line-pipe-shutterstock_1037473621.jpg'
---

![](/images/techsmith/line-pipe-shutterstock_1037473621.jpg)

**Starting Point - Open Card Data in a Flat Network:**

In the initial years of its operations, CW&L operated with an unsophisticated technology infrastructure. All cardholder data was processed, transmitted, and stored within a single, flat network. No distinction was made between different types of data, and sensitive cardholder information was often left unprotected, unencrypted, and easily accessible across the network. 

**The Need for Change:**

The wake-up call came in 2018 when CW&L suffered a significant data breach, leading to exposure of cardholder data. The breach exposed the inherent risks in their existing network structure and data handling practices. There was a clear need for transition - to move from transmitting open credit card data across the flat network to a more secure system of tokenized data transmission across a segmented network, with encrypted storage of sensitive data.

**The Transition Phase - Implementing Tokenization and Network Segmentation:**

The first step in CW&L's transition was the implementation of a tokenization system. Tokenization replaces sensitive cardholder data with unique identification symbols (tokens) that retain all the essential information about the data without compromising its security. This process was made possible by working closely with a PCI DSS compliant tokenization service provider.

The tokenization system, integrated into CW&L's online payment portal, immediately replaced the cardholder data with tokens as soon as customers entered their card information. This ensured that no actual cardholder data was transmitted across the network or stored in their databases, significantly reducing the risk of data exposure.

Simultaneously, CW&L began the process of moving from a flat network to a segmented network. This entailed creating a distinct Cardholder Data Environment (CDE) to handle all transactions involving tokens and segregating it from the corporate network, the administrative network, and the guest network. Firewalls, access control lists, and other security measures were implemented to ensure secure communication between these networks.

**The Outsourcing Phase - Moving from Unencrypted Storage to Secure Storage:**

While implementing tokenization greatly reduced the need for storing sensitive cardholder data, some older records still remained. As a part of their security overhaul, CW&L made the strategic decision to outsource the storage of these remaining sensitive data to their PCI DSS compliant tokenization service provider.

The service provider used strong encryption algorithms to secure the stored cardholder data, ensuring it was unreadable and unusable to unauthorized individuals. This not only transferred the responsibility of secure storage to an expert third-party but also further reduced the scope of CW&L's PCI DSS compliance efforts, as fewer systems now dealt with sensitive cardholder data.

**Reaching the Destination - A Secure, Compliant Network:**

By the end of 2021, CW&L successfully completed its transition. They had implemented a secure tokenization system, segmented their network, and outsourced secure storage of sensitive data to a compliant third-party. CW&L's journey from open card data in a flat network to tokenized data in a segmented network was a testament to its commitment to data security and PCI DSS compliance. It served as a model for other companies navigating their path towards a more secure data environment.
