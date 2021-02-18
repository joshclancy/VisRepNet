<p align="center">
  <img src="https://github.com/joshclancy/VisRepNet/blob/main/extra/logo2.png"
	title="VisRepNet" width="500"/>
</p>

**VisRepNet** is a symbolic language for describing and visualizing neural network architectures and their related training environments. The language is **specialized towards visualizing complex networks** at a high level of detail as to be presented on paper. We are continually refining this language and welcome suggestions for change. 
<br/>
<br/>
<details><summary>Learn how to read VisRepNet Diagrams</summary>
<p>
	
1. Symbols 
2. Organization

<h3> Symbols </h3>
VisRepNet aims to describe **all** neural networks and accurately visualize the differences between them. In striving towards this goal, we have created systems of visualization to represent as many niche cases as possible. This has resulted in general representational systems, but perhaps not obvious ones.  
<h3> Convolutions </h3>
A good example of this, is how VisRepNet represents a **convolutional layer**:
<p align="center">
  <img src="https://github.com/joshclancy/VisRepNet/blob/main/png_readme/convolutions.png"
	title="Convolutions" width="500"/>
</p>
This may seem to be overly complicated. However, this representational system allows us to represent various niche types of convolutions as well. Below we show, 1. A dilated convolution, 2. A custom convolution found in Axial Attention. 3. A convolution that allows for parallel processing along the group dimension. And 4. A temporal convolution. 
<p align="center">
  <img src="https://github.com/joshclancy/VisRepNet/blob/main/png_readme/convExamples.png"
	title="ConvolutionExamples" width="500"/>
</p>

<h3> Tensors </h3>

We employ another system of representation to visually describe a wide range of tensors. Simple tensors are represented simply and intuitively. However, we also provide a method of representing more complex tensors. This is done via a combinatorial system as shown below.

<p align="center">
  <img src="https://github.com/joshclancy/VisRepNet/blob/main/png_readme/tensorSymbolExplain.png"
	title="TensorSymbolExplain" width="500"/>
</p>
<p align="center">
  <img src="https://github.com/joshclancy/VisRepNet/blob/main/png_readme/tensorcombotable.png"
	title="TensorComboTable" width="500"/>
</p>

<h3> Other Neural Layers </h3>
Having a good system to represent and visualize tensors allows us to use those tensors to provide context to neural layers. 

<p align="center">
  <img src="https://github.com/joshclancy/VisRepNet/blob/main/png_readme/contextFromTensors.png"
	title="TensorContext" width="500"/>
</p>

<h3> Other Symbols </h3>
Our other symbols tend to be intuitive. 

<p align="center">
  <img src="https://github.com/joshclancy/VisRepNet/blob/main/png_readme/otherFunctions2.png"
	title="OtherFunctions" width="500"/>
</p>

When we need to represent a function for which we have no symbol, we use the symbol closest to the new function with a label (e.g., use down sample symbol to represent max pool) or we use our standard stand-in symbol with a label. 

<h2> Organization </h2>
We organize VisRepNet diagrams in procedural abstraction levels. There are three main levels. 
1.	Update Environment Level
2.	Network Architecture Level 
3.	Lower Function Level

<h3> Update Environment Level </h3>

In the Update Environment there is a system diagram that describes how the network is trained. This becomes particularly handy when a network is being trained in a new or obscure way. For example, below is DC-GANs training environment. We can see clearly that DC-Gan’s training involves an interaction between two networks. This interaction is both visualized and described.

<p align="center">
  <img src="https://github.com/joshclancy/VisRepNet/blob/main/png_readme/DCGan_trainingEnvironment.png"
	title="TensorContext" width="500"/>
</p>

The system diagram visualization is organized within the INOMU framework. INOMU stands for Input, Network, Output, Measure and Update. Each function is placed within its appropriate section to create a predictable and intuitive system diagram. 

Based on our user studies, deep learning practitioners want a lot of information about the update environment. VisRepNet then provides a written area to accommodate for this. VisRepNet expect a description of the preprocessing, input/s, output/s, loss function, and update hyperparameters. On top of this we expect a general description of the idea behind the network (or area of improvement, if the diagram is accompanying an academic paper). 

<h3>Network Architecture Level</h3>

The network architecture level describes a network’s architecture with the use of abstracted functions. For example, the sigmoid and phi functions are described in detail in the next lower layer. 

<p align="center">
  <img src="https://github.com/joshclancy/VisRepNet/blob/main/png_readme/networkArchitecture.png"
	title="TensorContext" width="500"/>
</p>

At this level we can see the general change in the shape of tensors as they travel through the network. 

<h3>Lower Function Level</h3>
At the lower function level, we get detailed descriptions of the functions within the neural network architecture. We aim to provide enough detail, so that one could use these diagrams to code up the network. 

<p align="center">
  <img src="https://github.com/joshclancy/VisRepNet/blob/main/png_readme/lowerFunctions.png"
	title="TensorContext" width="500"/>
</p>

</p>
</details>

<details><summary>Learn how to create VisRepNet Diagrams</summary>
<p>
	## Learn how to create VisRepNet Diagrams
</p>
</details>

<details><summary>Help design and innovate the next VisRepNet Update. </summary>
<p>
	## Help design and innovate the next VisRepNet Update. 
</p>
</details>

<br/>
<br/>


Some **examples** of VisRepNet v2.0 Diagrams:
<details><summary>Resnet- 34 layers</summary>
<p>
	<img src="https://github.com/joshclancy/VisRepNet/blob/main/png_examples/Resnet.png"
	title="Resnet"/>
</p>
</details>

<details><summary>DC-GAN</summary>
<p>
	<img src="https://github.com/joshclancy/VisRepNet/blob/main/png_examples/DC-GAN.png"
	title="DC-GAN"/>
</p>
</details>

<details><summary>BERT</summary>
<p>
	<img src="https://github.com/joshclancy/VisRepNet/blob/main/png_examples/BERT.png"
	title="BERT"/>
</p>
</details>                                                                                                   

<details><summary>SimCLR</summary>
<p>
	<img src="https://github.com/joshclancy/VisRepNet/blob/main/png_examples/SimCLR-ContrastiveLearning.png"
	title="SimCLR"/>
</p>
</details>             
<br/>

