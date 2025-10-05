@def title = "Axions, extra dimensions and more | Shihabul Haque"
@def hascode = true
@def date = Date(2025, 8, 6)

# Axions, extra dimensions and more
My two years BS-MS project at IACS, supervised by Prof. Sourov Roy (personal website [here](https://www.iacs.res.in/athusers/index.php?navid=0&userid=IACS0070)), was based
on axions - super-light, weakly interacting particles that are hypothesised to exist but have not yet been detected experimentally. This page describes the three broad aspects of my work: axion/photon mixing, ALPs in the RS model and axion echoes. The central theme of all three involved the consequences of the interaction term that couples together these axions with photons, our familiar light. This interaction looks like,
$$ 
\mathcal{L}_{ \text{int} } = - \frac{1}{4} g_{a \gamma \gamma} a F^{\mu \nu} \tilde{F}_{\mu \nu} 
$$
In the above equation, $a$ describes the axion field while $F^{\mu \nu}$ and $\tilde{F}_{\mu \nu}$ denote the photon field (more accurately, the field tensor of the photon
field) and its dual. One of the quantities of interest is $g_{a\gamma\gamma}$, the coupling strength - this parameter regulates how strongly axions interact with photons; a larger value of $g_{a\gamma\gamma}$ implies a stronger interaction leading to stronger observational effects, something we can look for in our experiments helping us refine our theory.

My project began with reviewing some of the early literature on "**axion/photon mixing**" - a consequence of the interaction term above. In the presence of a background electromagnetic field the axion "mixes" with photons. A rough way to see this is to note that both $F^{\mu\nu}$ and $\tilde{F}_{\mu\nu}$ are built out of the electromagnetic field and thus describe, in a crude sense, two such fields (so, on a Feynman diagram, we have two wiggly legs emerging from this vertex). One of these can be the background field, allowing the axion to interconvert with the other. In astrophysical situations, this can cause "dimming" of the light emitted by objects like supernovae due to background magnetic fields or polarization changes which can be detected experimentally. Closer home, "light-shining-through-wall" (LSW) experiments work similarly. For my part, I derived some of these results both analytically and computationally in a couple of simpler models of the intergalactic magnetic field, focusing mostly on polarization-based studies. 
~~~
<div class="row">
  <div class="container">
    <center><img src="/assets/axions.png" width = "250" height = "250"></center>
    <p style = "font-size: 15px">A comparison of how the axion intensity grows (if we start with only photons) in two models - the
<a href="https://www.sciencedirect.com/science/article/abs/pii/S0370269302024486?via%3Dihub">conventional model </a> and the
<a href="https://journals.aps.org/prd/abstract/10.1103/PhysRevD.96.043519">helical model </a>. Similar results can be obtained for gravitons too. 
</p>
</div>
~~~
In the following semester, I looked at a closely related idea: **graviton/photon mixing** which describes a similar phenomena, but for gravitons (or, gravitational waves). Once
linearised, the formalism is resembles the axion/photon case closely. Much of my project focused on polarisation changes in light that might result from such an oscillation 
phenomenon and how it might apply to real-life observations.
## ALPs in Randall-Sundrum models
One of the central open problems in physics is the "hierarchy problem" which is simply the question of why certain parameters in our universe take the values that they do. A more specific manifestation revolves around the huge order-of-magnitude difference between the Planck scale (the scale till which we assume the standard model of particle physics holds true before quantum gravity kicks in, around $10^{19}$ GeV) and the electroweak scale (set by the Higgs v.e.v of around $250$ GeV). The Randall-Sundrum (RS) model proposes a possible solution to this involving a five dimensional spacetime with a warped geometry structure - however, the RS solution only works if the extra-dimension of the model has a specific "size". 

Our work involved a specific kind of **axion-like particles** (ALPs) in such models originating from a Kalb-Ramond field: such ALPs couple to photons through a coupling strength that directly depends upon the size of the extra-dimension. Assuming the RS solution is true, therefore, leads to a "predicted" coupling strength. We calculated this value and compared it to current experimental bounds leading to an interesting observation: lighter ALPs seemed to be strongly disfavoured by such a consideration, while heavier ALPs, though not completely ruled out, still seemed to be in significant tension with data. The arXiv preprint based on this work is available [here](https://arxiv.org/abs/2411.08396).
~~~
<div class="row">
  <div class="container">
    <center><img src="/assets/rsmodel.png" width = "450" height = "350"></center>
    <p style = "font-size: 15px">A snapshot of the entire ALP/photon coupling parameter space: the red and black dotted lines are the values predicted assuming the RS solution is true in two separate contexts. The shaded regions represent excluded areas.
</p>
</div>
~~~
## Axion echoes in multi-ALP theories
A second consequence of the coupling term described above is the decay of an axion (or, axion-like particle) into two photons. The rates of such decays can be be enhanced 
significantly in the presence of an external photon with momentum half the mass of the axion. The two photons produced in the decay process are emitted back-to-back with one
being in the direction of the initial incident photon and the other in the opposite direction. Since this process involves a photon returning to the source of the initial photon, it is termed an "echo" photon while the phenomenon itself goes by the name of an "**axion echo**". 

Axion echoes can be an interesting and powerful way to search for these elusive particles. Essentially, this involves sending out a beam of photons into outer space and searching for possible "echo" photons at or near the source point. Also, since our universe is teeming with a multitude of natural sources of radiation, we could also look for echo photons produced by axion echoes triggered by these astrophysical photons. Such studies have helped refine our models and improve our current experimental constraints, but with a caveat - nearly all of them are single axion studies, i.e., theories with only a single ALP field.

Multiple ALPs might sound exotic, but they are quite common in theoretical models, for example, those rooted in string theory. Usually, the coupling strengths and masses of the
ALP fields depend on the kind of underlying model one considers. In our work, we theoretically tackled the problem of echoes generated in multi-ALP models in a model-ndependent
fashion. We considered two field configurations: coherent, with the different ALPs oscillating in phase, and incoherent, where they oscillate with random phases. Our results showed that while there was a sharp amplification in the first case, leading to potentially larger signals, the second case showed the exact opposite behaviour - signals weaker than even the single ALP case. Aside from observational ramifications, this also bears on how we actually interpret experimental results in these differing contexts. You can find more details in our arXiv preprint [here](https://arxiv.org/abs/2507.16555). 

[← Back](/menu1/)
