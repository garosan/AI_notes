https://en.wikipedia.org/wiki/Artificial_neural_network

ANNs are computing systems vaguely inspired by the biological neural networks of animal brains.
Such systems "learn" (i.e. progressively improve performance on) tasks by considering examples, 
generally without task-specific programming.

An ANN is based on a collection of connected units or nodes called artificial neurons 
(a simplified version of biological neurons in an animal brain). Each connection (a simplified 
version of a synapse) between artificial neurons can transmit a signal from one to another.

In common ANN implementations, the signal at a connection between artificial neurons is a real 
number, and the output of each artificial neuron is calculated by a non-linear function of the 
sum of its inputs. Artificial neurons and connections typically have a weight that adjusts as 
learning proceeds.

The original goal of the ANN approach was to solve problems in the same way that a human brain 
would. However, over time, attention focused on matching specific tasks, leading to deviations 
from biology.

## HISTORY

Warren McCulloch and Walter Pitts (1943) created a computational model for neural networks based 
on mathematics and algorithms called threshold logic. This model paved the way for neural network 
research to split into two approaches. One approach focused on biological processes in the brain 
while the other focused on the application of neural networks to artificial intelligence. This work 
led to work on nerve networks and their link to finite automata.

"A Logical Calculus of Ideas Immanent in Nervous Activity" (1943) proposed the first mathematical
model of a neural network.

### Hebbian learning

In the late 1940s, D.O. Hebb created a learning hypothesis based on the mechanism of neural 
plasticity that became known as Hebbian learning. Hebbian learning is unsupervised learning. 
Researchers started applying these ideas to computational models in 1948 with Turing's B-type 
machines.

Psychologist Frank Rosenblatt (1958) created the Perceptron, an algorithm for pattern recognition.

The 1st functional networks with many layers were published by Alexey Ivakhnenko and Lapa in 1965,
becoming the Group Method of Data Handling, a method of inductive statistical learning, for which
Ivakhnenko is sometimes referred as 'the father of deep learning'.

Neural network research stagnated after machine learning research by Minsky and Papert (1969) who
discovered two key issues:
1) Basic perceptrons were incapable of processing the exclusive-or circuit.
2) Computers didn't have enough processing power yet.

### Backpropagation

A key trigger for renewed interest in neural networks was Paul Werbos's backpropagation algorithm
(1975) which effectively solved the exclusive-or problem. Backpropagation distributed the error 
term back up through the layers, by modifying the weights at each node.

In the mid-1980s, parallel distributed processing became popular under the name connectionism. 
Rumelhart and McClelland (1986) described the use of connectionism to simulate neural processes.

Support vector machines and other, much simpler methods such as linear classifiers gradually 
overtook neural networks in machine learning popularity.

In 2012, Andrew Ng and Jeff Dean created a network that learned to recognize higher-level concepts, 
such as cats, only from watching unlabeled images taken from YouTube videos.

### Contests

Between 2009 and 2012, recurrent neural networks and deep feedforward neural networks developed in 
Schmidhuber's research group won eight international competitions in pattern recognition and machine 
learning.

### Convolutional networks

As of 2011, the state of the art in deep learning feedforward networks alternated convolutional 
layers and max-pooling layers. Such supervised deep learning methods were the first to achieve 
human-competitive performance on certain tasks.

## Models

An artificial neural network is a network of simple elements called neurons, which receive input,
change their internal state (activation) according to that input, and produce output depending on
the input and activation.

**Components of an artificial neural network**

**Neurons**
Generally consist of the following components:
- An activation
- Possibly a threshold
- An activation function
- An output function

**Connections and weights**

**Propagation function**

**Learning rule**
The learning rule is a rule or an algorithm which modifies the parameters of the neural network, in 
order for a given input to the network to produce a favored output. This learning process typically 
amounts to modifying the weights and thresholds of the variables within the network.

## Learning Paradigms

The three major learning paradigms each correspond to a particular learning task. These are 
supervised learning, unsupervised learning and reinforcement learning.

### Supervised Learning

### Unsupervised Learning

### Reinforcement Learning



Concepts
neuroplasticity
Turing B-type machine
Frank Rosenblatt's perceptron
Group Method of Data Handling
backpropagation
parallel distributed processing


People
Warren McCulloch
Walter Pitts
D. O. Hebb
Frank Rosenblatt
Alexey Ivakhnenko
Minksy 
Papert
Paul Werbos
Jürgen Schmidhuber
Andrew Ng
Jeff Dean



