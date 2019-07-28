<h1>List of resources</h1>

<h3>Relevant papers:</h3>
<ol>
<li> <a href="https://arxiv.org/abs/1511.07289">Exponential Linear Units paper</a>: Best performing 'unaugmented' model on CIFAR as of yet.</li>
<li> <a href="https://arxiv.org/abs/1802.02375">Shakedrop Regularization paper</a>: Checked.</li>
<li> <a href="https://arxiv.org/abs/1610.02357">Xception paper</a>: The concept of Depthwise Seperable Convolutions, *Uninspected*</li>
<li> <a href="https://arxiv.org/abs/1409.6070">Deep Sparse CNN paper</a>: Based on the concept of sparse CNNS. *Uninspected*</li>
<li> <a href="https://arxiv.org/abs/1510.00149">Deep Compression paper</a>: *important* Read more, implement quantization</li>
<li> <a href="https://arxiv.org/abs/1707.07012">Neural Architecture Search</a>: *Uninspected*</li>
</ol>

<h3>Conclusions reached thus far:</h3>
<ol>
<li>The architecture described in the ELU paper has ~42 million trainable parameters, so that's a no</li>
<li>Try implementing other papers, except with ELU activation functions and compare performance</li>
<li>Shakedrop only works for ResNet & PyramidNet category architectures</li>
</ol>
