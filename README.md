![image](https://github.com/Building-ML-Pipelines/Building-ML-Pipelines.github.io/raw/main/book_cover_jul20.png)

# Order your copy today!

{:refdef: style="text-align: center;"}
[Read on the O'Reilly platform](https://learning.oreilly.com/library/view/building-machine-learning/9781492053187/)
{: refdef}

{:refdef: style="text-align: center;"}
[Order from Amazon](https://www.amazon.com/Building-Machine-Learning-Pipelines-Automating/dp/1492053198/)
{: refdef}

{:refdef: style="text-align: center;"}
[Order from Powell’s](https://www.powells.com/book/building-machine-learning-pipelines-9781492053194)
{: refdef}

# From the Preface
Everybody’s talking about machine learning. It’s moved from an academic discipline to one of the most exciting technologies around. From understanding video feeds in self-driving cars to personalizing medications, it’s becoming important in every industry. While the model architectures and concepts have received a lot of attention, machine learning has yet to go through the standardization of processes that the software industry experienced in the last two decades. In this book, we’d like to show you how to build a standardized machine learning system that is automated and results in models that are reproducible.

# Who Is This Book For?
The primary audience for the book is data scientists and machine learning engineers who want to go beyond training a one-off machine learning model and who want to successfully productize their data science projects.

You should be comfortable with basic machine learning concepts and familiar with at least one machine learning framework (e.g., PyTorch, TensorFlow, Keras). The machine learning examples in this book are based on TensorFlow and Keras, but the core concepts can be applied to any framework.

A secondary audience for this book is managers of data science projects, software developers, or DevOps engineers who want to enable their organization to accelerate their data science projects. If you are interested in better understanding automated machine learning life cycles and how they can benefit your organization, the book will introduce a toolchain to achieve exactly that.

# What Did Readers Think?

> “I wish this book had existed when I started working in production ML! It’s an outstanding resource for getting a comprehensive view of production ML systems in general, and TFX in particular. Hannes and Catherine have worked directly with the TensorFlow team to get the most accurate information available for including in this book, and then explained it in clear, concise explanations and examples.”
**—Robert Crowe, TensorFlow Developer Advocate, Google**

> “As a person who had only used TensorFlow as a framework for training deep learning models, when reading this book I was amazed at the pipeline capabilities that the TensorFlow ecosystem has to offer. This book is a great guide to all of the tools for analyzing and deploying models available with TFX, and is easy to read and use for people looking to make their first machine learning pipeline with TensorFlow.”
**—Dr. Jacqueline Nolis, Principal Data Scientist, Brightloom and coauthor of Build a Career in Data Science**

> “This book is an exceptional deep-dive into Machine Learning Engineering. You will find cogent and practical examples of what it takes to build production-ready ML infrastructure. I would consider this required reading for any engineer or data scientist who intends to apply ML to real-world problems.”
**—Leigh Johnson, Staff Engineer, Machine Learning Services, Slack**

> “The data science practitioner knows that real-world machine learning involves more than just machine learning model training. This book demystifies the hidden technical debt in modern machine learning workflows such that you can put the lab and factory data science patterns into production as repeatable workflows.”
**—Josh Patterson, CEO, Patterson Consulting, Coauthor of Deep Learning: A Practitioner’s Approach and Kubeflow Operations Guide**

> “Wonderfully readable, Building Machine Learning Pipeline serves not only as a comprehensive guide to help data scientists and ML engineers build automated and reproducible ML pipelines, but it is also the only authoritative book on the subject. The book provides an overview of the clearly defined components needed to architect ML pipelines successfully and walks you through hands-on code examples in a practical manner.”
**—Adewale Akinfaderin, Data Scientist, Amazon Web Services**

> “I really enjoyed reading Building Machine Learning Pipelines. Having used TFX for several years internally at Google as it was growing, I must say I wish I had your book back then instead of figuring this all out on my own. You would have saved me many months of effort and confusion. Thanks for writing such a high quality guide!”
**—Lucas Ackerknecht, Machine Learning Specialist, Anti-Abuse Machine Learning, Google**

> “We all have some of these amazing prototype models lying around. This book will introduce you to the tools and techniques that will help you take that prototype to production. Not only that but you will also build a complete end-to-end pipeline around it so that any future enhancements get delivered automatically and smoothly. This is a great book for beginners in ML ops who want to take their skills to the next level and collaborate with larger teams to help realize the values of innovative new models.”
**—Vikram Tiwari, Cofounder, Omni Labs, Inc.**

# Overview of the Chapters

**Chapter 1** Introduction gives an overview of machine learning pipelines, discusses when you should use them, and describes all the steps that make up a pipeline. We also introduce the example project we will use throughout the book.

**Chapter 2** Introduction to TensorFlow Extended introduces the TFX ecosystem, explains how tasks communicate with each other, and describes how TFX components work internally. We also take a look at the ML MetadataStore and how it is used in the context of TFX, and how Apache Beam runs the TFX components behind the scenes.

**Chapter 3** Data Ingestion discusses how to get data into our pipelines in a consistent way and also covers the concept of data versioning.

**Chapter 4** Data Validation explains how the data that flows into your pipeline can be validated efficiently using TensorFlow Data Validation. This will alert you if new data changes substantially from previous data in a way that may affect your model’s performance.

**Chapter 5** Data Preprocessing focuses on preprocessing data (the feature engineering) using TensorFlow Transform to convert raw data to features suitable for training a machine learning model.

**Chapter 6** Model Training discusses how you can train models within machine learning pipelines. We also explain the concept of model tuning.

**Chapter 7** Model Analysis and Validation introduces useful metrics for understanding your model in production, including those that may allow you to uncover biases in the model’s predictions, and discusses methods to explain your model’s predictions. “Analysis and Validation in TFX” explains how to control the versioning of your model when a new version improves on a metric. The model in the pipeline can be automatically updated to the new version.

**Chapter 8** Model Deployment with TensorFlow Serving focuses on how to deploy your machine learning model efficiently. Starting off with a simple Flask implementation, we highlight the limitations of such custom model applications. We will introduce TensorFlow Serving and how to configure your serving instances. We also discuss its batching functionality and guide you through the setup of clients for requesting model predictions.

**Chapter 9** Advanced Model Deployments with TensorFlow Serving discusses how to optimize your model deployments and how to monitor them. We cover strategies for optimizing your TensorFlow models to increase your performance. We also guide you through a basic deployment setup with Kubernetes.

**Chapter 10** Advanced TensorFlow Extended introduces the concept of custom components for your machine learning pipelines so that you aren’t limited by the standard components in TFX. Whether you want to add extra data ingestion steps or convert your exported models to TensorFlow Lite (TFLite), we will guide you through the necessary steps for creating such components.

**Chapter 11** Pipelines Part I: Apache Beam and Apache Airflow connects all the dots from the previous chapters. We discuss how you can turn your components into pipelines and how you’ll need to configure them for the orchestration platform of your choice. We also guide you through an entire end-to-end pipeline running on Apache Beam and Apache Airflow.

**Chapter 12** Pipelines Part 2: Kubeflow Pipelines continues from the previous chapter and walks through end-to-end pipelines using Kubeflow Pipelines and Google’s AI Platform.

**Chapter 13** Feedback Loops discusses how to turn your model pipeline into a cycle that can be improved by feedback from users of the final product. We’ll discuss what type of data to capture to improve the model for future versions and how to feed data back into the pipeline.

**Chapter 14** Data Privacy for Machine Learning introduces the rapidly growing field of privacy-preserving machine learning and discusses three important methods for this differential privacy, federated learning, and encrypted machine learning.

**Chapter 15** The Future of Pipelines and Next Steps provides an outlook of technologies that will have an impact on future machine learning pipelines and how we will think about machine learning engineering in the years to come.

**Appendix A** Introduction to Infrastructure for Machine Learning gives a brief introduction to Docker and Kubernetes.

**Appendix B** Setting Up a Kubernetes Cluster on Google Cloud has some supplementary material on setting up Kubernetes on Google Cloud.

**Appendix C** Tips for Operating Kubeflow Pipelines has some useful tips for operating your Kubeflow Pipelines setup, including an overview of the TFX command-line interface.

# Questions? Comments?

Contact the authors at [buildingmlpipelines@gmail.com](buildingmlpipelines@gmail.com)
