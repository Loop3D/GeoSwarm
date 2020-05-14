# GeoSwarm

https://github.com/edekemp/GeoSwarm.git

Structural geology modelling example prototype code in Netlogo using Spatial Agents.

Developed by Eric A. de deKemp
Geological Survey of Canada
Ottawa, Ontario, Canada

May 13, 2020

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


Dip_Swarm_IAMG.nlogo3d			NL-3D 6.0.4        Sim with planar (strike/dip) observations

Rotate_IAMG.nlogo3d					NL-3D 6.0.4        Sim of quaternion rotations

Trace_IAMG.nlogo3d					NL-3D 6.0.4        Sim of vector fabric field

Mesh_IAMG.NetLogo3d         NL-3D 5.3.1        Sim of vector meshing

Polyhedra_IAMG.NetLogo3d    NL-3D 5.3.1        Sim of simple hierarchical objects

Wave_IAMG.nlogo3d           NL-3D 4.1.3        Sim of physical surface modelling


Many thanks to Uri Wilensky  NetLogo team of developers and contributors who continue to enhance applications and 
extend the functionality of NetLogo with extensions to 3D, GIS, nuimerical functionality and other shared codes. 
Several examples such as wave and flocking codes have been the starting codes for this work presented here. 
Many thanks to Sarah D'Ettorre (2013) who initiated the first agent meshing codes now incorporated into 
Mesh_IAMG.NetLogo3d. Thanks also to Doron Nussbaum, Carleton Unviersity, School of Computer Science who provided 
supervision of Sarah D'Ettorre while working on her M.Sc. and for advisory guidance in game theory, computer graphics
and computational approaches. Thanks to my collegues at the Geological Survey of Canada for support for this research 
and for valuable feedback esspecially Mike Hiller and Boyan Broadaric. Thanks to all the LOOP 3D team https://loop3d.org/ 
esspecially Mark Jessell and Laurent Ailleres for their patience and support of the project. Also thanks to Guilaume Caumon 
of RING https://www.ring-team.org/ who provided critical feedback and support for the research.

Note for the Wave code see http://ccl.northwestern.edu/netlogo/models/WaveMachine3D Copyright 1996 Uri Wilensky, 
all rights reserved, and for other codes such as the flocking codes used in Dip_Swarm see the Netlogo commons at
http://ccl.northwestern.edu/netlogo/. Center for Connected Learning and Computer-Based Modeling, Northwestern 
University, Evanston, IL. for terms of use. The Wave code and other code snippets have been reproduced here for 
accademic demo purposes with the understanding that these are to be used for the sole purpose of enhancing the 
community practice and use of spatial agents for scientific modelling.

Note also that many comments have been left in the code which will hopefully help the user to understand specific
functions as well as potential future direction for the code. There may be unfinished or commented out proceedures
that reduce functionality through the interface. These were left as bread crumbs for potential future development 
paths should an enthusiastic individual continue the exciting path awaiting in Agent Based structural geology 
development.

Please send comments, bug reports and potential collaboration requests to:
Eric A. deKemp at:  eric.dekemp@canada.ca with the word GeoSwarm in the subject heading. 
