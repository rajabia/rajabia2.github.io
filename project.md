
#### [Research Projects](#academic-research-projects) | [Industrial Project](#industrial-project) | [Coursework Projects](#coursework-projects) | [Hobby Projects](#hobby-projects)

### Academic Research Projects

* **Image Privacy (2019-Present)** 
   - *Practical Adversarial Perturbation for Image Privacy:* Image hosting platforms are a popular way to store and share images with family members and friends. 
However, such platforms typically have full access to images raising privacy concerns.
These concerns are further exacerbated with the advent of Convolutional Neural Networks (CNNs) that can be trained on available images to automatically detect and recognize faces with high accuracy.
In this project, we  proposed two practical adversarial perturbation approaches for image privacy. Our paper for image privacy got accepted in Privacy Enhancing Technology symposium (PETs).

* **Robust Convolutional Neural Networks (CNNs) (2017-2020)**
   
   - *Detect and Reject Adversarial Examples:* Detection and rejection of adversarial examples in security sensitive and safety-critical systems using deep CNNs is essential. In this projecr, We aimed to detect and reject or classify adversarial examples correctly. To this end we proposed three methods:
   
  
      1. Using influence of diversity in the ensemble of CNNs on the detection of black-box adversarial instances and hardening the generation of white-box adversarial attacks. To this end, we proposed an ensemble of diverse specialized CNNs along with a simple voting mechanism. The diversity in this ensemble creates a gap between the predictive confidences of adversaries and those of clean samples, making adversaries detectable. [Paper](https://arxiv.org/pdf/2005.08321)
      
      2. Learning augment CNNs with out-distribution learning in order to reduce misclassification rate by rejecting adversarial examples. We empirically show that our augmented CNNs can either reject or classify correctly most adversarial examples generated using well-known methods (> 95% for MNIST and> 75% for CIFAR-10 on average). Furthermore, we achieve this without requiring to train using any specific type of adversarial examples and without sacrificing the accuracy of models on clean samples significantly (< 4%). [Paper](https://arxiv.org/pdf/1804.08794)
      
      3.  Learning adversarial profiles for each class using only one adversarial attack generation technique. We then wrap a detector around the pre-trained CNN that applies the created adversarial profile to each input and uses the output to decide whether or not the input is legitimate.
     
   
   - *Out-distribution Ranking for Leaning Robust CNNs:*  We proposed  learning Augmented CNNs on out-distribution samples as a simple and effective solution rejecting thise samples. However adding all posible OOD set to training set is not possible. In other words, a critical question remains unanswered in this work: how to select an OOD set, among the available OOD sets, for training such CNNs that induces high detection rates on unseen OOD sets? We address this pivotal question through the use of Augmented-CNN (A-CNN) involving an explicit rejection option. We first provide a formal definition to precisely differentiate OOD sets for the purpose of selection. As using this definition incurs a huge computational cost, we propose novel metrics, as a computationally efficient tool, for characterizing OOD sets in order to select the proper one. [Paper](https://arxiv.org/pdf/1910.08650)


* **Complex Netwok Analysis (2010-2013)**

  - *Local Community Detection  in Complex Networks and Sampling form Social Networks*   [Chaos Paper](http://coinlab.ut.ac.ir/documents/17321997/30927624/Sampling%20from%20Complex%20Networks%20with%20High%20Community%20Structures.pdf), [Report](./projects/ArezooRajabi.LCD-RW.pdf)
  
  - *Social Networks Topology Inference Using Diffusion Information*  [Manuscript](https://arxiv.org/pdf/1706.00941)

* **Power Systems Cyberbersecurity (2016-2019)** 

   - *False Data Tolerance Mechanisms for Distributed Mode Estimation:* Standard Alternating Direction of Multipliers Method (S-ADMM) and Distributed Alternating Direction of Multipliers Method (D-ADMM)  have been proposed to detect  oscillations in distributed power systems. Unfortunately, these two methods are vulnerable to false data injection attack. In this project, we proposed  two resiliency mechanisms for S-ADMM and D-ADMM that have been published in IEEE SmartGridComm and ICSS. This project was funded by Cyber Resilient Energy Delivery Consortium (CREDC) and National Science Foundation (NSF). [ACSAC2016](https://www.acsac.org/2016/program/files/03-Resilient%20Algorithm%20for%20Power%20System%20Mode%20Estimation%20using%20Synchrophasors-A-Rajabi.pdf), [SmartGridComm2019](https://ieeexplore.ieee.org/abstract/document/8909709)


### Industrial Project

* **Data Anonymization and Synthesis (problem submitted by Desjardins- 2020)** \
Issues surrounding the protection of personal data are garnering more and more attention in society. Machine learning requires big data as well as granular data: thus it involves challenges, especially the protection of personal data and the transformation of data so that they cannot be traced to individuals. In this project, we investigated  practices for anonymizing or synthesizing data that allows retain as many "original data" features as possible  which is required to develop good predictive models. 




### Coursework Projects

* **Knowledge Discovery in Relational Databases (CS 540)** The main objective of this project was to learn new concept from structured dataset such as relational database. We studied the behavior of three relational machine learning algorithm including First Order Inductive Logic (FOIL) , Top-Down Inductive Decision Tree (TILDE) and Mixture Model Membership. The results showed that the TILDE algorithm performs better than FOIL algorithm. [Report](./projects/ProjectProposalCS540.pdf), [Slides](./projects/CS540Presentation.pdf)

* **Frequency Estimation in Single-Frequency Complex Tone Problem from Limited Number of Noisy Observations** In this project, we investigated frequency estimation in single-frequency complex tone problem from limited number of noisy observations. To estimate this parameter, we used two different estimators and compare them with each other. Also, we derived the Carmer-Rao lower bounds for all parameters of multiple-frequency complex tone problem. We evaluated performance of each estimator in different noise level. [Report](./projects/Frequency_Estimation.pdf)

* **Movie Recommender System** Today, recommender systems are one of the main part of e-commerce business. These systems try to find similar items to ones that the target costumer was interested before based on the given rates to them. Besides of huge number of users an movies, the similar rates for two items can not guarantee that these items are similar in real-world. In this project, we proposed a method to decrease search space and demonstrated.[Report](projects/RecommenderSystem.pdf)

* **Dental Growth Rates Approximation** In this project, we tended to investigate the dental growth rate for 27 kids and compare the rates for girls and boys. In this regard, I used 3 different models to describe the dental growth rate. At the end, I used these models to predict jaw's size for random selected samples. [Report](projects/DentalGrowth.pdf)



### Hobby Projects

* **Practing Network Security Problems and Solutions** To deepen my knowledge in security analysis and real-world challenges I implemeted [SEED](https://seedsecuritylabs.org/Labs_16.04/Networking/) labs of:
   - *DNS Rebinding attacks: The objective of this lab is two-fold: (1) demonstrate how the DNS rebinding attack works, and (2) help students gain the first-hand experience on how to use the DNS rebinding technique to attack IoT devices.  However, due to firewalls and browser's sandbox protection, it is difficult for attackers to interact with the IoT servers. The goal of the attack in this lab is to use the DNS rebinding technique to circumvent these protections, so attackers can set the temperature value of the thermostat to a dangerously high value. 
   - *Cross-site Request Forgery:*  A CSRF attack involves a victim user, a trusted site, and a malicious site. The victim user holds an active session with a trusted site while visiting a malicious site. The malicious site injects an HTTP request for the trusted site into the victim user session, causing damages.
In this lab, an adversary will be attacking a social networking web application using the CSRF attack.

   - *PKI Lab:* Public key cryptography is the foundation of today's secure communication, but it is subject to man-in-the-middle attacks when one side of communication sends its public key to the other side. The fundamental problem is that there is no easy way to verify the ownership of a public key, i.e., given a public key and its claimed owner information, how do we ensure that the public key is indeed owned by the claimed owner? The Public Key Infrastructure (PKI) is a practical solution to this problem. By doing the tasks in this lab, one should be able to gain a better understanding of how PKI works, how PKI is used to protect the Web, and how Man-in-the-middle attacks can be defeated by PKI. 



