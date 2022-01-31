---
layout: group
author: esmb
day: "Wednesday (Thursday)"
subgroup: "MMPB"
title: "Deterministic and stochastic models for complex cardiovascular phenomena"
organizers: "Martina Bukac (University of Notre Dame, United States), Daniele Schiavazzi (University of Notre Dame, United States)"
description: "Hemodynamic modeling has become a powerful tool in the study of basic vascular function, as well as many cardiovascular diseases. Biophysically detailed vascular simulations can reveal underlying mechanisms that help explain experimental and clinical observations. As a result, there is an increasing demand for fast and efficient numerical algorithms to solve coupled multi-physics problems arising from biomedical applications. Examples include fluid-structure interaction models (e.g., valvular modeling), fluid-porous or poroelastic medium interaction models (e.g., biological tissue or tumor modeling), as well as models of transport phenomena (e.g., transport of drugs or chemicals). Moreover, creation of realistic models might be difficult in situations where only partial knowledge is available for the input processes. Examples include, but are not limited to, uncertainty in the model anatomy, physiologic boundary conditions and material properties of the cardiac and vascular tissue. In such cases, uncertainty quantification becomes an integral part of the modeling exercise. While significant progress have been achieved in recent years, hemodynamic modeling still poses significant challenges in the mathematical and computational sciences. Thus, substantial effort is allocated to the design of adaptable and uncertainty-aware numerical methods for coupled problems due to their intricate multi-physics nature, possible strong nonlinearity and presence of uncertainty. Hence, this minisymposium focuses on methodological developments and analysis of results from deterministic and stochastic cardiovascular models."
code: "MS14"
code2: "MS20"
author1: "Suncica Canic"
inst1: " (University of California, Berkeley, United States)"
title1: "Computational design of a bioartificial pancreas"
abstract1: "This talk will address the design of a first implantable bioartificial pancreas without the need for immunosuppressant therapy. The design is based on transplanting the healthy (donor) pancreatic cells into a poroelastic medium (alginate hydrogel, or agarose gel) and encapsulating the cell-containing medium between two nanopore semi-permeable membranes. The nanopore membranes are manufactured to block the immune cells while allowing passage of nutrients and oxygen to keep the transplanted cells viable as long as possible. The key challenge is maintaining the survival of transplanted pancreatic cells for an extended period of time of which oxygen is the main limiting factor. This challenge is addressed via our nonlinear, multi-scale, multi-physics mathematical and computational model. At the micro scale we use particle-based simulations to study the nano-scale structure of the poroelastic medium containing the cells, and combine the results with Convolution Neural Networks approaches to recover the macro-scale parameters, such as hydraulic conductivity of the poroelastic get matrix. The macro-scale parameters are used to study fluid-structure interaction between blood flow at the multi-layered poroelastic medium containing the cells. The output of the FSI simulations is then used in the advection-reaction-diffusion models to study oxygen supply to the seeded pancreatic cell. The results of the numerical simulations have aided optimal design of the first implantable bioartificial pancreas without the need for immunosuppressant therapy."
author2: "Philipp Milović"
inst2: " (University of Zagreb, Croatia)"
title2: "A block-coupled finite volume solver for analysis of large strain in incompressible hyperelastic materials"
abstract2: "Efficient solution procedures for fluid-structure interaction simulations of
vascular flows require adequate solid phase solvers. Existing finite volume
based solvers exhibit convergence and stability issues for problems of
incompressible finite strain and unstructured meshes which commonly occur when
modelling arterial tissue. In this work a block-coupled finite volume solution
methodology employing a mixed displacement-pressure formulation for problems of
incompressible finite strain in hyperelastic materials is developed. The
solution strategy is based on integral momentum and mass conservation equations
wherein pressure is used as an additional variable to improve numerical
stability. The domain is discretized by cell-centred finite volumes of
arbitrary polyhedral shape and a coupled solution procedure is used to improve
convergence. Performance of the solution procedure is evaluated for several
test cases and compared with analytical and finite element solutions."
author3: "Paolo Zunino"
inst3: " (Politecnico di Milano, Italy)"
title3: "A meso-scale computational model for micro-vascular oxygen transfer"
abstract3: "We address a mathematical model for oxygen transfer in the microcirculation.
The model includes blood flow and hematocrit transport coupled with the interstitial flow, oxygen transport in the blood and the tissue, including capillary-tissue exchange effects. Moreover, the model is suited to handle arbitrarily complex vascular geometries. The purpose of this study is the validation of the model with respect to classical solutions and the further demonstration of its adequacy to describe the heterogeneities of oxygenation in the tissue micro-environment. Finally, we discuss the importance of these effects in the treatment of cancer using radiotherapy."
author4: "Rana Zakerzadeh"
inst4: " (Duquesne University, United States)"
title4: "The Role of Intraluminal Thrombus on the Vessel Wall Oxygen Starvation"
abstract4: "In this presentation, the biomechanical role of intraluminal thrombus (ILT) in an abdominal aortic aneurysm (AAA) is investigated. It is hypothesized that different ILT geometries can enhance wall strength while also inhibiting oxygen transport and inducing arterial wall degradation. The objective of this work is to simulate AAAs with variable ILT dimensions and analyze how ILT thickness and size influence AAA rupture.
A comparison between different ILT morphologies was performed. Geometric variations studied include the thickness, length, and degree of asymmetry of the ILT. Nine two-bulged, symmetrical AAAs were modeled with varying ILT thicknesses (0.1 cm, 0.2 cm, or 0.4 cm) and lengths (4cm, 6cm, or 8cm) using CAD software. A finite element method simulation of the Fluid-Solid Interactions (FSI) between arterial wall, ILT and blood was solved to assess the influence ILT geometry has on wall stress and oxygen concentration
Results are presented for wall stress and deformation patterns, lumen pressure and velocity fields, and oxygen concentration within the ILT and arterial wall. While ILT geometries were found to reduce wall stress, our simulations demonstrated that thicker and longer ILTs reduced oxygen transport, leading to wall degradation."
---
