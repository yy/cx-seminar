# Assignment 

The objective of this assignment is understanding mechanisms of homophily and segregation. Create your own model of polarization in networks (e.g. Twitter or political blogs) starting from Schelling or Axelrod model. Introspect your behaviors in terms of politics or other sensitive topics and think of systematic mechanisms that capture the dynamics.  [NetworkX](https://networkx.github.io) + [IPython Notebook](http://ipython.org/notebook.html) are probably the best option for you. You can easily visualize networks that you are playing with. 

1. If you identify another interesting and worthy problem, go ahead, do it, and let me know. 
2. Debate with your colleagues vigorously. Acknolwedge discussions in the paper. Team up if you would like to. 
3. Feel free to stop by or email me if you have any troubles. 

As in the first assignment, create a document that reviews the literature, answers the key questions (many questions are open ones without any clear solution), provide rationales and details of your model. 

# Main questions for the review

- Play with the NetLogo *Segregation* implementation. What happens if the tolerance is too high or too low? How does the density affect the results?
- Is segregation a result of homophily? Is homophily a result of segregation/avoidance? How are they related and how can we distinguish different scenarios?
- How can noise affect the results?
- Do you think the segregation and polarization of our society are getting worse? Why? or why not? What are the main factors that contribute to the trend? What do you think are the mechanisms?

# Starting points 

## Observations

- Explore this amazing map: [Racial dot map](http://www.coopercenter.org/demographics/Racial-Dot-Map)
- Polarization in the congress
  - http://www.economist.com/news/united-states/21591190-united-states-amoeba
  - http://www.washingtonpost.com/blogs/the-fix/wp/2013/06/05/it-wasnt-always-this-bad-the-growth-of-political-polarization-in-1-chart/
- Twitter 
  - http://truthy.indiana.edu
  - http://www.wsj.com/news/interactive/TwitterVerse1001
- Political blogs
  - http://dl.acm.org/citation.cfm?id=1134277 
- Pop vs. Soda
  - http://www.popvssoda.com/
  - http://blog.echen.me/2012/07/06/soda-vs-pop-with-twitter/

## Key papers

- T. Schelling, Dynamic models of segregation, The Journal of Mathematical Sociology 1, 143 (1971). - http://www.tandfonline.com/doi/abs/10.1080/0022250X.1971.9989794
- R. Axelrod, The dissemination of culture: a model with local convergence and global polarization, The Journal of Conflict Resolution 41, 203 (1997). - http://jcr.sagepub.com/content/41/2/203.short

## Others

- CR Shalizi, The Schelling Model, Notebooks - http://bactra.org/notebooks/schelling-model.html
- D. Stauffer and S. Solomon, Ising, Schelling and Self-Organising Segregation, EPJB 57, 473 (2007).

### Testing the idea with real data

- W.A.V. Clark, Residential Preferences and Neighborhood Racial Segregation: A Test of the Schelling Segregation Model, Demography 28, 1 (1991).
- W.A.V. Clark and M. Fossett, Understanding the social context of the Schelling segregation model, PNAS 105, 4109 (2008).
- Y. Xie and X. Zhou, Modeling individual-level heterogeneity in racial residential segregation, PNAS 109, 11646 (2012).

### Can it explain conflicts?

- M. Lim et al., Global Pattern Formation and Ethnic/Cultural Violence, Science 317, 1540 (2007).

### You can find physical analogue of Schelling model

- D. Vinkovic and A. Kirman, A physical analogue of the Schelling model, PNAS 103, 19261 (2006).

### People have throught about networks

- L.C. Freeman, Segregation in social networks, Sociological Methods & Research 6, 411 (1978).
- G. Fagiolo et al., Segregation in networks, Journal of Economic Behavior & Organization 64, 316 (2007).
- A.D. Henry et al., Emergence of segregation in evolving social networks, PNAS 108, 8605 (2011).

### A related problem: how groups emerge? why many socio-, techno-, and biological systems are modular?

- J.M. Kumpula et al., Emergence of Communities in Weighted Networks, PRL 99, 228701 (2007).
- X. Sun et al., Social Dynamics of Science, Scientific Reports 3, 1069 (2013).
- M. Marsili et al., The rise and fall of a networked society: A formal model, PNAS 101, 1439 (2004).
- N. Kashtan and U. Alon, Spontaneous evolution of modularity and network motifs, PNAS 102, 13773 (2005).
- J. Sun and M.W. Deem, Spontaneous Emergence of Modularity in a Model of Evolving Individuals, PRL 99, 228107 (2007). 
- G.P. Wagner et al., The road to modularity, Nature Reviews Genetics 8, 921 (2007).
- A. Kreimer et al., The evolution of modularity in bacterial metabolic networks, PNAS 105, 6976 (2008).
- D.M. Lorenz et al., The Emergence of Modularity in Biological Systems, Physics of Life Reviews 8, 129 (2011).
- Clune, Jeff, Jean-Baptiste Mouret, and Hod Lipson. "The evolutionary origins of modularity." Proceedings of the Royal Society b: Biological sciences 280.1755 (2013): 20122863.

### This topic is also linked to the heated debate about homophily and influence

- http://yyahnwiki.appspot.com/Homophily_and_influence
- N.A. Christakis and J.H. Fowler, The Spread of Obesity in a Large Social Network over 32 Years, NEJM 357, 370 (2007).
- C.R. Shalizi and A.C. Thomas, Homophily and Contagion Are Generically Confounded in Observational Social Network Studies, Sociological Methods and Research 40, 211 (2011).

