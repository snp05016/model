*------------------------------------------------------*
*       Crowd Dataset                                  *
*------------------------------------------------------*

written and prepared by:
	Ven Jyn, KOK and Mei Kuan, LIM
	{venjyn.kok, imeikuan} @siswa.um.edu.my


*------------------------------------------------------*
*                       Content                        *
*------------------------------------------------------*
 
 20 image sequences:
 	1)  Sequence1
 	2)  Sequence2
 	3)  Sequence3
 	4)  Sequence4
 	5)  Sequence5 
 	6)  Sequence6
 	7)  Sequence7 (similar to sequence 6, with the addition of noise to simulate instability)
 	8)  Sequence8
 	9)  Sequence9 (similar to sequence 8, with the addition of noise to simulate instability)
 	10) Sequence10
 	11) Sequence11
 	12) Sequence12
 	13) Sequence13
 	14) Sequence14
 	15) Sequence15
 	16) Sequence16
 	17) Sequence17
 	18) Sequence18
 	19) Sequence19
 	20) Sequence20
 	

20 groundtruth files in the \\Dataset\\Dataset Groundtruth\\ directory.
 
Ground truth details:
1) The ground truth files are named according to the respective dataset
   (i.e. Sequence1.txt).
2) The salient regions are defined by bounding box information in the form of either:
   -  Rectangle properties --> 
     (Frame no, Region Identifier,Minimum x-coordinate, Minimum y-coordinate,         
      Maximum x-coordinate, Maximum y-coordinate)
     (i.e. 34	1	75	76	140	130)
   - Polygon properties -->
     (Frame no, Region Identifier, Point 1 x-coordinate, Point 1 y-coordinate,
      Point 2 x-coordinate, Point 2 y-coordinate,
      Point 3 x-coordinate, Point 3 y-coordinate,
      Point 4 x-coordinate, Point 4 y-coordinate)
     (i.e. 1	11	153	182	323	121	342	173	170	232)

*------------------------------------------------------*
*                       CITATION                       *
*------------------------------------------------------*

This release contains dataset for the below publications. 
If you use this data for any published work, please cite the below:

[1] M.K. Lim, V.J. Kok, C.C. Loy, C. S. Chan,
    "Crowd Saliency Detection via Global Similarity Structure", 
    International Conference on Pattern Recognition, August, 2014.

Project page: http://web.fsktm.um.edu.my/~cschan/project4.htm

*------------------------------------------------------*

Please note that these dataset are obtained from a variety of sources, such as
UCF (http://www.cs.ucf.edu/~sali/Projects/CrowdSegmentation/) and 
Data-driven (http://www.mikelrodriguez.com/datasets-and-source-code/) crowd datasets.
These datasets are selected based on their relevancy to the goal of our work,
which is to detect salient region and the ground truth information may differ from one application
to another. 





