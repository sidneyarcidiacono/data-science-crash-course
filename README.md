# Data Science Crash Course

Although the name is quite catchy, this repo will not necessarily make you a master data scientist, nor is it guaranteed to get you a job.

It is, however, a repository of useful starting points, project ideas, and curiosity-sparking resources that I plan on updating as I also go through this entry into data science and learn more.

It aims to focus on *the skills that matter* as a data scientist - from my perspective, which is subject to evolve as I gain more information.

This will not be structured as an academic course, and as such will require discipline and your own curiosity to maximize the materials I've gathered here. For each section there will be a folder in [resources]() containing diagrams, notes, and links to external sources. There will also be a notebook for *most* sections, which contain tutorials, project starting code, datasets to play with, etc.

## What Matters? -- What's in the 'Course'?

1. Mathematics
  - Statistics
  - Probability
  - Linear Algebra
  - Calculus

  Math is extraordinarily important for data scientists and machine learning engineers to understand. While high-level APIs like Keras make modeling feel easy for anyone with some knowledge of Python, to make meaningful optimizations, tweaks, or predictions, it's important to understand the math that these APIs abstract away for us.

  Some questions to ask yourself as you play with tools like Tensorflow, Keras, or SciKit Learn:

  - *What is an activation function?*
  - *How do neural networks learn?*
  - *What is dropout, why do we use it?*
  - *Why do we need to normalize? How do I know what scale to use?*

  All of these questions are answered once you dive a little deeper into the mathematics behind your favorite machine learning or deep learning algorithm! These are only *some* of the questions that we need to answer when we look at solving a problem with data science!

2. Design -- The Process

  I can't call this "system design" because there *are* system design questions related to data science, and those aren't really what I'm going to talk about here. Instead, what I want you to learn is the process we need to go through to begin solving a problem. These include:

  - Deciding on the problem--what is the desired outcome? What are we trying to do?
  - What data do we have? --And an equally important question depending on your use case, "what data do we need that we might not have already?"
  - What is the tool?
    - In other words, what statistical methods, machine learning or deep learning algorithms should we try? How do I know what to try first?
  - Data gathering, cleaning and preprocessing
  - What's our measure of success?

  Then, once you've done all these steps, usually you'll evaluate your success (or lack thereof) and try something different (different preprocessing methods, algorithms, etc.) until you get the outcome you want.

3. Good data

  You'll notice that this is *part* of number 2, and I'm mentioning it separately for good reason. You can only get SO far with really great, high-tech or novel modeling techniques. You also HAVE to have good data. I'll share some resources for figuring out *what that means* for your specific use cases.

4. Feature Selection/Feature Engineering

  While neural networks are great at learning predictive features, your typical machine learning (statistical) models won't do as well with noise, and besides, good feature selection and feature engineering can make your training and inferencing more performative (both in terms of accuracy and speed).

  But I'm getting ahead of myself. Find all the resources and practice projects you need in this section!

5. Modeling

  This is everyone's favorite part (mine too) because it's fun. I'll share resources for a myriad of different statistical and deep learning techniques as well as some notebooks for you to try your hand at different preprocessing, feature selection, and hyperparameter tuning techniques.
