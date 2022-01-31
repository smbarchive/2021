---
layout: group
author: esmb
day: "Wednesday (Thursday)"
subgroup: "EVOP"
title: "Modeling and Simulation of Hydrodynamics in Cell Biology"
organizers: "Thomas Fai (Brandeis University, USA), Ying Zhang (Brandeis University, USA)"
description: "Hydrodynamics are ubiquitous in living organisms and influence many cellular properties and processes, including intracellular processes, reaction kinetics and cell-cell signaling cascade. Participants in this mini-symposium present research on the role of hydrodynamics across different scales ranging from the subcellular to single cell to collections of cells. At the subcellular scale, fluid dynamics are key in the organization of the intracelluar machinery for cell division and for the trafficking of proteins in the cell membrane. On the single cell level, cells sense and respond to the dynamic fluid environments in development, angiogenesis, and bone remodeling. On larger scales, the mechanics of suspensions of cells and how they interact with surfaces is important for the function of the circulatory system and in measurements using flow cytometry. To study these fluid-structure interaction problems, mathematical models involving deterministic or stochastic PDEs are combined with numerical methods such as the immersed boundary method."
code: "MS15"
author1: "Paul Atzberger"
inst1: " (UC Santa Barbara, USA)"
title1: "Surface Fluctuating Hydrodynamics Approaches for Proteins Kinetics and Transport within Curved Lipid Bilayer Membranes"
abstract1: "We introduce surface fluctuating hydrodynamics approaches for investigating transport and fluid-structure interactions arising in cell mechanics within curved lipid bilayer membranes.  We focus particularly on drift-diffusion dynamics of interacting proteins and microstructures. We show how a mesoscale stochastic description of the mechanics can be formulated (SPDEs) accounting for geometric contributions, hydrodynamic coupling, and thermal fluctuations.  The underlying stochastic equations (SPDEs) pose practical challenges for use in simulations, including, (i) a need for accurate and stable discretizations of geometric terms and differential operators on curved geometries, (ii) techniques for hydrodynamics handling surface incompressibility constraints, and (iii) stiffness from rapid time-scales introduced by the thermal fluctuations.  We show how practical spectral methods and meshfree computational approaches can be developed for simulations over long spatial-temporal scales.  We then present results for protein and microstructure interactions within membranes and the roles played by hydrodynamic coupling and geometry."
author2: "Luoding Zhu"
inst2: " (Indiana U-Purdue U Indianapolis, USA)"
title2: "Modeling and simulation of fluid flow over osteocyte"
abstract2: "Bone’s structure, development, and remodeling are highly complex. Bone is
permeated by an intricate system of interconnected canals (lacuno-canalicular
network) that are filled with interstitial fluid and connect mechanosensing
osteocytes. These networks multiply macroscale strains that occur during normal
motion (e.g. walking or running) approximately tenfold by the time they reach the
osteocytes. The amplification mechanism is still not well characterized. Due to the
extreme complexity of the osteocyte-fluid-lacuno-canalicular system and the hard
bone that encases the system, in-vivo laboratory experiments are challenging to
conduct. Mathematical modeling, however, can provide a viable approach for
shedding insights into the force amplification that occurs in the system.
We introduce two mathematical models for modeling and simulation of fluid-
osteocyte interaction. The first models fluid-osteocyte interactions in a lacuna-
canalicular network in two dimensions by using the lattice Boltzmann approach. The
model considers the influence of the number and geometry of the canaliculi on the
wall shear and wall normal stress on the osteocyte. The second models an osteocyte
exposed to viscous shear flow in three dimensions by using the immersed boundary
approach. The osteocyte is represented by a network of fibers constructed based on
images taken during experiments. The model considers how force is distributed
throughout the osteocyte when external forcing is applied to the cell. These studies
are ongoing and we will report our current progress on these efforts."
author3: "Nicholas Chisholm"
inst3: " (Worcester Polytechnic Institute, USA)"
title3: "Novel Regularized Stokeslets for Biological Fluid Flow Problems"
abstract3: "The method of regularized Stokeslets is well suited for simulating micro-scale biological fluid dynamics.  Over the past two decades, it has proven very useful for describing the locomotion of microorganisms and the fluid-structure interactions of propulsive organelles such as cilia and flagella.  However, there are many possible choices for regularizing the (singular) fundamental solution to the Stokes equations (the 'Stokeslet'), and this choice often requires tailoring to the specific problem at hand for best results.  In this talk, we generate regularized Stokeslets using their associated biharmonic and vector potentials.  These regularized Stokeslets are automatically divergence free, and they may be chosen to be equivalent (or arbitrarily close) to the singular Stokeslet outside a small region surrounding the point of forcing.  Regularized Stokeslets having this latter property may be especially useful with known image systems for, e.g., the flow inside of a spherical cavity because boundary conditions at the cavity boundary may be satisfied exactly.  We validate the usefulness of these regularized Stokeslets by quantifying their behavior for well-known problems such as flow due to the motion of a rigid cylinder/sphere and of thin, flexible filaments (e.g., cilia).  We anticipate that our method will be useful for simulating intracellular forces and fluid flows during active cellular processes such as mitosis."
author4: "Thomas Fai"
inst4: " (Brandeis University, USA)"
title4: "Hydrodynamics of cell suspensions near walls"
abstract4: "Many real-world examples of fluid-structure interaction, such as the motion of red blood cells through blood vessels, involve the near-contact of elastic structures with boundaries. We use the immersed boundary method to simulate the interactions of deformable objects with walls. In practice, the near-contact with the wall and resulting lubrication layer are often under-resolved, and we show how certain formulations of the boundary conditions lead to spurious behaviors. We show how the lubricated immersed boundary method can be used to increase the accuracy of simulations in the case of dense cell suspensions, in which near-contact occurs through cell-wall, cell-cell, and intracellular interactions."
---
