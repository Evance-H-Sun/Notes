
《Fundamentals of Deep Learning》读书笔记

## Chapter 1

`Traditional computer programs` 最擅长两件事情：

> * performing arithmetic really fast;
> * explicitly following a list of instructions;

但是，图像识别、自然语言处理、自动翻译等等这类问题，难以用 `Traditional computer programs` 解决，原因是：

> We don't know what program to write because we don't know how it's done by our brains. 

> A lot of the things we learn in school growing up have a lot in common with traditional computer programs. But the things we learn at an extremely early age, the things we find most natural, are **learned by example**, not by formula.

`Machine learning`通过类似人脑学习的方式（*learning from example*）来解决这类问题：

> In machine learning, instead of teaching a computer a massive list of rules to solve the problem, we give it a **model** with which it can evaluate examples, and **a small set of instructions** to modify the model when it makes a mistake. We **expect** that, over time, a well-suited model would be able to solve the problem extremely accurately.

最简单的一个 Model 是`linear perceptron`，但对于解决上面的这类复杂问题，远远不够。

`Deep Learning`采用类似人脑中的结构来构造模型，经过实践，很适合处理这类问题。

> Recent research in machine learning has attempted to build models that resemble the structures utilized by our brains. This is commonly referred as *deep learning*.

人脑的基本组成单元是神经元（`neuron`），大米粒大小的一小块就包含超过10000个神经元，每个神经元与6000个其他的神经元相连接，构成了一个大规模的生物网。

每个`neuron`的生物学结构为：

> At its core, the neuron is optimized to receive information from other neurons, process this information in a unique way, and send its result to other cells.

> The neuron receives its inputs along dendrites. Each of these incoming connections is dynamically strengthened or weakened based on how often it is used(this is how we learn new concepts!), and it's the strength of each connection that determines the contribution of the input to the neuron's output. After being weighted by the strenth of their respective connections, the inputs are summed together in the cell body. This sum is then transformed into a new signal that's propagated along the cell's axon and sent off to other neurons.

> Every linear perceptron model can be expressed as a single neuron.

人脑中大量的 `neuron` 是以分层的方式组织在一起的，人的大脑皮质由6层组成，信息一层层的传递，最终使得我们可以理解感知到的信息。据此，我们可以构造出人工神经网络（`artificial neural net`）。

> These weights constitute our parameter vector, and our ability to solve problems with neural network depends on finding the optimal values to plug into vector.

> Simplest neural network: *feed-forward neural network*.



