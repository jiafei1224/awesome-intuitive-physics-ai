# Awesome Intuitive Physics AI ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
> A curated list of resources for Machine Intuitive Physics.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) lists and and [awesome-cogsci](https://github.com/abi-aryan/awesome-cogsci).

By [Jiafei Duan](https://duanjiafei.com/). If you see papers missing from the list, please send me an email or a pull request (format see [below](#contributing)).

## Table of Content
- [Contributing](#contributing)
- [Papers](#papers)
  - [Probalistic Simulation Model](#probsimulation)
  - [Perception-based Deep Learning Model](#percetionbased)
  - [Heuristic & Rule-based Model](#heuristic)
  - [Psychology Literatures](#psychology)
- [Datasets](#datasets)
- [Physics Engine](#physengine)
- [Resources](#resources)
- [Publication Venues](#publicationvenues)

## <a name="contributing"></a> Contributing
When sending PRs, please put the new paper at the correct chronological position as the following format: <br>

```
* **Paper Title** <br>
*Author(s)* <br>
Conference, Year. [[Paper]](link) [[Code]](link) [[Website]](link)
```

## <a name="papers"></a> Papers

### <a name="probsimulation"></a> Probalistic Simulation Model
* **Galileo: Perceiving Physical Object Properties by Integrating a Physics Engine with Deep Learning** <br>
*Jiajun Wu, Ilker Yildirim, Joseph J. Lim, Bill Freeman, Josh Tenenbaum* <br>
NeurIPS, 2015. [[Paper]](https://papers.nips.cc/paper/2015/hash/d09bf41544a3365a46c9077ebb5e35c3-Abstract.html)

* **Interpretable Intuitive Physics Model** <br>
*Ye, Tian, Xiaolong Wang, James Davidson, and Abhinav Gupta* <br>
ECCV, 2018. [[Paper]](https://openaccess.thecvf.com/content_ECCV_2018/papers/Tian_Ye_Interpretable_Intuitive_Physics_ECCV_2018_paper.pdf)


### <a name="percetionbased"></a> Perception-based Deep Learning Model
* **PIP:Physical Interaction Prediction via Mental Simulation with Span Selection** <br>
*Jiafei Duan, Samson Yu, Soujanya Poria, Bihan Wen, Cheston Tan* <br>
Preprint, 2021. [[Paper]](https://arxiv.org/abs/2109.04683)

* **Learning physical intuition of block towers by example** <br>
*Adam Lerer, Sam Gross, Rob Fergus* <br>
PMLR, 2016. [[Paper]](http://proceedings.mlr.press/v48/lerer16.html)

* **Learning Visual Predictive Models of Physics for Playing Billiards** <br>
*Katerina Fragkiadaki, Pulkit Agrawal, Sergey Levine, Jitendra Malik* <br>
ICLR, 2016. [[Paper]](https://openreview.net/forum?id=KRjXbfLWkHo) [[Code]](https://github.com/pulkitag/pyphy-engine)

* **Interaction network for learning about objects, relations and physics** <br>
*Peter W. Battaglia, Razvan Pascanu, Matthew Lai, Danilo Rezende, Koray Kavukcuoglu* <br>
NeurIPS, 2016. [[Paper]](https://proceedings.neurips.cc/paper/2016/file/3147da8ab4a0437c15ef51a5cc7f2dc4-Paper.pdf) [[Code]](https://github.com/jsikyoon/Interaction-networks_tensorflow)

* **To fall or not to fall: A visual approach to physical stability prediction** <br>
*Wenbin Li, Seyedmajid Azimi, Aleš Leonardis, Mario Fritz* <br>
AAAI, 2017. [[Paper]](http://proceedings.mlr.press/v48/lerer16.html)

* **Newtonian image understanding: Unfolding the dyanmics of object in static images** <br>
*Roozbeh Mottaghi, Hessam Bagherinezhad, Mohammad Rastegari, Ali Farhadi* <br>
CVPR, 2016. [[Paper]](https://openaccess.thecvf.com/content_cvpr_2016/html/Mottaghi_Newtonian_Scene_Understanding_CVPR_2016_paper.html) [[Code]](https://github.com/allenai/newtonian)

### <a name="heuristic"></a>Heuristic & Rule-based Model
* **A Benchmark for Modeling Violation-of-Expectation in Physical Reasoning Across Event Categories** <br>
*Arijit Dasgupta, Jiafei Duan, Marcelo H Ang Jr, Yi Lin, Su-hua Wang, Renée Baillargeon, Cheston Tan* <br>
Preprint, 2021. [[Paper]](https://arxiv.org/abs/2111.08826) 


### <a name="psychology"></a>Psychology Literatures
* **Intuitive Physics** <br>
*Michael McCloskey* <br>
Scientific American, 1983. [[Paper]](https://www.jstor.org/stable/24968881) 

* **Intuitive physics: the straight-down belief and its origin.** <br>
*McCloskey, Michael, Allyson Washburn, and Linda Felch* <br>
Journal of Experimental Psychology: Learning, Memory, and Cognition 9, 1983. [[Paper]](https://psycnet.apa.org/record/1984-11308-001) 

* **Mind games: Game engines as an architecture for intuitive physics.** <br>
*Ullman, Tomer D., Elizabeth Spelke, Peter Battaglia, and Joshua B. Tenenbaum* <br>
Trends in cognitive sciences, 2017. [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S1364661317301134) 

* **Intuitive physics: Current research and controversies.** <br>
*Kubricht, James R., Keith J. Holyoak, and Hongjing Lu* <br>
Trends in cognitive sciences, 2017. [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S1364661317301262) 

* **Simulation as an engine of physical scene understanding.** <br>
*Battaglia, Peter W., Jessica B. Hamrick, and Joshua B. Tenenbaum* <br>
Proceedings of the National Academy of Sciences, 2013. [[Paper]](https://www.pnas.org/content/110/45/18327.short) 

## <a name="datasets"></a> Datasets
* **Physion: Evaluating Physical Prediction from Vision in Humans and Machines.** <br>
*Daniel M. Bear, Elias Wang, Damian Mrowca, Felix J. Binder, Hsiau-Yu Fish Tung, R. T. Pramod, Cameron Holdaway, Sirui Tao, Kevin Smith, Fan-Yun Sun, Li Fei-Fei, Nancy Kanwisher, Joshua B. Tenenbaum, Daniel L. K. Yamins, Judith E. Fan * <br>
NeurIPS, 2021. [[Paper]](https://arxiv.org/pdf/2106.08261v2.pdf) [[Code]](https://github.com/cogtoolslab/physics-benchmarking-neurips2021)

* **Physion: Evaluating Physical Prediction from Vision in Humans and Machines.** <br>
*Daniel M. Bear, Elias Wang, Damian Mrowca, Felix J. Binder, Hsiau-Yu Fish Tung, R. T. Pramod, Cameron Holdaway, Sirui Tao, Kevin Smith, Fan-Yun Sun, Li Fei-Fei, Nancy Kanwisher, Joshua B. Tenenbaum, Daniel L. K. Yamins, Judith E. Fan * <br>
NeurIPS, 2021. [[Paper]](https://arxiv.org/pdf/2106.08261v2.pdf) [[Code]](https://github.com/cogtoolslab/physics-benchmarking-neurips2021)

* **SPACE: A Simulator for Physical Interactions and Causal Learning in 3D Environments.** <br>
*Jiafei Duan, Samson Yu, Cheston Tan * <br>
ICCV SEAI Workshop, 2021. [[Paper]](https://openaccess.thecvf.com/content/ICCV2021W/SEAI/html/Duan_SPACE_A_Simulator_for_Physical_Interactions_and_Causal_Learning_in_ICCVW_2021_paper.html) [[Code]](https://github.com/jiafei1224/SPACE)

* **AVoE: A Synthetic 3D Dataset on Understanding Violation of Expectation for Artificial Cognition.** <br>
*Arijit Dasgupta, Jiafei Duan, Marcelo H.Ang Jr, Cheston Tan* <br>
NeurIPS PRIBR Workshop, 2021. [[Paper]](https://arxiv.org/abs/2110.05836) [[Code]](https://github.com/jiafei1224/AVoE)

## <a name="physengine"></a> Physics Engine
* Bullet (Blender)
* Newton Game Dynamics
* PhysX (Unreal & Omniverse)
* Box2D
* Tokamak Game Physics
* Havok Physics
* Phyz
* Unity Physics Engine (Unity)

## <a name="publicationvenues"></a> Publication Venues
* Conference on Computer Vision and Pattern Recognition (CVPR)
* Conference on Neural Information Processing Systems (NeurIPS)
* AAAI Conference on Artificial Intelligence (AAAI)
* International Conference on Learning Representations (ICLR)
