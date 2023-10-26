# phd_thesis

This is my PhD thesis was written in 2019-2021 and defended in 2022. 

The thesis focuses on binary __neutron star mergers__ (BNS), and 
specifically on the analysis of the BNS merger simulations performed 
with numerical relativity, i.e.,g general relativistic hydrodynamic 
code [WhiskiTHC](https://personal.science.psu.edu/dur566/whiskythc.html) 
written and maintained by [Prof. David Radice](https://personal.science.psu.edu/dur566/index.html) 
who co-supervised my thesis. 

---

In this thesis, I developed a __big data processing and analysis pipeline__ 
for the simulation data. The pipeline is located at this [repository](https://github.com/vsevolodnedora/bns_ppr_tools). 
The code is written in Python 3, employing __agile philosophy__, __lazy evaluation__ 
and __object-orientated infrastructure__. 

The code can be easily generalized to 
process simulations generated with other numerical relativity simulations, as 
was done for the [BAM](https://arxiv.org/abs/1807.06959) code. The implementation 
can be found in this [repository](https://github.com/vsevolodnedora/bam_m1_ppr). 

#### The pipeline has been used in numerous scientific publications to extract valuable, publication-ready information and plots from simulations

Besides the hydrodynamics and early evolution of the BNS merger and postmerger, 
the thesis focuses on the _electromagnetic counterparts_ to BNS mergers. 

Specifically, __kilonova__ is discussed and modeled using semi-analytic multicomponent 
code [MKN](https://github.com/albinoperego/macrokilonova_bayes) developed by 
[Prof. Albino Perego](http://www.albinoperego.eu/) who also co-supervised my PhD thesis. 

One of the findings of my 
research is that a newly discovered outflow from the postmerger remnant can be 
the source of _blue emission_ seen in GRB170817A/KN2017gfo, the famous multimessenger event 
observed in 2017. 

---

Finally, in this thesis, I developed a code to model _non-thermal emission_ from matter 
ejected at BNS mergers that move through the interstellar medium and shock it (so-called collisionless shocks). 
This is generally called an _afterglow_. For a gamma-ray burst, it is a _gamma-ray burst afterglow_ 
and for a kilonova, it would be a _kilonova afterglow_. 

The code, named __PyBlastAfterglow__ 
can be found in this [repository](https://github.com/vsevolodnedora/PyBlastAfterglow). It 
is written in Python 3 and has an __object-orientated infrastructure__. It is _malty-physics_, 
meaning that I implemented several physics modules that perform the same task but have different 
levels of approximation and numerical complexity. The code includes a set of _unit-tests_ and code-level tests. 

The discovery that I made applying this code to the ejecta from the BNS merger simulations I 
was working with is that the late-time emission GRB170817A event _can be explained self-consistently_ 
and, furthermore, additional new information about this event can be learned. This was 
published in a highly regarded [APJL journal](https://iopscience.iop.org/article/10.3847/2041-8213/ac504a) 
and was considered for publication in Nature. This project and this code were the foundation of my 
future research done at Max Plank Institute which can be found on my [page](https://vsevolodnedora.github.io/).
