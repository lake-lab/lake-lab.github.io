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
[compositional generalization](#compositional-generalization-in-minds-and-machines).

---

##### __Learning through the eyes and ears of a child__
<img class="fig" src="/images/projects/fig-saycam.jpg" width="260">
_Key people: Emin Orhan, Wai Keen Vong, Wentao Wang, Najoung Kim, and Guy Davidson_

Young children have wide-ranging and sophisticated knowledge of the world. What is the origin of this early knowledge? How much can be explained through generic learning mechanisms applied to sensory data, and how much requires more substantive innate inductive biases? We examine these *nature vs. nurture* questions by training large-scale neural networks through the eyes and ears of a single developing child, using longitudinal baby headcam videos (see recent dataset from <a href="https://psyarxiv.com/fy8zx/">Sullivan et al., 2020</a>).

Our results show that broadly useful visual features and high-level linguistic structure can emerge from self-supervised learning applied only to a slice of one child's experiences. Our ongoing work is studying whether predictive models of the world can also be learned via similar mechanisms.

<a href="https://www.science.org/doi/10.1126/science.adi1374"> Vong, W. K., Wang, W., Orhan, A. E., and Lake, B. M (2024). Grounded language acquisition through the eyes and ears of a single child.</a> <em>Science</em>, 383, 504-511.

<a href="https://www.nature.com/articles/s42256-024-00802-0"> Orhan, A. E., and Lake, B. M. (2024). Learning high-level visual representations from a child's perspective without strong inductive biases.</a> <em>Nature Machine Intelligence</em>, 6, 271-283.

<a href="https://cims.nyu.edu/~brenden/papers/WangEtAl2023CognitiveScience.pdf"> Wang, W., Vong, W. K., Kim, N., and Lake, B. M. (2023). Finding Structure in One Child’s Linguistic Experience.</a> <em>Cognitive Science</em>, 47, e13305.

<a href="https://cims.nyu.edu/~brenden/papers/DavidsonEtAlPreprint.pdf"> Davidson, G., Orhan, A. E., and Lake, B. M. (2023). Spatial Relation Categorization in Infants and Deep Neural Networks.</a> <em>Cognition</em>.

---

##### __Neuro-symbolic modeling__
<img class="fig" src="/images/projects/fig-gns.jpg" width="300">
_Key people: Reuben Feinman_


Human conceptual representations are rich in structural and statistical knowledge. Symbolic models excel at capturing compositional and causal structure, but they struggle to model the most complex correlations found in raw data. In contrast, neural network models excel at processing raw stimuli and capturing complex statistics, but they struggle to model compositional and causal knowledge. The human mind seems to transcend this dichotomy: learning structural and statistical knowledge from raw inputs.

We are developing neuro-symbolic models that learn compositional and causal generative programs from raw data, while using neural sub-routines for powerful statistical modeling (see diagram). We aim to better understand the dual structural and statistical natures of human concepts, and to learn neuro-symbolic representations for machine learning applications.

<a href="https://cims.nyu.edu/~brenden/papers/ZhouEtAl2024Cognition.pdf"> Zhou, Y., Feinman, R., and Lake, B. M. (2024). Compositional diversity in visual concept learning.</a> <em>Cognition</em>, 244, 105711.

<a href="https://cims.nyu.edu/~brenden/papers/FeinmanLake2021ICLR.pdf">Feinman, R. and Lake, B. M. (2020). Learning Task-General Representations with Generative Neuro-Symbolic Modeling.</a> <em>International Conference on Learning Representations (ICLR)</em>.

<a href="https://cims.nyu.edu/~brenden/papers/FeinmanLake2020CogSci.pdf">Feinman, R. and Lake, B. M. (2020). Generating new concepts with hybrid neuro-symbolic models.</a> In <em>Proceedings of the 42nd Annual Conference of the Cognitive Science Society.</em>

---

##### __Compositional generalization in minds and machines__
<img class="fig" src="/images/projects/fig-gscan-crop.png" width="200">
_Key people: Yanli Zhou, Laura Ruis, Max Nye, and Marco Baroni_

People make compositional generalizations in language, thought, and action. Once a person learns how to "photobomb" she immediately understands how to "photobomb twice" or "photobomb vigorously." We have shown that, despite recent advances in natural language processing, the best algorithms fail catastrophically on tests of compositionality.

To better understand these distinctively human abilities, we are studying human compositional learning of language-like instructions. Based on behavioral insights, we are developing novel meta-learning and neural-symbolic models to tackle popular compositional learning benchmarks. Additional work focuses on learning compositional visual concepts and developing more challenging benchmarks for AI, e.g., few-shot learning of concepts such as "cautiously" (see image of "walking to the small red circle cautiously," which requires looking both ways before moving).

<a href="https://www.nature.com/articles/s41586-023-06668-3.pdf">Lake, B. M. and Baroni, M. (2023). Human-like systematic generalization through a meta-learning neural network.</a> <em>Nature</em>, 623, 115-121.

<a href="https://cims.nyu.edu/~brenden/papers/2305.19374.pdf"> Zhou, Y., Feinman, R., and Lake, B. M. (2023). Compositional diversity in visual concept learning.</a> Preprint available on <em>arxiv.2305.19374</em>

<a href="https://cims.nyu.edu/~brenden/papers/RuisEtAl2020NeurIPS.pdf">Ruis, L., Andreas, J., Baroni, M. Bouchacourt, D., and Lake, B. M. (2020). A Benchmark for Systematic Generalization in Grounded Language Understanding</a>. <em>Advances in Neural Information Processing Systems 33</em>.

<a href="https://cims.nyu.edu/~brenden/papers/NyeEtAl2020NeurIPS.pdf">Nye, M., Solar-Lezama, A., Tenenbaum, J. B., and Lake, B. M. (2020). Learning Compositional Rules via Neural Program Synthesis.</a> <em>Advances in Neural Information Processing Systems 33</em>.