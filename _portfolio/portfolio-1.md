---
title: "Ako: Decentralised deep learning"
excerpt: "<img src='/images/ako.jpg' width='500'>"
collection: portfolio
---

Deep learning has remarkably improved our ability to apply machine learning in several areas such as image and speech recognition. One of the success factors comes from the availability of large dataset which allows the model to discover true underlying patterns rather than meaningless noises. Training model with large data is often computationally expensive so we need efficient and scalable data processing systems to finish model training within a reasonable amount of time.

The current state of the art is to use several processors to run model training in parallel. Each processor does computation on distinct part of data concurrently and synchronises the training periodically among each other via centralised servers. However, this training style needs the right system configurations to achieve fast model training. If we configure system poorly, the training process can easily become unnecessarily long which we do not want in the first place.

Here we propose our solution which removes the complex part of system configuration. We present Ako; a deep learning training system that trains model in a decentralised style i.e. without centralised servers. The system uses a new synchronisation approach which relies on direct exchange of training information among processors. Since such information exchange is done over the bandwidth which is often limited, the approach sends partial information at a time to control bandwidth usage but ,at the same time, makes sure that complete information will be eventually exchanged. We ran experiments and the results confirmed that Ako results in faster model training compared to the centralised server approach while there is no need to configure the system.
