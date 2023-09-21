# Vision Transformer


In this repository, we present our from-scratch implementation of the Vision Transformer (ViT), a breakthrough architecture for image classification tasks that relies on transformer structures traditionally used in NLP.

**Overview**

The Vision Transformer works by first splitting an image into fixed-size patches and then linearly embedding them into a sequence of vectors. These vectors are then processed by a series of Transformer blocks, specifically the multi-head self-attention mechanism, to generate global feature representations for classification.


## Process Breakdown

### Split into Patch

<img src = './img/00.png'>

### Sent to mult-head attention

<img src = './img/01.png'>

#### Q

<img src = './img/02.png'>

#### K

<img src = './img/03.png'>