---
title: "Conduit Weak & Leak: Prioritized Approach"
subtitle: ''
date: 2023-07-03 06:00:00
description: "Overview of Weak & Leak Infrastructure"
featured_image: '/images/techsmith/line-pipe-shutterstock_1037473621.jpg'
---

![](/images/techsmith/line-pipe-shutterstock_1037473621.jpg)

The Prioritized Approach is a tool provided by the PCI Security Standards Council to help organizations identify, prioritize, and address their PCI DSS compliance efforts. The Prioritized Approach breaks down the process into six security milestones, helping to manage the risk and achieve compliance incrementally. 

The journey of CW&L's PCI DSS compliance using the Prioritized Approach fits in with their broader GRC story as follows:

**1. Removal of Sensitive Cardholder Data:** 
The first step in CW&L's prioritized approach to PCI DSS compliance was to eliminate the storage of sensitive cardholder data wherever possible. This step came naturally after the data breach in 2018. By transitioning to a PCI DSS compliant tokenization service provider, they successfully removed unencrypted cardholder data from their systems.

**2. Protect Systems and Networks:**
Next, CW&L focused on securing their network and systems. This involved transitioning from a flat network to a segmented one, with separate networks for different functions. It also involved the implementation of robust access controls and the establishment of a secure data flow design.

**3. Secure Payment Card Applications:**
In parallel with the network and systems protection, CW&L also focused on securing their payment card applications. This involved regular vulnerability assessments, penetration testing, and proactive patch management, ensuring any vulnerabilities were quickly identified and remediated.

**4. Monitor and Control Access:**
The fourth step involved monitoring and controlling access to their systems and network. This stage saw the rollout of CW&L's comprehensive log monitoring program, which included real-time log analysis, regular review processes, and the integration of threat intelligence feeds.

**5. Protect Stored Cardholder Data:**
While CW&L had outsourced storage of sensitive cardholder data to a third-party tokenization provider, some data storage was still necessary for their operations. To protect this data, CW&L implemented strong encryption measures and stringent access controls.

**6. Finalize Remaining Compliance Efforts and Ensure All Controls are in Place:**
The final step in CW&L's prioritized approach involved ensuring that all other PCI DSS requirements were met. This included the formulation of comprehensive security policies, enhanced security training for employees, and regular audits and reviews to ensure ongoing compliance.

With this prioritized approach, CW&L successfully achieved full PCI DSS v4.0 compliance. This journey naturally intertwined with their broader GRC efforts, demonstrating the company's commitment to a comprehensive, systematic approach to security and compliance.
