---
title: "Security Alert - Solidity - Variables can be overwritten in storage"
date: "2016-11-01"
source: "Ethereum Foundation Blog"
sourceUrl: "https://blog.ethereum.org/feed.xml"
originalUrl: "https://blog.ethereum.org/en/2016/11/01/security-alert-solidity-variables-can-overwritten-storage"
author: ""
categories: ["Security"]
---

Summary: In some situations, variables can overwrite other variables in storage. Affected Solidity compiler versions: 0.1.6 to 0.4.3 (including 0.4.4 pre-release versions) Detailed description: Storage variables that are smaller than 256 bits are packed together into the same 256 bit slot if they can fit. If a...

---

📖 [Read original article](https://blog.ethereum.org/en/2016/11/01/security-alert-solidity-variables-can-overwritten-storage)