---
layout: post
title:  "Combatting Deepfakes with AI"
author: Durbar
categories: [artificial intelligence, Deepfakes, Cybersecurity, Face Detection]
image: assets/images/combatting_deepfakes-images/DF1.png
wide_image: assets/images/combatting_deepfakes-images/deepfake2.jpg
thumb_image: assets/images/combatting_deepfakes-images/deepfake1.jpg
last_added: false
hidden: false
---

It won’t be an overstatement to assert that today’s digital world almost solely relies on computers and cyber technologies in nearly every public sphere- from simple one-to-one communication to large-scale broadcasting to high-security message transmission. With exponentially escalating relevance of these technologies, rises the importance of cybersecurity. And in recent times, deepfakes pose one of the biggest threats to cybersecurity.

### What do we really mean by ‘Deepfakes’?

A deepfake is a fraudulent piece of content, which may include videos or audio recordings, that has been manipulated or created using Artificial Intelligence (AI). Deepfake tech is still young and is not yet sophisticated enough to pose a major threat across the world. However, a number of deepfake videos of world leaders like Barack Obama that went viral in the recent past proved that it is capable of turning into a major security breach issue in the near future.

### How do Deepfakes compromise security?

The first recorded deepfake attack took place in March 2019 and was revealed by insurance company Euler Hermes. According to Hermes, the UK-based CEO heard his boss’s voice- which had exactly the right tone, intonation and accent- asking him to transfer $243,000, supposedly into the account of a Hungarian supplier. The CEO did exactly as he was instructed, only to learn that he had been tricked.

An April 2021 report from _Recorded Future_ found evidence that malicious actors are increasingly looking to leverage deepfake technologies to use in cybercrime. The report shows how users of certain dark web forums, plus communities on Discord and Telegram, are discussing how to use deepfakes to carry out social engineering, fraud and blackmail.

### How are Deepfakes generated?

The technology behind deepfakes is abbreviated as **GANs**, for **Generative Adversarial Networks**. It’s a powerful Neural Network that was developed by Ian Goodfellow in 2014 for use in Machine Learning. The setup uses two neural networks, algorithms that are loosely based on our brain’s wiring, and train them on the same datasets of images, videos and audio. The first neural network is known as the generator network. It generates fake pieces of content based on what it learns from the dataset. The other neural network, called the discriminator, acts as an “investigator” and looks at the new creation and tries to determine whether it is a fake produced by the generator.

<div align="center">
 <img src="/assets/images/combatting_deepfakes-images/DF1.png"/>
</div>
<br>

The generative model captures the distribution of data and is trained in such a way that it tries to maximize the probability of the Discriminator in making a mistake. The Discriminator, on the other hand, is based on a model that is meant to calculate the probability that the received dataset is obtained from the learning data and not the Generator.

<div align="center">
 <img src="/assets/images/combatting_deepfakes-images/DF2.png"/>
</div>
<br>

### How can we combat Deepfakes?

In recent times, research shows there are several emerging technical loopholes that help AI detect Deepfakes:
1.  **Blink speeds:** Research shows that it’s possible to detect deepfake videos with AI by examining blinking patterns of the subject in the video. Since GANs use still images as their source material, when photos of someone blinking are published, the act of 
blinking is not well replicated in the videos.

1.  **Facial Warping:** Because of current processing resource constraints, the still images used must be processed at a common fixed resolution. However, the size and resolution of a face in video changes as camera angles shift or zoom in and out. Researchers have found a way to exploit this for detection of deepfakes.

1. **Contextual Clues:** Instead of analyzing individual frames of the video, when the entire context is considered, these deepfakes often fall short to generate an entirely plausible base. Consequently, this fallacy can be exploited as well to detect fakes.

<div align="center">
 <img src="/assets/images/combatting_deepfakes-images/DF3.png"/>
</div>
<br>

### Conclusion
At the end of the day, technological means for prevention of deepfakes have their own limitations, regardless of their efficiency. As a result, improved public awareness needs to be an additional aspect of the strategy for combatting deepfakes. Only through prudent judgement can we overcome this potential menace in the future.

### References:

- [https://blog.cdw.com/security/using-ai-to-combat-deepfakes](https://blog.cdw.com/security/using-ai-to-combat-deepfakes)
- [https://www.brookings.edu/blog/techtank/2019/02/14/artificial-intelligence-deepfakes-and-the-uncertain-future-of-truth/](https://www.brookings.edu/blog/techtank/2019/02/14/artificial-intelligence-deepfakes-and-the-uncertain-future-of-truth/)
- [https://www.tessian.com/blog/what-are-deepfakes/](https://www.tessian.com/blog/what-are-deepfakes/)
- [https://opendatascience.com/using-ai-to-combat-deepfakes-and-fake-news/](https://opendatascience.com/using-ai-to-combat-deepfakes-and-fake-news/)
- [https://blog.electroica.com/gan-neural-network-for-transfer-learning-is-absolutely-creative](https://blog.electroica.com/gan-neural-network-for-transfer-learning-is-absolutely-creative)

> **Note** :
> Utmost care has been taken to credit the original authors/sources and to make these as apt as possible.
