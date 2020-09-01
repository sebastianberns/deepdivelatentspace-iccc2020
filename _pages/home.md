---
permalink: /
title: "A Deep Dive into Latent Space: Image Generation and Manipulation with StyleGAN2"
excerpt: "Home"
author_profile: true
redirect_from:
  - /home/
  - /home.html
---

This tutorial introduces the concept of latent spaces in deep generative models, specifically StyleGAN2, and the possibilities of image generation and manipulation they provide. Focusing on a model trained on photographs of human faces, we will demonstrate how to localise the latent representation of a given image (e.g. a participant’s own face) in order to blend it with another and how to create an animation of the interpolation between the two.

[Sebastian Berns](https://sebastianberns.com), Queen Mary University of London<br>
[Terence Broad](https://terencebroad.com), Goldsmiths, University of London


Tutorial Structure
======
The tutorial is set up around an online code notebook and presented in two parts. The first part gives an overview of theory and technical background knowledge, and the second is a guided walk through the exercises in the notebook.


Part One: Theory and Background
======
Exercises in this tutorial are based on a pre-trained StyleGAN2 model, which employs particular architectural choices. The first part of the tutorial provides an overview over the progressive improvements and changes that helped evolve the original GAN proposal into the current state-of-the-art networks. The topics covered here build the base for a better technical understanding of the exercises in the second part of the tutorial.

Presentation slides: [ICCC 2020 Deep Dive Latent Space Tutorial Theory.pdf](https://drive.google.com/file/d/1bJ-atnS1B2jH2Mi437MTnkB1POHGmFl7/view?usp=sharing)

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/vu84G6McaCo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

&nbsp;

Part Two: Notebook Walk-through
======
The video below will guide through the exercises that are set up in the notebook: [deepdivetutorial.ipnyb](https://colab.research.google.com/drive/1PlvXkqgxyvJytA7muvdYuAznjCHnAa2B?usp=sharing).

The code repository used in the exercises: [terrybroad/deepdivelatentspace-tutorial-code](https://github.com/terrybroad/deepdivelatentspace-tutorial-code)

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/r3Vg2Z7SI4E" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

&nbsp;

Live Q&A Sessions
======
The tutorial organisers will be available for questions and discussion in two sessions on Monday, 7 September 2020. Feel free to join at any time.

Session 1<br>
9 am – 12 pm GMT+1

Session 2<br>
5 pm – 8 pm GMT+1


Additional Resources
======
- StyleGAN
  - [Original paper](https://arxiv.org/abs/1812.04948)
  - [StyleGAN2 paper](https://arxiv.org/abs/1912.04958)
  - [StyleGAN2 official TensorFlow implementation](https://github.com/NVlabs/stylegan2)
- Sampling Generative Networks
  - [Paper](https://arxiv.org/abs/1609.04468)
- StyleGAN2 Distillation for Feedforward image manipulation
  - [Paper](https://arxiv.org/abs/2004.02546)
  - [Github repo](https://github.com/EvgenyKashin/stylegan2-distillation)
- GANSpace: Discovering Interpretable GAN Controls
  - [Paper](https://arxiv.org/abs/2004.02546)
  - [Code](https://github.com/harskish/ganspace)
  - [Colab notebook](https://colab.research.google.com/github/harskish/ganspace/blob/master/notebooks/Ganspace_colab.ipynb)


Shameless Plugs
======
Berns and Colton. 2020. Bridging Generative Deep Learning and Computational Creativity. Proceedings of the 11th International Conference on Computational Creativity. [Paper](http://sebastianberns.com/iccc2020bridging/)

Broad, Leymarie and Grierson. 2020. Network Bending: Manipulating The Inner Representations of Deep Generative Models. [Paper](https://arxiv.org/abs/2005.12420), [code](https://github.com/terrybroad/network-bending), [colab notebook](https://colab.research.google.com/github/dvschultz/ml-art-colabs/blob/master/Network_Bending_Static_Images.ipynb)
