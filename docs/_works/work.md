---
title: "Algorithmic Bias"
category: Blog
category_slug: design
type: content
image: assets/img/works/work1.JPG
date: 2019-10-24 10:00:00
---


# Algorithmic Bias - A tool of manipulation

  
## Introduction

In 2018, an estimated 2.65 billion people were using social media worldwide, a number projected to increase to almost 3.1 billion in 2021[1]. Social platforms including Instagram, Facebook, twitter where a single feed of Greta Thunberg’s speech at UN’s 2019 climate action summit or Justin Trudeau’s liberal party winning 2019 general elections can govern people’s opinion about them or the viewpoint, they are taking stand for. The cognitive ability of Homo Sapiens allow them to take a stand either in favor or against a certain perspective, but manipulation has crept into their way of thinking. This manipulation which I’m talking about is regarding the algorithms that govern this social media on the back-end. Have you ever considered the fact that machine can be racist and that the algorithms and AI can be inherently prejudiced and that social platforms can have biases? But based on my research and findings, situations have come around when a tech industry was involved in such controversies. Well, the answers are complicated. Considering an example, Google’s search algorithm had no reason to offend the republicans, it just sought best results by looking at more than 200 signals [3]. Google relies on automated programs referred to as crawlers and has a large index of keywords just like any other browsers but what differentiates it from the rest is how it ranks it’s results which is done by a trademarked algorithm, PageRank setting up the relevancy score. But the procedure is so complicated according to it’s CEO that programmers who wanted to take out the rage at Republicans can’t possibly train algorithm according to their will. But the main question that needs to be answered here is whether enough efforts are being taken by tech industry to address the problem of bias. But the answer is no.
Dichotomy between Biased world and reality

Machine learning algorithms can produce results that can be biased due to erroneous assumptions made during the learning phase of the algorithms. These biases can be created knowingly or un knowingly and might be unknown until algorithms are implemented and which can amplify results. The bias can get embedded into learning processes and the standard practices are built to detect them. Most of the AI applications being used today consist of deep learning which involves dealing with patterns of the data. Since most of them affect people’s lives including usage in recruitment for companies, retail, security, forensics, criminal legal system [2]. The only resort to the problem of bias currently addressed is by ensuring that data fed into these algorithms is unbiased. But to feed unbiased data into these algorithms, it’s up to humans to train the system with unbiased data. But giving a magic handle in the hands of humans and expecting them to not play with fire on the way seems dangerous. It means the companies need to train their engineers and data scientists to understand the concept of bias themselves and learn how to combat.
Should the measures be taken to remove bias?

Most of the firms have frequently come under attack for a variety of algorithms they count on for implementation. Now why do we consider bias as a bad thing? The simple response to that would be because it directs us away from the truth. It sorts of creates filter which can alter our perception of reality. Like for sample we all know about the war of the currents[4] where Thomas Edison thought DC(Direct Current) was a better idea than AC(Alternating Current) but what he was doing was trying to save his own setup business by biasing people’s view and hiding the reality that AC in fact proved to be a long term reliable solution. God knows what would have been the condition if George Westinghouse and Nikola had not won that war, you would still be using DC power distribution systems and at the same time paying 4-5 time for your electric bill. Even the Instagram feeds or Facebook posts won’t affect your lives that much as the algorithms used for identifying criminals can. Even small pieces of wrong implementation can determine the trajectory of your life with you winding up in a prison cell for your life. Yes, that’s true. American Criminal Systems depend on automated tools in attempt to shuffle defendants through a legal system as safely as possible [5]. Facial recognition systems are used by law enforcement for identification of suspects, but even at their best implementation levels, these systems can fail spectacularly. Results are evident of that. In the courtroom, judges are making their decisions on basis of data driven recommendations and not on their guts [5]. Most of this work is centred around finding patterns in the data, they look for a person’s historical crime data and picks traits associated with crime. In conclusion, algorithmic bias can affect us one or in another way, we are being driven whom to vote, whom to like or not, etc. Some measures for mitigating bias have been implemented like adversarial de-biasing, encoding invariant representations with semi supervised, variational fair encoder, preventing disparity amplification etc. [6]. 
AIF360(AI Fairness 360 – open source toolkit from IBM)

We are going to discuss on such toolkit from IBM which helps in prevention of unwanted bias. AIF360(AI fairness 360) [7] is an open source toolkit designed for checking of unwanted bias in learning models and datasets. It also checks for algorithms for fairness. The initial release of this toolkit consisted of a python package which involved nine different algorithms developed by the community to mitigate unwanted bias. They all follow a generic approach while designing models. It’s a broader concept to translate collective results for usage by data scientists, software developers, data engineers. It consists of tutorials on credit scoring, predicting medical expenditures and classifying face images by gender.
![Image](https://static.wixstatic.com/media/191c7b_d48dedb7f6b8423bae7eeaf140966ada~mv2.png/v1/fill/w_925,h_484,al_c,q_90,usm_0.66_1.00_0.01/191c7b_d48dedb7f6b8423bae7eeaf140966ada~mv2.webp) 
---
***[Image Courtesy: (https://www.ibm.com/blogs/research/2018/09/ai-fairness-360/)]***

The toolkit also comes with an interactive web UI which provides concepts and capabilities for business users, detailed documentation and for researchers trying to integrate the tool for problem into their products [8].

Following diagram illustrates its detailed pipeline for bias mitigation
![Image](https://static.wixstatic.com/media/191c7b_2aa8449a36624572b9c66a766f73d736~mv2.png/v1/fill/w_925,h_485,al_c,q_90,usm_0.66_1.00_0.01/191c7b_2aa8449a36624572b9c66a766f73d736~mv2.webp) 
---
***[Image Courtesy: AI FAIRNESS 360: AN EXTENSIBLE TOOLKIT FOR DETECTING,
UNDERSTANDING, AND MITIGATING UNWANTED ALGORITHMIC BIAS paper - https://arxiv.org/pdf/1810.01943.pdf]***

We are not going to further dive into its detailed working. AIF360 is designed for providing an end to end workflow with just two aims: 1) ease of use and 2) extensible. Fairness seems to be a complicated concept.  Concluding with the fact that even though efforts are being made to avoid bias we need to take it as a potential threat which can affect our lives. We ourselves also need to know the difference between biased world and reality.

## References

*[1]. Number of global social network users -https://www.statista.com/statistics/278414/number-of-worldwide-social-network-users/*

*[2]. This is how AI bias really happens—and why it’s so hard to fix by Karen Hao. (https://www.technologyreview.com/s/612876/this-is-how-ai-bias-really-happensand-why-its-so-hard-to-fix/)*

*[3]. https://www.cnn.com/2018/03/21/politics/trump-campaign-cambridge-analytica/index.html*

*[4]. https://www.energy.gov/articles/war-currents-ac-vs-dc-power*

*[5]. https://www.technologyreview.com/s/612775/algorithms-criminal-justice-ai/*

*[6]. https://towardsdatascience.com/algorithmic-solutions-to-algorithmic-bias-aef59eaf6565*

*[7]. https://www.ibm.com/blogs/research/2018/09/ai-fairness-360/*

*[8]. AI FAIRNESS 360: AN EXTENSIBLE TOOLKIT FOR DETECTING,
UNDERSTANDING, AND MITIGATING UNWANTED ALGORITHMIC BIAS - https://arxiv.org/pdf/1810.01943.pdf*
