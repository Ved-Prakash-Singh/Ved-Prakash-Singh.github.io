---
layout: post
title: Type of Machine Learning Algorithms
---

Broadly, Machine Learning Algorithms can be categorized into below mentioned categories
1. Supervised Learning: <br> In Supervised Learning algorithm, machine needs label (external supervision) to learn the pattern in the input features, so that once trained, the model can predict label for the unlabelled data just based upon input features, using the learned pattern. The label used as external supervision, and during the learning process, machine try to come up with some function which predicts the label with least error. Once, machine has learned then it can predict the label based upon input features.
2. Unsupervised Learning: In Unsupervised Learning algorithm, machine doesn't need label (no external supervision) to learn the pattern. The objective here is different from the objective in Supervised Learning algorithm. In unsupervised learning, the optimization process is driven by the algorithm's specific goals, whether it's grouping similar data points, capturing important features, generating realistic samples, or estimating underlying distributions. The absence of explicit labels makes the optimization more focused on the intrinsic properties of the data rather than error with respect to labeled targets.
   Below mentioned are some example of Unsupervised Learning algorithms -
   a. Clustering Algorithms
   b. Dimensionality Reduction
   c. Association Rule Learning
   d. Density Estimation
3. Semisupervised Learning: In semi-supervised learning, the training dataset consists of a combination of labeled and unlabeled examples. The primary goal is to leverage the information contained in both labeled and unlabeled data to improve the performance of a machine learning model.

   Semi-supervised learning is a machine learning paradigm where the model is trained on a dataset that contains both labeled and unlabeled data. One common application of semi-supervised learning is in the field of image classification.

   Imagine you have a large dataset of images, but labeling each image with the corresponding category is time-consuming and expensive. In a semi-supervised approach, you might have a small subset of images that are labeled, while the majority of the dataset remains unlabeled. The model is then trained on both the labeled and unlabeled data.

   For example, consider a scenario where you want to build an image classifier to identify different species of animals. You have a small set of images with labeled examples of various animals like cats, dogs, and birds, but the majority of your images are unlabeled. In a semi-supervised learning approach, you could use the labeled data to initially train the model and then leverage the large pool of unlabeled data to improve the model's performance further.

   The model learns to generalize from the labeled examples and makes predictions on the unlabeled data. The predictions on the unlabeled data are then used to iteratively refine the model. This approach can be particularly useful when acquiring labeled data is challenging or expensive, as it allows for leveraging the available unlabeled data to enhance the model's performance.


4. Reinforcement Learning: In reinforcement learning, agent (model) learns to make sequences of decisions by interacting with an environment. The agent receives feedback in the form of rewards or punishments based on the actions it takes, and its goal is to learn a strategy, known as a policy, that maximizes the cumulative reward over time. Reinforcement learning is inspired by how humans and animals learn from trial and error to achieve goals in dynamic and uncertain environments. Popular Reinforcement Learning algorithms include Q-Learning, Deep Q Networks (DQN), Policy Gradient methods, and Actor-Critic methods.
   
5. Self-supervised Learning: Self-supervised learning algorithms trains based upon unsupervised dataset in supervised manner. This can be achieved by framing a supervised learning task in a special form to predict only a subset of information using the rest. In this way, all the information needed, both inputs and labels, has been provided. This is known as self-supervised learning.
