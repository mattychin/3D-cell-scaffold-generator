# 3D Cell Scaffold Generator (3D CSG) 🧑‍💻🔬🧫


**What:** 3D Cell Scaffold Generator (3D CSG) is a Grasshopper-based algorithmic toolset created by Dr Matthew Chin to generate bioinspired, 3D printable scaffolds. This toolset was developed as part of a project to create cell scaffolds recapitulating the structural complexity of tissue microenvironments.

**Why:** Cells interact with a wide variety of physical networks inside the human body. The connectivity of these networks has been shown to a wide range of cell behaviours. Thus, 3D cell culture platofrms, such as [cell scaffolds](https://www.wikilectures.eu/w/Scaffolds_in_tissue_engineering), are typically designed to possess a network architecture that supports the migration and growth of cells. Despite this, [graph theory](https://en.wikipedia.org/wiki/Graph_theory) (the mathematical study of graphs/networks) is rarely applied to drive the design of 3D cell scaffolds. To understand how the organisation of networks affects scaffold-adhered cells, we need a way to design networks that reflect the complex topologies found in microenvironments and fabricate them. 

**How:** <u>Note: step-by-step instructions are provided in the Grasshopper file (scaffold_AMI.gh).</u> To design the scaffolds, we took inspiration from [fibroblastic reticular cell (FRC) networks](https://en.wikipedia.org/wiki/Lymph_node_stromal_cell) typically found in secondary lymphoid organs (e.g. lymph nodes). FRC networks are essentially the "motorways" that support the migration of immune cells (e.g. T cells and dendritic cells) and maintain normal functioning of the immune system. These networks are organised in a so-called ["small-world"](https://en.wikipedia.org/wiki/Small-world_network) fashion. To generate small-world networks in 3D, we created an algorithm using Grasshopper in Rhino. The network generation is based on a random geometric graph model, previously used by Soekarjo *et al.* to model FRC networks *in silico*. We incorporated this model in our Grasshopper algorithm and added operations to improve the 3D printability of the generated structures. 

**Applications:** Scaffolds generated by this method are intended to be fabricated by [two-photon polymerisation](https://en.wikipedia.org/wiki/Multiphoton_lithography) and used as a 3D cell culture platform in tissue engineering and cell biology research. 

**📚 Further reading:** 


<u>Graph analysis / computational modelling of FRC networks</u>

- [Mario Novkovic, Lucas Onder, Jovana Cupovic, Jun Abe, David Bomze, Viviana Cremasco, *et al.* *PLoS Biol.* 2016; 14(7):e1002515.](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002515)
- [Mario Novkovic, Lucas Onder, Gennady Bocharov and Burkhard Ludewig. *Cell Reports.* 2020; 30(3): 893-904.e6.](https://www.sciencedirect.com/science/article/pii/S2211124719317279)
- [Kasper M. W. Soekarjo, Johannes Textor, Rob J. de Boer. *J Immunol.* 2019; 202(11): 3318-3325.](https://www.sciencedirect.com/science/article/pii/S2211124719317279)

<u>FRC networks and immunobiology</u>

- [Anne L. Fletcher, Sophie E. Acton, and Konstantin Knoblich. *Nat Rev Immunol.* 2015; 15(6): 350–361.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5152733/)

**📫 How to reach me:** 

Any suggestion to improve this toolset is welcome! 

<a href="mailto:ucbtmhw@ucl.ac.uk"><img src="https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white"></a>
<a href="https://twitter.com/MatthewHWChin"><img src="https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white"></a>
<a href="https://www.linkedin.com/in/matthewchin92/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"></a>


## Getting started 🚀

This algorithmic toolset was built using [Grasshopper](https://www.grasshopper3d.com/), a graphical algorithm editor available in the computer-aided design (CAD) application, [Rhino 7](https://www.rhino3d.com/).

To use some of the components in the toolset, third-party Grasshopper plug-ins will need to be installed:

Library                                                                            | Version         
|----------------------------------------------------------------------------------|------------------|
[Anemone](https://www.food4rhino.com/en/app/anemone)                               | 0.4
[Heteroptera](https://www.food4rhino.com/en/app/heteroptera)                       | 0.4.9.3   
[Fattener](https://discourse.mcneel.com/t/skeleton-fattener-mesh-cage-morph/74766) | 0.0.0.1     
[WeaverBird](https://www.giuliopiacentino.com/weaverbird/)                         | 0.9.0.1
[SpiderWeb](https://www.food4rhino.com/en/app/spiderweb)                           | 0.0.4.2   
[FlexHopper](https://www.food4rhino.com/en/app/flexhopper)                         | 1.0.0.0     
[Pufferfish](https://www.food4rhino.com/en/app/pufferfish)                         | 3.0.0.0   
[LunchBox](https://www.food4rhino.com/en/app/lunchbox)                             | 2020.11.2 .0
[Pancake](https://www.food4rhino.com/en/app/pancake)                               | 2.5.0.0

To use the the algorithm, download the **scaffold_AMI.gh** file and open it inside Grasshopper.


## Acknowledgements 😃

I would like to express my gratitude to the developers whose Grasshopper libraries and components have made this work possible.

I would like to thank Prof Marc-Olivier Coppens ([EPSRC "Frontier Engineering" Centre for Nature Inspired Engineering](https://www.ucl.ac.uk/nature-inspired-engineering/ucl-centre-nature-inspired-engineering), UCL) for his support and guidance on this project. 

Funding: This work was supported in part by the Engineering and Physical Sciences Research Council, EPSRC, through a “Frontier Engineering: Progression” Grant (EP/S03305X/1) and an underpinning multi-user equipment grant (EP/P030084/1); NIH NCI, Cancer Research UK and The Mark Foundation for Cancer Research through the Cancer Grand Challenges ([NexTGen](https://nex-t-gen.com/)).

## License

**3D Cell Scaffold Generator (3D CSG)**
| Copyright (c) 2023 Matthew H. W. Chin

3D CSG is free and you can redistribute and/or modify it under the terms of a [GNU General Public License version 3.0](https://www.gnu.org/licenses/gpl-3.0.html) as published by the Free Software Foundation.
