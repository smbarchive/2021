---
layout: group
author: esmb
day: "Monday (Tuesday)"
subgroup: "CDEV"
title: "Computational models of extracellular matrix effects on cell migration and tissue formation"
organizers: "Magdalena Stolarska (University of St. Thomas, United States), Lisanne Rens (Delft University of Technology, Netherlands)"
description: "During development, health and disease, cells actively migrate as single cells or collectively. Vital processes in which cell migration plays a role include embryogenesis, wound healing and cancer metastasis. Cells and tissues are surrounded by the extracellular matrix (ECM), a network of proteins and fibers. Cells have complex interactions with the ECM, as they deposit matrix fibers, pull on matrix fibers, respond to various cues like fiber alignment and ECM stiffness.

To understand how cell migration is guided by the ECM, computational modeling is a powerful tool. It allows us to (more readily, compared to wet-lab experiments) decompose different mechanical aspects, such as ECM stiffness, and study its effect on cell migration.

In this field of mathematical biology, many models have been developed. The aim of this mini- symposium is to bring together the diverse modeling approaches of specific ECM cues, and also bridge single cell migration to collective cell behavior and whole tissues.

We invite people to talk about their modeling approach and their gained biological insights. Four talks will focus on single cell migration, and four talks will be about collective cell migration and tissue formation. The studied extracellular matrix cues range from ECM density, stiffness, and fiber alignment."
code: "MS07"
code2: "MS06"
author1: "Qiyao Peng"
inst1: " (Delft University of Technology, Netherlands)"
title1: "A cell shape evolution model for wound contraction and cancer cell metastasis using morphoelasticity"
abstract1: "Cells may attain various shapes and sizes. It has been widely documented that cell geometry influences cellular activities like cell growth and death, cell mobility and adhesion to the direct environment. The shape of a motile cell is determined by its boundaries, which dynamically vary with a local balance between retraction and protrusion. During wound healing, epidermal cells alter their shape for re-epithelialization and fibroblasts (spindle shape) differentiate into myofibroblasts (dendric shape) to regenerate collagen bundles in the extracellular matrix, while they exert traction forces causing skin contraction. For cancer cell metastasis, which is the main reason of death of cancer patients, cancer cells need to deform in order to migrate through and around obstacles during invasion and they are observed to apply traction forces on their immediate environment.

We developed a phenomenological model to simulate cell shape evolution during cell migration, based on the work in [1] and [2], where the traction forces exerted by the cells were not yet considered. Plastic deformations of the direct environment of the cells are modeled by morphoelasticity theory and point forces, which result into partial differential equations describing the momentum balance with Dirac Delta distributions for point forces over the boundary elements of the cells. The partial differential equations are solved by finite-element methods.  In our model, the cell membrane is split into line segments by nodal points, and each point is connected to the cell center by an elastic spring to maintain the cell cytoskeleton (see Figure 1). Together with chemotaxis/mechanotaxis, passive convection and random walk, the displacement of the nodal point is determined. Hence, the cell shape evolves over time during cell migration.  

To validate the model, we managed to reproduce the most important trends observed in the experiment in [3]. The model can be applied to mimic various (microscopic) biological observations with several equilibrium shapes of cell, for instance, circular, elliptic and hypercloid-shaped. These equilibrium shapes are characteristic for the phenotype of the cell. Furthermore, the current model provides a basis that can be expanded to describe more experimentally observed phenomena in cell geometry. For more details about this part of work, we refer to [4].


References: 
[1] Chen J, Weihs D, Dijk MV, Vermolen FJ (2018) A phenomenological model for cell and nucleus deformation during cancer metastasis. Biomechanics and Modeling in Mechanobiology 17(5):1429–1450, DOI 10.1007/s10237-018-1036-5, URL https://doi.org/10.1007/s10237-018-1036-5

[2] Vermolen FJ, Gefen A (2012) A phenomenological model for chemico-mechanically induced cell shape changes during migration and cell–cell contacts. Biomechanics and Modeling in Mechanobiology 12(2):301–323, DOI 10.1007/s10237-012-0400-0, URL https://doi.org/10.1007/s10237-012-0400-0

[3]  Mak M, Reinhart-King CA, Erickson D (2013) Elucidating mechanical transition effects of invading cancer cells with a subnucleus-scaled microfluidic serial dimensional modulation device. Lab Chip 13(3):340–348, DOI 10.1039/c2lc41117b, URL https://doi.org/10.1039/c2lc41117b

[4] Peng Q, Vermolen FJ and Weihs D (2021) A Formalism for Modelling Traction forces and Cell Shape Evolution during Cell Migration in Various Biomedical Processes. Journal Biomechanics and Modeling in Mechanobiology. Online from April 2021."
author2: "Haryana Thomas"
inst2: " (University at Buffalo, The State University of New York, United States)"
title2: "Excess Collagen Deposition in Diabetic Kidney Disease Enhances Cellular Communication: A Mathematical Model"
abstract2: "Diabetic kidney disease is a significant health burden in the US and worldwide. During diabetic kidney disease collagen deposition occurs in the mesangium, a tissue located at the center of the filtration unit of the kidney. The collagen deposition that occurs in the mesangium changes the transport property of the matrix, and, therefore, the ability of signaling molecules to traverse through that medium. The extent to which collagen deposition impacts the ability of glomerular cells to communicate has not been previously investigated. Using established models, we investigated whether collagen deposition impacts glomerular cell communication. We hypothesize that the pathological deposition of collagen decreases the ability of glomerular cells to communicate.

Our model predicted that collagen deposition enhances the signaling range of the mesangial cell. This enhancement can disrupt the controlled, localized inter-cellular signaling that occurs in health and thus contribute to the exacerbation of diabetic kidney damage. Previously, many models have been developed to study the parameters that impact the signaling range of cells, however, the mathematical interrogation of inter-cellular signaling in the context of diabetic kidney damage has not been previously done. The novel insight gained from this mathematical study enhances our understanding of how pathological tissue damage induced by diabetes contributes to the disruption of cellular function."
author3: "Robyn Shuttleworth"
inst3: " (University of Saskatchewan, Canada)"
title3: "Cell-scale degradation of peritumoural extracellular matrix fibre network and its role within tissue-scale cancer invasion"
abstract3: "Local cancer invasion of tissue is a complex, multiscale process which plays an essential role in tumour progression. During the interaction between cancer cell population and the extracellular matrix (ECM), of key importance is the role played by both bulk two-scale dynamics of ECM fibres within collective movement of the tumour cells and the multiscale leading-edge dynamics driven by proteolytic activity of the matrix-degrading enzymes (MDEs) that are secreted by the cancer cells. We focus on understanding the cell-scale cross talk between the micro-scale parts of these two multiscale subsystems which get to interact directly in the peritumoural region, with immediate consequences both for MDE micro-dynamics occurring at the leading edge of the tumour and for the cell-scale rearrangement of the naturally oriented ECM fibres in the peritumoural region, ultimately influencing the way a tumour progresses in the surrounding tissue."
author4: "Katarzyna Rejniak"
inst4: " (H. Lee Moffitt Cancer Center & Research Institute, United States)"
title4: "ECM mechanical and metabolic architecture during early ductal invasions"
abstract4: "Progression from a ductal carcinoma in situ (DCIS) to an invasive tumor is a major step initiating a devastating and often lethal metastatic cascade. One sentinel event that initiate this process is the development of ductal microinvasions, i.e., small cohorts of tumor cells that breach the basement membrane surrounding the duct and migrate through the extracellular matrix (ECM) leading to irreversible changes in tumor and stromal architecture. We used a combination of advanced image analysis techniques applied to patients’ histology data to extract features which identify specific properties of individual tumor cells inside the duct and on the invasive front. By integrating these histology-based data with a hybrid agent-based mathematical model, we investigated the biomechanical interactions between the cells and the ECM fiber architecture, and microenvironmental physical and metabolic features that define tumor niche prone to microinvasions."
---
