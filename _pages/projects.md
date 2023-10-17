---
permalink: /projects/
excerpt: "My work history"
classes: wide
author_profile: true
---
#
# Tropical cyclones
Funded by the National Science Foundation, and in collaboration with Dr. Steve Guimond from Hampton University, we are investigating, by high-performance computing and numerical means, the fluid flow dynamics that control the rapid intensification of tropical cyclones. The software at the foundation of this (computationally demanding) project is the Nonhydrostatic Unified Model of the Atmosphere ([NUMA](https://frankgiraldo.wixsite.com/mysite/numa)), born from the fingers of my long-time mentor [Prof. Frank X. Giraldo](https://frankgiraldo.wixsite.com/mysite/) and James F. Kelly (Jim) at the [Naval Postgraduate School](https://www.nps.edu), and co-developed by the PI and graduate student Yassine Tissaoui for many years.
The fugure below shows the cloud content within a tropical cyclone simulated using adaptive mesh refinement up to LES resolution of 60 meters in the inner region of the hurricane! The 3D domain is massive, covering 800km X 800km X 30km. While the grid dimensions change as the simulation advances, the simulation at the time when this plot was created has a total of 127,000,000 grid points!
![Tc](/assets/images/cloud-NVIDIAIndex.png)

# Improving cloud modeling on large computers
The paper by graduate student Yassine Tissaoui investigated how vertically unstructured grids can be beneficial in the modeling of clouds on very large computers. This work sets the stepping stone towards the ability to use fully three-dimensional adaptive grids to study tropical cyclones (see project above) on exascale computers without breaking the bank when it comes to computational cost.
[Tissaoui et al.](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2022MS003283)
![cloud](../assets/images/cloudJAMES.jpg)

# Whale simulations
This study, in collaboration with scientists from different institutions, contributed to a better understanding of why remoras attachon some very specific parts of large blue whales. All simulations were performed by Dr. Abhishek Mukherjee while he was a doctoral student at NJIT. The multi-physics software [Alya](https://www.bsc.es/research-development/research-areas/engineering-simulations/alya-high-performance-computational) from the [Barcelona Supercomputing Center](https://www.bsc.es) was a key tool to obtain these results. The New York Times even wrote an article about this study [NY Times link](https://www.nytimes.com/2020/10/29/science/remoras-suckerfish-whales.html)! [Flammang et al. 2020](https://journals.biologists.com/jeb/article/223/20/jeb226654/226037/Remoras-pick-where-they-stick-on-blue-whales)
![whale](/assets/images/contour_blue_03.jpg)


# Tsunami modeling and simulation (Coastal resilience)
Communities around the world are increasingly interested in nature-based solutions to the mitigation of coastal risks by coastal forests, but it remains unclear how much protective benefits vegetation provides, particularly in the limit of highly energetic flows after tsunami impact. Abhishek Mukherjee's doctoral thesis started a long-term investigation of how much of the flow energy can be deviated or abosrbed by the presence of flexible large coastal trees. Some initial results were published in [Mukherjee et al.](https://www.sciencedirect.com/science/article/abs/pii/S0378383923000108). This work is in collaboration with Dr. Juan Carlos Cajas at the Universidad Autonoma de Mexico, en Merida, and Guillaume Houzeaux and Oriol Lehmkuhl from Barcelona Supercomputing Center. 
More work on tsunami modeling by the PI can be also found in [Madden et al.]((https://gmd.copernicus.org/articles/16/3479/2023/) and [Lunghino et al.](https://www.pnas.org/doi/10.1073/pnas.1911857117). I suggest to also read the review paper by [Marras and Mandli](https://www.mdpi.com/2076-3263/11/1/5)


![tsun](/assets/images/tsunami1.png)
