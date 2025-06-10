# Awesome Open-Ended AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of open-ended learning AI resources. The aim of open-ended algorithms is to keep on inventing new and ever-more complex tasks and solving them continually, even endlessly. From the invention of the wheel, to farming, vaccines, computers, and even rock and roll. These so-far uniquely human advancements and discoveries are the hallmark of civilization. What does AI need to possess to discover such new paradigms, as only humans have until now? Let's take a look at our progress on this frontier.

## Table of Contents
* [Papers](#papers)
* [Open-ended AI Safety](#safety)
* [Surveys and Perspectives](#surveys)
* [Blog Posts and Hacks](#blogs)

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

* **Co-optimising Robot Morphology and Controller in a Simulated Open-Ended Environment** <br>
*Emma Hjellbrekke Stensby, Kai Olav Ellefsen, Kyrre Glette* <br>
EvoStar 2021. [[Paper]](https://arxiv.org/pdf/2104.03062.pdf) [[Code]](https://github.com/EmmaStensby/poet-morphology)

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

* **Open-ended search for environments and adapted agents using map-elites** <br>
*Emma Stensby Norstein, Kai Olav Ellefsen, Kyrre Glette* <br>
EvoStar, 2022. [[Paper]](https://arxiv.org/pdf/2305.01153.pdf) [[Code]](https://github.com/EmmaStensby/environment-map)

* **Minimal Criterion Artist Collective** <br>
*Kai Arulkumaran; Thu Nguyen-Phuoc* <br>
GECCO, 2022. [[Paper]](https://dl.acm.org/doi/10.1145/3520304.3528763) [[Code]](https://github.com/Kaixhin/MCAC)

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

* **Flow-Lenia: Towards open-ended evolution in cellular automata through mass conservation and parameter localization** <br>
*Erwan Plantec, Gautier Hamon, Mayalen Etcheverry, Pierre-Yves Oudeyer, Clément Moulin-Frier, Bert Wang-Chak Chan* <br>
ALife 2023. [[Paper]](https://direct.mit.edu/isal/proceedings/isal/35/131/116921)

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

* **Discovering General Reinforcement Learning Algorithms with Adversarial Environment Design** <br>
*Matthew T. Jackson, Minqi Jiang, Jack Parker-Holder, Risto Vuorio, Chris Lu, Gregory Farquhar, Shimon Whiteson, Jakob N. Foerster* <br>
NeurIPS, 2023. [[Paper]](https://arxiv.org/abs/2310.02782) [[Code]](https://github.com/EmptyJackson/groove)

* **Voyager: An Open-Ended Embodied Agent with Large Language Models** <br>
*Guanzhi Wang, Yuqi Xie, Yunfan Jiang, Ajay Mandlekar, Chaowei Xiao, Yuke Zhu, Linxi Fan, Anima Anandkumar* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/abs/2305.16291) [[Code]](https://github.com/MineDojo/Voyager) [[Website]](https://voyager.minedojo.org/)

* **Augmenting Autotelic Agents with Large Language Models** <br>
*Cédric Colas, Laetitia Teodorescu, Pierre-Yves Oudeyer, Xingdi Yuan, Marc-Alexandre Côté* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/abs/2305.12487)

* **Reward-Free Curricula for Training Robust World Models** <br>
*Marc Rigter, Minqi Jiang, Ingmar Posner* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/abs/2306.09205)

* **Promptbreeder: Self-Referential Self-Improvement Via Prompt Evolution** <br>
*Chrisantha Fernando, Dylan Banarse, Henryk Michalewski, Simon Osindero, Tim Rocktäschel* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/abs/2309.16797)

* **Self-Taught Optimizer (STOP): Recursively Self-Improving Code Generation** <br>
*Eric Zelikman, Eliana Lorch, Lester Mackey, Adam Tauman Kalai* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/abs/2310.02304)

* **Motif: Intrinsic Motivation from Artificial Intelligence Feedback** <br>
*Martin Klissarov, Pierluca D'Oro, Shagun Sodhani, Roberta Raileanu, Pierre-Luc Bacon, Pascal Vincent, Amy Zhang, Mikael Henaff* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/abs/2310.00166) [[Code]](https://github.com/facebookresearch/motif)

* **Eureka: Human-Level Reward Design via Coding Large Language Models** <br>
*Yecheng Jason Ma, William Liang, Guanzhi Wang, De-An Huang, Osbert Bastani, Dinesh Jayaraman, Yuke Zhu, Linxi Fan, Anima Anandkumar* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/abs/2310.12931) [[Code]](https://github.com/eureka-research/Eureka) [[Website]](https://eureka-research.github.io/)

* **Practical PCG Through Large Language Models** <br>
*Muhammad U Nasir, Julian Togelius* <br>
CoG, 2023. [[Paper]](https://arxiv.org/abs/2305.18243)

* **Augmentative Topology Agents For Open-Ended Learning** <br>
*Muhammad U. Nasir, Michael Beukman, Steven James, Christopher W. Cleghorn* <br>
GECCO, 2023. [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3583133.3590576?casa_token=HxaGW9kHx3UAAAAA:7_JPaFAbzDZ_rlZqDDku_X-eb46ZRj87iz-rVDVpWs6NBHHoHXHL_3FdmpkajDdSQQi07kOxCElYMLA) [[Code]](https://github.com/umair-nasir14/ATEP)


* **OMNI: Open-endedness via Models of human Notions of Interestingness** <br>
*Jenny Zhang, Joel Lehman, Kenneth Stanley, Jeff Clune* <br>
ICLR, 2024. [[Paper]](https://arxiv.org/abs/2306.01711) [[Code]](https://github.com/jennyzzt/omni) [[Website]](http://www.jennyzhangzt.com/omni/)

* **Quality-Diversity through AI Feedback** <br>
*Herbie Bradley, Andrew Dai, Hannah Teufel, Jenny Zhang, Koen Oostermeijer, Marco Bellagente, Jeff Clune, Kenneth Stanley, Grégory Schott, Joel Lehman* <br>
ICLR, 2024. [[Paper]](https://arxiv.org/abs/2310.13032) [[Website]](https://qdaif.github.io/)

* **Quality Diversity through Human Feedback** <br>
*Li Ding, Jenny Zhang, Jeff Clune, Lee Spector, Joel Lehman* <br>
ICML, 2024. [[Paper]](https://arxiv.org/abs/2310.12103)

* **OS-Copilot: Towards Generalist Computer Agents with Self-Improvement** <br>
*Zhiyong Wu*, Chengcheng Han*, Zichen Ding, Zhenmin Weng, Zhoumianze Liu, Shunyu Yao, Tao Yu, Lingpeng Kong <br>
arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2402.07456.pdf) [[Code]](https://github.com/OS-Copilot/FRIDAY) [[Website]](https://os-copilot.github.io/)

* **Multi-Agent Diagnostics for Robustness via Illuminated Diversity** <br>
*Mikayel Samvelyan, Davide Paglieri, Minqi Jiang, Jack Parker-Holder, Tim Rocktäschel* <br>
AAMAS, 2024. [[Paper]](https://arxiv.org/abs/2401.13460) [[Website]](https://sites.google.com/view/madrid-marl)

* **Evolutionary Optimization of Model Merging Recipes** <br>
*Takuya Akiba, Makoto Shing, Yujin Tang, Qi Sun, David Ha* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/abs/2403.13187)

* **Discovering Preference Optimization Algorithms with and for Large Language Models** <br>
*Chris Lu, Samuel Holt, Claudio Fanconi, Alex J. Chan, Jakob Foerster, Mihaela van der Schaar, Robert Tjarko Lange* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/abs/2406.08414)

* **Generative Design through Quality-Diversity Data Synthesis and Language Models** <br>
*Adam Gaier, James Stoddart, Lorenzo Villaggi, Shyam Sudhakaran* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/abs/2405.09997)

* **OMNI-EPIC: Open-endedness via Models of human Notions of Interestingness with Environments Programmed in Code** <br>
*Maxence Faldor, Jenny Zhang, Antoine Cully, Jeff Clune* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/abs/2405.15568) [[Website]](https://omni-epic.vercel.app/)

* **Artificial Generational Intelligence: Cultural Accumulation in Reinforcement Learning** <br>
*Jonathan Cook, Chris Lu, Edward Hughes, Joel Z. Leibo, Jakob Foerster* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/abs/2406.00392)

* **Computational Life: How Well-formed, Self-replicating Programs Emerge from Simple Interaction** <br>
*Blaise Agüera y Arcas, Jyrki Alakuijala, James Evans, Ben Laurie, Alexander Mordvintsev, Eyvind Niklasson, Ettore Randazzo, Luca Versari* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/abs/2406.19108)

* **Intelligent Go-Explore: Standing on the Shoulders of Giant Foundation Models** <br>
*Cong Lu, Shengran Hu, Jeff Clune* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/abs/2405.15143)

* **Genie: Generative Interactive Environments** <br>
*Jake Bruce, Michael Dennis, Ashley Edwards, Jack Parker-Holder, Yuge Shi, Edward Hughes, Matthew Lai, Aditi Mavalankar, Richie Steigerwald, Chris Apps, Yusuf Aytar, Sarah Bechtle, Feryal Behbahani, Stephanie Chan, Nicolas Heess, Lucy Gonzalez, Simon Osindero, Sherjil Ozair, Scott Reed, Jingwei Zhang, Konrad Zolna, Jeff Clune, Nando de Freitas, Satinder Singh, Tim Rocktäschel* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/abs/2402.15391)

* **Debating with More Persuasive LLMs Leads to More Truthful Answers** <br>
*Akbir Khan, John Hughes, Dan Valentine, Laura Ruis, Kshitij Sachan, Ansh Radhakrishnan, Edward Grefenstette, Samuel R. Bowman, Tim Rocktäschel, Ethan Perez* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/abs/2402.06782)

* **Toward Artificial Open-Ended Evolution within Lenia using Quality-Diversity** <br>
*Maxence Faldor, Antoine Cully* <br>
ALife, 2024. [[Paper]](https://arxiv.org/abs/2406.04235)

* **Structurally Flexible Neural Networks: Evolving the Building Blocks for General Agents** <br>
*Joachim Winther Pedersen, Erwan Plantec, Eleni Nisioti, Milton Montero, Sebastian Risi* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/abs/2404.15193)

* **DreamCraft: Text-Guided Generation of Functional 3D Environments in Minecraft** <br>
*Sam Earle, Filippos Kokkinos, Yuhe Nie, Julian Togelius, Roberta Raileanu* <br>
FDG, 2024. [[Paper]](https://arxiv.org/abs/2404.15538)

* **Large Language Models as In-context AI Generators for Quality-Diversity** <br>
*Bryan Lim, Manon Flageat, Antoine Cully* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/abs/2404.15794)

* **Word2World: Generating Stories and Worlds through Large Language Models** <br>
*Muhammad U. Nasir, Steven James, Julian Togelius* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2405.06686) [[Code]](https://github.com/umair-nasir14/Word2World)

* **The AI Scientist: Towards fully automated open-ended scientific discovery** <br>
*Chris Lu, Cong Lu, Robert Tjarko Lange, Jakob Foerster, Jeff Clune, David Ha* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/abs/2408.06292) [[Code]](https://github.com/SakanaAI/AI-Scientist)

* **Automated design of agentic systems** <br>
*Shengran Hu, Cong Lu, Jeff Clune* <br>
ICLR, 2025. [[Paper]](https://arxiv.org/abs/2408.08435) [[Code]](https://github.com/ShengranHu/ADAS)

* **Automated Capability Discovery via Model Self-Exploration** <br>
*Cong Lu, Shengran Hu, Jeff Clune* <br>
arXiv, 2025. [[Paper]](https://arxiv.org/abs/2502.07577) [[Code]](https://github.com/conglu1997/ACD)

* **The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search** <br>
*Yutaro Yamada, Robert Tjarko Lange, Cong Lu, Shengran Hu, Chris Lu, Jakob Foerster, Jeff Clune, David Ha* <br>
arXiv, 2025. [[Paper]](https://arxiv.org/abs/2408.06292) [[Code]](https://github.com/SakanaAI/AI-Scientist-v2)

## <a name="safety"></a> Open-Ended AI Safety

* **Open Questions in Creating Safe Open-ended AI: Tensions Between Control and Creativity** <br>
*Adrien Ecoffet, Jeff Clune, Joel Lehman* <br>
arXiv, 2020. [[Paper]](https://arxiv.org/abs/2006.07495) 

* **Managing extreme AI risks amid rapid progress** <br>
*Yoshua Bengio, Geoffrey Hinton, Andrew Yao, Dawn Song, Pieter Abbeel, Trevor Darrell, Yuval Noah Harari, Ya-Qin Zhang, Lan Xue, Shai Shalev-Shwartz, Gillian Hadfield, Jeff Clune, Tegan Maharaj, Frank Hutter, Atılım Güneş Baydin, Sheila McIlraith, Qiqi Gao, Ashwin Acharya, David Krueger, Anca Dragan, Philip Torr, Stuart Russell, Daniel Kahneman, Jan Brauner, Sören Mindermann* <br>
Science, 2024. [[Paper]](https://arxiv.org/abs/2310.17688) 

* **Rainbow Teaming: Open-Ended Generation of Diverse Adversarial Prompts** <br>
*Mikayel Samvelyan, Sharath Chandra Raparthy, Andrei Lupu, Eric Hambro, Aram H. Markosyan, Manish Bhatt, Yuning Mao, Minqi Jiang, Jack Parker-Holder, Jakob Foerster, Tim Rocktäschel, Roberta Raileanu* <br>
NeurIPS, 2024. [[Paper]](https://arxiv.org/abs/2402.16822) [[Website]](https://sites.google.com/view/rainbow-teaming)

* **Safety is Essential for Responsible Open-Ended Systems** <br>
*Ivaxi Sheth, Jan Wehner, Sahar Abdelnabi, Ruta Binkyte, Mario Fritz* <br>
arXiv, 2025. [[Paper]](https://arxiv.org/abs/2502.04512)

## <a name="surveys"></a> Surveys and Perspectives on Open-Endedness

* **Why Greatness Cannot Be Planned: The Myth of the Objective** <br>
*Kenneth O. Stanley, Joel Lehman* <br>
Springer, 2015. [[Book]](https://link.springer.com/book/10.1007/978-3-319-15524-1)

* **Open-endedness: The last grand challenge you’ve never heard of** <br>
*Kenneth O. Stanley, Joel Lehman, Lisa Soros* <br>
O'Reilly Radar, 2017. [[Paper]](https://www.oreilly.com/radar/open-endedness-the-last-grand-challenge-youve-never-heard-of/)

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

* **Open-Endedness is Essential for Artificial Superhuman Intelligence** <br>
*Edward Hughes, Michael Dennis, Jack Parker-Holder, Feryal Behbahani, Aditi Mavalankar, Yuge Shi, Tom Schaul, Tim Rocktaschel* <br>
ICML, 2024. [[Paper]](https://arxiv.org/abs/2406.04268)

* **Evolution and The Knightian Blindspot of Machine Learning** <br>
*Joel Lehman, Elliot Meyerson, Tarek El-Gaaly, Kenneth O. Stanley, Tarin Ziyaee* <br>
arXiv, 2025. [[Paper]](https://arxiv.org/abs/2501.13075)

* **Darwin Godel Machine: Open-Ended Evolution of Self-Improving Agents** <br>
*Jenny Zhang, Shengran Hu, Cong Lu, Robert Lange, Jeff Clune* <br>
arXiv, 2025. [[Paper]](https://arxiv.org/abs/2505.22954) [[Code]](https://github.com/jennyzzt/dgm)

## <a name="blogs"></a> Blog Posts and Hacks

* **Interactive poetry breeding through Mixtral base model LLMs** <br>
*Joel Lehman*. 2024. [[Blog]](https://flourish.ing/interactive-poetry-breeding-through-mixtral-base-model-llms.html)

* **Identifying Life-Changing Books with LLMs** <br>
*Joel Lehman*. 2024. [[Blog]](https://flourish.ing/identifying-life-changing-books-with-llms.html)

* **SerendipityLM: Interactive evolutionary exploration of generative design spaces with large language models** <br>
*Samim*. 2024. [[Blog]](https://samim.io/studio/work/serendipityLM/)

* **AI that can improve itself** <br>
*Richard Cornelius Suwandi*. 2025. [[Blog]]([https://samim.io/studio/work/serendipityLM/](https://richardcsuwandi.github.io/blog/2025/dgm/))
