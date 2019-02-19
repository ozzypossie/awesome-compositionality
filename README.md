# awesome-compositionality [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A list of resources dedicated to compositionality. 

Contributions most welcome! Please check the [Contribution guideline](CONTRIBUTING.md) for an example.

## Table of Contents
* [Architectural Bias](#architectural-bias)
* [Datasets](#datasets)
* [Miscellaneous](#miscellaneous)
  * [Psycholinguistics](#psycholinguistics)
  * [Cognitive Sciences](#cognitive-sciences)
   

### Architectural Bias

- David Ha, Andrew Dai, Quoc V. Le. [HyperNetworks](https://arxiv.org/abs/1609.09106), arXiv:1609.09106, ICLR, 2017 
  * The main idea is to use a hypernetwork to generate the weights for another network. An “embedding vector” is generated by a hyper RNN. This embedding vector is used to dynamically scale the weights of a RNN at every timestep. The approach is evaluated on different language tasks: character-level language modeling (PTB, Wiki), machine translation and handwriting prediction. The results outperform the baselines on these tasks marginally.
  
### Datasets

- Lake, Brenden, and Marco Baroni. [Generalization without systematicity: On the compositional skills of sequence-to-sequence recurrent networks](http://proceedings.mlr.press/v80/lake18a/lake18a.pdf) ICML. 2018.
  * Study on the ability of RNNs to generalize in a compositional way on a data set for sequence-to-sequence modelling called SCAN, which requires models to create compositional solutions and generalize on new data based on related concepts.

- A Santoro, F Hill, D Barrett, A Morcos, T Lillicrap. [Measuring abstract reasoning in neural networks](http://proceedings.mlr.press/v80/santoro18a/santoro18a.pdf) ICML, 2018. 
    * A [dataset](https://github.com/deepmind/abstract-reasoning-matrices) for abstract reasoning inspired by human-like IQ tests. To succeed in the task the model must be able to generalize in various ‘regimes’ in which the training and test data differ in clearlydefined ways.
				
- Atzmon, Yuval, et al. [Learning to generalize to new compositions in image understanding](https://arxiv.org/pdf/1608.07639.pdf) arXiv:1608.07639 (2016).
    * A *compositional split* of the [MS COCO dataset](http://cocodataset.org/). This alternative split for training and test data can be used to test whether image captioning models can generalise to new (unseen) compositions.

### Miscellaneous

#### Psycholinguistics

- Christiansen, Morten H., and Nick Chater. [The Now-or-Never bottleneck: A fundamental constraint on language.](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/938D54E80A2A90A1C5990F4915B5E8D8/S0140525X1500031Xa.pdf/nowornever_bottleneck_a_fundamental_constraint_on_language.pdf) Behavioral and Brain Sciences 39 (2016).
  * Combining psycholinguistic evidence to hypothesize that the way humans process language is highly constrained by limited time and memory resources, therefore implying a very particular process in which the brain chunks incoming input and processes it into increasingly abstract representations.

#### Cognitive Sciences

- Lake, Brenden M., et al. [Building machines that learn and think like people.](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/A9535B1D745A0377E16C590E14B94993/S0140525X16001837a.pdf/building_machines_that_learn_and_think_like_people.pdf) Behavioral and Brain Sciences 40 (2017).
  * Highlighting the differences (and missing pieces) between human cognition and current Deep Learning architectures.
