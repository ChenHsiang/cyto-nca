CytoNCA is a [Cytoscape](http://www.cytoscape.org/) app  for network centrality analysis,and has been tested on Cytoscape 3.0.X.

[Please downlaod the manual.](https://drive.google.com/file/d/0B13gZNlVofBmcVZld1pjY0tDeDg/edit?usp=sharing)

### For version 2.1 ###
**New function**
<br>We offered the option to <b>remove self-loops and parallel edges</b> before calculation and users can decide whether to take these factors into account according to their demands.<br>
<br><b>Performance improvement</b>
<br>Due to the memory limits of java virtual machine, <b>memory overflow</b> may easily occur when Cytoscape plugins execute calculation for large-scale networks. We have already <b>fixed this problem</b> in the latest version 2.1. As far as we know, CytoNCA is the only Cytoscape plugin that calculates these three centralities on large scale networks (over 15000 nodes) without memory overflow error. And we <b>improved the operation efficiency</b>, reduced the computation time and memory usage.<br>
<br>
<h3><b>1. Introduction</b></h3>
<blockquote>Based on the open-source platform Cytoscape, a convenient app called CytoNCA for network centrality analysis has been designed and achieved.This app support eight typical centralities called Betweeness Centrality (BC) <sup>1</sup>, Closeness Centrality (CC) <sup>2</sup>, Degree Centrality (DC) <sup>3</sup>, Eigenvector Centrality (EC) <sup>4</sup>, Local Average Connectivity-based method (LAC) <sup>5</sup>, Network Centrality (NC) <sup>6</sup>, Subgraph Centrality (SC) <sup>7</sup>, Information Centrality (IC) <sup>8</sup> for undirected network, supporting weighted as well as unweighted calculation of multiple centralities.<br>
<p>For version 2.0, we added the option of uploading the bio-information for both edges and nodes, which made it possible to identify the proteins with significant biological as well as topological indexes simultaneously. </p>
<p>In addition to the basic analysis, CytoNCA achieves extensive visualizing capabilities, providing various forms of comprehensive analysis such as graph, table, chart and the like, individually and globally as well as longitudinally and cross-wisely.</p>
<p>CytoNCA provides evaluating performance of the centrality measures in ten statistical measures, including True Positives (TP), False Positives (FP), True Negatives (TN), False Negatives (FN), Sensitivity (SN), Specificity (SP), Positive Predictive Value (PPV), Negative Predictive Value (NPV), F-measure (F) and Accuracy (ACC).  </p>
<p>Combining the bio-information upload module with analysis or evaluation function, CytoNCA is able to analyze and assess experimental parameters or even centrality measure derived from other sources, which makes this application unlimited by eight built-in centralities, to be not only a centralities calculation tool but also a formidable instrument for visual analysis and evaluation, processing various data agilely.</p>
<p>This app is developed by Yu Tang, supported and directed by Dr. Jianxin Wang and Dr. Min Li, from Central South University.</p>
<h3><b>2. Quick Start</b></h3>
Following is a short quick start for the usage of CytoNCA, detailed information of the algorithms implemented in this plug-in can be found in related papers.<br>
</blockquote><ol><li>Download and install Cytoscape3.0(<a href='http://www.cytoscape.org/'>http://www.cytoscape.org/</a>).<br>
</li><li>Download the Jar version of CytoNCA(<a href='https://drive.google.com/file/d/0B13gZNlVofBmaWtkaERmNzRWZGs/edit?usp=sharing'>CytoNCA-2.1.jar</a> ).<br>
</li><li>Start Cytoscape, install the !CytoNCA.jar through App Manager(<b>Apps → App Manager → Install from file..</b>)<br>
</li><li>Import or open a network.<br>
</li><li>Click <b>App → CytoNCA → Start</b>.<br>
</li><li>It will switch to CytoNCA tab on left panel, choose one or multiple centralities as you want.<br>
</li><li>Click <b>upload essential protein list</b> button to upload the essential protein list of the current protein network. (optional).<br>
</li><li>Click <b>Analysis</b> button.<br>
</li><li>After analysis is done, results will be shown on the right panel. If you upload the essential protein list of current protein network, evaluation panel will be shown in the button.</li></ol>

<h3><b>3. Contact Information</b></h3>
If you any problems or suggestions of CytoCluster, please contact us at Email: <b>tangyu333@gmail.com</b>, <b>jxwang@mail.csu.edu.cn</b>, <b>limin@mail.csu.edu.cn</b>.<br>
<br>
<h3><b>4. References</b></h3>

<ol><li>Joy M P, Brock A, Ingber D E, et al. High-betweenness proteins in the yeast protein interaction network<a href='J.md'>J</a>. BioMed Research International, 2005, 2005(2): 96-103.<br>
</li><li>Wuchty S, Stadler P F. Centers of complex networks<a href='J.md'>J</a>. Journal of Theoretical Biology, 2003, 223(1): 45-53.<br>
</li><li>Jeong H, Mason S P, Barabási A L, et al. Lethality and centrality in protein networks<a href='J.md'>J</a>. Nature, 2001, 411(6833): 41-42.<br>
</li><li>Bonacich P. Power and centrality: A family of measures<a href='J.md'>J</a>. American journal of sociology, 1987: 1170-1182.<br>
</li><li>Li M, Wang J, Chen X, et al. A local average connectivity-based method for identifying essential proteins from the network level<a href='J.md'>J</a>. Computational biology and chemistry, 2011, 35(3): 143-150.<br>
</li><li>Wang J, Li M, Wang H, et al. Identification of essential proteins based on edge clustering coefficient<a href='J.md'>J</a>. IEEE/ACM Transactions on Computational Biology and Bioinformatics, 2012, 9(4): 1070-1080.<br>
</li><li>Estrada E, Rodríguez-Velázquez J A. Subgraph centrality in complex networks<a href='J.md'>J</a>. Physical Review E, 2005, 71(5): 056103.<br>
</li><li>Stephenson K, Zelen M. Rethinking centrality: Methods and examples<a href='J.md'>J</a>. Social Networks, 1989, 11(1): 1-37.