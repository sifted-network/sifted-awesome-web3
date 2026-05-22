---
title: "Transaction spam attack: Next Steps"
date: "2016-09-22"
source: "Ethereum Foundation Blog"
sourceUrl: "https://blog.ethereum.org/feed.xml"
originalUrl: "https://blog.ethereum.org/en/2016/09/22/transaction-spam-attack-next-steps"
author: ""
categories: ["Protocol Announcements"]
---

Today the network was attacked by a transaction spam attack that repeatedly called the EXTCODESIZE opcode (see trace sample here), thereby creating blocks that take up to 20-60 seconds to validate due to the 50,000 disk fetches needed to process the transaction. The result of this was a ~2-3x reduction...

---

📖 [Read original article](https://blog.ethereum.org/en/2016/09/22/transaction-spam-attack-next-steps)