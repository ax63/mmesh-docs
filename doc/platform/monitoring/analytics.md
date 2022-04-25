---
title: Analytics | mmesh
description: mmesh hybrid cloud integration platform
topic: platform
chapter:
  id: monitoring
  label: Monitoring
page:
  name: analytics
  label: Analytics
position: 801

nodeMetrics:
  - Load Average (not supported by Windows)
  - CPU Usage
  - Memory Usage
  - Disk Usage (main filesystem)
  - Network Usage (mmesh traffic)
---

mmesh monitors the nodes out-of-the-box. No configuration is required.

It monitors the following node metrics:

<docs-list :items="nodeMetrics"></docs-list>
