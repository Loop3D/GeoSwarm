# GeoSwarm

https://github.com/Loop3D/GeoSwarm.git

Structural geology modelling example prototype code in Netlogo using Spatial Agents.

Developed by Eric A. de deKemp
Geological Survey of Canada
Ottawa, Ontario, Canada

June 8, 2020

This repository is developed to help distribute GeoSwarm Netlogo codes for those wanting to demo, test, enhance and
explore the potential uses of Spatial Agent Based approaches to the modelling of sparse structural geology data for
more complex features.

Several movie clips have been included in the docs folder in MP4 file format for that purpose.
These are also viewable in the embedded gifs of the power point presentation in GeoSwarm/Docs/deKemp_Agents_2019.pptx,
also in the Docs folder, made at the International Association of Mathematical Geoscientists annual meeting in Penn State,
Pensilvania, USA in August 2019.

Importantly each NetLogo file has its own Netlogo version compatibility level. This is due to the long history of
 devleopment of the codes and adaptions of existing older codes from others such as Wave_IAMG.nlogo (1996) to
 Dip_Swarm_IAMG.nlogo (2019). Below is a list of codes and the version levels located in GeoSwarm/Main/.

NetLogo(NL) Code              Version             Description of Simulation (Sim)

      _____                   _______                ______________   


GeoSwarm.nlogo3d					  NL-3D 6.0.4        Structural agent demo for modelling simple data configurations

Dip_Swarm_IAMG.nlogo3d			NL-3D 6.0.4        Simulation with planar (strike/dip) observations

Rotate_IAMG.nlogo3d					NL-3D 6.0.4        Simulation of quaternion rotations

Trace_IAMG.nlogo3d					NL-3D 6.0.4        Simulation of vector fabric field

Mesh_IAMG.NetLogo3d         NL-3D 5.3.1        Simulation of vector meshing

Polyhedra_IAMG.NetLogo3d    NL-3D 5.3.1        Simulation of simple hierarchical objects

Wave_IAMG.nlogo3d           NL-3D 4.1.3        Simulation of physical surface modelling


Many thanks to Uri Wilensky, NetLogo team of developers and contributors who continue to enhance applications and extend the functionality of NetLogo with extensions to 3D, GIS, numerical functionality and other shared codes. Several examples such as wave and flocking codes have been the starting codes for this work presented here. Many thanks to Sarah D'Ettorre (2013) who initiated the first agent meshing codes now incorporated into Mesh_IAMG.NetLogo3d. Thanks also to Doron Nussbaum, Carleton University, School of Computer Science who provided supervision of Sarah D'Ettorre while working on her MSc. Thanks to Mike Hiller and Boyan Brodaric (GSC), for valuable feedback. Early consultation on AI methods from Éric Beaudry, (Université du Québec a Montréal), Khalid Djado and Mathieu Bouyrie (Kinna Technologies) is appreciated. Thanks to all the LOOP 3D team https://loop3d.org/ especially Mark Jessell and Laurent Ailleres for their patience and support of the project. Thanks to RING https://www.ring-team.org/ for academic support for use of Gocad/SKUA software and to Guilaume Caumon of who provided critical feedback for the research.

Note for the Wave code see http://ccl.northwestern.edu/netlogo/models/WaveMachine3D Copyright 1996 Uri Wilensky,
all rights reserved, and for other codes such as the flocking codes used in Dip_Swarm see the Netlogo commons at
http://ccl.northwestern.edu/netlogo/. Center for Connected Learning and Computer-Based Modeling, Northwestern
University, Evanston, IL. for terms of use. The Wave code and other code snippets have been reproduced here for
accademic demo purposes with the understanding that these are to be used for the sole purpose of enhancing the
community practice and use of spatial agents for scientific modelling.

Note also that many comments have been left in the code which will hopefully help the user to understand specific
functions as well as potential future direction for the code. There may be unfinished or commented out proceedures
that reduce functionality through the interface. These were left as bread crumbs for potential future development
paths should an enthusiastic individual continue the exciting path awaiting in agent-based structural geology
development.

Please send comments, bug reports and potential collaboration requests to:
Eric A. deKemp at:  eric.dekemp@canada.ca with the word GeoSwarm in the subject heading.

Contact Info:
Eric A. de Kemp
Geological Survey of Canada, three-dimensional Earth Imaging and Modelling Lab
601 Booth Street, Ottawa, Canada, K0E 1E9
E-mail:  eric.dekemp@canada.ca
https://orcid.org/0000-0003-0347-5792


Project Sites:

https://github.com/Loop3D/GeoSwarm.git

https://loop3d.org/
https://www.ring-team.org/
https://www.pdgm.com/products/skua-gocad/

References:

de Kemp E.A. (2020) Spatial Agents for Geological Surface Modelling, Mathematical Geosciences, (Submitted)

De Paor D G (1995) Quaternions, raster shears, and the modeling of rotations in structural and tectonic studies. In: Proceedings and abstracts: Geological Society of America, (New Orleans, LA, United States, November 6-9) 27(6):72

Wilensky U, Rand W (2015) An Introduction to Agent Based Modeling - Modeling Natural, Social and Engineered Complex Systems with Netlogo. Massachusetts Institute of Technology.  ISBN-10: 0262731894

Wilensky U (1998) NetLogo Flocking model.  http://ccl.northwestern.edu/netlogo/models/Flocking,  Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.

Wilensky U (1996) NetLogo Wave Machine 3D model. http://ccl.northwestern.edu/netlogo/models/WaveMachine3D, Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.

Wilensky U (1999) NetLogo. http://ccl.northwestern.edu/netlogo, Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL. NetLogo Home page: http://ccl.northwestern.edu/netlogo/

Woodcock N H (1977) Specification of Fabric Shapes using an eigenvalue method. Geological Society of America Bulletin 88:1231-1236
