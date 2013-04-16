---
title       : The Shape of Neutral & Adaptive Genetic Variance
subtitle    : Testing "How" instead of "If"
author      : Rodney J. Dyer
job         : Department of Biology, Virginia Commonwealth University
framework   : io2012        
highlighter : highlight.js  
hitheme     : tomorrow      
mode        : selfcontained
logo        : Dyerlab.small.png
biglogo     : joke.png
#license     : by-nc-sa
github      : {user: dyerlab, repo: talks }
widgets     : [mathjax]            

--- &twocol .nobackground

## Acknowledgements

The following work has been made possible by the contributions of time and/or funds by the following individuals and groups.  Without their input, I would not be here.

<hr>

*** =left

### People

- Victoria Sork (UCLA), Peter Smouse (Rutgers), John Nason (ISU)
- Ryan Garrick (Ole Miss), Andrew Eckert (VCU)
- Stephen Baker, Dan Carr, Angela Hutto, Crystal Meadows, Stephanie Burgess
- Owen, Janis & Marlo

*** =right

### Organizations

- National Science Foundation (DEB-0543102 & DEB-0640803)
- Virginia HTEF Research Fund (FY2008 & FY2013)
- Virginia Commonwealth University 
  - Rice Center Research Grant (1342)
  - Center for the Study of Biological Complexity






<script type = 'text/javascript'>
$('p:has(img.build)').addClass('build')
</script>


--- &vcenter .nobackground

## Path of the Talk

![route](assets/img/route.png)




<!--- 
#####################################################################
#                     Networks in Biology
#####################################################################
-->

--- &center_title .blue

# Network Models

##  The Topology of Biological Interactions


--- &twocol  .nobackground

*** =left

<center>![darwin](./assets/img/darwin.png)</center>

*** =right

&nbsp;

&nbsp;

&nbsp;

> The affinities of all beings of the same class have sometimes
> been represented by a great tree. I believe this simile 
> largely speaks the truth. 
&nbsp;

<p style="text-align:right">C. Darwin<br/>On the Origin of Species<br/>1872 Edition</p>

*** =pnotes

1859 <i>Origin of Species</i> single illustration (copied from 1837 notebook)


--- &vcenter .nobackground

## Network Structure

![network](./assets/img/airplane_network.png)


---  bg:white

## Spatial Context

&nbsp;
<center>![map](./assets/img/airplane_routes.png)</center>


---  bg:white

## Networks in Ecological Thinking

<center>![map](./assets/img/network_ecology.png)</center>


---  bg:white

## Networks in Evolutionary Thinking

<center>![map](./assets/img/network_popgen.png)</center>

*** =pnotes
Transition into Genetic variance






--- &twocol bg:white

## Shape Interest Redirects Focus

*** =left

### Parameter Estimation

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2.png) 



*** =right

### Topological Analysis

![plot of chunk unnamed-chunk-3](figure/unnamed-chunk-3.png) 



*** =pnotes 

This is where we go from "If" to "How"


<!--- 
#####################################################################
#                     Genetic Networks
#####################################################################
-->

--- &center_title .yellow

# Genetic Networks

##  I do not think it means what you think it means.



--- 

##  Adaptive & Neutral Variance

In general, a genome is comprised of two general kinds of sequences:

> 1. <b>Adaptive Variance:</b> The Part that Actually __Does Something__
    - Protein coding
    - Regulatory & promoter regions
    - xxxRNA
    <p>&nbsp;</p>
> + <b>Neutral Variance:</b> The __Rest__  <font color="#dddddd">(aka brother-in-law)</font>
    - repeaty regions
    - introns
    - spacers and jumpy bits

*** =pnotes

1. Mostly what people think of when discussiong DNA
2. Rule out the non-coding stuff that is right next to the stuff under selection.





--- &twocol

## Geometry of Variance


Mulitlocus genetic variance can be defined in a geometric context for both within and between stratum components.


&nbsp;

<span class="footnote">Dyer & Nason. (2004)  <i>Molecular Ecology</i>, <b>13</b>, 1713-1728.</span>

*** =left

![hypervol](./assets/img/hypervolume.png)

$\sigma^2_W = \sum_{i=1}^K \sigma_{W,i}^2$


*** =right

### Within population genetic variance

- Multivariate 
- Unique coordinate in HD space
- Volume






--- .nobackground &vcenter

![hypervols2](./assets/img/hypervolume2.png)

$\sigma_A^2 = \sum_{i \ne j} \sigma_{A,i \leftrightarrow j}^2$



--- .nobackground bg:black

<center>![baja](./assets/img/baja1.png)</center>




--- &twocol w1:60% w2:40% bg:white

## Pairwise Incompetence

Few useable inferences about underlying demographic model gained from _pair-wise_ approaches.

&nbsp;

<span class="footnote">Dyer (2007) <i>Theoretical Population Biology</i>, <b>71</b>, 71-79<br/> Dyer <i>et al.</i> (2010) <i>Molecular Ecology</i>, <b>19</b>, 3746-3759.</span>

*** =left

![plot of chunk unnamed-chunk-4](figure/unnamed-chunk-4.png) 



*** =right

![plot of chunk unnamed-chunk-5](figure/unnamed-chunk-5.png) 





--- &vcenter

## Conditional Covariance

![condcov](./assets/img/condcov.png)






--- #myslide bg:white

## Shape of Genetic Covariance

<script>
$('#myslide').on('slideenter', function(){
  $(this).find('article')
    .append('<center><iframe src="./assets/scripts/exampleTopology.html"></iframe></center>')
});
$('#myslide').on('slideleave', function(){
  $(this).find('iframe').remove();
});
</script>



*** =pnotes

Reemphasize the importance of focusing on topological shape over a single parameter.


--- #lopho bg:white

## [Shape](https://mapsengine.google.com/map/edit?mid=zbvgio1r3QDo.kkAl-A1evX6A) of Genetic Covariance

<script>
$('#lopho').on('slideenter', function(){
  $(this).find('article')
    .append('<center><iframe src="./assets/scripts/lopho.html"></iframe></center>')
});
$('#lopho').on('slideleave', function(){
  $(this).find('iframe').remove();
});
</script>







<!--- 
#####################################################################
#                     Neutral Example
#####################################################################
-->

--- &center_title .red

# Neutral Genetic Structure

## The part that doesn't do anything



--- &twocol

## Neutral Genetic Structure: What is it?

Neutral genetic strucuture is maintained by processes _other than selection_.  


*** =left 

### Panmitic Gene Flow

![plot of chunk unnamed-chunk-6](figure/unnamed-chunk-6.png) 



*** =right

### Stepping Stone-like Gene Flow

![plot of chunk unnamed-chunk-7](figure/unnamed-chunk-7.png) 




---

## Real-time Gene Flow

&nbsp;

<span class="footnote">Smouse <i>et al.</i> (2001). <i>Evolution</i>, <b>55</b>, 260-271.<br/>Dyer <i>et al.</i> (2004) <i>Heredity</i>, <b>92</b>, 204-211.</span>

![pollen](./assets/img/pollen_gf.png)

*** =pnotes

LIT Genetic structure in network, what about env?


--- &twocol bg:white

## Ecological Resistance

*** =left

### Shortest Path Distance

<center>![sp](./assets/img/shortest_path.png)</center>


*** =right

### Circuit Distance

<center>![circuit](./assets/img/circuit_paths.png)</center>

*** =pnotes

SP: Ecological surface, Not symmetric, may not optimize
RL: All paths, network flow, many routes


--- &twocol bg:white

## <i>Cornus florida</i> L.


*** =left

&nbsp;
- Endemic understory tree
&nbsp;
- Insect pollinated
&nbsp;
- Animal dispersed seeds
&nbsp;
- Early season phenology

*** =right

<center>![dogwood](./assets/img/dogwood.png)</center>


--- bg:white

## Study Site

<center>![site](./assets/img/study_location.png)</center>






---  bg:white

## Pollen Connectivity

<center>![pollen_graphs](./assets/img/pollen_graphs.png)</center>

<span class="footnote">Dyer <i>et al.</i> (2013) <i>Landscape Ecology</i>, <b>27</b>, 239-251</span>

--- bg:white

## Landscape Features Influencing Connectivity

&nbsp;

<span class="footnote">Dyer <i>et al.</i> (2013) <i>Landscape Ecology</i>, <b>27</b>, 239-251</span>

<center>![avoidanceModel](./assets/img/avoidance.png)</center>


--- bg:white

<center>
![neighborhood](./assets/img/neighborhood_area.png)
</center>











<!--- 
#####################################################################
#                     Adaptive Example
#####################################################################
-->



--- &center_title .green

# Adaptive Genetic Structure

## The part most people think of


*** =pnotes
1. Fundamental interest to biologists
  - understand functionality and interaction with ecology



--- .nobrackground 
![outliers](./assets/img/outliers.png)


*** =pnotes
1. Luikart et al. 2003
2. Fst outliers (AFLP & SNP), Heterozygosity (sweeps), Linkage


---   bg:white
![paper](./assets/img/coop.png)



--- &twocol

## Selection & Genetic Covariance

The shape of genetic covariance among human populations defined by the CEPH SNP dataset.


*** =left

### Neutral Variance

![plot of chunk unnamed-chunk-8](figure/unnamed-chunk-8.png) 





*** =right

### LCT (Chr2)

![plot of chunk unnamed-chunk-9](figure/unnamed-chunk-9.png) 





--- &vcenter

## Leveraging A Covariance Approach



![concept](./assets/img/walking_concept.png)


> 1. Topological change to __deviation__ from neutral
> 2. __Not__ all outliers are the same
> 3. __Hypothesis__ typologies

*** =pnotes

1. It is the pattern of covariance that changes not the magnitude of differentiation.
  - potential to reveal additional regions of interest
2. Grouping outliers
3. Scanning based upon external data
4. MUST HAVE EXPECTATIONS FOR WHAT IS ODD








---

Feature     | Trt Means       | P(neu=neg)       | P(neu=pos) 
------------|-----------------|------------------|------------------
Degree      | Pos < Neu < Neg | $0.84$           | __$8.68e^{-13}$__
Node Btwn   | Neu < Neg < Pos | $0.62$           | __$2.09e-4$__
Closeness   | Pos < Neg < Neu | __$1.25e^{-7}$__ | __$5.20e-12$__
cGD         | Neu < Neg < Pos | __$1.45e^{-3}$__ | __$<2.0e-16$__
Edge Btwn   | Neu < Neg < Pos | $0.49$           | __$5.77e-9$__
SlopeDegree | Pos < Neu < Neg | $0.78$           | $0.88$ 
Diameter    | Neu < Neg < Pos | $0.24$           | __$2.06e-9$__


--- &twocol w1:60% w2:40%

## Outliers on Chromosome 2

Simultaneous outliers for all topologically informative parameters.

*** =left

<center>![feature outliers](./assets/img/feature_outliers.png)</center>

*** =right

&nbsp;

### Identified outliers.

- 17 topologies
&nbsp;

- All previously identified [gdoc](https://docs.google.com/document/d/1rBx09khUDTW7dMEpjS1O_p7j44j5mSrrUW8fOTIfPk4/edit?usp=sharing)
&nbsp;

- Not all the same!



--- 

## Putatively Adaptive Buckets: LCT


$H_O$ Among outliers, what topologies are similar?

&nbsp;


<center>![LCT similarity](./assets/img/Similarity0.001percent_LCT.png)</center>


--- bg:white

## Putatively Adaptive Buckets: LCT

&nbsp;


<center>![LCT similarity](./assets/img/adaptive_bucket.png)</center>





--- 

## Ecologically Motivated Hypothesis Matrix

&nbsp;

What elements of genome covary in a way similar to an ecological variable?

&nbsp;

<center>![humanpops](./assets/img/human.maxtmp.png)</center>


--- 

## Ecologically Motivated Hypothesis Matrix


<center>![human.outlier](./assets/img/human.maxtmp.outliers.png)</center>

Distance Congruence between maximum local _Temperature_ and inter-population _genetic covariance_ 


--- #genomeBrowser1079 bg:white

<script>
$('#genomeBrowser1079').on('slideenter', function(){
  $(this).find('article')
    .append('<iframe src="http://tinyurl.com/c7go5d2"></iframe>')
});
$('#genomeBrowser1079').on('slideleave', function(){
  $(this).find('iframe').remove();
});
</script>



*** =pnotes
- _EPB41L5:_ Mammalian cell polarity (PMID: 17920587)
- _PTPN4:_ T Cell development & Function (PMID: 18614237)
- _PCDP1:_ Flagellar biogenesis (PMID: 18039845) sinusitis male infertility hydrocephalus citus inversus







--- &twocol

## Utility of Shape-based Approaches

Focusing on the topology of covariance provides complementary insights.

*** =left 
### Neutral Variance

1. $H_O:If$ &nbsp;&nbsp; $\to$ &nbsp;&nbsp; $H_O:How$.

2. Magnitude of structure less relevant.

3. Spatial congruence.


*** =right
### $\;$ &nbsp; &nbsp; $\;$ &nbsp; &nbsp; Adaptive Variance

1. Reduce Type II Error

2.  Negative selection?

3. Internal clustering

4. External hypothese




--- bg:black .nobackground

<center>![last](./assets/img/last.png)</center>





