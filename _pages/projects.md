---
layout: lab_custom
title: projects
permalink: /projects/
nav: true
id: 3
---

### __Projects__
Read about our current projects on
[learning through the eyes of a child](#learning-through-the-eyes-of-a-child),
[concept learning](#concept-learning-in-minds-and-machines),
[compositional generalization](#compositional-generalization-in-minds-and-machines),
and [video game learning](#video-game-learning-in-minds-and-machines).

---

##### __Learning through the eyes of a child__
<img class="fig" src="/images/projects/fig-saycam.jpg" width="260">
_Key people: Emin Orhan, Vaibhav Gupta, Wai Keen Vong, and Kanishk Gandhi_

Young children have wide-ranging and sophisticated knowledge of the world. What is the origin of this early knowledge? How much can be explained through generic learning mechanisms applied to sensory data, and how much requires more substantive innate inductive biases? We examine these *nature vs. nurture* questions by training large-scale neural networks through the eyes of a single developing child, using longitudinal baby headcam videos (see recent dataset from <a href="https://psyarxiv.com/fy8zx/">Sullivan et al., 2020</a>).

Our results so far show how high-level visual representations emerge from a subset of one baby's experience, through only self-supervised learning. Our ongoing work is investigating whether basic concept of objects and agents, and simple predictive models of the world, can also be learned via similar generic learning mechanisms.

<a href="https://cims.nyu.edu/~brenden/papers/OrhanEtAl2020NeurIPS.pdf">Orhan, A. E., Gupta, V. B., and Lake, B. M. (2020). Self-supervised learning through the eyes of a child.</a> <em>Advances in Neural Information Processing Systems 33.</em> [<a href="https://cims.nyu.edu/~brenden/papers/OrhanEtAl2020NeurIPS_supp.pdf">Supporting Info</a>] [<a href="https://github.com/eminorhan/baby-vision">Code and pre-trained models</a>] [<a href="https://www.newscientist.com/article/2251529-baby-mounted-cameras-teach-ai-to-see-through-a-childs-eyes/">New Scientist article</a>]

<a href="https://cims.nyu.edu/~brenden/papers/DavidsonLake2021CogSci.pdf">Davidson, G. and Lake, B. M. (2021). Examining Infant Relation Categorization Through Deep Neural Networks.</a> In <em>Proceedings of the 43rd Annual Conference of the Cognitive Science Society.</em>

---

##### __Neuro-symbolic modeling__
<img class="fig" src="/images/projects/fig-gns.jpg" width="300">
_Key people: Reuben Feinman_


Human conceptual representations are rich in structural and statistical knowledge. Symbolic models excel at capturing compositional and causal structure, but they struggle to model the most complex correlations found in raw data. In contrast, neural network models excel at processing raw stimuli and capturing complex statistics, but they struggle to model compositional and causal knowledge. The human mind seems to transcend this dichotomy: learning structural and statistical knowledge from raw inputs.

We are developing neuro-symbolic models that learn compositional and causal generative programs from raw data, while using neural sub-routines for powerful statistical modeling (see diagram). We aim to better understand the dual structural and statistical natures of human concepts, and to learn neuro-symbolic representations for machine learning applications.

<a href="https://cims.nyu.edu/~brenden/papers/FeinmanLake2021ICLR.pdf">Feinman, R. and Lake, B. M. (2020). Learning Task-General Representations with Generative Neuro-Symbolic Modeling.</a> <em>International Conference on Learning Representations (ICLR)</em>.

<a href="https://cims.nyu.edu/~brenden/papers/FeinmanLake2020CogSci.pdf">Feinman, R. and Lake, B. M. (2020). Generating new concepts with hybrid neuro-symbolic models.</a> In <em>Proceedings of the 42nd Annual Conference of the Cognitive Science Society.</em> [<a href="https://cims.nyu.edu/~brenden/papers/FeinmanLake2020CogSci_supp.pdf">Supporting Info.</a>]

---

##### __Compositional generalization in minds and machines__
<img class="fig" src="/images/projects/fig-gscan-crop.png" width="200">
_Key people: Yanli Zhou, Laura Ruis, Max Nye, and Marco Baroni_

People make compositional generalizations in language, thought, and action. Once a person learns how to "photobomb" she immediately understands how to "photobomb twice" or "photobomb vigorously." We have shown that, despite recent advances in natural language processing, the best algorithms fail catastrophically on tests of compositionality.

To better understand these distinctively human abilities, we are studying human compositional learning of language-like instructions. Based on behavioral insights, we are developing novel meta-learning and neural-symbolic models to tackle popular compositional learning benchmarks. Additional work focuses on learning compositional visual concepts and developing more challenging benchmarks for AI, e.g., few-shot learning of concepts such as "cautiously" (see image of "walking to the small red circle cautiously," which requires looking both ways before moving).

<a href="https://cims.nyu.edu/~brenden/papers/RuisEtAl2020NeurIPS.pdf">Ruis, L., Andreas, J., Baroni, M. Bouchacourt, D., and Lake, B. M. (2020). A Benchmark for Systematic Generalization in Grounded Language Understanding</a>. <em>Advances in Neural Information Processing Systems 33</em>.

<a href="https://cims.nyu.edu/~brenden/papers/NyeEtAl2020NeurIPS.pdf">Nye, M., Solar-Lezama, A., Tenenbaum, J. B., and Lake, B. M. (2020). Learning Compositional Rules via Neural Program Synthesis.</a> <em>Advances in Neural Information Processing Systems 33</em>.

---

##### __Video game learning in minds and machines__
<img class="fig" src="/images/projects/fig-games-crop.jpg" width="280">
_Key people: Guy Davidson_

Video games are ideal for comparing human and machine learning. Although the best algorithms outscore people on many games, they require hundreds of hours of experience to learn a new game while people need just a few minutes. The experience gap is only widening: OpenAI recently trained their Dota 2 bot for 45,000 years worth of game experience. Our hypothesis is that key cognitive ingredients are missing from contemporary AI systems &mdash; objects, agents, compositionality, and causality &mdash; and this absence is holding these systems back.

To evaluate this hypothesis, we are incorporating cognitive ingredients into deep reinforcement learning (RL) algorithms and evaluating their performance. In the "Frostbite challenge," we have found that adding object masks leads to higher scores and better generalization to novel test scenarios: An agent surrounded by crabs now knows it's toast! (see image) Ongoing work is studying the importance of agents, compositionality, and causality.

<a href="https://cims.nyu.edu/~brenden/papers/DavidsonLake2020CogSci.pdf">Davidson, G. and Lake, B. M. (2020). Investigating simple object representations in model-free deep reinforcement learning.</a> In <em>Proceedings of the 42nd Annual Conference of the Cognitive Science Society.</em>

<a href="https://cims.nyu.edu/~brenden/papers/LakeEtAl2017BBS.pdf">Lake, B. M., Ullman, T. D., Tenenbaum, J. B., and Gershman, S. J. (2017). Building machines that learn and think like people.</a> <em>Behavioral and Brain Sciences</em>, 40, E253.