---
layout: page
title: Projects
permalink: /projects/
---
# Multiscale modelling of biochemical networks within compartmental models

Integration of rule-based models of biochemical networks with
compartmental models

# Development of the nervous system

## Retistruct

![Retistruct](/images/retistruct.png){: style="float: right"}

With Ian Thompson and Daniel Lyngholm (MRC Centre for Developmental
Neurobiology, KCL) I have developed Retistruct, a program to morph a
flat surface with incisions (a dissected retina) onto a curvilinear
surface (the original retinal shape). For more details and to download
the software, see the paper or go to the Retistruct home page.

## Modelling the development of neural topographic maps

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

There are a number of existing computational models of the
establishment of the mapping between the retina and its targets, which
have shown how both marker-based and activity-based mechanisms can set
up topographic maps. In the years since these models were devised a
great deal of experimental evidence has accumulated and it is
important to assess whether existing models can account for new
experimental data. The key challenge is to integrate as many of the
biological constraints as possible into models that can still explain
the large-scale topographic organisation of the connections. I am
carrying out this work in collaboration with Professor David Willshaw
(Edinburgh) and Drs Stephen Eglen and Johannes Hjorth (Cambridge).

## Paper on analysis of topographic maps

David Willshaw, Adrianna Teriakidis and I have just published a paper
in the Journal of Neuroscience on analysis of topographic maps. We
have devised a new computational method entitled the "lattice method"
to analyse experimental data. Our method reveals that there is hidden
order in some maps that were previously thought to be disordered.


# Learning and memory, in particular asccociative networks

## Distance-dependent synaptic plasticity

Signals from spines in a model CA1 neuronSignals from spines in a
model CA1 neuron

In hippocampal CA1 cells, synapses that are further from the cell body
are larger than those closer to the cell body. In collaboration with
Dr Arjen van Ooyen (Sterratt & van Ooyen 2002, 2004; Sterratt, Groen,
Meredith & van Ooyen, 2012), I have been investigating whether this
distance-dependent scaling could arise as a result of voltage and
calcium signals elicited by synaptic inputs to the dendrites of
hippocampal CA1 cells. To achieve this, we used the NEURON simulation
package to implement a detailed compartmental model of a CA1 cell
incorporating spines into which calcium can flow via NMDA receptors
and voltage-dependent calcium channels. In contrast to earlier
modelling work, we fed more naturalistic patterns of synaptic activity
into the model and our results suggest that the magnitude of calcium
signals could provide the information needed for synapses to be
scaled. In a separate strand of work (Sterratt & Willshaw, 2008), I
have analysed the expected improvement in the performance of a CA1
cell as an associative memory due to scaling synapses appropriately
for distance.

## Learning and forgetting in associative memories

How best to forget? Click to enlarge.How best to forget? Click to
enlarge.

In collaboration with Professor David Willshaw (Sterratt & Willshaw,
2008), I have undertaken rigorous mathematical analysis and simulation
of feedforward associative memories that incorporate a family of
synaptic learning rules and synaptic weight decay. The networks learn
newly presented memories and forget old ones. The mathematical
formulation of these networks also allows the effects of
distant-dependent attenuation and stochastic transmission to be
modelled. For an overview of the method, see these slides from
Computational Neuroscience 2006

In collaboration with Dr Jesus Cortes (Granada) and Dr Mark van Rossum (Edinburgh), I am using mean-field analysis and simulation to investigate the performance of recurrent associative networks with sparsely-coded memory patterns, where activity levels are controlled by a mixture of inhibition and thresholds.

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

