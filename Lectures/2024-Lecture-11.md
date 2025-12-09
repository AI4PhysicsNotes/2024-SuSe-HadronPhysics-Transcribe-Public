---
title: (2024) Lecture 11
author: ''
presenter: Mikhail Mikhasenko
note_taker: Anna Zimmer
date: '2024'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



## Analytic Mapping and Lattice QCD Fundamentals

### Lecture 11: Analytic Structure, Chiral Dynamics, and Lattice QCD

### **Recap: Scattering Amplitudes and Analytic Structure**

So far, we have discussed the scattering amplitude as a function of the Mandelstam variable  $S$ , which is defined as:
  $$S = (P_1 + P_2)^2$$  
This variable  $S$  is the squared center-of-mass energy and is very convenient for describing the partial wave expansion of the amplitude.


::: callout-note
**Mandelstam Variable  $S$ :** This is the primary Lorentz-invariant variable used to describe the energy in a two-particle scattering process.
:::




![This figure illustrates the relationship between the analytic structure of the scattering amplitude in the Mandelstam variable  $S$  (the  $S$ -plane) and the breakup momentum  $K$  (the  $K$ -plane), as discussed in the lecture.  - The **top left and center panels** show the  $S$ -plane on two Riemann sheets:   - **First Sheet (left)**: The real axis above the two-particle threshold ( $S > (m_1 + m_2)^2$ ) represents the physical scattering region. There is a bound state pole (labeled 4) on the real axis below threshold, corresponding to a stable composite particle. The thick, shaded line on the cut indicates the branch cut beginning at threshold.    - **Second Sheet (center)**: Important features like resonances (points 1 and 2) appear off the real axis on the second sheet, along with a virtual state (point 3) below threshold. The branch cut is present here as well, representing the analytic continuation through the physical cut.  - The **top right panel** displays the corresponding  $K$ -plane. Here,  $K$  is the breakup momentum and is related to  $S$  via  $K = \sqrt{(S - (m_1 - m_2)^2)(S - (m_1 + m_2)^2)}/(2\sqrt{S})$ . The analytic structure becomes simpler: the two Riemann sheets of the  $S$ -plane are mapped onto a single  $K$ -plane. All physical and unphysical regions are now unified, branch cuts become lines on the imaginary  $K$  axis, and singularities (poles) are points in the complex  $K$ -plane.  - The **bottom portion** of the figure gives the explicit formula for  $k$  in terms of  $S$ , and shows how the mapping works:   - Different types of singularities—resonances (1,2), virtual state (3), and bound state (4)—are shown as points in the  $K$ -plane. The real  $K$  axis corresponds to the physical scattering region ( $S > (m_1+m_2)^2$ ), while the imaginary  $K$  axis represents energies below threshold.  **Physical meaning:**   This mapping clarifies the analytic structure of scattering amplitudes, especially near threshold. The complicated two-sheet structure of the  $S$ -plane, featuring square root branch cuts and multiple types of poles (bound states, virtual states, resonances), is transformed into a single, continuous  $K$ -plane. Here, analytic continuation and the connections between different physical situations (such as how a bound state can evolve into a virtual state or a resonance) become manifest. This is crucial for understanding finite-volume effects in lattice QCD, resonance dynamics, and the analytic properties of strong-interaction amplitudes.](2024-Lecture-11-images/fig1.png){#fig-fg1}

 




![This figure represents the analytic structure of the scattering amplitude in the context of two-particle scattering. The horizontal line symbolizes the real axis of the Mandelstam variable  $S$  (or energy, equivalently), marking the threshold for particle production. The vertical line emanating from the threshold point illustrates the branch cut associated with the square root behavior near the two-particle threshold, which is related to the breakup momentum  $K$  discussed in the lecture. The diagram indicates the mapping between the  $S$ -plane and  $K$ -plane, with the threshold  $S = (m_1 + m_2)^2$  corresponding to  $K=0$ , and the physical region lying just above this threshold. The small circles or arcs may denote the movement around the branch point to different Riemann sheets—representing the physical (first sheet) and unphysical (second sheet) regions where resonances, bound states, and virtual states may occur, as discussed when mapping the analytic structure from  $S$  to  $K$ .](2024-Lecture-11-images/fig2.png){#fig-fg2}






Equivalently, one can consider the **breakup momentum  $K$ **, which is essentially the magnitude of the momentum each particle carries in the center-of-mass frame. The variable  $K$  is related to  $S$  via the kinematic function:
  $$k = \frac{\sqrt{(s - (m_1 - m_2)^2)(s - (m_1 + m_2)^2)}}{2\sqrt{s}}$$  
The analytic structure of the amplitude is often simpler when expressed in terms of  $K$ , particularly near the reaction threshold.


::: callout-tip
**Breakup Momentum  $K$ :** Using  $K$  instead of  $S$  can simplify the analytic structure near threshold ( $S \approx (m_1 + m_2)^2$ ), as it "unfolds" the square root branch point present in the  $S$ -plane.
:::

I would like us to now map the analytic structure from the  $S$ -plane to the  $K$ -plane. Specifically, we need to understand how key features—such as resonances on the second Riemann sheet (points 1 and 2), a bound-state pole on the real axis of the first sheet (point 4), and a virtual state on the unphysical sheet below threshold (point 3)—are represented in the  $K$ -plane.

The real  $S$  axis above threshold corresponds to the physical scattering region. When mapped to the  $K$ -plane, this region remains physical. The threshold  $S = (m_1+m_2)^2$  maps to  $K=0$ . Below this threshold,  $S$  is real but  $K$  becomes purely imaginary because the expression under the square root becomes negative.


::: callout-important
**Mapping Riemann Sheets:** The two Riemann sheets in the  $S$ -plane, related by the sign of the square root  $\sqrt{s - (m_1+m_2)^2}$ , both map onto the **single**  $K$ -plane. The plus and minus signs for  $K$  are already part of the same complex plane. This is why the  $K$ -plane has a simpler, single-sheeted structure.
:::

The key insight is that the  $K$ -plane is just an analytic mapping of the  $S$ -plane. If you have a function with a square root branch cut in  $S$ , it has two Riemann sheets. By using the variable  $K$ , which is essentially that square root, you work on a single sheet. The two-sheeted structure of the  $S$ -plane can be understood as arising from the squaring operation  $S \propto K^2$ , which maps the single  $K$ -plane onto the two sheets of the  $S$ -plane.

### **Transition to QCD and Confinement**

Now, let's transition to discussing Quantum Chromodynamics (QCD) and the phenomenon of confinement. The fundamental degrees of freedom in QCD are quarks and gluons. However, in the low-energy regime we observe composite particles like protons and pions—this is the signature of confinement.


::: callout-note
**Confinement vs. QED:** In Quantum Electrodynamics (QED), the coupling constant is small:  $\alpha_{\text{QED}} = e^2/(4\pi) \approx 1/137$ . This allows us to use perturbative expansions with Feynman diagrams. In contrast, the QCD coupling  $\alpha_s$  becomes large at low energies, leading to the non-perturbative, confining regime where quarks and gluons are bound into hadrons.
:::

At low energies, the appropriate effective theory is **Chiral Perturbation Theory**. This is not an expansion in a small coupling constant, but rather in the small masses and momenta of the particles (pions). The theory is built on the concept of **spontaneous chiral symmetry breaking**.


::: callout-important
**Spontaneous Symmetry Breaking and the Quark Condensate:** The order parameter for chiral symmetry breaking is the **quark condensate**, denoted  $\langle \bar{q} q \rangle \neq 0$ .
:::




![This image illustrates the "Mexican hat" or "wine bottle" potential, which is used to depict spontaneous chiral symmetry breaking in QCD. The horizontal axis is labeled  $\sigma$ , corresponding to the sigma field (magnitude of the quark condensate), while the radial direction along the rim is associated with the  $\pi$  (pion) fields, representing the Nambu-Goldstone bosons.  The minimum of the potential forms a circle in field space, and the vacuum selects a particular point on this circle, breaking the chiral symmetry. Excitations along the rim (fluctuations in the direction of the arrow labeled  $\pi$ ) correspond to nearly massless pions, due to the flatness (zero curvature) in these directions—these are the Goldstone modes. Fluctuations in the  $\sigma$  direction (vertical upward arrow) are associated with the  $\sigma$  particle and correspond to oscillations in the magnitude of the quark condensate, which are massive due to the curvature of the potential at the minimum.  This physical picture, directly discussed in your lecture notes, shows how the vacuum expectation value of the quark condensate gives rise to massless Goldstone bosons (pions) and a massive  $\sigma$  resonance, visualized as classical averaged fields in the Mexican hat potential.](2024-Lecture-11-images/fig3.png){#fig-fg3}




 This means the QCD vacuum is filled with a non-zero expectation value of quark-antiquark pairs. The potential for the associated sigma field has a "Mexican hat" shape, and the vacuum settles into one point in the minimum, breaking the symmetry.

In this picture:

*   The **sigma ( $\sigma$ ) field** corresponds to the fluctuating magnitude of the condensate. Its mass is related to the curvature of the potential at the minimum.
*   The **pion ( $\pi$ ) fields** correspond to fluctuations along the "flat" directions of the potential (the rim of the Mexican hat). In the ideal chiral limit (massless quarks), these directions have **zero curvature**, meaning the pions are **massless Goldstone bosons**.


::: callout-tip
**Goldstone Boson Mass Relation:** When small quark masses  $m_q$  are introduced, they explicitly break the chiral symmetry, giving the pions a small mass. This is described by the Gell-Mann–Oakes–Renner relation:
  $$m_\pi^2 \propto m_q \langle \bar{q} q \rangle$$  
:::

A common point of confusion concerns the proton mass. If pions are (nearly) massless Goldstone bosons, why is the proton heavy? The proton is not a Goldstone boson. Its mass, like that of most hadrons (e.g., the rho meson), is generated dynamically by the confining quark-gluon interactions and is of the order of the QCD scale  $\Lambda_{\text{QCD}} \sim 1$  GeV. The proton mass remains significant even in the chiral limit where quark masses are zero.
### **Introduction to Lattice QCD** 




![This figure represents the discretized spacetime "box" used in Lattice QCD calculations. The physical meaning of the image is the finite four-dimensional grid (lattice) on which quark and gluon fields are defined. The spatial extent of the box is labeled  $L$ , highlighting the periodic boundary conditions that lead to quantization of momenta ( $p = 2\pi n / L$ ) for particles within the box. This finite, periodic volume introduces **finite volume effects** and causes the particle spectrum to become discrete, which is crucial for calculating correlations and extracting particle properties (such as masses and phase shifts) from first-principles QCD. The figure visually encodes the main systematic effects discussed in the lecture: finite volume and discretization, both central to interpreting results from lattice QCD.](2024-Lecture-11-images/fig4.png){#fig-fg4}






To study QCD from first principles, we use **Lattice QCD**. This is a non-perturbative method where spacetime is discretized onto a four-dimensional grid (a lattice). Typical lattices might have a spatial extent of ~7 fm divided into 50 points per side, and a temporal extent of ~200 points.


::: callout-caution
**Two Main Systematic Errors:**

1.  **Finite Volume Effects:** The lattice has a finite size  $L$ . Physical quantities (like masses) approach their infinite-volume values with corrections that are **exponentially suppressed**:  $\Delta m \propto e^{-m_\pi L}$ .
2.  **Discretization Errors:** The lattice spacing  $a$  is finite. Results must be extrapolated to the continuum limit ( $a \to 0$ ). Computations are therefore repeated at several lattice spacings to control this error.
:::

The primary quantities computed on the lattice are **correlation functions**. For an operator  $\mathcal{O}$  that creates a state of interest (like a pion), the Euclidean correlation function is:
  $$C(t) = \langle 0 | \mathcal{O}(t) \mathcal{O}^\dagger(0) | 0 \rangle$$  


::: callout-note
**Wick Rotation:** To make the path integral weight real and positive for efficient Monte Carlo sampling, we work in **Euclidean spacetime**. This replaces the Minkowski action  $e^{iS_M}$  with  $e^{-S_E}$ .
:::

This correlation function has a spectral decomposition:
  $$C(t) = \sum_n |\langle 0 | \mathcal{O} | n \rangle|^2 e^{-E_n t}$$  
At large time separations  $t$ , the sum is dominated by the ground state (lightest particle with the quantum numbers of  $\mathcal{O}$ ), because excited states are exponentially suppressed by  $e^{-(E_n - E_0)t}$ .


::: callout-tip
**Extracting the Ground State Mass:** To extract the mass  $m = E_0$ , we compute the **effective mass**:
  $$m_{\text{eff}}(t) = -\ln \left( \frac{C(t+1)}{C(t)} \right)$$  
At sufficiently large  $t$ ,  $m_{\text{eff}}(t)$  will plateau at the value of the ground state mass.
:::

The lattice calculation itself involves evaluating a path integral with an astronomically high number of dimensions. This is done via **Monte Carlo integration**, where field configurations are sampled with a probability proportional to  $e^{-S_E}$ . The correlation functions are then averaged over these sampled "ensembles" of configurations.

This concludes our introductory overview. Lattice QCD is a vast and technically rich field, but these principles form the foundation for extracting hadron masses, decay constants, and other non-perturbative quantities directly from QCD.



## Periodic Boundaries and Spectral Shifts in Lattice Systems

We are already over time, but it's important to note that the homework exercise today is to realize that a particle in a box is slightly different from a particle in this space.

Due to the periodic boundary condition, you have a quantization of the momentum. If your wave function is  $e^{i p x}$ , and you require that  $\psi(x + L) = \psi(x)$ , you immediately realize that  $p L$  must be  $2 \pi n$ . In order for this to match, the power of the exponential should be  $n$  times  $2 \pi i$ .

The momentum of particles is quantized and can only take values in discrete steps proportional to  $1/L$ :
  $$p = \frac{2\pi n}{L}, \quad n \in \mathbb{Z}$$  

Therefore, if you consider a two-particle system, it has a discrete spectrum. This is the periodic boundary condition.

You can think of two particles moving in a circle of length  $L$ . The physics of the one-dimensional case of this box computation would be a circle, and the spectrum is discrete. (see @fig-fg4)
In that case, you see that I just simply add the energy. The total energy of the system is equal to the sum of the individual particle energies:
  $$E_{\text{total}} = \sum_i E_i$$  
The particles are freely moving; they don't interact.

It appears that once they interact, the energy of the system is slightly different. So we can still write the energy as a sum, but then one has to take into account the interaction energy.

It's natural that once you compute the spectrum of an interacting system, your spectrum is going to be slightly different. So there is a shift due to interaction. That's the idea of computing interaction on the lattice and doing spectroscopy.

You compute the spectrum in the absence of interaction. You compute the spectrum when interactions are present, and you see how different the levels are from each other. That gives you information about the particles, essentially the **phase shift** of the interaction.

So you compute the two-point correlator:
  $$C(t) = \langle \mathcal{O}(t) \mathcal{O}^\dagger(0) \rangle$$  
You compute such a quantity for two pions. 




![This figure represents the behavior of a two-point correlation function,  $\tilde{C}(t)$ , as a function of Euclidean time  $t$  in a typical Lattice QCD computation. Physically, this correlator describes the probability amplitude for a quantum state—created by some operator  $\mathcal{O}$  at time  $0$ —to be annihilated at a later time  $t$ , as measured on the lattice.  The curve shows an exponentially decaying function, which corresponds to the spectral decomposition:   $$C(t) = \sum_n |\langle 0 | \mathcal{O} | n \rangle|^2 e^{-E_n t}$$   At large  $t$ , the dominant contribution comes from the ground state (lowest energy  $E_1$ ), with excited states ( $E_2$ ,  $E_3$ ,...) becoming exponentially suppressed. The vertical lines at discrete time points illustrate that lattice calculations are performed only at certain values of  $t$  (due to discretization into  $a_t$  points).  This plot emphasizes how, by analyzing the large- $t$  behavior ("plateau") of the effective mass or the correlator, one can extract the energy/mass of the ground state and learn about the excited states in the system. The stacked energies  $E_1, E_2, ...$  at the right margin represent this discrete spectrum resulting from the finite volume and lattice discretization.](2024-Lecture-11-images/fig5.png){#fig-fg5}




 You see where it separates at high energy, where it saturates.

Where this correlator function saturates at a large value of  $t$ , you have a measurement of this energy level. Now you do the same computation for the interacting system. You find the energy of the interacting system, and then you compare the two to find the shift.

You relate the shift to the scattering phase shift:
  $$\Delta E \propto \delta(p)$$  
The way to compare with the answer is by using another kind of technique. You always give them in configuration space or real values of the wavefunctions.


::: callout-note
In lattice QCD, the two-point correlation function is used to extract energy levels. At large Euclidean time  $t$ ,  $C(t) \sim e^{-E t}$ , where  $E$  is the ground-state energy. Comparing interacting and non-interacting spectra yields energy shifts, which are related to the scattering phase shift via finite-volume formulas like the **Lüscher formula**.
:::

This is the last QCD lecture. I invite you to the full lectures if someone offers them; it's a fascinating subject. In recent years we have learned so much about the hadron spectrum from the lattice.

That's amazing. The treatment on the lattice has the rather isolated setup where there are no experimental effects. You can really do things you cannot imagine doing in an experiment.

You can scatter two pions. You can still scatter two pions in an experiment, but scattering, for example, a photon on a sigma meson, you can never do in an experiment. On the lattice, this is a problem that people start discussing.

You have a 2-pion sigma meson; the sigma meson is the  $\pi\pi$  S-wave. This is one of the tetraquark candidates at low energy that sits in the spectrum that people observe as a broad resonance.

What you can do is consider  $\pi\pi$  scattering, insert a current (the photon), and compute the correlation function to construct the object that gives access to such a form factor.

This in turn gives you access to the spatial distribution of how inside these mesons the quarks and gluons are arranged. One of the exciting frontiers of lattice QCD is understanding what hadrons look like when you insert a current.

You can see how quarks and gluons are distributed in the space that you can access. You can't do that with pure QED because there you just have electromagnetic states, and you cannot look at the quarks directly.

You cannot compute the form factors in that way. You do not have a way to fix low-energy constants. Some people doing Lattice Perturbation Theory (LPT) might object, but I'm not aware of a way of doing that.

Also, in experiments for these low-lying resonances, you produce them in some process with stable particles. You only have access to the production amplitude, for example, from a pion and a proton target.

We have a production amplitude and constraints—unitarity constraints that we discussed are much stronger on the scattering amplitude and the elastic amplitudes. Last time I wrote a matrix element on the board in the recap.

Some of you said, "Oh wait, shouldn't the imaginary part be positive because of the unitarity relation?" This is about the scattering amplitude. The constraints are very severe. You cannot just take a random number and put it in for the elastic scattering amplitude.

The amplitude should lie inside the unitary circle. If the scattering is purely elastic, it should be on the circle; it cannot be outside. The imaginary part is always positive:
  $$\text{Im}\, \mathcal{M} \geq 0$$  

On the lattice, you can access this quantity, to which you have a strong constraint. Elastic amplitudes like  $\pi \pi \to \pi \pi$ ,  $\pi \pi \to K K$ ,  $\pi K \to K \pi$ ,  $\eta \pi \to \eta \pi$ . You can do all this, plus you have a handle on the quark masses.

*   You can now make your pions massless.
*   You can make them massive.
*   What changes significantly is the region where the amplitude is elastic.

When the pion mass is zero, you have a  $\pi$  threshold. So the 2-pion, 3-pion, and 5-pion thresholds are at the same point. But once you move and make pions heavy, you realize that a large area opens where the 2-pion threshold is open, but the 3-pion or 4-pion thresholds are not yet open.

There is a large area of elastic scattering where all your constraints from unitarity give you an almost parameter-free parameterization. Then you can learn a lot of physics.

Moreover, by moving masses you can make your particles transit in the complex momentum ( $K$ ) plane. We started our lecture by seeing where resonances could be located in this  $K$  plane. There are analytic, smooth connections between different regimes.

By moving these quark masses, you can make your particle transition from a bound state to a resonance, effectively traveling in the whole plane. That's something amazing that tells you all these phenomena are closely connected.

A bound state, a virtual state, a resonance—these are all different manifestations of states in QCD. Depending on the quark mass, one could become another.

I hope you're going to like the exercise sheet that was kindly prepared and printed. It was prepared last night and printed. Thank you very much for being here, for coming today, and sorry for being a little bit overtime. Well done.

