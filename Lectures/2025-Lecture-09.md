---
title: (2025) Lecture 9
author: ''
presenter: Mikhail Mikhasenko
note_taker: Anna Zimmer
date: '2025'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



## The Kibble Function and Dalitz Plot Boundaries

#### Lecture 9 Recap

The **Dalitz plot** is the usual representation of a decay in the coordinates of the invariants. The same coordinates can be used for the cross process (scattering).

The border of the Dalitz plot (decay region) and the border for the scattering process are both determined by the same equation:
  $$\Phi(s,t,u)=0$$  
This is the **Kibble function** (also called the **Chew-Low function**), which involves the mass of the decaying particle and the pair masses of the two particles.

### Deriving the border condition

The border is obtained by requiring the scattering angle to be  $\pm 1$ :
  $$\cos\theta = \pm 1$$  
Although the meaning of the scattering angle changes slightly between scattering and decay domains, the condition  $\cos\theta = \pm 1$  holds for both. 




![This figure represents the **Mandelstam plane**, a plot with axes labeled by the Mandelstam variables  $s$  and  $t$ , which describe the kinematics of scattering processes. The "physical region" indicated in the diagram corresponds to the subset of allowed values of  $s$  and  $t$  where the scattering or decay process can physically occur, determined by kinematic constraints (such as the Kibble or Chew function discussed in the lecture). Outside this region, the amplitude can still be defined by analytic continuation, but does not correspond to direct physical processes—these are the unshaded or shaded regions outside the "physical region" boundary. The diagram illustrates how analytic properties of scattering amplitudes extend beyond the physical region into the complex Mandelstam plane, a concept central to the analytic approach to scattering theory described in the lecture.](2025-Lecture-09-images/fig11.png){#fig-fg11}




 The fact that it describes both appears when you consider that changing one particle to the other side does not change the kinematics. In the  $s$ -channel (with particles 1, 2, 3)  $\cos\theta$  is defined in the rest frame of two particles. To derive the border, write  $\cos\theta$  in terms of invariants and set it equal to  $\pm 1$  — this yields  $\Phi(s,t,u)=0$ .

| Process | Domain | Border condition |
|---------|--------|------------------|
| Decay (0 → 1+2+3) | Dalitz plot |  $\cos\theta = \pm 1$  inside the decay region |
| Scattering (1+2 → 3+4) | Physical region for scattering |  $\cos\theta = \pm 1$  at the edges of the physical region |

When you derive this, you encounter the **Källén function** and the **breakup momentum**:
  $$p = \frac{\sqrt{s - (m_1+m_2)^2}\,\sqrt{s - (m_1-m_2)^2}}{2\sqrt{s}}$$  
This formula is easy to remember once derived; it is common knowledge and can be found in textbooks such as Bickling and Cajenti.

The recipe: start with scattering kinematics and use the fact that the physical region boundaries correspond to  $\cos\theta = \pm 1$ . 




![This figure illustrates the analytic structure and kinematic channels of the pion-pion ( $\pi\pi$ ) scattering amplitude as a function of the Mandelstam variable  $s$ :  - **Left Side (Complex  $s$ -Plane):**     The horizontal axis represents the real part of the complex Mandelstam variable  $s$ , and the vertical axis is the imaginary part. The amplitude  $A_{\pi\pi \rightarrow \pi\pi,\rho}(s)$  is analytic except along cuts, which are indicated on the real axis. The solid blue line starting at the threshold  $4m_\pi^2$  (where  $m_\pi$  is the pion mass) represents the **s-channel unitarity cut**, i.e., the physical region where two-pion production becomes kinematically allowed. This is the beginning of the non-analytic region associated with the opening of the  $\pi\pi$  channel. The blue region labeled "u-channel" on the negative real axis represents the unitarity cut for the crossed channel, corresponding to different intermediate states due to crossing symmetry. The label "cardinal sheet" refers to the principal (physical) Riemann sheet of the analytic amplitude. The threshold marks the onset of physical two-pion states, relating to where the imaginary part of the amplitude (discontinuity) develops, as discussed under analytic and real analytic functions and their branch cuts.  - **Right Side (Feynman Diagram):**     This shows a generic  $2 \to 2$  pion scattering process: two incoming pions ( $\pi_1, \pi_2$ ) scatter via an interaction blob into two outgoing pions ( $\pi_3, \pi_4$ ). The Mandelstam variable  $s$  labels the center-of-mass energy squared of the incoming channel, and  $t$  labels the momentum transfer. This diagram is used to define the physical process that the complex  $s$ -plane structure corresponds to, connecting the analytic properties of the amplitude to physical scattering.  **Physical meaning in context:**   This figure visually connects the analytic properties (cuts, thresholds, Riemann sheets) of the scattering amplitude in the complex  $s$ -plane with their physical origins in pion-pion scattering. Concepts like the unitarity cut, threshold, and crossing symmetry (s-channel and u-channel) are depicted, illustrating how non-analyticities (branch cuts) in the amplitude arise from opening physical channels—key points in the study of analyticity and scattering theory as discussed in the lecture.](2025-Lecture-09-images/fig10.png){#fig-fg10}






### Crossing and additional physical regions

If you put  $\Phi(s,t,u)=0$  into Mathematica and ask for the regions in the two-dimensional plane where the equation is satisfied, you obtain not only the decay region but also other regions corresponding to **cross processes**. Those regions lie near the lines where the Källén function is zero — the borders of the other processes.

For the decay 0 → 1, 2, 3:

-  $s$  is positive inside the Dalitz plot.
- In one adjacent region  $s$  is still positive but the other invariants become negative.
- In another region two particles are still physical (either in the initial or final state), while for other regions particles are crossed to the opposite side.

The process corresponding to a particular crossing domain is  $0 \, \bar{3} \to 1, 2$ .

#### Example:  $\pi^- \omega \to \pi^- \pi^0$ 

We need to assign particles 1, 2, 3 consistently. The axes of the Dalitz plot are  $\omega\pi^0$  and  $\pi^-\pi^0$ . Here  $\pi^-\pi^0$  is one channel. The threshold for that channel is the production threshold for the initial state. As  $s$  increases, you move along that axis.

### Asymptotes of the physical regions

In the original Mandelstam paper, the boundaries are not hyperbolae; they are curves that approach lines at very high energy when masses can be neglected. The lecturer notes that the asymptotes are not the same as the lines themselves — they can cross — but that at high energy you approach those lines (possibly offset by threshold). For the process  $\pi^- \omega \to \pi^- \pi^0$ , the particle that is crossed to the other side becomes an antiparticle. Note that for  $\omega$  and  $\pi^0$ , particle and antiparticle are identical.



## Unitarity and the Optical Theorem in Elastic Scattering

### Spin Considerations

Things become more involved when spin is accounted for. For correct treatment, helicity indices  $\lambda$  should be written, because the state  $\Omega$  has spin; helicities also exhibit peculiar relations under crossing. This is not discussed further here. For kinematical considerations it is sufficient to treat the particles as scalars. Relating amplitudes with helicity indices requires additional work. The kinematic regions were drawn roughly; for greater accuracy one may open a computational notebook, but the picture is otherwise intuitive.

<hr>

### Elastic Scattering and the Amplitude  $A$ 

The second unit concerns the RT equations for elastic scattering.

| Symbol | Meaning |
|--------|---------|
|  $S$  | Mandelstam variable:  $S = (P_1+P_2)^2$  |
|  $T$  | Mandelstam variable:  $T = (P_1-P_3)^2$ , related to the scattering angle  $\theta$  |
|  $A$  | Scattering amplitude (the main object of discussion) |

<b>Elastic scattering</b> means that initial and final states are the same; energy is conserved.

<b>Q:</b> How should  $S$  and  $T$  be related to the amplitude  $A$ ?
<b>A:</b> The amplitude is often normalized with respect to energy, introducing a phase‑space factor. One writes  $S = 1 + i\rho A$ , and unitarity then gives a constraint on  $A$ .

This is the **unitarity equation** for  $A$ , not the optical theorem.

<hr>

### Unitarity Equation and Partial Wave Expansion

The imaginary part of the amplitude is related to the squared amplitude in the elastic region. This is the unitarity equation: one must integrate over all intermediate states when contracting one amplitude with another. Since the scattering is elastic, the same particles appear in the intermediate state. The integration accounts for different configurations of those particles. With only one type of particle state present, the phase‑space integration includes only different orientations of the same particles.

At high energy, many more intermediate states contribute. Fix the initial and final states.  $T$  is related to the scattering angle  $\theta$  between initial and final momenta. 




![This figure represents a schematic energy spectrum of hadronic states, specifically showing the quantum mechanical levels of a two-particle system (for instance, a pion–pion or pion–strange meson system) as a function of a variable labeled "lqq," which likely refers to quantum numbers or a kinematic variable relevant in the study of hadron physics. The vertical axis is energy ( $E$ ), while the horizontal axis shows "lqq".  The diagram features boxes corresponding to different energy levels and angular momentum (orbital) quantum numbers:   - "1S" and "2S" indicate the first and second S-wave (zero orbital angular momentum) states, while   - "1P" indicates the first P-wave (one unit of orbital angular momentum) state.  In the context of the lecture, which discusses scattering theory, analytic properties, and resonance spectroscopy, this diagram illustrates how physical resonances (hadronic states) appear as discrete levels in energy for two-particle systems, categorized by their angular momentum. The variables within the boxes—such as  $a_0, a_2, b_4$ —represent scattering parameters or possibly resonance parameters like scattering lengths (for different partial waves). This reflects how amplitude analysis and the study of analytic functions in the S-matrix formalism enable the extraction and classification of resonance parameters from the energy dependence of scattering amplitudes. The structure of the levels ties into discussions of analytic properties, poles (resonances), and real analyticity as these physical states correspond to singularities (poles) in the complex energy plane.](2025-Lecture-09-images/fig13.png){#fig-fg13}




 The momenta lie in the  $x$ –$z $plane. The intermediate state has an arbitrary orientation. Label momenta:

- Initial:$ P_1 $,$ P_2 $- Intermediate:$ Q_3 $,$ Q_4 $- Final:$ P_3 $,$ P_4 $Two scattering processes occur: first$ P$ to  $Q$ , then  $Q$  to  $P$ . We integrate over all  $Q$  configurations, introducing  $T'$  and  $T''$ . This gives the unitarity equation for the full amplitude.

The phase space is a regular two‑body phase space. We integrate over all possible configurations of two vectors, with the constraint that they are back‑to‑back. Writing this in terms of  $T'$  and  $T''$  is a highly non‑trivial task. The way to obtain the familiar unitarity equation (where the amplitude is related to itself) requires a partial wave expansion.

From the last lecture, each amplitude can be expanded into partial waves:

  $$A(s,\cos\theta)=\sum_{\ell=0}^{\infty}(2\ell+1)\,a_\ell(s)\,P_\ell(\cos\theta).$$  

Using the orthogonality of the Legendre polynomials, the angular integral disappears and the unitarity equation becomes

  $$\operatorname{Im} a_\ell(s)=\rho(s)\,|a_\ell(s)|^2,$$  

where  $\rho(s)=\dfrac{2p}{\sqrt{s}}$  is the phase‑space factor, with  $p$  the centre‑of‑mass momentum. More explicitly,

  $$\rho(s)=\frac{\sqrt{s-(m_1+m_2)^2}\,\sqrt{s-(m_1-m_2)^2}}{s}.$$  

The partial‑wave amplitudes depend only on  $s$ ; there is no  $t$  dependence. This simplifies matters drastically.

<hr>

### Comparison of  $T'$  and  $T''$ 

 $T'$  and  $T''$  are different because they are computed for different pairs of momenta:

| Amplitude | Between which momenta |
|-----------|----------------------|
|  $T'$  |  $Q_3$  and  $P_1$  |
|  $T''$  |  $Q_3$  and  $P_3$  |

There is one limit where they become the same: **forward scattering**,  $t=0$ . In that case  $P_1 = P_4$ , so  $T' = T''$ . In backward scattering,  $t$  reaches its maximum (negative) value, but the two amplitudes are **not** equal. Only forward scattering makes them identical.

<b>Q:</b> Isn't it the same for backward scattering?
<b>A:</b> No. In forward scattering the angles coincide; in backward scattering they do not. Therefore  $T'$  and  $T''$  can be identified only in the forward limit.

<hr>

### Forward Limit and the Optical Theorem

In forward scattering the amplitude  $A(s,t=0)$  appears. The squared amplitude can be written directly. The final expression is the **optical theorem**:

  $$\operatorname{Im} A(s,t=0)=2k\sqrt{s}\,\sigma_{\text{tot}}(s),$$  

where  $k$  is the initial momentum. This is valid in the elastic region. Forward scattering is important because it allows elimination of one variable – the total cross section depends only on  $s$ .

<hr>

### Recap of Key Relations

1. **Unitarity for the full amplitude** (in the elastic region):
  $$\operatorname{Im} A(s,\cos\theta) = \rho(s) \int d\Omega'\, |A(s,\cos\theta')|^2 + \text{inelastic contributions}.$$  

2. **After partial wave expansion**, the angular integral factorises and we obtain
  $$\operatorname{Im} a_\ell(s) = \rho(s) |a_\ell(s)|^2,$$  
showing that partial waves do not mix.

3. **The optical theorem** is the  $t=0$  limit of the full unitarity equation. It is a consequence of unitarity in the forward limit.

It is important to relate these concepts to each other.



## Analyticity and Scattering Amplitudes in Hadron Spectroscopy

#### Lecture: Analytic Functions and Scattering Matrix Principles (see @fig-fg7)

Today we discuss analytic functions and how scattering matrix principles constrain scattering amplitudes, particularly analyticity. We begin with analytic functions and the reality condition

  $$f(z) = f^*(z^*)$$  

and then say a few words about analytic continuation at the end.

<hr>

### Approach in Hadron Physics

In hadron physics, interactions are not driven by simple Lagrangian or Hamiltonian dynamics. Scattering amplitudes cannot be derived from first principles. Instead, we study well-known general principles of scattering theory. These principles appear constraining enough to derive the general form of the amplitude, with parametric freedom that can be fixed from data.

| Principle | Role in Hadron Physics |
|-----------|------------------------|
| Unitarity | Ensures probability conservation; used in parameterizations |
| Elasticity | Often assumed in the dominant channel |
| Analyticity | Constrains the amplitude in different regions of the variables |
| Crossing symmetry | Used only rarely |


::: callout-important
Analyticity tells us that the function is constrained in different regions of the variables. If a function depends on  $S$  and  $T$ , it must extend its validity beyond the physical region, imposing extra constraints.
:::

Therefore, the approach used to describe scattering of hadrons—especially in experimental data—is to use general parameterizations of the amplitudes that satisfy unitarity and elasticity. Crossing symmetry is used only rarely.

We fix the parametric freedom, obtain the scattering amplitude as a mathematical expression, and study its properties. By studying the properties of the scattering amplitude, we learn about the properties of the objects we describe—namely the resonances.

<hr>
### Program of Hadron Spectroscopy (see @fig-fg13)

This is the program of hadron spectroscopy: using amplitude building and scattering theory tools to access the properties of resonances. We study resonances, and one constraint is analyticity.

<hr>
### Scattering Amplitude as a Complex Function (see @fig-fg8) (see @fig-fg12)

We consider the scattering amplitude as a complex function of its variables. All observables are real-valued: for example, the cross section is a real number. The amplitude itself is a complex number:

  $$A = |A| e^{i \varphi}$$  

This gives important information about the scattering.



## Analytic Functions and Singularities in the Complex Plane

The scattering amplitude is a complex multivariable function of the Mandelstam variables  $S$  and  $T$ . 




![This figure illustrates the analytic structure of the scattering amplitude  $A(s, t)$  as a function of the complex Mandelstam variable  $s$ , for fixed  $t$ . The horizontal axis represents the real part of  $s$  ( $\text{Re}(s)$ ), while the vertical axis is the imaginary part ( $\text{Im}(s)$ ). The depicted thick lines along the real axis correspond to the **branch cuts** associated with physical thresholds for two different scattering channels:  - The **threshold for the s-channel** is marked on the positive real- $s$  axis. This is where physical s-channel particle production can occur and corresponds to the opening of the unitarity cut. - The **fixed threshold for the u-channel** is indicated on the negative real- $s$  axis. This relates to the production threshold for the crossed (u-channel) process.  The region between the cuts, on the real  $s$ -axis below threshold, is labeled "real analytic," indicating that the amplitude is real and analytic in that segment — in accordance with the property of real analytic functions discussed in the lecture. The cuts themselves signify the locations where the amplitude develops an imaginary part (discontinuity), corresponding to physical particle production (unitarity cuts).  This diagram physically encodes how the analytic (and specifically, real analytic) properties of the scattering amplitude in the complex  $s$ -plane reflect causality and unitarity, with thresholds demarcating the transition points where new physical channels become accessible. These analytic properties are crucial for defining the amplitude's behavior and for connecting it to physical observables.](2025-Lecture-09-images/fig8.png){#fig-fg8}




 By treating  $S$  (the energy) or the scattering angle as complex variables — e.g.,  $30^\circ + i$  — new insights emerge. (see @fig-fg10) The amplitude is not just complex but **analytic** in its arguments everywhere except for a few segments. (see @fig-fg11)

### Analytic (holomorphic) functions
Holomorphic functions match their Taylor series in the vicinity of every point in their domain. More precisely, a function is analytic in a domain if it is complex differentiable there; it then equals its convergent Taylor series. (see @fig-fg7) A polynomial is analytic throughout  $\mathbb{C}$ . Functions like  $\sqrt{z}$  and  $\log z$  are analytic except along a line segment (the **branch cut**), whose endpoints are **branch points**.

### Branch cuts and branch points
The table below shows common functions and their branch‑cut structures. In the  $z$ -plane the real part is the  $x$ -axis, the imaginary part the  $y$ -axis. 




![This figure represents the analytic structure of the complex function  $f(z) = \sqrt{z-1} - \sqrt{z}$  in the complex  $z$ -plane. The real axis is labeled as "Re" and the imaginary axis as "Im." The blue wavy line running from  $z = 0$  to  $z = 1$  along the real axis indicates a **branch cut**—a region where the function is non-analytic due to the multivalued nature of the square root functions.   Physically, this branch cut corresponds to a discontinuity in the value of the function as you cross from just above to just below the real axis, reflecting a non-trivial analytic structure. In the context of scattering amplitudes discussed in the lecture, such branch cuts represent kinematic thresholds—boundaries in the complex energy plane (or similar Mandelstam variables) where new physical processes (such as particle production) can occur and the amplitude develops an imaginary part.   This analytic feature is essential for understanding the behavior of scattering amplitudes, as the existence and location of branch cuts (and their associated **branch points** at  $z = 0$  and  $z = 1$ ) dictate where the amplitude ceases to be real and begins to have a discontinuity—properties crucial for unitarity and the correct physical description of processes.](2025-Lecture-09-images/fig4.png){#fig-fg4}

 




![This figure illustrates the analytic structure of the function  $f(z) = \sqrt{z^2 - 1}$  in the complex  $z$ -plane, specifically highlighting the locations of branch cuts and branch points. The real and imaginary axes are labeled as "Re" and "Im," and the function is annotated in the upper right.  Physically, in the context of the lecture, this type of function models the analytic structure one encounters in scattering amplitudes, where the square root reflects the opening of new channels or thresholds. The blue wavy lines represent branch cuts: one running from  $-\infty$  to  $-1$  along the real axis, and another from  $1$  to  $+\infty$ , indicating non-analytic (discontinuous) behavior of  $f(z)$  across these intervals. The endpoints  $z = -1$  and  $z = 1$  are branch points, signaling the start of the branch cuts and corresponding to physical thresholds (like the onset of new particle production in scattering).   This structure encodes how the amplitude (or any analytic function with such a branch cut structure) changes its value when moving around these points in the complex plane, which is crucial for understanding phenomena like the development of an imaginary part (related to physical processes becoming possible) and the analytic continuation to different Riemann sheets—core ideas in the analytic S-matrix approach discussed in the lecture.](2025-Lecture-09-images/fig5.png){#fig-fg5}






| Function | Branch point(s) | Branch cut |
|----------|----------------|------------|
|  $\sqrt{z}$  |  $z=0$  | from  $0$  to  $-\infty$  (leftward) |
|  $\sqrt{z-1}$  |  $z=1$  | from  $1$  to  $-\infty$  (leftward) |
|  $\sqrt{-z}$  |  $z=0$  | from  $0$  upward |
|  $\sqrt{z(z-1)}$  |  $z=0,\;z=1$  | from  $0$  to  $1$  |
|  $\sqrt{z^2-1}$  |  $z=\pm1$  | from  $1$  to  $0$  to  $+\infty$ , then from  $-\infty$  to  $-1$  |
|  $\log z$  |  $z=0$  | from  $0$  to  $-\infty$  (leftward) |

For every cut we have two branch points. Sometimes one branch point is at infinity, another in the finite range.

The discontinuity across the cut is seen in examples:
  $$\sqrt{-1 + i\varepsilon} = i,\qquad \sqrt{-1 - i\varepsilon} = -i$$  
This discontinuity does not occur on the other side:  $\sqrt{1 + i\varepsilon}$  and  $\sqrt{1 - i\varepsilon}$  both give  $1$ . So along that side there is a discontinuity. 




![This figure illustrates the concept of a **pole** in the complex plane, which is a type of isolated singularity important in the analytic structure of scattering amplitudes. The function shown,  $f(z) = \frac{1}{z - 1 + i}$ , has a pole at  $z = 1 - i$ , indicated by the black dot on the diagram at that coordinate in the complex  $z$ -plane (with the real and imaginary axes labeled).   Physically, such poles in the scattering amplitude correspond to resonances or bound states in hadron physics; the amplitude becomes very large near the pole, signaling a strong "signal" or enhancement in the cross section. In the analogy provided in the lecture, the pole is like an "internet router"—the amplitude is strongest (largest) when you are closest to the pole in the complex plane, reflecting elevated probability or cross section values in experiments.   Thus, this figure emphasizes how the analytic properties—specifically the location and nature of poles—encode key physical information about the behavior of scattering processes and resonances.](2025-Lecture-09-images/fig6.png){#fig-fg6}






### Poles
A **pole** is an isolated singularity where the function goes to complex infinity. 




![This figure illustrates the analytic structure of a function in the complex  $z$ -plane, focusing on the concept of branch points and branch cuts. The point at the origin is labeled as a **branch point**, from which a **branch cut** extends along the negative real axis. This reflects the analytic properties of functions like  $\sqrt{z}$ , which are analytic everywhere except along the branch cut that starts at the branch point (here,  $z=0$ ).  Physically, in the context of the lecture, this is used to describe how complex functions (such as scattering amplitudes) behave: they are analytic in most of the complex plane, but exhibit non-analytic behavior (discontinuity) when crossing the branch cut. At points just above or below the cut (e.g.,  $f(-1 + i\epsilon)$  vs.  $f(-1 - i\epsilon)$ ), the function takes different values, highlighting the multivalued nature due to the branch point. This property is crucial for understanding the analytic structure of scattering amplitudes, where cuts and branch points correspond to physical thresholds and the opening of new channels, and dictate how analytic continuation—and hence the exploration of resonances, unitarity, and causality—are treated in quantum field theory.](2025-Lecture-09-images/fig1.png){#fig-fg1}




 For example,  $1/(z-(1-i))$  has a pole at  $z=1-i$ . 




![This figure illustrates the analytic structure of the function  $f(z) = \sqrt{z - 1}$  in the complex  $z$ -plane. The horizontal axis represents the real part of  $z$  ( $\mathrm{Re}(z)$ ), and the vertical axis represents the imaginary part ( $\mathrm{Im}(z)$ ).   The blue wavy line begins at the point  $z = 1$  on the real axis and extends to  $-\infty$  along the real axis. This line marks the **branch cut** of the function, which connects the **branch point** at  $z = 1$  to  $-\infty$ .   Physically, this illustrates the concept that functions like  $\sqrt{z-1}$ , which appear in the description of scattering amplitudes, are analytic everywhere in the complex plane except along their branch cut. The presence of the branch point and associated cut means that the value of the function is discontinuous across the cut, reflecting the multi-sheeted nature of such complex functions. This analytic structure is fundamental in understanding how scattering amplitudes behave as functions of complex variables, especially when we discuss analytic continuation and the physical meaning of singularities and discontinuities in scattering theory.](2025-Lecture-09-images/fig2.png){#fig-fg2}




 Away from the pole the function is large but finite.

::: callout-note
Poles are like Wi‑Fi routers: the closer you are, the stronger the signal (larger  $|A|$ ).
:::




![This figure represents the analytic structure of the function  $f(z) = \sqrt{-z}$  in the complex  $z$ -plane. The plot shows a branch cut along the positive real axis, indicating the line segment where the function is non-analytic. This cut starts at the branch point at the origin ( $z=0$ ) and extends to  $+\infty$  along the real axis.  Physically, in the context of scattering amplitudes, such branch cuts correspond to the thresholds for physical processes, such as the onset of particle production or scattering channels, and the branch point represents where a new channel opens. The function is analytic everywhere else except along this branch cut. The existence of the branch cut is a manifestation of the multi-valuedness of the function (here, due to the square root), and the discontinuity across the cut reflects the appearance of an imaginary part in the amplitude, related to inelastic processes and the unitarity cut in scattering theory. This structure illustrates how analytic functions in physics, such as scattering amplitudes, are characterized by their branch points and cuts in the complex plane, which encode essential physical information about reaction thresholds and continuations to different Riemann sheets.](2025-Lecture-09-images/fig3.png){#fig-fg3}




 In scattering, a large cross section is often driven by a nearby pole in the complex plane. 




![This figure illustrates the analytic structure of a scattering amplitude as a function of the Mandelstam variable  $s$  in the complex  $s$ -plane. The real axis represents physically allowed values of  $s$ , while the imaginary axis corresponds to complex (unphysical) values.  The branch points at  $(m_1 - m_2)^2$  and  $(m_1 + m_2)^2$  indicate the kinematic thresholds for particle production in the scattering process, i.e., the minimal and maximal invariant mass squared for producing particles of masses  $m_1$  and  $m_2$ . Between and beyond these points, the amplitude develops branch cuts (shown as wavy lines), which represent the discontinuities or non-analytic regions associated with the opening of physical channels.  The blue annotation that "the branch cuts cancel out → function is continuous" emphasizes that, across certain regions (possibly when combining different contributions or sheets), the discontinuity due to the branch cuts can be made to vanish, resulting in a function that is continuous in the complex plane except at the branch points themselves. This reflects the property of **real analyticity** discussed in the lecture: the amplitude is analytic everywhere except along the physical cuts, and across the real axis (below threshold) it is continuous and real. The Schwarz reflection principle guarantees that the amplitude behaves smoothly except precisely along and across these branch cuts.  Physically, this diagram encodes how the analytic properties of the scattering amplitude connect to physical thresholds, and how analyticity and unitarity restrict the possible singularities (cuts and poles) in the complex  $s$ -plane. The function is analytic except for these branch cuts associated with the creation of intermediate states or particles.](2025-Lecture-09-images/fig9.png){#fig-fg9}

 




![This figure illustrates the **analytic continuation** of the scattering amplitude  $A_{\pi\pi \to \pi\pi, \rho}^{II}(s)$  onto the **second Riemann sheet** in the complex  $s$ -plane. In the context of this lecture, the figure shows that:  - The **real axis** (horizontal line) represents physical values of the Mandelstam variable  $s$ , with the thick segment (branch cut) indicating the area where the imaginary part of the amplitude appears due to the opening of physical thresholds (e.g., two-pion production). - The **branch cut** is associated with the onset of physical intermediate states (unitarity cut), and analytic continuation through this cut leads to a different "sheet" of the function—a key concept in complex analysis of scattering amplitudes. - The **second Riemann sheet** (notated with  $II$ ) is accessed by analytically continuing the amplitude through the branch cut—this is where **resonance poles** appear. These poles correspond to unstable particles (resonances), which manifest as enhancements ("bumps") in the cross section in physical processes. - The figure also marks a **virtual state** (star on the imaginary axis left of threshold), representing a singularity not associated with a physical particle, but with a non-observable state. - Thus, the physical meaning is that the analytic structure of the scattering amplitude in the complex  $s$ -plane, especially the nature and position of its singularities (poles and cuts), encodes information about observable resonances and virtual states in hadron spectroscopy. This is a direct consequence of considering the amplitude as a **real analytic function** and performing analytic continuation.  In the context of the lecture, the figure emphasizes how complex analysis and the concept of Riemann sheets are essential for understanding the nature of resonances in scattering theory.](2025-Lecture-09-images/fig12.png){#fig-fg12}

 




![This figure illustrates the physical manifestations of different singularities of the scattering amplitude  $a$  in the complex energy plane, as discussed in the context of analyticity and amplitude analysis. The horizontal axis represents  $\sqrt{s}$ , where  $s$  is a Mandelstam variable related to the squared center-of-mass energy, while the vertical axis shows  $|a|^2$ , the squared modulus of the scattering amplitude, which is related to observable probabilities or cross sections.  - The **top panel** depicts a **resonance**, characterized by a pronounced peak in  $|a|^2$  above the threshold. The resonance is associated with a pole in the complex  $s$ -plane near the real axis. The curve rises sharply, reaches a maximum (the resonance energy or mass), then falls off. The threshold marks the lowest energy where the reaction can occur. The nearby **branch point** is also indicated, signifying the opening of the physical channel (threshold), and the analytic continuation shows how singularities influence the physical amplitude.  - The **middle panel** shows a **bound state**, which appears as a divergence in  $|a|^2$  below the threshold, indicated by a pole on the real axis below threshold. This manifests as a sharp feature (essentially a "delta function"-like effect in the cross-section) signaling a stable particle or state that cannot decay into the considered channel.  - The **bottom panel** demonstrates a **virtual state**, which manifests as a cusp or an enhancement right at the threshold, but there is no true resonance peak or bound state pole on the physical sheet. The cusp reflects the analytic structure of the amplitude due to a pole on the unphysical sheet, which doesn't correspond to a particle but still impacts the observable cross-section near threshold.  These cases illustrate how underlying singularities in the analytic structure of the scattering amplitude (poles and branch points in the complex  $s$ -plane) physically manifest as observable features—resonances, bound state divergences, or threshold cusps—in experimental scattering data. The analytic continuation concept is critical for understanding how such "hidden" (complex-plane) singularities influence real, measurable quantities due to the analyticity and real analytic properties of the amplitude.](2025-Lecture-09-images/fig14.png){#fig-fg14}

 




![This figure illustrates the analytic structure of the scattering amplitude  $A(s)$  in the complex  $s$ -plane, demonstrating the physical meaning of different singularities and cuts as discussed in the lecture. The real axis  $\mathrm{Re}(s)$  corresponds to physical kinematic values, with a branch cut (in magenta) starting at the threshold  $s > s_{\text{th}}$ , representing the onset of physical scattering (the unitarity or right-hand cut). The blue and green lines indicate different analytic domains or "sheets" of the amplitude.  The orange point above the real axis on the imaginary axis denotes a "bound state" pole, corresponding to a stable particle below threshold on the physical sheet. The orange point below the real axis, labeled "virtual state," represents a pole associated with an unstable or non-physical state (on the unphysical sheet). The orange crosses on the lower half-plane, labeled "resonances," represent poles associated with resonant states—unstable particles that manifest themselves as peaks in the cross section—on the second Riemann sheet ( $A^{II}(s)$ ).   The diagram also demonstrates how the amplitude  $A(s)$  behaves in various regions, showing the importance of analytic continuation and Riemann sheets: the physical amplitude is found on the first (physical) sheet, while resonances and virtual states manifest as poles on other sheets, accessible via analytic continuation across the cut. This structure encodes the complex analytic (and real analytic) nature of the scattering amplitude, the linkage of poles to observable physical phenomena, and the impact of branch cuts associated with multi-particle thresholds.](2025-Lecture-09-images/fig15.png){#fig-fg15}






All features in scattering, like bumps or cusps, are related to singularities in the complex plane.

### Branch cuts as doors to analytic continuation
Instead of viewing the cut location as arbitrary, think of defining a *different* function  $f_2$  that analytically continues the original  $f$  across the cut. For example, for a function with a branch point at  $0$  and a cut to the left, define  $f_2$  so that joining the two domains removes the cut. The original  $f$  and  $f_2$  agree on one side and differ on the other:
  $$f(z) = \begin{cases} f_1(z), & \operatorname{Im}(z) \geq 0 \\ f_2(z), & \operatorname{Im}(z) < 0 \end{cases}$$  
An explicit case is the logarithm:  $f_2 = \log z + 2\pi i$ . The branch point remains, but the function becomes analytic in the combined domain.

<hr>

<b>Q:</b> Shouldn't there be two branch cuts — one from  $1$  to  $-\infty$  and one from  $0$  to  $-\infty$ ?

<b>A:</b> You are referring to the function  $\sqrt{z-1}$ ? If the function has a minus sign (i.e.,  $\sqrt{z-1}$  with a single cut), there is only one cut from  $1$  to  $-\infty$ . If, instead, the function is a product like  $\sqrt{z(z-1)}$ , the cut runs from  $0$  to  $1$ , not two separate cuts. For any function with a cut, one can define an analytic continuation  $f_2$  across that cut, often by introducing a minus sign or a  $2\pi i$  shift.



## Riemann Sheets and Analytic Continuation of Square Root and Logarithm

### Riemann Sheets and Analytic Continuation

Instead of defining separate functions  $f_1, f_2, f_3$  on different Riemann sheets, one can speak of a single **multivalued function** whose values differ from sheet to sheet.  This is equivalent to saying:

  $$f(z) = \begin{cases} f_1(z), & \operatorname{Im}(z) \ge 0 \\ f_2(z), & \operatorname{Im}(z) < 0 \end{cases}$$  

For a give branch point, the analytic continuation onto a new sheet is determined by how the function behaves when crossing the branch cut.

<hr>

### Examples: Square Root and Logarithm

The relation between the first two sheets is known for common functions:

| Function | Relation between  $f_2$  and  $f_1$  | Comment |
|----------|--------------------------------------|---------|
|  $\sqrt{z-1}$  |  $f_2 = -f_1$  | The second sheet is the negative of the first. |
|  $\log z$     |  $f_2 = \log z + 2\pi i$  | The second sheet adds  $2\pi i$ . |

For  $\log z$ , the values just above and below the branch cut (e.g., at  $z = -1$ ) differ by  $2\pi i$ :

  $$\log(-1 + i\epsilon) = +\pi i, \qquad \log(-1 - i\epsilon) = -\pi i.$$  

Adding  $2\pi i$  to the lower-side value gives the upper-side value:

  $$(-\pi i) + 2\pi i = +\pi i,$$  

so  $f_2$  indeed continues analytically to the sheet above the cut.

<hr>

### Labeling of Sheets

Why is the continued function called Sheet 2 and not Sheet 3?  **The numbering is arbitrary**; it depends on the chosen labeling convention.  One may call the function continued from above  $f_2$  and the one from below  $f_3$ , or vice versa — the notation is up to the user.



## Real Analyticity and the Schwarz Reflection Principle in Scattering Amplitudes

#### Real Analyticity and Scattering Amplitudes (see @fig-fg6) 




![This figure illustrates the concept of real analyticity for complex functions in the context of scattering amplitudes. The shaded segment along the real axis represents the domain where the function  $f(z)$  is real. When moving away from this segment into the complex plane (either above or below the real axis), the function develops an imaginary part: moving upward in the imaginary direction leads to a positive imaginary component, while moving downward results in a negative imaginary part. This behavior reflects the Schwarz reflection principle, which states that the value of the function at a point and its complex conjugate are related such that  $f(z^*) = f^*(z)$ . Physically, this underpins the analytic properties of scattering amplitudes and ensures that discontinuities across cuts in the complex plane are purely imaginary, as discussed in the lecture.](2025-Lecture-09-images/fig7.png){#fig-fg7}






<b>Real analyticity</b> is an aspect closely related to the scattering amplitude. A real analytic function is analytic and real on a segment of the real axis. In an extended definition, a function is called real analytic if it has a segment along the real axis where it is real.

Consider the complex  $z$ -plane with the real axis. If  $f(z)$  is computed for real  $z$  and yields a real value, the function has a peculiar property: it satisfies the **Schwarz reflection principle**. The function is real on that segment. Analyticity is a special type of continuity — once you move away from the real axis, an imaginary part must appear. The function cannot stay real away from the axis. If the imaginary part develops in the positive direction when moving upward from the real axis, it must become negative when moving downward.

The Schwarz reflection principle states:

  $$f(z) = f^*(z^*)$$  

where the star denotes complex conjugation (which flips the imaginary part).

<hr>

If you perform analytic continuation of a function that is real on a segment, the only way for the function to stop being real on the real axis is to encounter a **branch point**. The function along the real axis is real on a segment and only becomes non‑real once the branch point is introduced. The only way to obtain an imaginary part is to have a branch point and a cut. The imaginary part on one side of the cut is positive; on the other side it is negative. Therefore, the discontinuity around the cut is twice the imaginary part (since they develop in opposite directions). This corresponds to the **second lowest threshold opening**.

There is no notion of the size of the segment; any segment along the real axis is either open or closed. Analytic functions always have an open domain. As soon as you include one of the edges, you cannot place a small circle around it and still say the function is smooth. Points such as  $s - i\epsilon$  are included in the domain.

<hr>
Scattering amplitudes are examples of real analytic functions. Analyticity forces them to be real analytic. (see @fig-fg2) For  $2\to2$  scattering, the amplitude  $A(s,t)$  is a function of the Mandelstam variables. (see @fig-fg3) On the Mandelstam plane there are  $s$ -,  $t$ -, and  $u$ -channel scattering regions. (see @fig-fg4) If  $t$  is fixed to a physical value (e.g., corresponding to 30° scattering), then  $A$  becomes a function of  $s$  only. (see @fig-fg5) In the complex  $s$ -plane,  $A(s)$  has thresholds corresponding to the opening of the  $s$ -channel and the  $u$ -channel. (see @fig-fg9) There is a domain where the function is real. (see @fig-fg12) Once the function has a real segment along the real axis, the Schwarz reflection principle applies. (see @fig-fg14) (see @fig-fg15)

The discontinuity around a cut can be related to the imaginary part, connecting to **unitarity**. (see @fig-fg8) Unitarity constrains the discontinuity around the unitarity cut: (see @fig-fg10)

  $$A(s+i\epsilon,t) - A(s-i\epsilon,t) = \int d\phi \, A(s-i\epsilon,t') A(s+i\epsilon,t')$$  

The discontinuity is  $A(s+i\epsilon) - A(s-i\epsilon)$ , not involving a complex conjugate. The proof of this relation exists for general scattering, is valid at any order in perturbation theory, and generalizes to any scattering.

| Concept | Equation | Notes |
|---------|----------|-------|
| Schwarz reflection principle |  $f(z) = f^*(z^*)$  | Function real on a segment implies this symmetry. |
| Discontinuity from unitarity |  $A(s+i\epsilon,t) - A(s-i\epsilon,t) = \int d\phi \, A(s-i\epsilon,t') A(s+i\epsilon,t')$  | Relates cut discontinuity to unitarity integral; no complex conjugate. |

<hr>
Analyticity — considering the amplitude as a complex function of its variables — gives extra constraints and helps understand the origin of bumps (peaking behavior) along the real axis. By examining the complex plane, you find branch points that appear along the real axis. (see @fig-fg1) They are responsible for **kinks** in the amplitude: the derivative does not exist at the branch point. The function does not go to infinity but has a kink.

Once a spike appears, you can investigate its origin. Likely there is a pole somewhere. Beneath the cut, by constructing an analytic continuation (e.g.,  $F_2$ ), you find that a pole may cause the function to spike at a certain threshold. This is possible not by rotating cuts but by considering what other functions are analytic.



## Coupled Channels in Scattering Amplitudes

### Scattering Channels and Coupled Channels

A **scattering channel** is the subsystem of particles that can appear in the initial or final state and that can scatter into each other. Scattering is considered in the space of these channels.

For example, the following channels belong to the same scattering problem:

| Scattering Problem | Channels |
|--------------------|----------|
| Meson–Meson        |  $\pi\pi$ ,  $KK$ ,  $\eta\eta$  |
| Baryon–Kaon        |  $\Lambda K$ ,  $\Xi\pi$  | (see @fig-fg13)

All channels within a scattering problem can scatter to each other. They are labeled by indices such as  $a, b, c$  and are called **scattering channels**.

When two or more channels can transform into each other, we speak of **coupled channels**. For instance,  $\Lambda K$  and  $\Xi\pi$  are coupled: in the complex plane of the scattering amplitude, branch points appear for each coupled channel. The scattering problems of these channels are not isolated but coupled.


::: callout-important
Causality implies analyticity, which forces the amplitude to be **real analytic**. This means the only allowed singularities are poles and cuts on the real axis.
:::

Because the channels are coupled, the amplitude for  $\Xi\pi \to \Xi\pi$  is connected to the amplitude for  $\Lambda K \to \Lambda K$  and also to the crossing amplitude  $\Xi\pi \to \Lambda K$  in the energy (or  $S$ -) plane. Consequently, branch points arise for each coupled channel.

Once one moves away from the elastic region, more scattering possibilities appear. In the unitarity equations, for a given process there is not just one term (e.g.,  $A^* A$ ) but several terms, each corresponding to a different coupled channel.



## Complex Angles and Analytic Continuation in Multi-Variable Scattering

### Singularities, Causality, and Analytic Structure (see @fig-fg1) (see @fig-fg14)

The complete plane does not allow any singularities; the cut is not allowed to go upwards. (see @fig-fg6) This is the only configuration allowed.

<b>Q:</b> Is that because I had to determine the location of the poles or just the fact that the function is analytic?
<b>A:</b> The function must be analytic everywhere in the complex plane away from the real axis. That is what causality tells us.

This seems more like a tool. In the end you are describing physics effects. The answer comes from probability considerations. Causality appears a decent thing: actions come afterwards. Causes come after actions. This is always true because you use **microcausality**. (see @fig-fg2) (see @fig-fg3) (see @fig-fg4) (see @fig-fg5) (see @fig-fg9) (see @fig-fg15)

With this hypothesis you get dislocated regions (branch cuts), but then you complexify them. You also mentioned complex scattering — that would mean making  $t$  complex as well. You can relate all these regions. I think I like that background. The introduction in Martin's experiment says this is an interrelated object; different amplitudes look different but are all connected? They are different.

<hr>

<b>Q:</b> Why do you say the angles are complex? I didn't see this complexity.
<b>A:</b> The function is a complex function of two variables.  $t$  is almost an angle — it depends on the angle. Both variables  $s$  and  $t$  could be complex.

<b>Q:</b> How does causality act in the multi‑variable case? How does it lead to electricity? I don't understand that. But on a larger level, how does this work in multi‑dimensional energy space?
<b>A:</b> From two dimensions you go to four dimensions because  $s$  becomes complex and  $t$  becomes complex. Then instead of a domain of real analyticity with a segment of real, you need a domain where the function is real. That domain exists; we demonstrated it.

<hr>

### Branch Points and Thresholds

For fixed  $t$  negative (in a scattered region), the distance between two branch points is controlled by  $t$ . As you change  $t$ , the branch points get closer together. In a slice of the complex  $s$ ‑plane, a region appears where they overlap, and there is no longer any segment of real analyticity. But because for different  $t$  there is a segment, you can use analytic continuation to go into the overlapping domain.

<b>Dialogue on threshold motion:</b>

| Branch point | Behavior |
|--------------|----------|
|  $(m_1+m_2)^2$  | **Fixed** – this is the threshold for the  $s$ ‑channel. |
|  $(m_1-m_2)^2$  | **Moves** with  $t$ . |

<b>Q:</b> How can they be different if you move  $t$ ? Shouldn't these be two points where you cross the border of the channels?
<b>A:</b> Absolutely not. The question is why they move when you move  $t$ . The  $s$ ‑channel expression changes for this channel? It will not. I think this one should move, but I don't see it now. Why? Because  $(m_1+m_2)^2$  stays — it's always that threshold, it's fixed. The other one moves. I'm having a hard time seeing this now.

The function  $g(s)$  encoding the thresholds is:

  $$g(s)=\frac{\sqrt{s-(m_1+m_2)^2}\,\sqrt{s-(m_1-m_2)^2}}{s}$$  

where  $(m_1+m_2)^2$  and  $(m_1-m_2)^2$  are the branch points.

<hr>

### Optical Theorem and Unitarity

<b>Q:</b> More questions? I'm still thinking about the optical theorem you were saying, but I don't want to.
<b>A:</b> Let's discuss with you, because you have more questions concerning the P2L non‑zero  $p$  in. Depends what it is for. But go to that file. It's important.

<b>Q:</b> Is it this? Unitarity. Now how to get to the amplitudes?
<b>A:</b> It's like the separators. You get, say,  $B$  to  $A$ , and then you have the transition matrix. That equals a matrix element because these do not know about each other. It depends on whether this is a basis. It's always confusing that you can say intermediate states, but with the help of Chad. (see @fig-fg11) I want to stop now.


::: callout-note
The discussion on thresholds highlights that one branch point is fixed ( $(m_1+m_2)^2$ ) while the other moves with  $t$ , which is crucial for analytic continuation in the Mandelstam variables.
:::



## Optical Theorem Derivation and Unitarity

<b>Q:</b> Is it a dagger?
<b>A:</b> No, it is the  $T$  dagger.

<b>Professor:</b> We are looking at the identity

  $$A(s+i\epsilon, t) - A(s-i\epsilon, t) = \int d\phi \, A(s-i\epsilon, t') A(s+i\epsilon, t')$$  

I am trying to derive the left‑hand side and right‑hand side, essentially squeezing in this. I wanted to check the right‑hand side integrated over centre‑of‑mass time — where does it come from?

<b>Professor:</b> It comes from the identity above.

<b>Q:</b> So this identity is a shorthand for continuous states. Now I start to see the optical theorem appearing in this form. The object you wrote — the red star — becomes the  $A$ , and the  $T$  operators come from exactly there. That means on the left‑hand side there is something like a factor of two? But what do we do with that? Oh, that is important because this is not phase space; it is just a differential. The  $T$  operator gives a  $\delta^4$  function, and the identity gives the product of the same  $\delta^4$  functions. Then the left‑hand side and right‑hand side have this differential structure. So the left side has two terms that cancel and yield the basis.

<b>Professor:</b> Then you can wrap the whole thing into a partial wave expansion — that is the next step.

<b>Q:</b> So the optical theorem is first referred to as the cross‑section optical theorem. But I was surprised to see that the generalized optical theorem comes from Heisenberg, and it is exactly this form. It is derived from unitarity, which is what we are doing here. That is good to know. I fake to get this diagram — now that disappears. Why do we have the intermediate state? That whole intermediate state was confusing because I thought, why are we sending to about resonances here? Does this also need a differentiation of carry effectors? Let us go through this. I can vaguely understand that this leads to the spatial spectrum — it means if you reformulate in terms of  $S$ . But let us assume this: you can write the space‑parameters thing. The way you proceed is to say that the amplitude is  $\tilde{A}$  times  $p^L$  — this is called singularity‑free. You said it is a mathematical argument. Did you say you want to suppress the general volume of  $x$ ? I do not really see that it has to be there, but mathematically speaking you still have this factor.

<b>Professor:</b> If you follow the BDG section, this factor shows up here for the less competitive  $P$ . Let us put the key to 12 and then have the imaginary part of the amplitude delta. More elements square it.


::: callout-note
The central identity used to derive the optical theorem is
  $$A(s+i\epsilon, t) - A(s-i\epsilon, t) = \int d\phi \, A(s-i\epsilon, t') A(s+i\epsilon, t')$$  
It is a direct consequence of unitarity.
:::

| Object | Role in the derivation |
|--------|------------------------|
|  $T$  operator | Gives a  $\delta^4$  function in the differential structure |
|  $\delta^4$  function | Ensures the left‑ and right‑hand sides have matching differential figures |
| Intermediate state | Appears in the product of amplitudes; its presence was initially confusing because it suggests resonances |
| Partial wave expansion | Next step: wrap the identity into a partial‑wave decomposition |

The generalized optical theorem is derived from unitarity, and it takes the form shown above. The student’s initial confusion about intermediate states is clarified: they are not necessarily resonant states — the identity holds for any intermediate state consistent with unitarity.

The expression  $\tilde{A} \, p^L$  is called singularity‑free; it is a mathematical ansatz that suppresses the volume of  $x$  (though the need for that factor may not be obvious).

