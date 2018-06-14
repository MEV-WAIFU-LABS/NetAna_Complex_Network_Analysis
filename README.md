# 🌺 NetAna - Complex Network Analysis Package 🌺


Extraction and analysis of several graph features from publicly available datasets using NetworkX.

[Results, sources, draft of the paper, etc.](http://mariwahl.us/html_files/mloutputs.html)


### Analyzed Features:


1* Assortativity

2* Clique number

3* Clustering

4* Density

5* Diameter

6* Edge connectivity

7* Node connectivity

8* Number of cliques

9* Number of edges

10* Number of nodes

11* Radius

12* Clustering and Transitivity

13* Betweeness centrality

14* Closeness centrality

15* Communicability centrality

16* Coreness

17* Degree centrality

18* Eccentricity

19* Number of triangles

20* Pagerank

21* Square clustering

22* Transitivity



### Networks:


1* Social networks: online social networks, edges represent interactions between people

2* Ground truth: ground-truth network communities in social and information networks

3* Communication: email communication networks with edges representing communication

4* Citation: nodes represent papers, edges represent citations

5* Collaboration: nodes represent scientists, edges represent collaborations (co-authoring a paper)

6* Web graphs: nodes represent webpages and edges are hyperlinks

7* Products: nodes represent products and edges link commonly co-purchased products

8* p2p: nodes represent computers and edges communication

9* Roads: nodes represent intersections and edges roads connecting the intersections

10* Autonomous systems: graphs of the Internet

11* Signed networks: networks with positive and negative edges (friend/foe, trust/distrust)

12* Location based networks: Social networks with geographic check-ins

13* Wikipedia: Talk, editing and voting data from Wikipedia

14* Bio Atlas: Food-webs  selected from Ecosystem Network Analysis site and from ATLSS.

15* Bio Cellular: Substrate in cellular network of corresponding organism.

16* Bio Metabolic: Metabolic network of corresponding organism.

17* Bio Carbon: Carbon exchanges in the cypress wetlands of South Florida during the wet and dry season.

18* Bio Yeast: Protein-protein interaction network in budding yeast.



### Normalization and Graph sampling:

Performed using snowball sampling (choosing the sample order, i.e. number of nodes). Optimized for number of edges and multiple samplings.


### Next Steps


* [Cleanse the data here.](https://github.com/mariwahl/NetClean-Complex-Networks-Data-Cleanser)

* [Classify the networks with lots of machine learning techniques here.](https://github.com/mariwahl/MLNet-Classifying-Complex-Networks)


### License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
