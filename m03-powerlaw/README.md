# Assignment 

## Zipf's law

Let's check Zipf's law. Download some big English corpora. It can be Wikipedia, some books from the Project Gutenberg, etc. 

1. Count the frequency of each word. 

2. Try several plots: rank-frequency plot (Zipf's law), cumulative plot (CCDF), and PDF. What's the relationship between rank-frequency plot and the cumulative plot?

3. Measure the power-law exponent of your corpus using the MLE method suggested by Clauset, Shalizi, and Newman. You can find multiple versions of code online. Does your corpus follow a power-law? How about the Zipf's law? (see this paper: [Zipf's law holds for phrases, not words](http://arxiv.org/abs/1406.5181))

## Benford's law

Find a large set of interestnig numbers and test the Benford's law. 


## Notes 

1. If you identify another interesting and worthy problem, go ahead and let me know. 
2. Debate with your colleagues vigorously. If you discuss, acknolwedge discussions in the paper. Team up if you would like to. 
3. Feel free to stop by or email me if you have any troubles. 

As in the previous assignments, create a document that reviews the literature, answers the key questions (many questions are open ones without any clear solution), provide rationales and details of your model. 

# Main questions for the review

- Why is a power-law distribution called "scale-free"?
- What's the relationship between Zipf's law, Pareto's law, and power-law?
- What are the mechanisms of generating a power-law? 
- What mechanisms can generate Zipf's law of human language?
- Why is power-law so common in nature?
- Why is MLE better than linear regression in log-log scale? 
- Can we identify the correct mechanism that generate observed power-law? How?

# Starting points 

## Key papers

- M.E.J. Newman, [Power laws, Pareto distributions and Zipf's law](http://arxiv.org/abs/cond-mat/0412004), Contemporary Physics 46, 323 (2005).
- A. Clauset et al., [Power-law distributions in empirical data](http://arxiv.org/abs/0706.1062), SIAM Review 51, 661 (2009).
- M. Mitzenmacher, [A brief history of generative models for power law and lognormal distributions](http://www.eecs.harvard.edu/~michaelm/postscripts/im2004a.pdf)
- L.A. Adamic, [Zipf, Power-laws, and Pareto - a ranking tutorial](http://www.hpl.hp.com/research/idl/papers/ranking/ranking.html)
- C.R. Shalizi, [Power Law Distributions, 1/f Noise, Long-Memory Time Series](http://vserver1.cscs.lsa.umich.edu/~crshalizi/notebooks/power-laws.html), Notebooks 

## Others

### Fun

- M.V. Simkin and V.P. Roychowdhury, [Re-inventing Willis](http://arxiv.org/abs/physics/0601192), Physics Reports 502, 1 (2011).
- [RadioLab: Numbers](http://www.radiolab.org/2009/nov/30/)

### Zipf's law and Heap's law

- G. K. Zipf, [The Psycho-Biology of Language](http://mitpress.mit.edu/books/psycho-biology-language). 
    - G. K. Zipf, [Human Behaviour and the Principle of Least-Effort](http://www.amazon.com/Human-Behavior-Principle-Least-Effort/dp/161427312X). 
    - B. B. Mandelbrot, in Communication Theory, edited by W. Jackson (Butterworth, Woburn, MA, 1953) pp. 486–502.
    - H. A. Simon, [On a class of skew distribution function](http://www.jstor.org/stable/2333389?seq=1#page_scan_tab_contents), Biometrika 42, 425 (1955).
    - G. A. Miller, [Some effects of intermittent silence](http://www.jstor.org/stable/1419346?seq=1#page_scan_tab_contents), American Journal of Psychology 70, 311 (1957).
    - R. Ferrer-i Cancho and B. Elvevåg, [Random Texts Do Not Exhibit the Real Zipf's Law-Like Rank Distribution](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0009411), PLoS ONE 5, e9411 (2010).
    - R. M. D’Souza, C. Borgs, J. T. Chayes, N. Berger, and R. D. Kleinberg, [Emergence of tempered preferential attachment from optimization](http://www.pnas.org/content/104/15/6112.short) Proc. Natl. Acad. Sci. 104, 6112 (2007). 
    - B. Coromina-Murtra and R. Solé, [Universality of Zipf's law](http://journals.aps.org/pre/abstract/10.1103/PhysRevE.82.011102), Phsyical Revew E 82, 011102 (2010).
    - Jake Ryland Williams, Paul R. Lessard, Suma Desu, Eric Clark, James P. Bagrow, Christopher M. Danforth, Peter Sheridan Dodds, [Zipf's law holds for phrases, not words](http://arxiv.org/abs/1406.5181), arXiv

- Seung Ki Baek, Sebastian Bernhardsson, Petter Minnhagen, [Zipf's law unzipped](http://arxiv.org/abs/1104.1789), New J. Phys. 4, 043004 (2011). 
    - Sebastian Bernhardsson, Seung Ki Baek, Petter Minnhagen, [A Paradoxical Property of the Monkey Book](http://arxiv.org/abs/1103.2681), J. Stat. Mech. (2011) P07013. 
    - Sebastian Bernhardsson, Luis Enrique Correa da Rocha, Petter Minnhagen, [The meta book and size-dependent properties of written language](http://arxiv.org/abs/0909.4385), New J. Phys. 11 (2009) 123015. 
    - Sebastian Bernhardsson, Luis Enrique Correa da Rocha, Petter Minnhagen, [Size dependent word frequencies and translational invariance of books](http://arxiv.org/abs/0906.0716), Physica A 389:2, pp. 330-341 (2010). 

- Leo Egghe, [Untangling Herdan's law and Heaps' law: Mathematical and informetric arguments](http://onlinelibrary.wiley.com/doi/10.1002/asi.20524/abstract), Journal of the American Society for Information Science and Technology 58 (5): 702 (2007). 

### Benford's law 

- http://en.wikipedia.org/wiki/Benford's_law
- http://testingbenfordslaw.com
- [Vi and Sal talk about the mysteries of Benford's law](https://www.khanacademy.org/math/algebra2/logarithms-tutorial/logarithmic-scale-patterns/v/vi-and-sal-talk-about-the-mysteries-of-benford-s-law)
    - [Benford's law explanation (sequel to mysteries of Benford's law)](https://www.khanacademy.org/math/algebra2/logarithms-tutorial/logarithmic-scale-patterns/v/benford-s-law-explanation-sequel-to-mysteries-of-benford-s-law)

### Critical perspectives

- M.P.H. Stumpf and M. Porter, [Critical Truths About Power Laws](http://www.sciencemag.org/content/335/6069/665), Science 335, 665 (2012). 
- M. Stumpf, Are power laws useful? - http://www.slideshare.net/theosysbio/powerlaws

### Common distributions in nature

- S.A. Frank, [The common patterns of nature](http://onlinelibrary.wiley.com/doi/10.1111/j.1420-9101.2009.01775.x/full), Journal of Evolutionary Biology 22, 1563 (2009).

### 1/f noise and music

- R.F. Voss and J. Clarke, [‘1/fnoise’ in music and speech](http://www.nature.com/nature/journal/v258/n5533/abs/258317a0.html), Nature 258, 317 (1975).
    - R.F. Voss, [Evolution of long-range fractal correlations and 1/f noise in DNA base sequences](http://prl.aps.org/abstract/PRL/v68/i25/p3805_1), PRL 68, 3805 (1992).
    - D.J. Levitin et al., [Musical rhythm spectra from Bach to Joplin obey a 1/f power law](http://www.pnas.org/content/109/10/3716.abstract), PNAS 109, 3716 (2012).
    - M. Gardner, [White and brown music, fractal curves and one-over-f fluctuations](http://www.informatics.indiana.edu/donbyrd/teach/PapersEtcByOthers/SciAmMathGames77_FractalMusic.pdf), Sci. Am. (1978)
    - K.J. Hsü and A.J. Hsü, [Fractal geometry of music](http://www.pnas.org/content/87/3/938.short), PNAS 87, 938 (1990).
    - K.J. Hsü and A. Hsü, [Self-similarity of the "1/f noise" called music](http://www.pnas.org/content/88/8/3507.short), PNAS 88, 3507 (1991).
    - M. Schroeder, [Is there such a thing as fractal music?](http://www.nature.com/nature/journal/v325/n6107/abs/325765c0.html), Nature 325, 765 (2002).
    - [Scholarpedia: 1/f noise](http://www.scholarpedia.org/article/1/f_noise)
    - [Wikipedia: Colors of noise](http://en.wikipedia.org/wiki/Color_of_noise)

### Fractal

- http://en.wikipedia.org/wiki/Box-counting_dimension
- http://en.wikipedia.org/wiki/Hausdorff–Besicovitch_dimension
- http://en.wikipedia.org/wiki/Mandelbrot_set
- B. Mandelbrot, [How Long Is the Coast of Britain? Statistical Self-Similarity and Fractional Dimension](http://www.jstor.org/sici?sici=0036-8075%2819670505%293%3A156%3A3775%3C636%3AHLITCO%3E2.0.CO%3B2-N), Science 156, 636 (1967).
    - D. Avnir et al., [Is the geometry of nature fractal?](http://www.sciencemag.org/content/279/5347/39.full), Science 279, 39 (1998).
- R.P. Taylor et al., [Fractal analysis of Pollock's drip paintings, Nature 399, 422 (1999); K. Jones-Smith and H. Mathur, Fractal Analysis: Revisiting Pollock's drip paintings](http://www.nature.com/nature/journal/v399/n6735/abs/399422a0.html), Nature 444, E9 (2006).
    - K. Jones-Smith et al., [Drip paintings and fractal analysis](http://journals.aps.org/pre/abstract/10.1103/PhysRevE.79.046111), PRE 79, 046111 (2009).
- J. Leskovec et al., [Realistic, Mathematically Tractable Graph Generation and Evolution, Using Kronecker Multiplication](http://www.cs.cmu.edu/~jure/pubs/kronecker-pkdd05.pdf), PKDD'05
    - J. Leskovec and C. Faloutsos, [Scalable modeling of real graphs using Kronecker multiplication](http://dl.acm.org/citation.cfm?id=1273559), ICML'07
    - J. Leskovec et al., [Kronecker Graphs: An Approach to Modeling Networks](http://dl.acm.org/citation.cfm?id=1756039), The Journal of Machine Learning Research 11, 985 (2010).
- G. Palla et al., [Multifractal network generator](http://www.pnas.org/content/107/17/7640.short), PNAS 107, 7640 (2009).
    - G. Palla et al., [Rotated multifractal network generator](http://iopscience.iop.org/1742-5468/2011/02/P02003), J. Stat. Mech. 2011, P02003
- C. Song et al., [Self-similarity of complex networks](http://www.nature.com/nature/journal/v433/n7024/abs/nature03248.html), Nature 433, 392 (2004).
    - C. Song et al., [Origins of fractality in the growth of complex networks](http://www.nature.com/nphys/journal/v2/n4/abs/nphys266.html), Nature Physics 2, 275 (2006).
    - K.-I. Goh et al., [Skeleton and Fractal Scaling in Complex Networks](http://prl.aps.org/abstract/PRL/v96/i1/e018701), PRL 96, 018701 (2006).
    - H.D. Rozenfeld et al., [Small world-Fractal Transition in Complex Networks: Renormalization Group Approach](http://arxiv.org/abs/0909.4832), PRL 104, 025701 (2010).
- L.K. Gallos et al., [A small world of weak ties provides optimal global integration of self-similar modules in functional brain networks](http://www.pnas.org/content/109/8/2825.short), PNAS 109, 2825 (2012).
- D.S. Bassett et al., [Efficient Physical Embedding of Topologically Complex Information Processing Networks in Brains and Computer Circuits](http://www.ploscompbiol.org/article/info%3Adoi%2F10.1371%2Fjournal.pcbi.1000748), PLOS Comp. Biol. 6, e1000748 (2010).
- [TED: Benoit Mandelbrot: Fractals and the art of roughness](http://www.ted.com/talks/benoit_mandelbrot_fractals_the_art_of_roughness.html)
- [TED: Ron Eglash: The fractals at the heart of African designs](http://www.ted.com/talks/ron_eglash_on_african_fractals.html)
- [African Fractals](http://homepages.rpi.edu/~eglash/eglash.dir/afractal/afractal.htm) by Ron Eglash
- http://en.wikipedia.org/wiki/List_of_fractals_by_Hausdorff_dimension

### Self-organized criticality 

- P. Bak et al., [Self-organized criticality: an explanation of the 1/f noise](http://prl.aps.org/abstract/PRL/v59/i4/p381_1), PRL 59, 381 (1987).
    - P. Bak and K. Sneppen, [Punctuated equilibrium and criticality in a simple model of evolution](http://prl.aps.org/abstract/PRL/v71/i24/p4083_1), PRL 71, 4083 (1993).
- D.L. Turcotte, [Self-organized criticality](http://iopscience.iop.org/0034-4885/62/10/201), Reports on Progress in Physics 62, 1377 (1999).
- J.M. Beggs and D. Plenz, [Neuronal Avalanches in Neocortical Circuits](http://www.jneurosci.org/content/23/35/11167.short), J. Neurosci 23, 11167 (2003).
- I. Shmulevich et al., [Eukaryotic cells are dynamically ordered or critical but not chaotic](http://www.pnas.org/content/102/38/13439.short), PNAS 102, 13439 (2005).
- M. Nykter et al., [Gene expression dynamics in the macrophage exhibit criticality](http://www.pnas.org/content/105/6/1897.short), PNAS 105, 1897 (2008).
- E. Romanelli and M.L. Tushman, [Organizational transformation as punctuated equilibrium: an empirical test](http://amj.aom.org/content/37/5/1141.short), Acad. Manage. J. 37, 1141 (1994).
- J. Pu et al., [Developing neuronal networks: Self-organized criticality predicts the future](http://www.nature.com/srep/2013/130117/srep01081/full/srep01081.html), Sci. Rep. 3, 1081 (2013).
- [The Bak-Sneppen model](http://cmol.nbi.dk/models/bs/bs.html)
