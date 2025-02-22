# What is a Tensor?

In the last video, we left off with the cliffhanger question: **What is a tensor?**

I also issued you a challenge to research what a tensor is because this course is not just about telling you what things are—it’s about sparking curiosity so you can discover the answers yourself. But now, let’s explore the concept together.

## Understanding Tensors in Deep Learning

If you recall the graphic of a neural network, you’ll remember that we start with some form of input data, which is numerically encoded before being passed to the neural network. The neural network then learns **representations** or **patterns** within that numerical encoding, producing an output representation that we can transform into something humans understand.

### What is a Tensor?

A **tensor** is essentially a representation of numerical data. It could be almost anything—an array, a matrix, or a higher-dimensional structure. In PyTorch, tensors are the fundamental building blocks used to represent and manipulate data.

Here’s a crucial takeaway:
- You have **some input data** (images, text, or audio).
- You need to **numerically encode** this data into a tensor.
- You pass this tensor to a **neural network**, which performs **mathematical operations** on it.
- The neural network outputs another tensor, which you then convert into something meaningful for humans.

### Example: Image Classification

Imagine we’re building an **image classification model** that distinguishes between a plate of spaghetti and a person named Raymond.
- The **input** consists of images.
- These images are converted into **numbers** (tensors).
- The **tensor** is passed to a neural network.
- The neural network applies **mathematical transformations** to this tensor.
- The network produces an **output tensor**, which we convert into a human-readable prediction (e.g., “spaghetti” or “Raymond”).

Even when working with **millions or billions of images**, the same principle holds: numerical encoding, mathematical transformations, and interpretation of the results.

## Moving Forward

We’ve now covered:
- What machine learning is.
- What deep learning is.
- What neural networks are.
- Why we use PyTorch.
- The role of tensors in deep learning.

Tensors are the **fundamental building blocks** of deep learning. In the next video, we’ll dive into coding and start working with PyTorch tensors directly. Get ready—we’re about to start writing some code!

See you in the next video!

