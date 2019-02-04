# EPANetX
An integration project of EPANet with NetworkX

◆What is EPANet◆
EPANet is an hydraulic simulation software developed by Sir Rossman in 2000 (see https://www.epa.gov/water-research/epanet).
EPANet can simulate pressure, velocity and water quality (water age, chemical concentration)  in water distribution systems (WDSs) as a snapshot or extended period simulation (so-called,EPS).
This software can be programmed by using its Programmer's toolkit and now wraped for other programming languages such as Python, R, VBA etc.
This software is widely used by a symbol of water distrion systems analysis (WDSA) community for almost twenty years.

◆What is NetworkX◆
NetworkX is an graph/network theory libraryfor Python Environment (see https://networkx.github.io/documentation/stable/tutorial.html).
This can solve a variety of network problem such as shortest path between nodes, and visualize networks composed of links and nodes with attributes (e.g, elavation, pressure, diameter).
This is now used by WNTR (pronounced "winter") , an WDSs resilience analysis softawre developed by US-EPA (see https://cfpub.epa.gov/si/si_public_record_report.cfm?Lab=NHSRC&dirEntryId=337793). But still, NetworkX has not used so much despite high compatibility of its library with EPANet.

◆EPANetX◆
Major version of EPANET is 2.0 and EPANET is being developed as an open-souce project (see https://github.com/OpenWaterAnalytics/EPANET).
Throhgh its open-source project version 2.1 has already been released and ver. 3.0 is planed to be released in the near future (hopefully). 
An major drawbacks of EPANET are poor visualization capability, limited number of legend component and so on.
EPANET is often integrated into optimization algorithms through EPANET toolkit, but the toolkit does not have a calling function for network visulization. Thus, users have to input optimized network configuration into EPANET and visualize the optimized network for every single optimization of any kind of simulation using the toolkit. It waste your time.
It should be great if network visualization function can be called in your programme with better visualization and network analysis capability.
This project is to improve and support EPANet function by integrating NetworkX into EPAnet.

◆Required Library◆
Python 3 https://www.python.org/
EPANETTOOLS https://pypi.org/project/EPANETTOOLS/
NetworkX https://networkx.github.io/documentation/stable/tutorial.html
Numpy http://www.numpy.org/
Matplotlib https://matplotlib.org/

◆Required file◆
EPANET input file (.inp)

◆Acknowledgement◆


Welcome any modifications, ideas, or comments from motivated and skillful users!!

◆History of README◆
1st: 2019.02.04
2nd:

◆Release Note◆
1st: 2019.
