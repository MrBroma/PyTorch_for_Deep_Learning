# Neural Networks Overview

In the last video, we left off with the question: **What are neural networks?**

Let’s explore this together.

## What Are Neural Networks?

Neural networks are a type of algorithm that learns patterns in data. There are many definitions out there, but here's the one for our course:

### Inputs and Numerical Encoding
We start with some unstructured data like images, tweets, or speech. These inputs need to be converted into numerical form, as computers understand numbers. This is called **numerical encoding** or **representation**.

### The Neural Network Process
- **Input Layer**: Data is passed into the neural network as numbers.
- **Hidden Layers**: These layers perform mathematical operations on the inputs to discover patterns.
- **Output Layer**: The network produces the result based on the learned patterns.

## Types of Neural Networks
Different types of neural networks are suited to different tasks:
- **CNN (Convolutional Neural Network)**: Often used for image recognition.
- **Transformers**: Common in natural language processing and speech recognition.

### Learning Patterns
The neural network doesn't need us to define specific patterns. It learns these patterns or "features" on its own through training. These are often referred to as **weights** or **features**.

### Human-Understandable Outputs
Once the neural network has processed the data and learned patterns, it outputs something that can be interpreted by humans, such as:
- An image label (e.g., "ramen" or "spaghetti")
- A classification (e.g., "natural disaster" or "not a natural disaster")

## Anatomy of a Neural Network
The basic components of a neural network include:
1. **Input Layer**: Where data enters.
2. **Hidden Layers**: Layers that learn patterns.
3. **Output Layer**: The final result.

These components can be customized in many ways:
- **Number of layers**
- **Number of units in each layer**
- **Types of functions used**

### Example: Layers and Units
- **Input Layer**: 2 units
- **Hidden Layer**: 1 to many units (e.g., 3 units here)
- **Output Layer**: 1 unit

## Neural Network Architecture
The **architecture** refers to the entire structure of the network, including all layers and units.

## Functionality of Layers
Layers in a neural network use a combination of:
- **Linear functions** (straight lines)
- **Nonlinear functions** (curves)

Together, these functions help neural networks learn complex patterns in data.

## Next Video
In the next video, we’ll dive into the different learning paradigms of neural networks.
