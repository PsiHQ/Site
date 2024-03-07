@def title = "Research"
@def hascode = true
@def date = Date(2024, 3, 7)

@def tags = ["syntax", "code"]

# Research interests

As someone who likes a fair bit of maths, I am primarily interested in the theoretical side of things. My research interests and past exposure are diverse - I have not yet settled on a very niche topic yet. However, I am more inclined towards _particle physics_ and _high-energy phenomena_ - the topic my BS-MS project is broadly based in. 

At the same time, I have played around a fair bit with other areas - _nonlinear dynamics_, _quantum foundations_ and _gravity_. On this page, you will find a broad description of my interests and exposure. 

\toc

## Nonlinear systems, parametric resonances and oscillators (spoiler alert: _lots_ of oscillators!)

At IACS, I worked with Prof. Jayanta K. Bhattacharjee (who you can see on the homepage!) on nonlinear systems for around a year before he left for IIT Kanpur. Broadly, my work with him can be categorised into three separate intervals. 

### Nonlinear systems

Initially, I worked on simple nonlinear systems to look at some interesting aspects of their dynamics. As a fresh undergrad, this familiarised me with basic _approximating techniques_, _differential equations_, ideas like _linearization_ and _fixed points_ and so on. 

~~~
<div class="row">
  <div class="container">
  <img class = "right" src="/assets/phs.png" width = "250" height = "200">
  <p style = "font-size: 15px"> As an example, I worked on a biquadratic potential for some time and looked into its time period which blew up in a certain case. Apart from identifying various possibilities and the divergence, I also looked into the exact dependence of the divergence, visualising the same and so on. </p>
  <p style = "font-size: 13px"><i> Right: Cool phase space dynamics for the double well described above! </i></p>
</div>
~~~

I also worked on forced oscillators around resonance and learnt to use perturbative techniques to identify their resonant frequencies, applied certain techniques (like Krylov Bogolioubov averaging) to look at their solutions and determined approximate analytical solutions around resonance. 

A report on the more interesting aspects of this work can be found 
~~~
<a href="_assets/Pr___2___Non_linear_oscillations_and_resonance__KVPY_.pdf" download="rep1"><i>here.</i></a>
~~~

### Parametric resonances in more complicated systems

In the latter part of 2022, I worked with my classmate, Nilanjan, and Prof. Bhattacharjee on an elastic double pendulum - a 6 dimensional complicated system. We identified four resonance conditions using perturbative techniques (two of which, to the best of our knowledge, were not analysed in existing literature). We looked at the numerical solutions at resonance and briefly investigated the chaotic aspects of the system by computationally getting an idea of the Lyapunov exponent. Unfortunately, due to the system's complexity, deriving an approximate analytical behavior at resonance proved challenging. 

I presented our work on the elastic double pendulum in the summer of 2023 at **NODYCON 2023**, held in Rome (unfortunately, I had to present remotely). The abstract that we submitted can be found 
~~~
<a href="_assets/Abstract_Revised_2_(accepted).pdf" download="abstract"><i>here.</i></a>
~~~
The presentation slides can be found 
~~~
<a href="_assets/Presentation_NODYCON2023_D.pptx" download="slides"><i>here.</i></a>
~~~

### Bounded solutions and forced oscillators

While working on the elastic double pendulum, Prof. Bhattacharjee and I became interested a different problem - the simple forced undamped oscillator. It has a very well known resonance condition and its behaviour around this point is well known (in the linear order). Yet, the linear order solution diverges while the actual equation does not lead to such behaviour - we looked at the system perturbatively and found, surprisingly, that such finite solutions can be explained, even in undamped cases, by an interesting camaraderie between the amplitudes in various orders leading to a destructive interference like effect - just as in the case of light! 

~~~
<div class="row">
  <div class="container">
    <center><img src="/assets/PT37n_img.jpg" width = "250" height = "250"></center>
    <p style = "font-size: 15px"><i> A comparison of the linear solution (which blows up) and what the original equation describes. </i></p>
</div>
~~~

The preprint on this work can be found 
~~~
<a href="_assets/REVTPT_AJP_auth.pdf" download="rep2"><i>here</i></a>
~~~
and also on the arXiv (though the arXiv version is a bit outdated).


### Classical tunneling 

This one is a work in progress - I became interested in the possiblity of "tunneling" in classical contexts while discussing a recent preprint of Prof. Bhattacharjee's with him. At the moment, I have some interesting ideas and results but a lot more work is needed! I hope to update this part very soon.

## Weak measurements and quantum theory

My curiosity in quantum theory was piqued ever since I read Anil Ananthaswamy's _Through Two Doors at Once_ (on the many interpretations of the quantum theory through the double slit experiment) - J. J. Sakurai's _Modern Quantum Mechanics_, in particular, is one of my favourite textbooks. I reached out to Prof. Otto C. W. Kong for insight into the mathematical foundations and he advised me to build up my mathematical repertoire apart from discussing certain interesting issues with me. I later wrote a term paper as part of my curricula on the double slit experiment in classical and quantum contexts, taking inspiration from Richard Feynman's belief that the whole of quantum theory was hidden in that one singular experiment.

~~~
<div class="row">
  <div class="container">
    <img class = "left" src="/assets/pic6.jpg" width = "200" height = "175">
    <p style = "font-size: 15px"><i> <br><br><br> Left: Diffraction pattern from an experiment to measure the wavelength of light that we conducted in the IACS physics lab. <br><br><br> </i>  </p>
</div>
</div>
~~~

I visited the _Chennai Mathematical Institute_ in the summer of 2023 to work on weak measurements in quantum theory under Prof. H. S. Mani. It was one of the most interesting summers I have spent - looking at basic measurement theory in quantum physics, the groundbreaking Albert-Aharonov-Vaidman paper and its later interpretations. I looked comprehensively into the conceptual idea of a weak measurement and its relation to interference and the quantum nature of matter and explicitly calculated the weak values for certain observables in simple systems - spin-1 particles, oscillator potentials and so on. I also looked at the relation of weak values to non-normal observables and entanglement and briefly investigated PT-symmetric Hamiltonians - I have been intrigued by the possibility of non Hermitian observables for a long time and it was rewarding to look at some of the advances made in the direction.

## Axions, dark matter and neutrinos 

I have had a bit of exposure to particle physics quite early in my undergrad days - I wrote a term paper on the solar neutrino problem in my first year (available
~~~
<a href="_assets/The_Solar_Neutrino_Problem___A_review.pdf" download="rep3"><i>here</i></a>
~~~ 
if interested) and I got very interested in the idea of neutrino oscillations and mass mixing. I later spent the summer of 2022 reading up on some basic ideas related to this - Dirac equations, spinors, neutrino mass models - under the supervision of Prof. Amitava Raychaudhuri at the Raja Bazaar Science College in Kolkata, gaining more depth into my naive ideas of neutrinos. 

My BS-MS project thesis, under Prof. Sourov Roy at IACS, is on axions - super light, weakly interacting particles that are there but maybe not there. Axions are one of the hypothesised components of dark matter - the mysterious matter that is supposed to occupy the vast majority of our universe dictating its expansion and the formation of structures like galaxies and so on but which we haven't yet observed directly. There are, of course, a lot of indirect evidences for dark matter and axions and a lot of experiments suggested to detect the both of them but nothing yet definitive or concrete. 

For now, my work, which started in August 2023, has involved reading up on existing literature on axions and related phenomena - like axion - photon coupling and transitions in the presence of magnetic fields, something I find fascinating even now and despite its obvious similarity to the neutrino oscillations I know of. 

## Gravitational formalism

One of the very first exposures to research I had was with Prof. Tapobrata Sarkar at IIT Kanpur. I (along with some of my classmates) did a brief reading project under him during the latter part of 2021 (online, due to the pandemic) and I learnt a bit about basic mathematical ideas of the relativistic theories - specifically learning about vectors, covectors, geodesics, Lie derivatives and so on. More importantly, Prof. Sarkar introduced us to some interesting packages on Mathematica built for relativists - I played around with them quite a bit, replicating parts of the results from a paper he discussed with us. While it was a brief association, I benefitted from the early exposure to gravity formalism and computational work - it is part of the reason I chose general relativity as an elective in my 4th year since I was very interested in looking more into the formalism I had once attempted to learn a bit on my own.
