@def title = "Nonlinear oscillators and parametric resonances | Shihabul Haque"
@def hascode = true
@def date = Date(2025, 8, 6)

# Nonlinear oscillators and parametric resonances
At IACS, starting from my second year, I worked with Prof. Jayanta K. Bhattacharjee (who you can see on the homepage) on nonlinear systems for around a year before he left for IIT, Kanpur, after which we collaborated online. Broadly, my work with him can be categorised into three separate intervals. 

## Nonlinear systems
Initially, I worked on simple nonlinear systems and looked at some interesting features of their dynamics. As a fresh undergrad, this familiarised me with ideas like 
_linearization_ and _fixed points_. As an example, I worked on a biquadratic potential for some time which had a diverging its time period under a certain condition. 
Apart from identifying various possibilities and the divergence, I also looked into the exact dependence of the divergence, visualising the same.
~~~
<div class="row">
  <div class="container" style="text-align: center;">
    <img src="/assets/phs.png" width="300" height="300" style="display: block; margin-left: auto; margin-right: auto;">
    <p style="font-size: 15px; margin-top: 10px;">
      Cool phase space dynamics for the double well described above.
    </p>     
    <div style="clear: both"></div> 
  </div>
</div>
~~~
I worked on forced oscillators around resonance and learnt to use **perturbative techniques** to identify their resonant frequencies. I applied certain techniques (like 
**Krylov Bogolioubov averaging**) to determine approximate analytical solutions around resonance. A report on the more interesting aspects of this work can be found
~~~
<a href="/assets/Pr___2___Non_linear_oscillations_and_resonance__KVPY_.pdf" download="Non_linear_oscillations_and_resonance.pdf">here.</a>
~~~
## Parametric resonances in more complicated systems
In the latter part of 2022, I worked with my classmate, Nilanjan, and Prof. Bhattacharjee on an **elastic double pendulum** - a six-dimensional system. We identified four 
resonance conditions using perturbative techniques (two of which, to the best of our knowledge, were not analysed in existing literature). We looked at the numerical solutions 
at resonance and briefly investigated the chaotic aspects of the system by computationally estimating the Lyapunov exponent. Unfortunately, due to the system's complexity, 
deriving an approximate analytical expression proved challenging. I presented our work on the elastic double pendulum at **NODYCON 2023**, held in Rome (I presented remotely 
due to personal circumstances). The abstract we submitted can be found [here](https://nodycon.org/2023/papers/192/abstract_submissions/621/view_abstract) 
(link to the official NODYCON abstract page). The presentation slides can be found
~~~
<a href="/assets/Presentation_NODYCON2023_D.pdf" download="Presentation_NODYCON2023">here.</a>
~~~
The published chapter after peer-review can be accessed [here](https://link.springer.com/chapter/10.1007/978-3-031-50631-4_12).
## Bounded solutions and forced oscillators
While working on the elastic double pendulum, Prof. Bhattacharjee and I became interested in a different problem - the simple **forced undamped oscillator**. It has a very 
well-known resonance condition and its behaviour around this point is known (in the linear order). Yet, the linear order solution diverges while the actual equation does not - we looked at the system perturbatively and found, surprisingly, that such finite solutions can be explained, even in undamped cases, by an interesting camaraderie between 
the amplitudes in various orders leading to a **destructive interference like effect** - just as in the case of light! Furthermore, we found that the amplitude and the time 
period of the oscillations are drive-dependent and follow some interesting power laws - this only happens in a specific interval of drive magnitude after which the oscillator 
tends to become more and more messy - a first-order phase transition! This work resulted in a peer-reviewed publication - you can find it 
[here](https://iopscience.iop.org/article/10.1088/1751-8121/ad6412). The arXiv preprint of the same manuscript is available [here](https://arxiv.org/abs/2305.04125).
~~~
<div class="row">
  <div class="container" style="text-align: center;">
    <img src="/assets/PT37n_img.jpg" width="300" height="300">
    <p style="font-size: 15px; margin-top: 10px;">
      A comparison of the linear solution (which blows up) and what the original equation describes.
    </p>     
    <div style="clear: both"></div> 
  </div>
</div>
~~~

[← Back](/menu1/)
