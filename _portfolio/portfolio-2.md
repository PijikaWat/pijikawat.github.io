---
title: "BrowserFlow: Preventing data leak to untrusted cloud"
excerpt: "<img src='/images/browserflow.jpg' width='500'>"
collection: portfolio
---

Cloud applications are popular for many organisations. At the same time, other third-party consumer cloud applications can be used hand-in-hand with the internal cloud via web browser. This can be a challenge for the organisations to control confidential data propagation. Although employees have liability to comply with their organisation’s data propagation policies, it is possible that they accidentally disclose organisation’s confidential data to untrusted third-party cloud.

In this work, we introduce BrowserFlow, which is a browser extension that helps employees comply with organisation’s data propagation when cloud technology is used to support enterprise applications. The system continuously monitors web applications and keep all the information that employees accessed. When they try to upload data to cloud, the system will use the past information to reason about their action and check if it complies with organisation’s policy. If any policy is violated, the system will prevent confidential data from being sent to untrusted third-party cloud service providers. Inside BrowserFlow, we use fingerprinting techniques to calculate text similarity and apply decentralised label model to check the confidentiality and privilege.
