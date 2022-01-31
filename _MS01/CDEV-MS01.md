---
layout: group
author: esmb
day: "Monday (Tuesday)"
subgroup: "CDEV"
title: "Data-driven modeling across scales - from cytoskeleton to bacterial swarms to multicellular motility to angiogenesis"
organizers: "Alex Mogilner (NYU, United States), Angelika Manhart (UCL, UK)"
description: "Mathematical modeling in cell and developmental biology is thriving. Traditional continuum PDEs' modeling, and discrete particle-based simulations brought quantitative insight and generated testable predictions for experiment. Recently, novel experimental techniques started to yield great volumes of quantitative data, opening new modeling possibilities. To exploit these possibilities, modelers started to combine the traditional mathematical approaches with novel data science tools, including topological data analysis, machine learning, homology analysis and unsupervised feature classification. Four talks will demonstrate how combining the traditional and novel mathematical approaches allows to build predictive models from data. The talks span biological scales, from subcellular (cytoskeletal dynamics), to supercellular (bacterial swarming, collective cell migration, and angiogenesis)."
code: "MS01"
author1: "Angelika Manhart"
inst1: " (UCL, United Kingdom)"
title1: "Explaining the dynamic steady state of actin networks"
abstract1: "Many motile cells use dense, branched actin networks for movement. This requires “macroscopic treadmilling”, where assembly at the front balances disassembly at the rear. We combine the use of a biomimetic motility system with data-driven mathematical modeling to investigate how cofilin, a known disassembly agent, creates dynamic networks of fixed lengths. To capture the observed macroscopic fragmentation of the network, we combine PDE-based modeling of the cofilin binding dynamics with a discrete network disassembly model. This allows to derive a simple formula predicting the equilibrium network length across various control parameters."
author2: "Hannah Jeckel"
inst2: " (University of Marburg, Germany)"
title2: "Learning the space-time phase diagram of bacterial swarm expansion"
abstract2: "Coordinated dynamics of individual components in active matter are an essential aspect of life on all scales. Establishing a comprehensive, causal connection between intracellular, intercellular, and macroscopic behaviors has remained a major challenge due to limitations in data acquisition and analysis techniques suitable for multiscale dynamics. Here, we combine a high-through-put adaptive microscopy approach with machine learning, to identify key biological and physical mechanisms that determine distinct microscopic and macroscopic collective behavior phases which develop as Bacillus subtilis swarms expand over five orders of magnitude in space. Our experiments, continuum modeling, and particle-based simulations reveal that macroscopic swarm expansion is primarily driven by cellular growth kinetics, whereas the microscopic swarming motility phases are dominated by physical cell–cell interactions. These results provide a unified understanding of bacterial multiscale behavioral complexity in swarms."
author3: "Dhananjay Bhaskar"
inst3: " (Yale and Brown Universities, USA)"
title3: "Discrete Agent Modeling and Topological Data Analysis of Self-Organized Multicellular Architectures"
abstract3: "Animal tissues are spatially patterned into complex topologies via directed motility and cell-cell interactions during development, repair, and disease. Segregation and cell sorting, driven by differential adhesion and interfacial tension, generate complex yet stable configurations that underlie tissue morphogenesis. Moreover, alterations of cell-cell adhesion and polarity in epithelial-mesenchymal transition (EMT) are associated with tumor dissemination and metastasis. In this talk, I will describe the use of topological data analysis for the automated classification of multicellular structures associated with EMT and cell sorting.

First, individual and collective phases of epithelial migration are characterized by varying adhesion and random propulsion parameters in an agent-based model derived from experimental observations. Next, persistent homology is computed using cell positions as input, followed by unsupervised classification of the topological features (connected components and loops). Finally, classification results are mapped onto the adhesion-propulsion phase diagram for automatic delineation of phase boundaries. A similar methodology, applied to co-culture simulations with varying adhesion parameters, reveals phase transitions between various patterns of self-assembly in cell sorting. I envision this computational approach will enable new quantitative insights into the emergence of complex tissue topologies via spatiotemporal interactions between one or more cell types."
author4: "John Nardini"
inst4: " (NC State University, USA)"
title4: "Topology discriminates parameter regimes in a model of angiogenesis"
abstract4: "Angiogenesis is the process by which blood vessels form from pre-existing 
vessels. It plays a key role in many biological processes, including embryonic development 
and wound healing, and contributes to many diseases including cancer and rheumatoid 
arthritis. The structure of the resulting vessel networks determines their ability to 
deliver nutrients and remove waste products from biological tissues. Here we simulate 
the Anderson-Chaplain model of angiogenesis at different parameter values and quantify 
the vessel architectures of the resulting synthetic data. Specifically, we propose a 
topological data analysis (TDA) pipeline for systematic analysis of the model. TDA is a 
vibrant and relatively new field of computational mathematics for studying the shape of 
data. We compute topological and standard descriptors of model simulations generated by 
different parameter values. We show that TDA of model simulation data stratifies parameter 
space into regions with similar vessel morphology. The methodologies proposed here are 
widely applicable to other synthetic and experimental data including wound healing, 
development, and plant biology."
---
