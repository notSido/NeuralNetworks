# Understanding Neural Networks
###### *Author: Mikhail Sidorenko*
###### *2024*

---
## 1.1 The History of Neural Networks
### 1.1.1 The Pre-Computing Era
#### The McCulloch-Pitts Model
The very first attempt at creating a neural network was made in 1943 by neurophysiologist **Warren McCulloch** and mathematician **Walter Pitts**, after authoring a whitepaper titled *A Logical Calculus of the Ideas Immanent in Nervous Activity*[^1]. The goal of the paper was to gain a better understanding of how the mammalian brain functions. This is important to note because, at that time, their goal was not to create Artificial Intelligence, this topic will be touched on later. To practically demonstrate their theory, they created a simple neural network in the form of an electrical circuit[^2], which was, quite predictably, very limited in its capabilities, mainly due to its incredibly simplistic nature. None the less, their work set the stage for future advancements in neural network research.

#### The Emergence of Hebbian Learning
6 years later, in 1949, **Donald Hebb** published *The Organization of Behaviour*[^3], where he introduced the concept of **Hebbian learning**[^4]. He argues that if two neurons fire at the same time, the connection between them is reinforced. This concept is fundamental to our understanding of learning processes in the brain and serves as the basis for many theories of synaptic plasticity.

Hebb's research laid the foundation for research into neural plasticity and the mechanisms underlying learning and memory. His concept of Hebbian learning has had a profound impact on both neuroscience and artificial intelligence, shaping not only our understanding of how neural networks adapt and learn from experience, but also increasing our understanding of how we as humans learn.

Today, Hebbian learning remains a key concept in computational neuroscience and machine learning, with applications ranging from the development of learning algorithms in artificial neural networks to the study of synaptic plasticity in biological systems.

### 1.1.2 The Beginning of The Computing Era

#### Perceptron
The **perceptron**[^5], developed by **Frank Rosenblatt** in 1957, stands as one of the pioneering computational models of neural networks. Comprising a single layer of interconnected artificial neurons, the perceptron operates by aggregating weighted inputs and applying an activation function to produce an output. It was conceived with the aim of classifying input patterns into distinct categories based on a linear decision boundary. The perceptron learning rule, a form of supervised learning, allowed for iterative adjustment of connection weights to minimize classification errors during training. Although celebrated for its simplicity and potential applications in pattern recognition and artificial intelligence, the perceptron was limited by its inability to handle non-linearly separable data, a restriction that prompted further research into more complex neural network architectures and learning algorithms. Nonetheless, the perceptron's introduction marked a significant milestone in the early exploration of neural computation and laid the foundation for subsequent advancements in the field.

#### ADALINE
In 1960 **Bernard Widrow** and **Marcian Hoff** of Stanford University developed a revolutionary neural network named "ADALINE"[^6] (Adaptive Linear Neuron), a variation of the earlier Perceptron, marking a significant advancement in the realm of neural network research. It addressed some of the Perceptron's limitations, namely its inability to handle linearly inseparable data. Adaline introduced a continuous linear activation function and used a gradient descent algorithm for weight adjustment during training. These improvements enabled ADALINE to adapt and learn from more complex input patterns, paving the way for more sophisticated neural network architectures and training algorithms.

The introduction of ADALINE marked a crucial milestone in the evolution of neural network research, demonstrating the potential of computational models inspired by the brain to tackle real-world problems in pattern recognition, classification, and artificial intelligence.

#### MADALINE
In 1962, **Bernard Widrow** with a team consisting of his students at Stanford University introduced another groundbreaking neural network model named "MADALINE"[^6] (Multiple Adaptive Linear Neurons). Building upon the foundation laid by ADALINE, MADALINE represented a significant advancement in the field of neural network research. Unlike its predecessor, which consisted of a single layer of neurons, MADALINE featured multiple layers of adaptive linear neurons, arranged in a hierarchical fashion. This architectural innovation allowed MADALINE to capture more complex patterns and relationships in the input data, making it suitable for a wider range of classification tasks. By incorporating multiple layers of adaptive neurons, MADALINE demonstrated enhanced flexibility and discriminative power, enabling it to tackle challenging classification problems that were beyond the capabilities of single-layer models like the perceptron and ADALINE. The introduction of MADALINE marked a pivotal moment in the evolution of neural network research, laying the groundwork for the development of deeper and more powerful neural network architectures in the years to come.

### 1.1.3 Transition to the era of modern neural networks
The factor most responsible for the rapid evolution of neural networks into the marvels of computer science we know today, is the identically rapid development of processor technology, with the GPU (Graphics Processing Unit) and its unrivalled ability to perform a massive amount of simultaneous calculations being the lifeblood of the Artifical Intelligence Models that we use today, with other revolutionary discoveries in the fields of Mathematics, Computer Science, and microprocessor manufacturing proving themselves to be the key to the recent advancements in computing technology.











---
###### *sources and references*

[^1]: [*McCulloch, W. S., & Pitts, W. (1943). A Logical Calculus of the Ideas Immanent in Nervous Activity. Bulletin of Mathematical Biophysics, 5(4), 115-133*](https://home.csulb.edu/~cwallis/382/readings/482/mccolloch.logical.calculus.ideas.1943.pdf)

[^2]: [Neural Network Conceptual Diagram](https://www.researchgate.net/publication/323465059/figure/fig2/AS:599207769554946@1519873673906/McCulloch-Pitts-computational-model-of-a-neuron.png)

[^3]: [Hebb, D. O. (1949). The Organization of Behavior. Wiley & Sons](https://pure.mpg.de/rest/items/item_2346268_3/component/file_2346267/content)

[^4]: [Hebbian theory wikipedia page](https://en.wikipedia.org/wiki/Hebbian_theory#:~:text=The%20theory%20attempts%20to%20explain,for%20education%20and%20memory%20rehabilitation)

[^5]: [Perceptron neural network](https://en.wikipedia.org/wiki/Perceptron)

[^6]: [ADALINE and MADALINE neural networks](https://en.wikipedia.org/wiki/ADALINE/)
