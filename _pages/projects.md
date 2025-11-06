---
layout: lab_custom
title: projects
permalink: /projects/
nav: true
id: 3
---

<style> p:has(+ ul) { margin-bottom: 0; } p + ul { margin-top: 0; } </style>

### __Projects__
Read about our projects on
1. [learning through the eyes of a child](#learning-through-the-eyes-and-ears-of-a-child)
2. [prior-enhanced neural networks](#new-modeling-human-behavior-with-prior-enhanced-neural-networks)
3. [machines that reason more like people](#new-more-human-like-reasoning-in-machines)
4. [compositional generalization](#compositional-generalization-in-minds-and-machines)
5. [neuro-symbolic models](#neuro-symbolic-modeling)

Prospective lab members are encouraged to review the __Future directions__ within each project section, and then report back about the directions that pique their interest.

---

##### __Learning through the eyes and ears of a child__
<img class="fig" src="/images/projects/fig-luna-lowres.jpeg" width="260">
Young children have wide-ranging and sophisticated knowledge of the world. Where does this early knowledge come from? How much can be explained through generic learning mechanisms applied to sensory data, and how much requires stronger innate inductive biases? We examine these classic *nature vs. nurture* questions by training large-scale neural networks through the eyes and ears of a single developing child, using longitudinal baby headcam videos. We call these Child's View AI (CVAI) models and build on the amazing <a href="https://psyarxiv.com/fy8zx/">SAYCam dataset</a>. Remarkably, we find that broadly useful visual features and word-referent mappings can emerge from CVAI models trained in a self-supervised way on just slices of one child's everyday experiences.

__Recent articles__
- <a href="https://www.science.org/doi/10.1126/science.adi1374"> Vong, W. K., Wang, W., Orhan, A. E., and Lake, B. M (2024). Grounded language acquisition through the eyes and ears of a single child.</a> <em>Science</em>, 383, 504-511.
- <a href="https://www.nature.com/articles/s42256-024-00802-0"> Orhan, A. E., and Lake, B. M. (2024). Learning high-level visual representations from a child's perspective without strong inductive biases.</a> <em>Nature Machine Intelligence</em>, 6, 271-283.
- <a href="https://www.cs.princeton.edu/~bl8144/papers/WangEtAl2023CognitiveScience.pdf"> Wang, W., Vong, W. K., Kim, N., and Lake, B. M. (2023). Finding Structure in One Child’s Linguistic Experience.</a> <em>Cognitive Science</em>, 47, e13305.

__Future directions__
- Add inductive biases (shape bias, mutual exclusivity bias, objects, social cues, etc.) and study their impact on word learning from egocentric video
- Add active learning (taking actions in a virtual rendering of that child's home) to the passive video learning during CVAI training
- Create a benchmark for evaluating how well CVAI models explain key developmental findings

---

##### __Modeling human behavior with prior-enhanced neural networks__
Behavioral scientists must often choose between two computational paradigms with complementary strengths and weaknesses: Bayesian models or neural networks. An ideal paradigm would facilitate testing different priors; Bayesian models make this easy, while neural networks do not. Similarly, an ideal paradigm would avoid over-simplifications; neural networks make this easy, while Bayesian models do not. We aim to combine the best of both with an approach we call Bayesian distillation with Behavioral Tuning (BBT). BBT allows for flexible modeling of behavior using powerful Transformers, even from minimal behavioral data, by distilling Bayesian priors into the networks and then by fine-tuning the networks further on raw behavioral examples.

__Recent articles__
- Lake, B. M. (2025). More accurate behavioral predictions with hybrid Bayesian-connectionist models. <em>Preprint coming soon</em>.

__Future directions__
- Advance interpretability for BBT models (hypothesis decoding, causal analysis,understanding the gradient steps during behavioral tuning)
- Develop software tools for popularizing BBT modeling
- Extend the BBT approach to reinforcement learning, reasoning, etc. 

---

##### __More human-like reasoning in machines__
Simulating human reasoning in an open-ended task space has been a long-standing dream of cognitive science. Recent advances in LLMs brings this closer to reality, yet these models are not developed with human-like reasoning as an objective. In this project, we fine-tune reasoning-capable LLMs on large datasets of people reasoning "out loud" to align their reasoning processes with human patterns, akin to the [Centaur LLM](https://www.nature.com/articles/s41586-025-09215-4) from Binz et al. but for reasoning. We will evaluate whether fine-tuned models better predict human reasoning and whether they can simulate human-like reasoning on novel problems.

__Recent articles__

__Future directions__
- Collecting large-scale behavioral dataset of people thinking out loud on reasoning tasks
- Applications to education sciences

---

##### __Compositional generalization in minds and machines__
<img class="fig" src="/images/projects/fig-mlc.jpg" width="350">
People make rule-like, compositional generalizations in language, thought, and action --- a hallmark of human intelligence often called systematic generalization. For example, once a person learns how to "photobomb" she immediately understands how to "photobomb twice" or "photobomb vigorously." Despite recent advances, AI systems (including LLMs) still struggle with this kind of generalization. We are studying how humans learn to generalize compositionally and developing Meta-Learning for Compositionality (MLC) models to better capture and understand these human abilities. We also explore how systematic generalization relates to safety challenges in LLM, where failures of generalization can lead to unexpected or unsafe behavior. 

__Recent articles__
- <a href="https://arxiv.org/abs/2505.21828">Chen, Y. H., Davidson, G., and Lake, B. M. (2025). SAGE-Eval: Evaluating LLMs for Systematic Generalizations of Safety Facts.</a> Preprint available on <em>arxiv:2505.21828</em>.
- <a href="https://arxiv.org/abs/2502.14791">Wang, W., Jiang, G., Linzen, T., and Lake, B. M. (2025). Rapid word learning through meta in-context learning</a>. In <em>Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing (EMNLP)</em>.
- <a href="https://www.nature.com/articles/s41586-023-06668-3.pdf">Lake, B. M. and Baroni, M. (2023). Human-like systematic generalization through a meta-learning neural network.</a> <em>Nature</em>, 623, 115-121.

__Future directions__
- Study meta-learning as a model of rapid learning in cognitive development
- Study compositional generalization in large language models across many tasks (with Simon Schug)
- Solve the SAGE-Eval systematic generalization safety benchmark (see recent artcle)
- Understand what issues in AI safety can be traced back to systematic generalization

---

##### __Neuro-symbolic modeling__
<img class="fig" src="/images/projects/fig-gns.jpg" width="300">
Human conceptual representations are rich in structural and statistical knowledge. Symbolic models excel at capturing compositional and causal structure, but they struggle with complex correlations. In contrast, neural network models excel at processing raw stimuli and capturing complex statistics, but they struggle with compositional and causal knowledge. The human mind seems to transcend this dichotomy: learning both structural and statistical knowledge from raw inputs. We are developing neuro-symbolic models that can capture the dual structural and statistical natures of human conceptual representation.
 
__Recent articles__
- <a href="https://www.cs.princeton.edu/~bl8144/papers/ZhouEtAl2024Cognition.pdf"> Zhou, Y., Feinman, R., and Lake, B. M. (2024). Compositional diversity in visual concept learning.</a> <em>Cognition</em>, 244, 105711.
- <a href="https://www.cs.princeton.edu/~bl8144/papers/FeinmanLake2021ICLR.pdf">Feinman, R. and Lake, B. M. (2020). Learning Task-General Representations with Generative Neuro-Symbolic Modeling.</a> <em>International Conference on Learning Representations (ICLR)</em>.

__Future directions__
- Build neuro-symbolic models of human reasoning on the Abstraction and Reasoning Corpus (ARC) (with Solim LeGris and Todd Gureckis)
- Model the illusion of explanatory depth using neuro-symbolic models (with Solim LeGris and Todd Gureckis)