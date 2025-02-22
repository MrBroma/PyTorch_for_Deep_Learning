# Learning Paradigms in Neural Networks

## 1. Supervised Learning
Supervised learning is when we have **data** and **labels**. For example, in the case of cooking a Sicilian grandmother's famous roast chicken, the data could be raw ingredients like vegetables and chicken, and the labels would describe the ideal outcome. 

Another example: In a **cat vs. dog** image classification problem, you have a thousand photos of cats and a thousand of dogs, each labeled accordingly. The machine uses this labeled data to learn to discern patterns between the two.

### Key Points:
- **Data** and **labels** are required.
- The model learns from labeled examples.
  
## 2. Unsupervised Learning & Self-Supervised Learning
Unsupervised learning and self-supervised learning don't use labels. You only have **data** itself.

### Unsupervised Learning:
- The algorithm learns patterns or representations (like features or weights) from the data without any pre-defined labels.

### Self-Supervised Learning:
- The model learns internal representations from the data, but does not know the actual categories (like distinguishing between cats and dogs). You can later interpret the learned patterns to categorize them.

### Key Points:
- **Data** without **labels** is used.
- The model learns representations from the data without predefined categories.

## 3. Transfer Learning
Transfer learning is a powerful method where you take a model pre-trained on one dataset and transfer the patterns it has learned to another model. 

For example, in a cat vs. dog image classifier, you might start with a model that has already learned general image patterns. Then, you can fine-tune this model to recognize specific patterns for distinguishing cats from dogs.

### Key Points:
- **Transfer learned patterns** from one model to another.
- **Speeds up training** and improves performance on new tasks.

## 4. Reinforcement Learning (Extension)
Reinforcement learning is a different paradigm where an agent interacts with an environment. The agent performs actions, receives feedback, and is either rewarded or punished based on its actions. 

For example, if you wanted to train a dog to urinate outside, the dog would be rewarded for urinating outside and not rewarded for urinating inside.

### Key Points:
- Involves an **agent** and an **environment**.
- **Rewards** and **punishments** guide learning.

### Note:
While this course will focus on **supervised learning** and **transfer learning**, you are encouraged to explore other paradigms like reinforcement learning on your own.

## Next Steps
- Think about what deep learning is currently used for.
- Try searching and coming up with some of your own examples for deep learning applications.
