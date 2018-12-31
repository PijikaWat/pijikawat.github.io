---
title: "Similaire: Medical image search"
excerpt: "<img src='/images/medimagesearch.png' width='500'>"
collection: portfolio
---

Similaire is a prototype of image search system that is based on image similarity. The system is a computer-aided decision making system that helps physicians identify clinical abnormalities presented in images taken by a new type of endoscope called endomicroscope.

The endomicroscopic technology gives us an in-depth information about colon tissue and this enables us to detect disease progression much earlier than the standard endoscope. Meaning that patients have more chance to be cured with the early detection. Unlike traditional colonoscope where it is straightforward to identify abnormal growing tissue (mass), it can be challenging to interpret these images as they are presented in microscopic view (tissue-level). This, as a result, requires learning curve from physicians.

In this work, we think that it makes sense to have a system that helps physicians to interpret these special images in order to maximise the benefit of this technology.

Similaire is an image search system. When given an image to identify, it searches through its medical database, which is full of images attached with correct diagnosis, and returns a set of resulting images that are similar to the one in question. The system calculates similarity between images based on the actual image content, not metadata. Another word, it takes Content-based image retrieval (CBIR) approach. To compare such content, the system relies on Gabor filters which extract information of edge and shape within the image. In fact, we also use similar edge detector in our human visual system.

The search in Similaire is also adaptive. The system can take feedbacks from the user and further tune the search according to the relevance information from the feedback. With this adaptive search functionality, the system can return as similar and relevant images as possible.

Similaire does not make any diagnosis. Instead, it assists physicians by giving more clues and useful information which enables them to interpret endomicroscopic images and eventually make the final diagnosis.
