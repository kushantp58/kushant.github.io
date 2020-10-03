---
title: "GANs by IAN GoodFellow"
category: Blog
category_slug: design
type: content
image: assets/img/works/work2.JPG
date: 2019-10-25 10:00:00
---

# The most interesting idea in Last 10 years of Machine Learning

Most of you might already know the answer to the above question- The GANs. GAN stands for Generative Adversarial Networks. Pitched at a pub one late night in Montreal, who knew Ian Goodfellow [1] will revolutionize the way of using Thor’s hammer. We all have come across some sort of algorithms which classifies images whether animals or humans. These algorithms have always been better at classifying images but what about creating new ones.

## GANs

An excellent example of innovations in deep learning, these provide a framework for creating new data instances which mimics training data. Consider an example of creating images of human faces which might not belong to a real person but still look like real photographs taken from some optical devices. The framework generally includes coupling with a generator which as the name suggests generates target output with a discriminator which then learns to differentiate the true form of image from the output produced by the generator.

![Image](https://static.wixstatic.com/media/191c7b_4c1a7eb2bb534d53a3bca64f8e3f8035~mv2.jpg/v1/fill/w_925,h_445,al_c,q_90,usm_0.66_1.00_0.01/191c7b_4c1a7eb2bb534d53a3bca64f8e3f8035~mv2.webp)

---
**[Image source - https://github.com/junyanz/CycleGAN]**

The images depicted above are generated using a specific class of GANs referred to as cyclic GANs. Let’s go into details of how these GANs work. The basic structures used for GANs are nothing but layers of CNNS (Convolution Neural Network) combined with batch normalization and Reinforcing Learning Unit with skip connections. For someone who doesn’t know much about neural networks, CNNs i.e. Convolutional Neural Networks are a perfect combo of Maths and Biology with CS used for garnishment. The most traditional but still very popular used networks for image processing and within image processing mainly used for image classification. Reducing the classification error from 26% to 15% for the first time in field of computer vision, these networks received its attention from ImageNet competition[2] where Alex Krizhevsky used CUDA with GPU support for creation of Alex Net [3]. Nowadays widely used for automatic tagging (Facebook), photo search or image browsing(google) , photo recommendations(Amazon) or search infrastructure(Instagram), these networks are fed an input image and their task is to classify that image and output a class(cat ,dog etc.) or a probability which fits a certain class. We never realize that our neural networks have this feature right from our birth, but we also learn it as we grow up. Even if we are shown an image which is somewhat unfamiliar to us, we won’t be able to identify it. The below meme still cracks me up.

![Image](https://static.wixstatic.com/media/191c7b_89d2c91b10b6448ea69635c7f277ec95~mv2.jpg/v1/fill/w_480,h_309,al_c,q_90,usm_0.66_1.00_0.01/191c7b_89d2c91b10b6448ea69635c7f277ec95~mv2.webp)

---
**[Image source -https://catchymemes.com/post/186718747582]**

So back to GANs, these networks are composed of two parts:

1. A generator – which generates negative training examples for the discriminator.

2. Discriminator – which is responsible for identifying fake image from a real form of the same.

Following diagram illustrates the whole system:

![Image](https://static.wixstatic.com/media/191c7b_9573e25da93145848ef35763118a3065~mv2.png/v1/fill/w_925,h_405,al_c,q_90,usm_0.66_1.00_0.01/191c7b_9573e25da93145848ef35763118a3065~mv2.webp)

---
**[Image source – google images]**

The generator and discriminator are neural networks, therefore one’s output(generator) is directly connected to another one’s input(discriminator). Now, we know that open loop systems don’t care about error and hence are bound to make mistakes, so the solution are always closed loop systems with proper feedback giving our systems an idea on how far they from true output are. This concept when implemented in neural networks takes the name Backpropagation, which is primarily used for performing gradient descent on neural nets. In short, the output values of each node are calculated in a forward pass and then a partial derivative of the errors is calculated w.r.t each parameter, in a backward pass.

![Image](https://static.wixstatic.com/media/191c7b_6a03dfb85b2e4193a160afd985525e1a~mv2.png/v1/fill/w_574,h_299,al_c,q_90,usm_0.66_1.00_0.01/191c7b_6a03dfb85b2e4193a160afd985525e1a~mv2.webp)

---
**[Image Source - https://www.guru99.com/backpropogation-neural-network.html]**

I’m not going to bore you with more technical details.

 GANs are very useful in every domain. They provide a wide variety of training datasets for a classifier to classify, they could prove useful for forensics, image editing, for attention prediction etc.

![Image](https://static.wixstatic.com/media/191c7b_52c76f6c14c64654aa558a867d7e395e~mv2.png/v1/fill/w_925,h_636,al_c,q_90,usm_0.66_1.00_0.01/191c7b_52c76f6c14c64654aa558a867d7e395e~mv2.webp)

---
**[Image Source -  https://arxiv.org/pdf/1609.04802.pdf]**

Following denotes use of GANs in different areas:

· Pose guided person image generation

![Image](https://static.wixstatic.com/media/191c7b_d13f05bdea8f4f02bebc8dd036d8bf8a~mv2_d_2104_1292_s_2.png/v1/fill/w_648,h_398,al_c,q_90,usm_0.66_1.00_0.01/191c7b_d13f05bdea8f4f02bebc8dd036d8bf8a~mv2_d_2104_1292_s_2.webp)

---

**[Image Source - Pose Guided Person Image Generation, Liqian Ma, Xu Jia, Qianru Sun,Bernt Schiele Tinne ,Tuytelaars Luc Van Gool1- https://papers.nips.cc/paper/6644-pose-guided-person-image-generation.pdf]**

· Image Editing

![Image](https://static.wixstatic.com/media/191c7b_98d87dbebef0459b9602d2291b29216d~mv2.png/v1/fill/w_923,h_281,al_c,lg_1,q_90/191c7b_98d87dbebef0459b9602d2291b29216d~mv2.webp)

· Progressive growing GANs for improved quality, stability and variation

![Image](https://static.wixstatic.com/media/191c7b_4baca477590640ea8b5094e0399c6b53~mv2.png/v1/fill/w_925,h_540,al_c,q_90,usm_0.66_1.00_0.01/191c7b_4baca477590640ea8b5094e0399c6b53~mv2.webp)

**[Source - Progressive growing GANs for improved quality, stability and variation- Tero K., Timo A., Samuli L., Jaakko Lehtinen etc.]**

## References Used

*[1]. (n.d.). Retrieved from  https://en.wikipedia.org/wiki/ImageNet#ImageNet_Challenge*

*[2]. GoodFellow, I. (n.d.). http://www.iangoodfellow.com/.  Retrieved from http://www.iangoodfellow.com/: http://www.iangoodfellow.com/*

*[3]. Krizhevsky, A. (Retrieved 17 November 2013.).  "ImageNet classification with deep convolutional neural networks".*

*I've used an implementation of cyclic GANs using python in my research work, so if anyone of you wants to know more about it, just drop me a mail at mentioned mail id. I'll be more than happy to assist you.*