# numerical-computing-project-3--spectral-graph-clustering-solved
**TO GET THIS SOLUTION VISIT:** [Numerical Computing Project 3- Spectral Graph Clustering Solved](https://www.ankitcodinghub.com/product/numerical-computing-spectral-graph-clustering-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121279&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Numerical Computing Project 3- Spectral Graph Clustering Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Clustering is a technique used for exploratory data analysis in an increasing number of fields, ranging from computer science and biology to statistics and social sciences. The main motivation behind the use of clustering is the need to extract information from a set of data, by grouping elements that are similar one to another according to a metric of choice. This technique aims, in fact, to put together elements which display similar behaviours (e.g., costumers purchasing the same set of goods if we think about an application in economics), while separating them from the others.

In this project, you will be introduced to the family of spectral clustering algorithms, which present significant advantages over the traditional clustering algorithms (e.g., k-means or single linkage). The implementation of spectral clustering is very straightforward and the results obtained usually outperform those obtained with the traditional techniques. For further details see e.g., [2]). The purpose of this project is to give you a gentle introduction to spectral clustering through the implementation of a spectral graph clustering algorithm in Matlab. In order to validate your results, you will then have to test it against a variety of 2D graphs.

1. Spectral clustering of non-convex sets [50 points]:

Download the clustering toolbox clustering.tgz from the iCorsi webpage. This toolbox contains Matlab code for spectral and k-means clustering, as well as various additional routines necessary for these 2 methods. In the directory datasets you will find a variety of pointclouds and 2D graphs, that will serve as test cases for this assignment. Your first task consists in modifying the Matlab script ClusterPoints.m, by completing the following tasks:

1. Run the Matlab function datasets/getPoints(). A graphical output of 6 different non-convex sets will be produced. Use this function to output the coordinate list of the different cloudpoints and replace the variable Pts dummy with the set you wish to cluster. Consider the set named half-kernel: can you identify the two obvious clusters in this dataset? Describe them briefly and explain what difficulties a clustering algorithm could eventually encounter in a scenario of this kind.

2. Use the function minSpanTree() to find the minimal spanning tree of the full graph. Use this information to determine the factor for the -similarity graph.

3. Complete the Matlab function epsilonSimGraph(). It should generate the similarity matrix of the similarity graph.

4. Create the adjacency matrix for the similarity graph and visualize the resulting graph using the function gplotg().

5. Create the Laplacian matrix and implement spectral clustering. Your goal is to find the eigenvectors of the Laplacian corresponding to the K = 2 smallest eigenvalues. Afterwards, use the function kmeansmod() to cluster the rows of these eigenvectors.

6. Use the kmeansmod() function to perform k-means clustering on the input points. Visualize the two clustering results using the function gplotmap(). You can debug your implementation by using as a reference the results reported in Figure 1, which are relative to the half-kernel dataset.

Figure 1: Clustering results for the half-kernel dataset.

7. Cluster the datasets i) Two spirals, ii) Cluster in cluster, and iii) Crescent &amp; full moon in K = 2 clusters, and visualize the results obtained with spectral clustering and k-means directly on the input data. Do the same for i) Corners, and ii) Outlier for K = 4 clusters.

HINT: The parameters σ, for the Gaussian similarity function

, (1)

and , that controls the size of the neighborhood in the similarity graph have to be chosen according to the position of the points of each dataset in the 2D space, and the distances between them. Include the values that you selected in your report.

2. Spectral clustering of real-world graphs [35 points]:

We will now cluster 2D graphs emerging from structural engineering matrices of NASA, available in the SuiteSparse Matrix Collection (SSMC) [1]. Use/modify your already developed Matlab functions and routines, and add the following points to the script ClusterGraphs.m:

1. Construct the Laplacian matrix, and draw the graphs using the eigenvectors to supply coordinates. Locate vertex i at position:

(xi,yi) = (v2(i),v3(i)),

where v2,v3 are the eigenvectors associated with the 2nd and 3rd smallest eigenvalues. Figure 2 illustrates these 2 ways of visualizing the airfoil1 graph. Plot your results for all the three additionally supplied meshes, grid2, barth, 3elt.

Figure 2: Visualization of the airfoil1 graph.

2. Cluster each graph in K = 4 clusters with the spectral and the k-means method. Plot all of your results and describe the differences that you can see in the output of the 2 different algorithms and where they might come from. The clusters obtained by the 2 techniques in the case of the airfoil1 graph are presented in Figure 3.

Figure 3: The airfoil1 clusters (left: spectal clusters, right: k-means clusters).

3. Report in Table 1 the number of nodes per cluster and plot a histogram of the reported values in a way similar to Figure 4. What can you observe?

Table 1: Clustering results, K = 4

Case Spectral K-Means

grid2 barth 3elt

Figure 4: Histograms representing the number of nodes per cluster for the airfoil1 graph.

Quality of the code and of the report [15 Points]

The highest possible score of each project is 85 points and up to 15 additional points can be awarded based on the quality of your report and code (maximum possible grade: 100 points). Your report should be a coherent document, structured according to the template provided on iCorsi. If there are theoretical questions, provide a complete and detailed answer. All figures must have a caption and must be of sufficient quality (include them either as .eps or .pdf). If you made a particular choice in your implementation that might be out of the ordinary, clearly explain it in the report. The code you submit must be self-contained and executable, and must include the set-up for all the results that you obtained and listed in your report. It has to be readable and, if particularly complicated, well-commented.

Additional notes and submission details

In-class assistance

If you experience difficulties in solving the problems above, please join us in class either on Tuesdays 15:30-17:00 or on Wednesdays 13:30-15:00 in room C1.03.

References
