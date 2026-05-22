---
title: "Security Advisory [Implementation bugs in Go and Python clients can cause DoS – Fixed – Please update clients]"
date: "2015-09-02"
source: "Ethereum Foundation Blog"
sourceUrl: "https://blog.ethereum.org/feed.xml"
originalUrl: "https://blog.ethereum.org/en/2015/09/02/security-advisory-implementations-bugs-in-go-and-python-clients-can-cause-dos"
author: ""
categories: ["Security"]
---

State transition and consensus issue in geth client causes panic (crash) when processing a (valid) block with a specific combination of transactions, which may cause overall network instability if block is accepted and relayed by unaffected clients thus causing a DoS. This may happen in a block that contains transactions...

---

📖 [Read original article](https://blog.ethereum.org/en/2015/09/02/security-advisory-implementations-bugs-in-go-and-python-clients-can-cause-dos)