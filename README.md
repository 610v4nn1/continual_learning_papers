# Continual Learning Literature 
This repository is maintained by Massimo Caccia and Timothée Lesort don't hesitate to send us an email to collaborate or fix some entries ({massimo.p.caccia , t.lesort} at gmail.com). The automation script of this repo is adapted from [Automatic_Awesome_Bibliography](https://github.com/TLESORT/Automatic_Awesome_Bibliography).

 For contributing to the repository please follow the process [here](https://github.com/optimass/continual_learning_papers/blob/master/scripts/README.md) 

 You can directly use our bib.tex in overleaf [with this link](https://www.overleaf.com/project/606f5acf8bf59dcda3e66f9e) 

## Outline 
- [Classics](https://github.com/optimass/continual_learning_papers/blob/master/README.md#classics)
- [Empirical Study](https://github.com/optimass/continual_learning_papers/blob/master/README.md#empirical-study)
- [Surveys](https://github.com/optimass/continual_learning_papers/blob/master/README.md#surveys)
- [Influentials](https://github.com/optimass/continual_learning_papers/blob/master/README.md#influentials)
- [New Settings or Metrics](https://github.com/optimass/continual_learning_papers/blob/master/README.md#new-settings-or-metrics)
- [General Continual Learning Methods (SL and RL)](https://github.com/optimass/continual_learning_papers/blob/master/README.md#general-continual-learning-methods-(sl-and-rl))
- [Task-Agnostic Continual Learning](https://github.com/optimass/continual_learning_papers/blob/master/README.md#task-agnostic-continual-learning)
- [Regularization Methods](https://github.com/optimass/continual_learning_papers/blob/master/README.md#regularization-methods)
- [Distillation Methods](https://github.com/optimass/continual_learning_papers/blob/master/README.md#distillation-methods)
- [Rehearsal Methods](https://github.com/optimass/continual_learning_papers/blob/master/README.md#rehearsal-methods)
- [Generative Replay Methods](https://github.com/optimass/continual_learning_papers/blob/master/README.md#generative-replay-methods)
- [Dynamic Architectures or Routing Methods](https://github.com/optimass/continual_learning_papers/blob/master/README.md#dynamic-architectures-or-routing-methods)
- [Hybrid Methods](https://github.com/optimass/continual_learning_papers/blob/master/README.md#hybrid-methods)
- [Continual Few-Shot Learning](https://github.com/optimass/continual_learning_papers/blob/master/README.md#continual-few-shot-learning)
- [Meta-Continual Learning](https://github.com/optimass/continual_learning_papers/blob/master/README.md#meta-continual-learning)
- [Lifelong Reinforcement Learning](https://github.com/optimass/continual_learning_papers/blob/master/README.md#lifelong-reinforcement-learning)
- [Task-Agnostic Lifelong Reinforcement Learning](https://github.com/optimass/continual_learning_papers/blob/master/README.md#task-agnostic-lifelong-reinforcement-learning)
- [Continual Generative Modeling](https://github.com/optimass/continual_learning_papers/blob/master/README.md#continual-generative-modeling)
- [Miscellaneous](https://github.com/optimass/continual_learning_papers/blob/master/README.md#miscellaneous)
- [Applications](https://github.com/optimass/continual_learning_papers/blob/master/README.md#applications)
- [Thesis](https://github.com/optimass/continual_learning_papers/blob/master/README.md#thesis)
- [Libraries](https://github.com/optimass/continual_learning_papers/blob/master/README.md#libraries)
- [Workshops](https://github.com/optimass/continual_learning_papers/blob/master/README.md#workshops)

## Classics
- [**Catastrophic forgetting in connectionist networks**](https://www.sciencedirect.com/science/article/abs/pii/S1364661399012942) , (1999) by *French, Robert M.* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1171-L1185) 
- [**Lifelong robot learning**](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.71.3723&rep=rep1&type=pdf) , (1995) by *Thrun, Sebastian and Mitchell, Tom M* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L259-L268) 
``` Argues knowledge transfer is essential if robots are to learn control with moderate learning times ``` 
- [**Catastrophic interference in connectionist networks: The sequential learning problem**](https://www.sciencedirect.com/science/article/pii/S0079742108605368) , (1989) by *McCloskey, Michael and Cohen, Neal J* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L851-L861) 
``` Introduces CL and reveals the catastrophic forgetting problem ``` 

## Empirical Study
- [**Continual learning: A comparative study on how to defy forgetting in classification tasks**](https://arxiv.org/abs/1909.08383) , (2019) by *Matthias De Lange, Rahaf Aljundi, Marc Masana, Sarah Parisot, Xu Jia, Ales Leonardis, Gregory Slabaugh and Tinne Tuytelaars* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L344-L353) 
``` Extensive empirical study of CL methods (in the multi-head setting) ``` 
- [**Three scenarios for continual learning**](https://arxiv.org/abs/1904.07734) , (arXiv 2019) by *van de Ven, Gido M and Tolias, Andreas S* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L883-L890) 
``` An extensive review of CL methods in three different scenarios (task-, domain-, and class-incremental learning) ``` 
- [**Towards Robust Evaluations of Continual Learning**](https://arxiv.org/abs/1805.09733) , (arXiv 2018) by *Farquhar, Sebastian and Gal, Yarin* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L271-L278) 
``` Proposes desideratas and reexamines the evaluation protocol ``` 

## Surveys
- [**Embracing Change: Continual Learning in Deep Neural Networks**](https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613(20)30219-9) , (2020) by *Hadsell, Raia, Rao, Dushyant, Rusu, Andrei and Pascanu, Razvan* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L1-L12) 
- [**Towards Continual Reinforcement Learning: A Review and Perspectives**](https://arxiv.org/abs/2012.13490) , (2020) by *Khimya Khetarpal, Matthew Riemer, Irina Rish and Doina Precup* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L128-L137) 
``` A review on continual reinforcement learning ``` 
- [**A Wholistic View of Continual Learning with Deep Neural Networks: Forgotten Lessons and the Bridge to Active and Open World Learning**](https://arxiv.org/abs/2009.01797) , (arXiv 2020) by *Mundt, Martin, Hong, Yong Won, Pliushch, Iuliia and Ramesh, Visvanathan* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2425-L2432) 
``` propose a consolidated view to bridge continual learning, active learning and open set recognition in DNNs ``` 

## Influentials
- [**Towards Robust Evaluations of Continual Learning**](https://arxiv.org/abs/1805.09733) , (arXiv 2018) by *Farquhar, Sebastian and Gal, Yarin* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L271-L278) 
``` Proposes desideratas and reexamines the evaluation protocol ``` 

## New Settings or Metrics
- [**A Wholistic View of Continual Learning with Deep Neural Networks: Forgotten Lessons and the Bridge to Active and Open World Learning**](https://arxiv.org/abs/2009.01797) , (arXiv 2020) by *Mundt, Martin, Hong, Yong Won, Pliushch, Iuliia and Ramesh, Visvanathan* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L2425-L2432) 
``` propose a consolidated view to bridge continual learning, active learning and open set recognition in DNNs ``` 

## Lifelong Reinforcement Learning
- [**Towards Continual Reinforcement Learning: A Review and Perspectives**](https://arxiv.org/abs/2012.13490) , (2020) by *Khimya Khetarpal, Matthew Riemer, Irina Rish and Doina Precup* [[bib]](https://github.com/optimass/continual_learning_papers/blob/master/bibtex.bib#L128-L137) 
``` A review on continual reinforcement learning ``` 
