---
title: "Condueit Weak & Leak: Reactive and Inefficient Logging"
subtitle: ''
date: 2023-06-27 06:00:00
description: "Overview of Weak & Leak Infrastructure"
featured_image: '/images/techsmith/line-pipe-shutterstock_1037473621.jpg'
---

![](/images/techsmith/line-pipe-shutterstock_1037473621.jpg)

**Initial Stage - Reactive and Inefficient Logging:**

In the early stages, CW&L's approach to logging was fairly basic and reactive. The systems and network devices were set up to create logs, but there was no centralized system for log management or monitoring. Logs were reviewed only when an incident occurred and required investigation. This lack of proactive log monitoring was a significant gap in their security posture, which became apparent during the 2018 data breach.

**Post-Breach - Recognizing the Importance of Log Monitoring:**

After the data breach, the necessity for a more systematic and proactive approach to log monitoring was clear. The newly appointed CISO made log management and monitoring a key part of the security overhaul. The goal was to detect and respond to suspicious activities in real-time, rather than in the aftermath of a security incident.

**Development Stage - Establishing a Log Management and Monitoring System:**

The first step in developing a proactive log monitoring program was to establish a centralized log management system. All systems and network devices were configured to send their logs to this central repository. This allowed for efficient storage and unified monitoring of all logs.

Next, they implemented automated log monitoring tools to analyze the logs in real-time. These tools were configured to flag unusual patterns or suspicious activities, such as multiple failed login attempts, changes in file integrity, or unusual network traffic patterns.

**Enrichment Phase - Enhancing Log Monitoring:**

In addition to real-time monitoring, they set up regular review processes. Security analysts were tasked with reviewing the flagged events and determining whether they posed a genuine security risk. This review process helped minimize false positives and ensured that real threats were promptly identified and addressed.

To further enhance their log monitoring, CW&L integrated threat intelligence feeds into their log monitoring tools. These feeds provided information on known malicious IP addresses, URLs, and other threat indicators, helping to identify potential threats more quickly.

**Ongoing Maintenance - Continual Improvement and Compliance:**

Once the log management and monitoring system was in place, CW&L introduced regular audits to ensure the system's effectiveness. They also implemented procedures to ensure logs were retained as per PCI DSS requirements. The audits checked that logs were being appropriately generated, collected, monitored, reviewed, and retained.

**Current Status - Proactive and Efficient Log Monitoring:**

Today, CW&L's log management and monitoring system is robust and plays a critical role in their security posture. The journey from a reactive approach to a proactive log monitoring system was instrumental in achieving and maintaining PCI DSS v4.0 compliance. It also provided valuable insights into their network operations, helping to identify and address potential issues before they escalate into serious security incidents.
