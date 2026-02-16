# authors:
#Gianfranco_Cortés
#Maria_Esteban-Casadevall
#Yueqing_Feng
#Jonas_Henkel
#Edward_Hirst
#Tancredi_Schettini Gherardini
#Alexander_G. Stapleton


# summary:
This work introduces the Nirenberg Neural Network: a numerical approach to the Nirenberg problem of prescribing Gaussian curvature on $S^2$ for metrics that are pointwise conformal to the round metric. Our mesh-free physics-informed neural network (PINN) approach directly parametrises the conformal factor globally and is trained with a geometry-aware loss enforcing the curvature equation. Additional consistency checks were performed via the Gauss-Bonnet theorem, and spherical-harmonic expansions were fit to the learnt models to provide interpretability.  For prescribed curvatures with known realisability, the neural network achieves very low losses ($10^{-7} - 10^{-10}$), while unrealisable curvatures yield significantly higher losses. This distinction enables the assessment of unknown cases, separating likely realisable functions from non-realisable ones. The current capabilities of the Nirenberg Neural Network demonstrate that neural solvers can serve as exploratory tools in geometric analysis, offering a quantitative computational perspective on longstanding existence questions.

# link:
URL:http://arxiv.org/abs/2602.12368v1

[INSPIRE](https://inspirehep.net/literature/3119938)