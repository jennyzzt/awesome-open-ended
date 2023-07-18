# Awesome Open-Ended AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of AI open-ended learning resources. As the list grows longer, I will split it into more sections.

## Table of Contents
* [Papers](#papers)
* [Open-ended AI Safety](#safety)
* [Surveys and Perspectives](#surveys)

## <a name="contributing"></a> Contributing
When submitting a pull request, please put the new paper at the correct chronological position as the following format: <br>
```
* **Paper Title** <br>
*Author(s)* <br>
Conference, Year. [[Paper]](link) [[Code]](link) [[Website]](link)
```

## <a name="papers"></a> Papers

* **Minimal Criterion Coevolution: A New Approach to Open-Ended Search** <br>
*Jonathan C. Brant, Kenneth O. Stanley* <br>
GECCO, 2017. [[Paper]](https://eplex.cs.ucf.edu/papers/brant_gecco17.pdf) [[Code]](https://github.com/jbrant/MinimalCriterionCoevolution)

* **Paired Open-Ended Trailblazer (POET): Endlessly Generating Increasingly Complex and Diverse Learning Environments and Their Solutions** <br>
*Rui Wang, Joel Lehman, Jeff Clune, Kenneth O. Stanley* <br>
GECCO, 2019. [[Paper]](https://arxiv.org/abs/1901.01753) [[Code]](https://github.com/uber-research/poet) [[Website]](https://www.uber.com/en-CA/blog/poet-open-ended-deep-learning/)

* **Enhanced POET: Open-Ended Reinforcement Learning through Unbounded Invention of Learning Challenges and their Solutions** <br>
*Rui Wang, Joel Lehman, Aditya Rawal, Jiale Zhi, Yulun Li, Jeff Clune, Kenneth O. Stanley* <br>
ICML, 2020. [[Paper]](https://arxiv.org/abs/2003.08536) [[Code]](https://github.com/uber-research/poet) [[Website]](https://www.uber.com/en-CA/blog/enhanced-poet-machine-learning/)

* **Co-generation of game levels and game-playing agents** <br>
*Aaron Dharna, Julian Togelius, L.B.Soros* <br>
AIIDE 2020. [[Paper]](https://arxiv.org/abs/2007.08497) [[Code]](https://github.com/aadharna/UntouchableThunder)

* **Emergent Complexity and Zero-shot Transfer via Unsupervised Environment Design** <br>
*Michael Dennis, Natasha Jaques, Eugene Vinitsky, Alexandre Bayen, Stuart Russell, Andrew Critch, Sergey Levine* <br>
NeurIPS, 2020. [[Paper]](https://arxiv.org/abs/2012.02096) [[Code]](https://github.com/google-research/google-research/tree/master/social_rl/adversarial_env) [[Website]](https://ai.googleblog.com/2021/03/paired-new-multi-agent-approach-for.html)

* **Prioritized Level Replay** <br>
*Minqi Jiang, Edward Grefenstette, Tim Rocktäschel* <br>
ICML, 2021. [[Paper]](https://arxiv.org/abs/2010.03934) [[Code]](https://github.com/facebookresearch/level-replay)

* **Replay-Guided Adversarial Environment Design** <br>
*Minqi Jiang\*, Michael Dennis\*, Jack Parker-Holder, Jakob Foerster, Edward Grefenstette, Tim Rocktäschel* <br>
NeurIPS, 2021. [[Paper]](https://arxiv.org/abs/2110.02439) [[Code]](https://github.com/facebookresearch/dcd)

* **Environment Generation for Zero-Shot Compositional Reinforcement Learning** <br>
*Izzeddin Gur, Natasha Jaques, Yingjie Miao, Jongwook Choi, Manoj Tiwari, Honglak Lee, Aleksandra Faust* <br>
NeurIPS, 2021. [[Paper]](https://arxiv.org/abs/2201.08896)

* **MiniHack the Planet: A Sandbox for Open-Ended Reinforcement Learning Research** <br>
*Mikayel Samvelyan, Robert Kirk, Vitaly Kurin, Jack Parker-Holder, Minqi Jiang, Eric Hambro, Fabio Petroni, Heinrich Küttler, Edward Grefenstette, Tim Rocktäschel* <br>
NeurIPS, 2021. [[Paper]](https://arxiv.org/abs/2109.13202) [[Code]](https://github.com/facebookresearch/minihack) [[Website]](https://minihack.readthedocs.io)

* **Open-Ended Learning Leads to Generally Capable Agents** <br>
*Open Ended Learning Team, Adam Stooke, Anuj Mahajan, Catarina Barros, Charlie Deck, Jakob Bauer, Jakub Sygnowski, Maja Trebacz, Max Jaderberg, Michael Mathieu, Nat McAleese, Nathalie Bradley-Schmieg, Nathaniel Wong, Nicolas Porcel, Roberta Raileanu, Steph Hughes-Fitt, Valentin Dalibard, Wojciech Marian Czarnecki* <br>
arXiv, 2021. [[Paper]](https://arxiv.org/abs/2107.12808) [[Website]](https://www.deepmind.com/blog/generally-capable-agents-emerge-from-open-ended-play)

* **SPOTTER: Extending Symbolic Planning Operators through Targeted Reinforcement Learning** <br>
*Vasanth Sarathy, Daniel Kasenberg, Shivam Goel, Jivko Sinapov, Matthias Scheutz* <br>
arXiv, 2021. [[Paper]](https://arxiv.org/abs/2012.13037) [[Code]](https://github.com/spotter-ai/spotter) 

* **EvoCraft: A New Challenge for Open-Endedness** <br>
*Djordje Grbic, Rasmus Berg Palm, Elias Najarro, Claire Glanois, Sebastian Risi* <br>
EvoStar, 2021. [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-72699-7_21) [[Website]](https://evocraft.life/)

* **Video Games as a Testbed for Open-Ended Phenomena** <br>
*Sam Earle; Julian Togelius; L. B. Soros* <br>
IEEE Conference on Games, 2021. [[Paper]](https://ieeexplore.ieee.org/abstract/document/9619042)

* **Evolving Curricula with Regret-Based Environment Design** <br>
*Jack Parker-Holder\*, Minqi Jiang\*, Michael Dennis, Mikayel Samvelyan, Jakob Foerster, Edward Grefenstette, Tim Rocktäschel* <br>
ICML, 2022. [[Paper]](https://arxiv.org/abs/2203.01302) [[Code]](https://github.com/facebookresearch/dcd) [[Demo]](https://accelagent.github.io/)

* **Evolution through Large Models** <br>
*Joel Lehman, Jonathan Gordon, Shawn Jain, Kamal Ndousse, Cathy Yeh, Kenneth Stanley* <br>
arXiv, 2022. [[Paper]](https://arxiv.org/abs/2206.08896) [[Code]](https://github.com/CarperAI/OpenELM)

* **RAPid-Learn: A Framework for Learning to Recover for Handling Novelties in Open-World Environments** <br>
*Shivam Goel, Yash Shukla, Vasanth Sarathy, Matthias Scheutz, Jivko Sinapov* <br>
arXiv, 2022. [[Paper]](https://arxiv.org/abs/2206.12493) [[Code]](https://github.com/goelshivam1210/RAPid-Learn) 

* **Transfer Dynamics in Emergent Evolutionary Curricula** <br>
*Aaron Dharna, Amy K. Hoover, Julian Togelius, Lisa Soros*  <br>
IEEE Transactions on Games, 2022. [[Paper]](https://arxiv.org/abs/2203.10941) [[Code]](https://github.com/aadharna/UntouchableThunder)

* **Watts: Infrastructure for Open-Ended Learning** <br>
*Aaron Dharna, Charlie Summers, Rohin Dasari, Julian Togelius, Amy K. Hoover* <br>
ALOE Workshop 2022 [[Paper]](https://arxiv.org/abs/2204.13250) [[Code]](https://github.com/aadharna/watts)

* **MineDojo: Building Open-Ended Embodied Agents with Internet-Scale Knowledge** <br>
*Linxi Fan, Guanzhi Wang, Yunfan Jiang, Ajay Mandlekar, Yuncong Yang, Haoyi Zhu, Andrew Tang, De-An Huang, Yuke Zhu, Anima Anandkumar* <br>
NeurIPS, 2022. [[Paper]](https://arxiv.org/abs/2206.08853) [[Code]](https://github.com/MineDojo/MineDojo) [[Website]](https://minedojo.org/)

* **Grounding Aleatoric Uncertainty in Unsupervised Environment Design** <br>
*Minqi Jiang, Michael Dennis, Jack Parker-Holder, Andrei Lupu, Heinrich Küttler, Edward Grefenstette, Tim Rocktäschel, Jakob Foerster* <br>
NeurIPS 2022. [[Paper]](https://arxiv.org/abs/2207.05219)

* **Language and Culture Internalisation for Human-Like Autotelic AI** <br>
*Cédric Colas, Tristan Karch, Clément Moulin-Frier, Pierre-Yves Oudeyer* <br>
Nature Machine Intelligence, 2022. [[Paper]](https://arxiv.org/abs/2206.01134) [[Website]](https://vygotskian-autotelic-ai.github.io/)

* **MAESTRO: Open-Ended Environment Design for Multi-Agent Reinforcement Learning** <br>
*Mikayel Samvelyan, Akbir Khan, Michael Dennis, Minqi Jiang, Jack Parker-Holder, Jakob Foerster, Roberta Raileanu, Tim Rocktäschel* <br>
ICLR, 2023. [[Paper]](https://arxiv.org/abs/2303.03376) [[Website]](https://sites.google.com/view/maestro-ued)

* **Powderworld: A Platform for Understanding Generalization via Rich Task Distributions** <br>
*Kevin Frans, Philip Isola* <br>
ICLR, 2023. [[Paper]](https://arxiv.org/abs/2211.13051) [[Website]](https://kvfrans.com/static/powder/) [[Code]](https://github.com/kvfrans/powderworld) 

* **Human-Timescale Adaptation in an Open-Ended Task Space** <br>
*Adaptive Agent Team, Jakob Bauer, Kate Baumli, Satinder Baveja, Feryal Behbahani, Avishkar Bhoopchand, Nathalie Bradley-Schmieg, Michael Chang, Natalie Clay, Adrian Collister, Vibhavari Dasagi, Lucy Gonzalez, Karol Gregor, Edward Hughes, Sheleem Kashem, Maria Loks-Thompson, Hannah Openshaw, Jack Parker-Holder, Shreya Pathak, Nicolas Perez-Nieves, Nemanja Rakicevic, Tim Rocktäschel, Yannick Schroecker, Jakub Sygnowski, Karl Tuyls, Sarah York, Alexander Zacherl, Lei Zhang* <br>
ICML, 2023. [[Paper]](https://arxiv.org/abs/2301.07608) [[Website]](https://sites.google.com/view/adaptive-agent/)

* **Deep Laplacian-based Options for Temporally-Extended Exploration** <br>
*Martin Klissarov, Marlos C. Machado* <br>
ICML, 2023. [[Paper]](https://arxiv.org/abs/2301.11181) [[Blogpost 1]](https://medium.com/@marlos.cholodovskis/the-representation-driven-option-discovery-cycle-e3f5877696c2) [[Blogpost2]](https://medium.com/@marlos.cholodovskis/deep-laplacian-based-options-for-temporally-extended-exploration-7bf8dd469838)

* **Voyager: An Open-Ended Embodied Agent with Large Language Models** <br>
*Guanzhi Wang, Yuqi Xie, Yunfan Jiang, Ajay Mandlekar, Chaowei Xiao, Yuke Zhu, Linxi Fan, Anima Anandkumar* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/abs/2305.16291) [[Code]](https://github.com/MineDojo/Voyager) [[Website]](https://voyager.minedojo.org/)

* **OMNI: Open-endedness via Models of human Notions of Interestingness** <br>
*Jenny Zhang, Joel Lehman, Kenneth Stanley, Jeff Clune* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/abs/2306.01711) [[Code]](https://github.com/jennyzzt/omni)

* **Augmenting Autotelic Agents with Large Language Models** <br>
*Cédric Colas, Laetitia Teodorescu, Pierre-Yves Oudeyer, Xingdi Yuan, Marc-Alexandre Côté* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/abs/2305.12487)

* **Reward-Free Curricula for Training Robust World Models** <br>
*Marc Rigter, Minqi Jiang, Ingmar Posner* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/abs/2306.09205)


## <a name="surveys"></a> Open-Ended AI Safety

* **Open Questions in Creating Safe Open-ended AI: Tensions Between Control and Creativity** <br>
*Adrien Ecoffet, Jeff Clune, Joel Lehman* <br>
arXiv, 2020. [[Paper]](https://arxiv.org/abs/2006.07495) 


## <a name="safety"></a> Surveys and Perspectives on Open-Endedness

* **Open-endedness: The last grand challenge you’ve never heard of** <br>
*Kenneth O. Stanley, Joel Lehman, Lisa Soros* <br>
O'Reilly Radar, 2017. [[Paper]](https://www.oreilly.com/radar/open-endedness-the-last-grand-challenge-youve-never-heard-of/)

* **Why Greatness Cannot Be Planned: The Myth of the Objective** <br>
*Kenneth Stanley, Joel Lehman* <br>
arXiv, 2019. [[Book]](https://link.springer.com/book/10.1007/978-3-319-15524-1)

* **AI-GAs: AI-generating algorithms, an alternate paradigm for producing general artificial intelligence** <br>
*Jeff Clune* <br>
arXiv, 2019. [[Paper]](https://arxiv.org/abs/1905.10985)

* **Creative Problem Solving in Artificially Intelligent Agents: A Survey and Framework** <br>
*Evana Gizzi, Lakshmi Nair, Sonia Chernova, Jivko Sinapov* <br>
arXiv, 2022. [[Paper]](https://arxiv.org/abs/2204.10358)

* **Executive Function: A Contrastive Value Policy for Resampling and Relabeling Perceptions via Hindsight Summarization?** <br>
*Chris Lengerich, Ben Lengerich.* <br>
arXiv, 2022. [[Paper]](https://arxiv.org/abs/2204.12639)

* **General Intelligence Requires Rethinking Exploration** <br>
*Minqi Jiang, Tim Rocktäschel, Edward Grefenstette* <br>
Royal Society Open Science, 2023. [[Paper]](https://arxiv.org/abs/2211.07819)
