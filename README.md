# CoRL 2018 - Automorphing Kernels for Nonstationarity in Mapping Unstructured Environments

### Repository for the paper "[Automorphing Kernels for Nonstationarity in Mapping Unstructured Environments](url_todo)", The Conference on Robot Learning (CoRL), 2018
#### Ransalu Senanayake*, Anthony Tompkins*, and Fabio Ramos
 In order to deploy robots in previously unseen and unstructured environments, the robots should have the capacity to learn on their own and adapt to the changes in the environments. For instance, in mobile robotics, a robot should be able to learn a map of the environment from data itself without the intervention of a human to tune the parameters of the model. To this end, leveraging the latest developments in automatic machine learning (AutoML), probabilistic programming, and statistical sampling, under the Hilbert mapping framework which can represent the occupancy of the environment as a continuous function of locations, we formulate a Bayesian framework to learn all parameters of the map. Crucially, this way, the robot is capable of learning the optimal shapes and placement of the kernels in Hilbert maps by merely embedding high-level human knowledge of the problem by means of prior probability distributions. Since the proposed framework employs stochastic variational inference, the model learns tens of thousands of parameters within minutes in both big data and data-scarce regimes. Experiments conducted on simulated and real-world datasets in static and dynamic environments indicate the proposed method significantly outperforms existing stationary occupancy mapping techniques, verifying the importance of learning the interdependent position-shape relationship of kernels alongside other model parameters. .
[Full paper with appendix](http://proceedings.mlr.press/v87/senanayake18a.html)

### Backgroud
* [Bayesian Hilbert Mapping (BHM)](https://github.com/RansML/Bayesian_Hilbert_Maps) is a technique that uses variational inference to estimate uncertainity in occupancy mapping. It uses kernels to project LIDAR data into a high dimensional linear feature space to capture nonlinear spatial patterns and perferm Bayesian inference to model uncertainty. 


**Video**: [https://www.youtube.com/watch?v=IirUlJS49Yw](https://www.youtube.com/watch?v=IirUlJS49Yw)

**Instructions to run the code**: TODO
Simply run dataset1.py in the /Code/ folder

**BibTeX**:
```
@inproceedings{senanayake2018automorphing,
  title={Automorphing Kernels for Nonstationarity in Mapping Unstructured Environments.},
  author={Senanayake, Ransalu and Tompkins, Anthony and Ramos, Fabio},
  booktitle={CoRL},
  year={2018}
}
```
