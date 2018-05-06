http://news.mit.edu/2017/explained-neural-networks-deep-learning-0414

Deep learning, new name for an approach to AI called neural networks that has been around for 70
years. Neural nets were 1st proposed in 1944 by Warren McCullough & Walter Pitts. NNs were big
until killed off by MIT mathematicians Marvin Minsky & Seymour Papert in 1969. NNs enjoyed a
resurgence in 1980s, fell into eclipse in the 2000s and returned after 2010s, fueled largely by
the increased processing power of graphics chips.

Tomaso Poggio, Eugene McDermott Professor of Brain and Cognitive Sciences at MIT, an investigator 
at MIT’s McGovern Institute for Brain Research, and director of MIT’s Center for Brains, Minds, and
Machines: "Ideas like these are like viruses".

** Weighty matters **

Neural nets are a means of doing machine learning, in which a computer learns to perform some task 
by analyzing training examples. Usually, the examples have been hand-labeled in advance.

Modeled loosely on the human brain, NNs have a lot of processing nodes densely interconnected. Most
of today's NNs are organized into layers, and they're "feed-forward", the data moves only in one 
direction. 

Each node, after receiving information, assigns a 'weight' to the info and makes a calculation. If
the weight is below a certain threshold value, the node passes no data to the next layer. If the 
resulting number exceeds the threshold value, the node 'fires', sending the number - the sum of the
weighted inputs - to all its outgoing connectins.

When a neural net is being trained, all of its weights and thresholds are initially set to random 
values. Training data is fed into the input layer. During training, the weights and thresholds are 
continually adjusted until training data with the same labels consistently yield similar outputs.

** Minds and machines **

The NNs by McCullough & Pitts had thresholds & weights but weren't arranged into layers. Their point
was to show that the human brain could be thought of as a computing device (more about neuroscience
than computer science.) Neural nets continue to be a valuable tool for neuroscientific research.

The first trainable neural network, the Perceptron, was demonstrated by psychologist Frank Rosenblatt
in 1957. The Perceptron’s design was much like that of the modern neural net, except that it had only 
one layer with adjustable weights and thresholds, sandwiched between input and output layers.

Perceptrons were an active area of research in psychology & CS until 1959, when Minsky and Papert 
published "Perceptrons" which demonstrated that Perceptrons would be impractically time consuming.

** Periodicity **

By the 1980s, researchers had developed algorithms that were efficient enough for NNs with more
than one layer. The field enjoyed a renaissance.

But it seems that in the 1980s nobody knew very well how NNs arrived at their conclusions. So 
around the 90s, NNs were supplanted by support vector machines, an alternate approach to ML based
on very clean and elegant mathematics.

The recent resurgence in NNs -the deep learning revolution- is thanks to the computer game industry.
Modern GPUs helped move from one-layer, two-layer NNs of the 1960s into the 10, 15 or 50-layer NNs
that we have today. That's what the 'deep' in deep learning refers to.

** Under the hood **

Plenty of questions to be answered about how DL NNs actually exactly work. Tomaso Pogio at the
Center for Brains, Minds, and Machines (CBMM) is helping answer those questions.