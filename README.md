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

* **Paired Open-Ended Trailblazer (POET): Endlessly Generating Increasingly Complex and Diverse Learning Environments and Their Solutions** <br>
*Rui Wang, Joel Lehman, Jeff Clune, Kenneth O. Stanley* <br>
GECCO, 2019. [[Paper]](https://arxiv.org/abs/1901.01753) [[Code]](https://github.com/uber-research/poet) [[Website]](https://www.uber.com/en-CA/blog/poet-open-ended-deep-learning/)

* **Enhanced POET: Open-Ended Reinforcement Learning through Unbounded Invention of Learning Challenges and their Solutions** <br>
*Rui Wang, Joel Lehman, Aditya Rawal, Jiale Zhi, Yulun Li, Jeff Clune, Kenneth O. Stanley* <br>
ICML, 2020. [[Paper]](https://arxiv.org/abs/2003.08536) [[Code]](https://github.com/uber-research/poet) [[Website]](https://www.uber.com/en-CA/blog/enhanced-poet-machine-learning/)

* **Emergent Complexity and Zero-shot Transfer via Unsupervised Environment Design** <br>
*Michael Dennis, Natasha Jaques, Eugene Vinitsky, Alexandre Bayen, Stuart Russell, Andrew Critch, Sergey Levine* <br>
NeurIPS, 2020. [[Paper]](https://arxiv.org/abs/2012.02096) [[Code]](https://github.com/google-research/google-research/tree/master/social_rl/adversarial_env) [[Website]](https://ai.googleblog.com/2021/03/paired-new-multi-agent-approach-for.html)

* **Prioritized Level Replay** <br>
*Minqi Jiang, Edward Grefenstette, Tim Rocktäschel* <br>
ICML, 2021. [[Paper]](https://arxiv.org/abs/2010.03934) [[Code]](https://github.com/facebookresearch/level-replay)

* **Replay-Guided Adversarial Environment Design** <br>
*Minqi Jiang*, Michael Dennis*, Jack Parker-Holder, Jakob Foerster, Edward Grefenstette, Tim Rocktäschel* <br>
NeurIPS, 2021. [[Paper]](https://arxiv.org/abs/2110.02439) [[Code]](https://github.com/facebookresearch/dcd)

* **Open-Ended Learning Leads to Generally Capable Agents** <br>
*Open Ended Learning Team, Adam Stooke, Anuj Mahajan, Catarina Barros, Charlie Deck, Jakob Bauer, Jakub Sygnowski, Maja Trebacz, Max Jaderberg, Michael Mathieu, Nat McAleese, Nathalie Bradley-Schmieg, Nathaniel Wong, Nicolas Porcel, Roberta Raileanu, Steph Hughes-Fitt, Valentin Dalibard, Wojciech Marian Czarnecki* <br>
arXiv, 2021. [[Paper]](https://arxiv.org/abs/2107.12808) [[Website]](https://www.deepmind.com/blog/generally-capable-agents-emerge-from-open-ended-play)

* **Evolving Curricula with Regret-Based Environment Design** <br>
Jack Parker-Holder*, Minqi Jiang*, Michael Dennis, Mikayel Samvelyan, Jakob Foerster, Edward Grefenstette, Tim Rocktäschel <br>
ICML, 2022. [[Paper]](https://arxiv.org/abs/2203.01302) [[Code]](https://github.com/facebookresearch/dcd) [[Demo]](https://accelagent.github.io/)

* **Evolution through Large Models** <br>
*Joel Lehman, Jonathan Gordon, Shawn Jain, Kamal Ndousse, Cathy Yeh, Kenneth Stanley* <br>
arXiv, 2022. [[Paper]](https://arxiv.org/abs/2206.08896) [[Code]](https://github.com/CarperAI/OpenELM)

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

* **Human-Timescale Adaptation in an Open-Ended Task Space** <br>
*Adaptive Agent Team, Jakob Bauer, Kate Baumli, Satinder Baveja, Feryal Behbahani, Avishkar Bhoopchand, Nathalie Bradley-Schmieg, Michael Chang, Natalie Clay, Adrian Collister, Vibhavari Dasagi, Lucy Gonzalez, Karol Gregor, Edward Hughes, Sheleem Kashem, Maria Loks-Thompson, Hannah Openshaw, Jack Parker-Holder, Shreya Pathak, Nicolas Perez-Nieves, Nemanja Rakicevic, Tim Rocktäschel, Yannick Schroecker, Jakub Sygnowski, Karl Tuyls, Sarah York, Alexander Zacherl, Lei Zhang* <br>
ICML, 2023. [[Paper]](https://arxiv.org/abs/2301.07608) [[Website]](https://sites.google.com/view/adaptive-agent/)

* **Voyager: An Open-Ended Embodied Agent with Large Language Models** <br>
*Guanzhi Wang, Yuqi Xie, Yunfan Jiang, Ajay Mandlekar, Chaowei Xiao, Yuke Zhu, Linxi Fan, Anima Anandkumar* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/abs/2305.16291) [[Code]](https://github.com/MineDojo/Voyager) [[Website]](https://voyager.minedojo.org/)

* **OMNI: Open-endedness via Models of human Notions of Interestingness** <br>
*Jenny Zhang, Joel Lehman, Kenneth Stanley, Jeff Clune* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/abs/2306.01711) [[Code]](https://github.com/jennyzzt/omni)

* **Augmenting Autotelic Agents with Large Language Models** <br>
*Cédric Colas, Laetitia Teodorescu, Pierre-Yves Oudeyer, Xingdi Yuan, Marc-Alexandre Côté* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/abs/2305.12487)


## <a name="surveys"></a> Open-Ended AI Safety

* **Open-endedness: The last grand challenge you’ve never heard of** <br>
*Kenneth O. Stanley, Joel Lehman, Lisa Soros* <br>
O'Reilly Radar, 2017. [[Paper]](https://www.oreilly.com/radar/open-endedness-the-last-grand-challenge-youve-never-heard-of/)

## <a name="safety"></a> Surveys and Perspectives on Open-Endedness
* **Why Greatness Cannot Be Planned: The Myth of the Objective** <br>
*Kenneth Stanley, Joel Lehman* <br>
arXiv, 2019. [[Paper]](https://link.springer.com/book/10.1007/978-3-319-15524-1)

* **AI-GAs: AI-generating algorithms, an alternate paradigm for producing general artificial intelligence** <br>
*Jeff Clune* <br>
arXiv, 2019. [[Paper]](https://arxiv.org/abs/1905.10985)

* **Open Questions in Creating Safe Open-ended AI: Tensions Between Control and Creativity** <br>
*Adrien Ecoffet, Jeff Clune, Joel Lehman* <br>
arXiv, 2020. [[Paper]](https://arxiv.org/abs/2006.07495) 

* **General Intelligence Requires Rethinking Exploration** <br>
*Minqi Jiang, Tim Rocktäschel, Edward Grefenstette* <br>
Royal Society Open Science, 2023. [[Paper]](https://arxiv.org/abs/2211.07819)

