---
layout: default
title: Projects
permalink: /projects/
---
# Multiscale modelling of biochemical networks within compartmental models

Integration of rule-based models of biochemical networks with
compartmental models

* Sterratt, D. C.,  Sorokina, O. and Armstrong, J. D. (2014). ‘Integration of rule-based models and compartmental models of neurons’. Presented to the Third International Workshop on Hybrid Systems Biology  Vienna, Austria, July 23-24, 2014 at the International Conference on  Computer-Aided Verification 2014. To be published in the proceedings; now available at <span class="list-identifier"><a title="Abstract" href="http://arxiv.org/abs/1411.4980">arXiv:1411.4980</a>

# Development of the nervous system

## Modelling the development of neural topographic maps

_In collaboration with Professor David Willshaw (Edinburgh) and
Drs Stephen Eglen and Johannes Hjorth (Cambridge)._

<figure>
<img src="{{site.url}}/images/retinotopy2-400.png" />
<figcaption>Schematic diagram of retinotopy.</figcaption>
</figure>

During early development in vertebtrates, topographic maps form
between retinal ganglion cells and their targets, the optic
tectum/superior colliculus and the lateral geniculate
nucleus. Chemical markers, expressed in gradients, and electrical
activity have been shown to influence the growth and pruning of
connections between retinal ganglion cells and target cells. Chemical
markers, such as Ephs and ephrins, are expressed in the membranes of
retinal ganglion cell axons at levels that depend on the location of
the cell body in the retina. Complementary gradients of Ephs and
ephrins are expressed in gradients throughout the target region, and
repulsive interactions between Ephs and ephrins are thought to inhibit
axonal branching in particular regions of the target region, leading
to a diffuse topographic map. Electrical activity combined with
synaptic plasticity is thought to refine this mapping. 

An important issue is how to quantify and analyse of topographic
maps. In Willshaw, Sterratt and Teriakidis (2014), we have devised a
new computational method entitled the "lattice method" to analyse
experimental data. Our method reveals that there is hidden order in
some maps that were previously thought to be disordered.

There are a number of existing computational models of the
establishment of the mapping between the retina and its targets, which
have shown how both marker-based and activity-based mechanisms can set
up topographic maps. In the years since these models were devised a
great deal of experimental evidence has accumulated and it is
important to assess whether existing models can account for new
experimental data as we do in our review (Hjorth et al., 2015). The
key challenge is to integrate as many of the biological constraints as
possible into models that can still explain the large-scale
topographic organisation of the connections. 

Sterratt (2013) uses an existing model to examine how crucial it is
for countergradients of ephrins in the retina and Ephs in the superior
colliculus to be tuned to each other, in the presence and absense of a
compensatory mechanism. Sterratt and Hjorth (2013) provide a critical
commentary on a Grimbert and Cang's (2012) model of the development of
retinotopy.

* Hjorth, J. J. J. , Sterratt,  D. C., Cutts, C. S., Willshaw, D. J. and  Eglen, S. J. (2015). ‘Quantitative assessment of computational models  for retinotopic map  formation’ Developmental Neurobiology 75: 641–666.  <a href="http://dx.doi.org/10.1002/dneu.22241">doi:10.1002/dneu.22241</a>. Preprint available at   <span class="list-identifier"><a title="Abstract" href="http://arxiv.org/abs/1408.6132">arXiv:1408.6132</a>

* Willshaw, D. J., Sterratt, D. C. and Teriakidis, A. (2014). ‘Analysis of local and global topographic order in mouse retinocollicular maps’. Journal of Neuroscience 34:1791-1805. <a href="http://dx.doi.org/10.1523/JNEUROSCI.5602-12.2014">doi:10.1523/JNEUROSCI.5602-12.2014</a> <a href="http://www.jneurosci.org/content/34/5/1791.full.pdf+html">[PDF]</a>

* Sterratt, D. C. and Hjorth, J. J. J. (2013). ‘Retinocollicular mapping explained?’ <a href="http://journals.cambridge.org/action/displayJournal?jid=vns">Visual Neuroscience</a><br />30:125-128. <a href="http://dx.doi.org/10.1017/S0952523813000254">doi:10.1017/S0952523813000254</a> <a href="http://journals.cambridge.org/repo_A90JlXNl">[PDF]</a>

* Sterratt, D. C. (2013). ‘On the Importance of Countergradients for the Development of Retinotopy: Insights from a Generalised Gierer Model’. <a href="http://www.plosone.org">PLoS ONE</a> 8:e67096. <a href="http://dx.doi.org/10.1371/journal.pone.0067096">doi:10.1371/journal.pone.0067096 </a> <a href="http://www.plosone.org/article/fetchObject.action;jsessionid=709C56F55549DE602C90FA4DBF8882BD?uri=info%3Adoi%2F10.1371%2Fjournal.pone.0067096&amp;representation=PDF">[PDF]</a>

## Retistruct

<figure>
<img src="{{site.url}}/images/retistruct-400.png" />
<figcaption>Reconstructing a retina in Retistruct</figcaption>
</figure>

_In collaboration with Ian Thompson and Daniel Lyngholm._

We have developed Retistruct, a program to morph a flat surface with
incisions (a dissected retina) onto a curvilinear surface (the
original retinal shape). For more details and to download the
software, see
[the paper](http://www.ploscompbiol.org/article/info%3Adoi%2F10.1371%2Fjournal.pcbi.1002921)
or go to the
[Retistruct home page](http://retistruct.r-forge.r-project.org/).

* Sterratt, D. C., Lyngholm, D., Willshaw, D. J. and Thompson,
  I. D. (2013). ’Standard anatomical and visual space for the mouse
  retina: Computational reconstruction and transformation of flattened
  retinae with the Retistruct Package’. <a
  href="http://www.ploscompbiol.org/article/info%3Adoi%2F10.1371%2Fjournal.pcbi.1002921">PLoS
  Computational Biology</a> 9(2): e1002921. <a
  href="http://dx.doi.org/doi:10.1371/journal.pcbi.1002921">doi:10.1371/journal.pcbi.1002921</a>

# Learning and memory

## Distance-dependent synaptic plasticity

<figure>
<img src="{{site.url}}/images/ddsp-fig2.png"/>
<figcaption>Signals from spines in a model CA1 neuron</figcaption>
</figure>

In hippocampal CA1 cells, synapses that are further from the cell body
are larger than those closer to the cell body. In collaboration with
Dr Arjen van Ooyen (Sterratt & van Ooyen 2002, 2004; Sterratt, Groen,
Meredith & van Ooyen, 2012), I have been investigating whether this
distance-dependent scaling could arise as a result of voltage and
calcium signals elicited by synaptic inputs to the dendrites of
hippocampal CA1 cells. To achieve this, we used the NEURON simulation
package to implement a detailed compartmental model of a CA1 cell
incorporating spines into which calcium can flow via NMDA receptors
and voltage-dependent calcium channels.

In contrast to earlier modelling work, we fed more naturalistic
patterns of synaptic activity into the model and our results suggest
that the magnitude of calcium signals could provide the information
needed for synapses to be scaled. In a separate strand of work
(Sterratt & Willshaw, 2008), I have analysed the expected improvement
in the performance of a CA1 cell as an associative memory due to
scaling synapses appropriately for distance.

* Sterratt, D. C., Groen, M. R., Meredith, R. M. and van Ooyen,
  A. (2012). ‘Spine calcium transients induced by synaptically-evoked
  action potentials can predict synapse location and establish
  synaptic democracy’. <a
  href="http://www.ploscompbiol.org/article/info%3Adoi%2F10.1371%2Fjournal.pcbi.1002545">PLoS
  Computational Biology</a> 8(6): e1002545. <a
  href="http://dx.doi.org/10.1371/journal.pcbi.1002545">doi:10.1371/journal.pcbi.1002545</a>

* Sterratt, D. C.  and van Ooyen, A. (2004).  ‘Does a dendritic
  democracy need a ruler?’ <a
  href="http://www.elsevier.com/locate/neucom"><span
  class="cmti-10">Neurocomputing</a> 58-60:437-442.  <a
  href="http://dx.doi.org/10.1016/j.neucom.2004.01.078">doi:10.1016/j.neucom.2004.01.078</a>. <a
  href="/sites/sterratt.me.uk/files/cns2003.pdf">[PDF]</a>

* Sterratt, D. C.  and van Ooyen, A. (2002).  ‘Does morphology
  influence temporal plasticity?’ In J. R. Dorronsoro, ed., Artificial
  Neural Networks -- ICANN 2002, vol.  2415 of <a
  href="http://www.springeronline.com/sgw/cda/frontpage/0,10735,3-164-0-0-0,00.html">Lecture
  Notes in Computer Science</a>, pp.  186-191.  <a
  href="http://www.springer.de">Springer-Verlag</a>, Berlin,
  Heidelberg, New York.  <a
  href="/sites/sterratt.me.uk/files/do-delays-matter.pdf">[PDF]</a>

* Sterratt, D. C. and Willshaw, D. (2008). ‘Inhomogeneities in
  heteroassociative memories with linear learning rules’ <a
  href="http://neco.mitpress.org/">Neural Computation</a>
  20:311-344. <a
  href="/sites/sterratt.me.uk/files/inhomog-assoc-net.pdf">[Preprint]</a>

## Learning and forgetting in associative memories

<figure> <img src="{{site.url}}/images/forgetting-400.png" />
<figcaption>Results of a model of forgetting in which the rate at
which synapses are weakened can be adjusted. <strong>Top</strong> The
Signal to Noise Ratio (SNR) is higher for better recall, and decreases
with the age of the memory. How the SNR decays with the age of a
memory depends on whether synapses are weakened quickly, slowly or
optimally. The point at which performance becomes unacceptable
(indicated by the black line) depends on rate. Too fast, and memories
disappear quickly. Too slow, and traces of old memories start to
interfere with recall. <strong>Bottom</strong> Equivalently, this can
be viewed as the fraction of bits that are wrong. </figcaption>
</figure>

In collaboration with Professor David Willshaw (Sterratt & Willshaw,
2008), I have undertaken rigorous mathematical analysis and simulation
of feedforward associative memories that incorporate a family of
synaptic learning rules and synaptic weight decay. The networks learn
newly presented memories and forget old ones. The mathematical
formulation of these networks also allows the effects of
distant-dependent attenuation and stochastic transmission to be
modelled. For an overview of the method, see these slides from
Computational Neuroscience 2006

In collaboration with Dr Jesus Cortes (Granada) and Dr Mark van Rossum
(Edinburgh), I am using mean-field analysis and simulation to
investigate the performance of recurrent associative networks with
sparsely-coded memory patterns, where activity levels are controlled
by a mixture of inhibition and thresholds.

* Sterratt, D. C. and Willshaw, D. (2008). ‘Inhomogeneities in
  heteroassociative memories with linear learning rules’ <a
  href="http://neco.mitpress.org/">Neural Computation</a>
  20:311-344. <a
  href="/sites/sterratt.me.uk/files/inhomog-assoc-net.pdf">[Preprint]</a>

## Familiarity memory

Familiarity memory the type of memory involved in being able to
identify that a stimulus (e.g. someone met in the street) is familiar,
but not being able to recall any more facts about the stimulus
(e.g. the person's name, where we know them from). Humans have a
tremendous capacity for this, and in a neural network model, the
number of stimuli that can be identified as familiar scales with the
square of the number of neurons. This capacity is much greater than
for being able to recall memories, which scales with the number of
units. In collaboration with Dr Andrea Greve and Dr Mark van Rossum, I
have investigated optimal learning rules for familiarity detection
(Greve, Sterratt, Donaldson, Willshaw & van Rossum, 2009). Some work
in preparation suggests that with a more realistic network, the
capacity isn't so great - but still better than for recall.

* Greve, A., Sterratt, D. C., Donaldson, D. I., Willshaw, D. J. and
  Rossum, M. C. W. (2009) ‘Optimal learning rules for familiarity
  detection’ <a
  href="http://www.springerlink.com/content/100465/">Biological
  Cybernetics</a> 100:11-19. <a
  href="http://dx.doi.org/10.1007/s00422-008-0275-4">doi:10.1007/s00422-008-0275-4</a>
