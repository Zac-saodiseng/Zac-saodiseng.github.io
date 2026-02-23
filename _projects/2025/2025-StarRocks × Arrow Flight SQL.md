---
title: "StarRocks × Arrow Flight SQL: A Leap in Data Transfer Performance"
date: 2025-07-02 00:01:00 +0800
selected: true  # 是否高亮显示 (true/false)

description: >-
  This project introduces a high-performance data transfer channel based on the Apache Arrow Flight SQL protocol in StarRocks version 3.5.1. It establishes a fully columnar data pipeline from the StarRocks columnar execution engine to the client, eliminating the row-to-column conversions and serialization overhead of traditional JDBC/ODBC interfaces, enabling true zero-copy, low-latency, and high-throughput data transfer. In practical testing, transfer efficiency improved by up to 160× (e.g., a query reading 10 million rows of integer data was reduced from 35 seconds to 0.4 seconds), significantly enhancing StarRocks' applicability in high-throughput scenarios such as data science, data lake analytics, and machine learning.
cover: /assets/images/covers/2025-StarRocks × Arrow Flight SQL.png
links:
  Code: https://github.com/StarRocks/starrocks/pull/57956
---

