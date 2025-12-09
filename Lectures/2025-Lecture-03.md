---
title: (2025) Lecture 3
author: ''
presenter: Mikhail Mikhasenko
note_taker: Anna Zimmer
date: '2025'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



## Lecture Outline: Hadron Structure and Symmetry

Today we have lecture number three. 




![This image schematically represents the internal structure of a hadron, such as a proton, as discussed in the lecture. The large enclosing circle denotes the finite spatial extent of the hadron, indicating that it is **not point-like**. Inside the hadron, the three smaller circles represent its constituent **quarks** (e.g., two up quarks and one down quark in a proton), in line with the **quark model**. The lines connecting the quarks symbolize the strong interaction, or the color force, mediated by gluons that confine the quarks within the hadron. This visualization is physically meaningful because it illustrates how scattering experiments reveal that the proton has an **internal structure** and a spatial **charge distribution**. The existence of form factors in scattering cross sections, introduced in the lecture, is direct evidence of this composite, extended nature rather than a point-like particle. The drawing thus encapsulates the key idea that hadrons are quantum systems with substructure, as probed by high momentum transfer ( $Q^2$ ) processes.](2025-Lecture-03-images/fig7.png){#fig-fg7}






We will follow the consideration of the symmetry from the last lecture, but also look more carefully at what we know about the structure of hadrons, how they look inside, and what are the actual experimental evidences that they are **not point-like**, that they're made of quarks.

### **Lecture Plan & Key Topics**

We will go through this list of topics:

1.  **Kinematics and Cross Sections:** Starting with the calculation of cross sections and multibody kinematics.
2.  **Classical Scattering:** A simple classical scattering model of an electron and a proton.
3.  **Form Factors:** Discussing the form factors that appear in scattering, and how they relate to hadron properties like charge distributions and magnetic moments.
4.  **The Quark Model:** Discussing these quantities assuming hadrons are made of quarks, and relating experimental distributions to internal structure.
5.  **Symmetry Considerations:** Returning to flavor and spin symmetry from the last lecture.
6.  **Proton & Neutron Wavefunctions:** Examining the proton and neutron spin and flavor wave functions.
7.  **Magnetic Moments:** Computing the magnetic moment in the quark model and relating it to our observables.

That's the plan, which hopefully gives a little bit of structure to the detailed discussion we are going to have.

### **1. From Classical to Quantum Scattering**

I will start with the kinematics and something very fundamental: the calculation of cross sections. We begin with a simple classical picture of electron-proton scattering.

For a point-like target like a proton, the differential cross section is given by the **Rutherford formula**:
  $$\frac{d\sigma}{d\Omega} = \left( \frac{Z_1 Z_2 e^2}{4E} \right)^2 \frac{1}{\sin^4(\theta/2)}$$  
This describes scattering via a Coulomb potential, assuming **no internal structure**.

However, for relativistic spin-1/2 particles like electrons, we use the **Mott cross section**, which adds a spin-relativistic correction:
  $$\frac{d\sigma}{d\Omega}_{\text{Mott}} = \left(\frac{d\sigma}{d\Omega}_{\text{Ruth}}\right) \left(1 - \beta^2 \sin^2 \frac{\theta}{2}\right), \quad \beta = \frac{v}{c}$$  


::: callout-important
The key experimental discovery was that the proton is **not point-like**. The measured cross section deviates from the Mott prediction, introducing a **form factor**  $F(q^2)$ :
  $$\left(\frac{d\sigma}{d\Omega}\right)_{\text{exp}} = \left(\frac{d\sigma}{d\Omega}\right)_{\text{Mott}} |F(q^2)|^2$$  
This form factor encodes the proton's finite size and internal structure.
### **2. Form Factors and Internal Structure**
:::




![This figure schematically represents the process of electron-proton scattering, a central topic in the lecture. The diagram shows an incoming electron ( $e$ ) scattering off a proton ( $p$ ), resulting in an outgoing electron and outgoing proton. The central blob indicates that the interaction is not just point-like but involves the internal structure of the proton. The lower left part of the diagram, with three small circles inside the proton, symbolizes the proton being composed of three quarks, highlighting its non-point-like nature.  Physically, this figure illustrates the concept that, as discussed in the lecture, high momentum transfer ( $Q^2$ ) in electron-proton scattering experiments probes the internal quark structure of the proton. The departure from the predictions of point-like scattering (e.g., the Mott or Rutherford cross section) leads to the introduction of form factors, which encode the finite size and non-trivial internal structure of the proton due to its composition from quarks. The image thus visually encapsulates the main lecture theme: probing hadron structure and inferring the presence of quarks inside the proton through scattering experiments.](2025-Lecture-03-images/fig1.png){#fig-fg1}

 




![This diagram represents the kinematics of elastic electron-proton scattering in the **center of momentum frame (CMF)**. The incoming particles, an electron ( $e$ ) and a proton ( $p$ ), approach each other along the horizontal axis. After their interaction, they scatter into final states: the outgoing electron ( $e'$ ) and outgoing proton ( $p'$ ). The angle  $\Theta$  denotes the **scattering angle** of the electron relative to its initial direction.  In the context of the lecture, this figure is used to illustrate the basic setup for analyzing  $2 \to 2$  scattering, defining important variables like the scattering angle ( $\theta$  or  $\Theta$ ) and emphasizing that these kinematic variables (in particular, the angle and the corresponding transferred momentum  $Q^2$ ) are central to measuring and interpreting cross sections and exploring the proton's internal structure. The CMF is the natural frame for describing the energy and momentum relations used in the calculation of Mandelstam variables  $s$  and  $t$ , and for connecting experimental observables (like the scattering angle) to theoretical quantities such as form factors and phase space integrals.](2025-Lecture-03-images/fig2.png){#fig-fg2}

 




![This figure represents the Feynman diagram for elastic electron-proton scattering, a key process discussed in the lecture. An incoming electron ( $e^-$ ) scatters off a proton ( $p$ ) by exchanging a virtual photon, depicted as a wavy line labeled by the four-momentum transfer  $Q$ . The proton vertex is marked with a shaded “blob,” indicating that the proton is not a point-like particle but possesses internal structure. The blob encodes proton form factors ( $F_1$ ,  $F_2$  or equivalently  $G_E$ ,  $G_M$ ), which parameterize the spatial charge and magnetic distributions inside the proton and cause measurable deviations from the predictions for point-like scattering. The scattering angle and resulting momentum transfer ( $Q^2$ ) probe either the overall charge radius or the internal quark structure, depending on the kinematic regime, as described in the lecture.](2025-Lecture-03-images/fig3.png){#fig-fg3}

 




![This figure illustrates the kinematics of electron-proton scattering in the center-of-mass frame. The incoming electron ( $e^-$ ) approaches along the  $z$ -axis and is scattered at an angle  $\theta$  relative to its initial direction, emerging as the outgoing electron ( $e'$ ). The azimuthal angle  $\phi$  represents the rotation of the scattered electron around the  $z$ -axis. These angles,  $\theta$  and  $\phi$ , define the entire final-state configuration for a 2-to-2 scattering process. In the context of the lecture,  $\theta$  is directly related to the transferred momentum squared  $Q^2$ , which determines the sensitivity to the proton’s internal structure. The azimuthal angle  $\phi$  often drops out for unpolarized, rotationally symmetric reactions, leaving  $\theta$  as the key observable for extracting cross section dependencies and probing hadron structure through angular distributions.](2025-Lecture-03-images/fig4.png){#fig-fg4}

 




![This figure represents the Feynman diagram for elastic electron-proton scattering, also known as electron-proton scattering via single photon exchange. In the context of this lecture, it illustrates the fundamental physical process used to probe the internal structure of the proton.   - The incoming electron (labeled "e") approaches the proton (labeled "p"), and they interact through the exchange of a virtual photon (wavy line labeled "q")—the mediating particle of the electromagnetic interaction. - The outgoing electron (labeled "e'") and outgoing proton (labeled "p'") are detected after the scattering event. - The exchanged photon transfers four-momentum  $q$  to the proton, with the squared four-momentum transfer  $Q^2 = -q^2$  serving as the key variable characterizing the resolution of the probe: small  $Q^2$  corresponds to probing the overall charge distribution (forward scattering), while large  $Q^2$  accesses the internal, quark-level structure (deep inelastic scattering). - The black blob on the proton side of the vertex symbolizes the fact that the proton is not a point-like particle. Instead, its electromagnetic vertex is characterized by form factors, such as  $F_1(q^2)$  and  $F_2(q^2)$ , encapsulating information about its finite size and internal quark-gluon dynamics. - This process is described mathematically by the matrix element  $\mathcal{M}$ , and the experimentally measurable cross section depends on the squared amplitude  $|\mathcal{M}|^2$ , the phase space, and the kinematic flux factor.  Overall, the image encapsulates how high-energy electron scattering is employed to extract the electromagnetic form factors of the proton, thereby revealing its spatial charge distribution and internal structure.](2025-Lecture-03-images/fig6.png){#fig-fg6}

 




![This figure illustrates the relationship between the internal charge density distribution of different particles or composite systems and their corresponding form factors, which are directly probed in scattering experiments such as electron-proton elastic scattering.  - **First Row (Point-like, e.g., the Electron):**   - **Charge density:** The charge is concentrated at a single point, mathematically represented by a delta function,  $\delta(r)/4\pi$ .   - **Form factor:** The Fourier transform of a delta function is a constant. In scattering, this means the cross section follows the prediction for point-like particles (e.g., Mott or Rutherford formulas), with no  $Q^2$ -dependence beyond kinematics.  - **Second Row (Exponential, e.g., the Proton):**   - **Charge density:** The charge is distributed according to an exponential profile, such as  $(a^3/8\pi)\exp(-ar)$ . This spatially extended charge means the particle is not point-like.   - **Form factor:** The Fourier transform gives a "dipole" form factor—decreasing smoothly with increasing  $Q^2$ . This behavior encodes the finite size of the proton, as revealed by deviations from point-like scattering in experiment.  - **Third Row (Sphere with Diffuse Edge, e.g., Nucleus like  $^{40}$ Ca):**   - **Charge density:** The charge is spread over a sphere, with a possible diffuse edge (approximated as proportional to  $r^3$  for certain nuclei).   - **Form factor:** The result is an "oscillating" form factor, i.e., the Fourier transform has zeros and oscillations as a function of  $Q^2$ , characteristic of sharp-edged spatial distributions.  Physically, the left column identifies the spatial structure (form) of the charge distribution, the middle column shows its mathematical or qualitative profile (charge density as a function of radius  $r$ ), and the right column shows the resulting form factor, which determines how the elastic scattering cross section deviates from the point-like behavior as a function of momentum transfer  $Q^2$ . This directly connects internal structure (probed by form factors) to experimental observations in electron scattering—central themes of this lecture.](2025-Lecture-03-images/fig8.png){#fig-fg8}






The form factors that appear in scattering are directly related to the spatial properties of the hadron.

*   The **electric form factor**  $G_E(Q^2)$  is the Fourier transform of the spatial charge distribution  $\rho(r)$ :
  $$G_E(Q^2) = \int \rho(\mathbf{r}) \, e^{i \mathbf{q} \cdot \mathbf{r}} \, d^3r$$  
For a spherically symmetric distribution, this simplifies to:
  $$G_E(Q^2) = \int_0^\infty 4\pi r^2 \rho(r) \frac{\sin(qr)}{qr} \, dr$$  
where  $q = |\mathbf{q}|$ .

*   The **mean square charge radius**, a key observable, is extracted from the low- $Q^2$  behavior of this form factor:
  $$\langle r^2 \rangle = -6 \hbar^2 \left. \frac{d G_E}{d Q^2} \right|_{Q^2=0}$$  

For a full quantum mechanical description of elastic electron-proton scattering, we use the **Rosenbluth formula**, which separates the contributions from the proton's electric ( $G_E$ ) and magnetic ( $G_M$ ) structure:
  $$\frac{d\sigma}{d\Omega} = \left( \frac{d\sigma}{d\Omega} \right)_{\text{Mott}} \left[ \frac{G_E^2(Q^2) + \tau G_M^2(Q^2)}{1+\tau} + 2\tau G_M^2(Q^2) \tan^2\left(\frac{\theta}{2}\right) \right]$$  
where  $\tau = Q^2/(4M_p^2)$  and  $Q^2 = -q^2$  is the squared four-momentum transfer.

These Sachs form factors ( $G_E, G_M$ ) are related to the more fundamental Dirac ( $F_1$ ) and Pauli ( $F_2$ ) form factors:
  $$G_E = F_1(Q^2) - \frac{Q^2}{4 m^2} F_2(Q^2), \quad G_M = F_1(Q^2) + F_2(Q^2)$$  
### **3. The Quark Model: Symmetry, Wavefunctions, and Predictions** 




![This figure schematically represents the three spatial axes (typically labeled as the x, y, and z axes, or 1, 2, and 3) within the proton or hadron. The dashed oval outline suggests the finite spatial extent of the hadron, emphasizing that it is not a point-like object but has an internal structure. The labeled arrows (1, 2, 3) correspond to the directions in space along which observables like spin, momentum, or angular momentum can be projected.  In the context of the lecture, this visualization is relevant to the discussion of the proton's internal charge and magnetic distributions, which are characterized via form factors. Measuring properties such as form factors or the magnetic moment requires considering the projection of physical quantities (such as spin or orbital angular momentum) onto these axes. The axes are also essential in describing how the proton's (or nucleon's) wave function and associated observables transform under rotations and other symmetry operations discussed in the lecture, particularly as related to the SU(3) and isospin symmetries.  Thus, the image is a schematic for understanding the orientation and internal degrees of freedom accessible within a finite-sized, structured hadron.](2025-Lecture-03-images/fig5.png){#fig-fg5}






Now, we relate these observations to internal structure by assuming hadrons are made of quarks. We return to the **symmetry considerations**—flavor symmetry and spin symmetry—and combine them within **SU(6) spin-flavor symmetry**. 




![This figure illustrates the excitation spectrum of hadrons (such as baryons or mesons) in terms of quantum numbers  $N$  (principal quantum number, or radial excitation), and  $L$  (orbital angular momentum). The lowest state (ground state) corresponds to  $N=0$ ,  $L=0$  (labeled "1S"), while the first excited radial state is  $N=1$ ,  $L=0$  ("2S"). The next set shown is for orbital excitation,  $N=0$ ,  $L=1$  ("1P"), which results in a multiplet of five mass states depending on spin and angular momentum coupling.  A key physical interpretation in the context of the lecture is the "mass difference" (about 600 MeV) between the S and P states, highlighted here as arising from "spin-spin interaction" between quarks inside the hadron. This difference in energies (masses) between states with the same radial quantum number but different angular momentum reflects the internal structure of hadrons: the presence of constituent quark degrees of freedom, and the influence of quantum numbers on the energy spectrum, as described through the quark model and the potential (e.g., spin-spin) interactions among quarks. The labeled mass range (1500–1700 MeV) for the 1P states corresponds to observed masses of excited hadronic states.   Overall, the diagram gives a schematic representation of the energy level structure of hadrons, and how spectroscopy (mass splitting) provides evidence for internal structure, consistent with the quark model discussed in the lecture.](2025-Lecture-03-images/fig11.png){#fig-fg11}






*   The proton wavefunction must be fully antisymmetric. Its **spin-flavor wavefunction** is a specific combination:
  $$|p\uparrow\rangle = \frac{1}{\sqrt{18}} \left[ 2|u\uparrow u\uparrow d\downarrow\rangle - |u\uparrow u\downarrow d\uparrow\rangle - |u\downarrow u\uparrow d\uparrow\rangle + \text{permutations} \right]$$  

*   In the quark model, the **magnetic moment operator** for a hadron is the sum of its constituent quarks' moments:
  $$\boldsymbol{\mu} = \sum_{i=1}^3 \frac{q_i}{2m_i} \boldsymbol{\sigma}_i$$  
where  $q_i$ ,  $m_i$ , and  $\boldsymbol{\sigma}_i$  are the charge, mass, and spin operator of quark  $i$ .

Assuming  $m_u = m_d$ , we define quark magnetic moments  $\mu_u = \frac{2}{3} \frac{e\hbar}{2m_u c}$  and  $\mu_d = -\frac{1}{3} \frac{e\hbar}{2m_d c}$ .

*   This leads to concrete **predictions for the proton and neutron magnetic moments**:
  $$\mu_p = \frac{4}{3} \mu_u - \frac{1}{3} \mu_d, \quad \mu_n = \frac{4}{3} \mu_d - \frac{1}{3} \mu_u$$  
These can be compared to the **experimental values**:
  $$\mu_p = 2.793 \, \mu_N, \quad \mu_n = -1.913 \, \mu_N, \quad \text{where } \mu_N = \frac{e}{2m_p}$$  
The success of these predictions is a major triumph of the quark model.



## Isospin Symmetry and Quark Content in Hadrons

But before starting, I wanted to pose a question to recap. There are two questions.

The first I'm sure you all will be able to solve. The second I'm sure you all won't be able to solve, but after today's lecture you will.

1.  **First question:** What is the isospin of the  $D$  meson? Specifically, what is the isospin of the  $D^+$  meson and the  $D^0$  meson?
2.  **Second question:** What is the isospin of the  $\Xi_{cc}$  baryon and its quark content?

For the  $D$  meson,  $D^+$  is a charm and anti-up,  $c\bar{u}$ , and  $D^0$  is charm and anti-down,  $c\bar{d}$ . So that was correct.

The charm quark has a charge of  $+\frac{2}{3}$ . The anti-up quark has a charge of  $-\frac{2}{3}$ . The anti-down quark has a charge of  $+\frac{1}{3}$ . So then let's get the charge correct here.

What is the  $\Xi_{cc}$  charge? It's  $++$ .

The second question for those who are done with the first:  $J/\psi$  decays to a pair of identical vector particles.  $J/\psi$  has spin one, parity minus,  $J^P = 1^-$ , then decays to two vector particles, each with  $J^P = 1^-$ .

I'm asking, what is the orbital angular momentum between these two particles to have a correct parity interaction? Who thinks that it is one? Who thinks it's zero? Who thinks it's one half? All right, we'll work on that.


::: callout-important
**Parity Conservation in  $J/\psi \to VV$  Decay**
For the decay  $J/\psi \to V V$ , parity conservation requires:
  $$P_{J/\psi} = P_V \cdot P_V \cdot (-1)^L$$  
Substituting the parities  $P_{J/\psi} = -1$  and  $P_V = -1$  gives:
  $$(-1) = (-1) \cdot (-1) \cdot (-1)^L$$  
This simplifies to  $(-1)^L = +1$ , meaning the orbital angular momentum  $L$  must be **even** (e.g.,  $L = 0, 2, \ldots$ ).
:::

Isospin symmetry is related to the wave functions of the light quarks. You have a  $u$ -quark or a  $d$ -quark. These are two light quarks.

We are dealing with the isospin wave function that has two components: up or down. Isospin has two components,  $\psi_u$  and  $\psi_d$ , and that corresponds to the up and down as a two-component function.

This multiplicity-two wave function corresponds to the  $+\frac{1}{2}$  or  $-\frac{1}{2}$  isospin projection onto the quantization axis, say  $I_3$ , of the total isospin  $I = \frac{1}{2}$ .

*   As soon as you see one light quark, you are dealing with isospin  $\frac{1}{2}$ .
*   If you have two light quarks, then you deal with a system that has a combination of two  $\frac{1}{2}$  spins that could be 1 or 0:
  $$\frac{1}{2} \otimes \frac{1}{2} = 1 \oplus 0$$  

Answering this question is as easy as just counting the number of the light quarks. Here is one, has isospin one half. Here is one, has isospin one half. If you see two light quarks, then you have to think either it's zero or one.

So, one thing I've always found strange about this relation to the light quarks. Why don't you have like an isospin for a heavier quark? You can have an internal group that relates.

Now you're asking, let me introduce the symmetry that acts in the space of the light quarks plus charm. Or let's extend by one. Let's say light quarks plus strange. But it has to include the lower quarks as well.

Somehow looking at the charm quark over here. Charm quark, let's say, or light... it's a bit of a weird example anyways. Charm and strange. Fine, let's consider.

Is there a symmetry that relates charm and strange? Every wave function we would write and consider the dimension related to the charm and strange presence. The charm quark would be the upper component, the strange would be the lower component.

And we would say this is a symmetry. The entire consideration is exactly the same as SU(2). The only problem is that our Lagrangian, our nature does not obey this symmetry because as soon as you change strange to charm, they don't have equal masses.

Therefore you sort of get a different world. The Lagrangian is not symmetric with respect to this symmetry. So the reason why we consider  $u$  and  $d$  quarks here as a part of the multiplet is because they have the same mass,  $m_u \approx m_d$ .

And if you change  $u$  to  $d$ , nothing happens with the Lagrangian. Sort of... there is a mass difference, right? Both of them are almost zero. Six MeV versus four MeV. So then people say, you know, like the strange quark is 100 MeV. 103, not that different.

If you look at the scale of 1 GeV where QCD breaks, where the low-energy QCD changes the regime, maybe 100 MeV of this strange quark is not that different from the light quarks. So let's consider the  $s$  quark to be part of the same dimension.

And then you could say, let's introduce not an isospin, but a different quantity that reflects SU(3), that reflects the sort of place of the meson in the three-quark symmetry.

And then we come back from the isospin to the diagram of the hypercharge versus isospin that was drawn last time. So then I could ask the same question: where in this hypercharge versus strangeness plane does this meson lie? And that would be a question that includes the strange quark into it.

One could ask another question. One can include the charm quark. And people do this, say, well, the charm quark is still lighter than the top and bottom. Let's just include it in the consideration of the symmetry.

Let's pretend that we live in a world where the charm quark, strange quark, and light quarks have the same mass and it's low. Then every meson gets mapped into the three-dimensional point of the symmetry group.

On one axis you have isospin, another axis you have strangeness, on yet another axis you have charmness. And then all these mesons get their place in this three-dimensional symmetry pattern.

Symmetry tells you that the  $D^+$  meson is almost the same as the  $D^0$  meson because the only difference between them is the light quark, and light quarks are part of the multiplet. So  $D^+$  and  $D^0$  are the same particle with respect to the strong interaction.

That's what isospin symmetry tells you. Also that particle would be the same as yet another one with respect to the strong interaction. And please tell me which one.

This particle has, since its isospin is  $\frac{1}{2}$ , it has a brother or sister, which one? Not in the last row. We are talking about light quarks and I'm saying that replacing light quark  $u$  to light quark  $d$  does not change the particle properties.

That's the claim of the isospin symmetry. So if you replace a  $u$  quark to a  $d$  quark, I'm going to have particles with almost identical properties. Same mass, charge... we don't care because it's not a quantity that QCD cares about, it's electromagnetic interaction, but same mass, similar width, similar interactions with other particles, similar decay modes.

Even in the Particle Data Group, sometimes we don't separate them into different nodes; they are in the same node. We kind of understand, it's understood in the field that particles that differ by the presence of  $u$  and  $d$  by the isospin, they are not that different, they are the same particle.

So if I'm asking for the brother of this, you say well replace  $u$  to  $d$  and then you have another particle. Which one will it be? I have a question. Would that be the same case for  $D^+$  and anti- $u$ ? So would I have three other options in that case? Very good.

So yet another symmetry that we have not considered here is making an antiparticle. And then from this it will be  $D^-$  which has a  $\bar{c} d$ , and for the other one it will be  $\bar{D^0}$  which is  $\bar{c} u$ .

*   **Particle to antiparticle symmetry** (charge conjugation  $C$ ) is even better than isospin symmetry.
*   **Isospin symmetry** breaks a little bit by the quark masses and by their charges. Someone said  $u$  quark is not the same mass as  $d$  quark. Yes, there is a little difference and that's what makes this symmetry not exact.

The  $D^+$  and  $D^0$  are not exactly the same particles, but they have similar properties. While  $D$  and  $\bar{D}$  are so similar to each other that we don't even talk about them separately unless we measure tiny effects in the standard model like CP violation.

So charge conjugation is a super good symmetry and we will not discuss that much of charge conjugation because deviations from the property of a particle and its antiparticle are tiny. And they are addressed in the BSM studies, beyond standard model.

But deviation between  $D^+$  and  $D^0$  is an interesting question. This is related to the electromagnetic interactions and the different masses of quarks: **isospin breaking effects**.



## Isospin Partners and Symmetry Breaking in D Mesons

To finish, I would like to identify the isospin partner in the multiplet. Let's start with the quark content, and then we can name it.

The charm mesons form an isospin doublet. Their quark content is  $c\bar{d}$  for the  $D^+$  and  $c\bar{u}$  for the  $D^0$ :
  $$\begin{pmatrix} D^+ \\ D^0 \end{pmatrix} = \begin{pmatrix} c\bar{d} \\ c\bar{u} \end{pmatrix}$$  

The name is the same for particles within the same isospin multiplet. If the symmetry were exact, their properties would be identical, leading to:
  $$m_{D^+} \approx m_{D^0}$$  

In your homework, you will see a display of this principle. You will also see an example where **isospin breaking** is strong, which results in completely different decay modes for the  $D^+$  and  $D^0$ .

Isospin symmetry is broken only **hardly in observable quantities**. On the level of quantum couplings, it actually holds very well. The primary reason for the breaking is the mass difference.


::: callout-important
The breaking is driven by the small quark mass difference:
  $$\Delta m_q = m_d - m_u$$  
This slight difference in constituent quark masses (e.g.,  $m_u \approx 338 \text{ MeV}, m_d \approx 322 \text{ MeV}$ ) can sometimes lead to huge deviations in observables like decay widths.
:::

Although the fundamental couplings ( $|\mathcal{M}|^2$ ) are similar, the **phase space** available for decays can differ significantly. The decay width is given by:
  $$\Gamma \propto |\mathcal{M}|^2 \times \Phi$$  
where  $\Phi$  is the phase space factor, which is highly sensitive to small mass differences between the initial and final states.



## Spin Addition and Quantum Number Combinations

One curious fact if you look at any LHCb paper is a standard sentence on the first page. It states that charge-conjugated processes are not listed explicitly, but it is assumed every time we write in our papers. For example, when we write  $B \to D \mu \nu$ , we assume the charge-conjugated sample was analyzed simultaneously, and we do not even discuss it separately.

The reason for this is that analyzing one charge and the other addresses the same physics. There is no difference. We combine them and forget about charges, hence the note about charge-conjugated fractions on the first page of every paper. The properties of charge-conjugated mesons are homogeneous. We might revisit this when discussing deviations from the Standard Model and CP violation, if we get to it. But that is the first point done.

Let us quickly discuss the second question. It is easier to address from the final state. You see two vector states; you add them and ask what possible configurations exist. What is the possible length of a vector you can make with one stick one meter long and another stick one meter long? We have vector one with spin  $S = 1$  and vector two with spin  $S = 1$ . You are going to add them.

The three possible configurations—since spin is quantized in units of 1—are  $S = 0$ ,  $S = 1$ , and  $S = 2$ . This is one of the things I hope you will learn from this course: how to add spins. We will practice this every lecture until you understand. We combine these two vectors and can have a total spin combination of zero, a spin combination of one, or a total spin combination of two.

Here I have  $J_{V1}$  and  $J_{V2}$ . They interact with each other. If I consider them together, I can have a total  $J$ . On one side of a table, I draw their individual quantum numbers. On the other side is the total  $J$ . The parity is multiplicative when you combine them with zero orbital angular momentum. They do not rotate relative to each other. You just take one, take the second, put them together, and look at the total  $J$ . You have  $J^P = 0^+$ ,  $1^+$ ,  $2^+$ . This is called the  $L = 0$  s-wave.


::: callout-note
**Key Formula: Total Spin Addition**
For two particles with spins  $\vec{S}_1$  and  $\vec{S}_2$ , the total spin  $\vec{S}$  is given by  $\vec{S} = \vec{S}_1 + \vec{S}_2$ . The possible quantum numbers for  $S$  range from  $|S_1 - S_2|$  to  $S_1 + S_2$  in integer steps. For two spin-1 particles:  $S = 0, 1, 2$ .
:::

Now we start adding orbital angular momentum. This produces another set of quantum numbers. Orbital angular momentum is easier to address by looking only at the left part and stating that every configuration spans a ladder of states: for  $L = 0$ ,  $L = 1$ ,  $L = 2$ . I will draw in the rows of the table what is possible.

Let me start with the  $0^+$  total combination and add one unit of orbital angular momentum,  $L = 1^-$ . This means multiplying this  $0^+$  or adding to it the vector  $1^-$ . I add  $1^-$  to  $0^+$  and get  $1^-$ . Now these two are trickier because I have one meter stick and another meter stick together. You have three spin combinations:  $S = 0, 1, 2$ . They will have a parity of minus. Here I have another three combinations:  $J = 1, 2, 3$ . This is called the P-wave.

The last one is the D-wave, which I will consider. We can continue to F-wave, G-wave, and so on. For this project, I probably need the F-wave. Yes, because there will be one. We call it F-wave. The way I address it is by looking again only at the first row, not the second, and adding two units of orbital angular momentum,  $L = 2^+$ . The parity for orbital angular momentum is given by  $(-1)^L$ . So we have  $0^+$ ,  $1^-$ ,  $2^+$ ,  $3^-$ ,  $4^+$ ,  $5^-$ .

*   Starting with  $0^+$ , I add  $L = 2^+$  and get  $2^+$ .
*   Adding it to  $S = 1$ , I have to think a little. I bring another vector of length two and add. What can I get? The minimum is when they subtract:  $|1-2| = 1$ . The maximum is  $1+2 = 3$ . All integer steps are allowed. So possible  $J$  are 1, 2, 3.
*   Now for  $S = 2$  and  $L = 2$ : I need help. Here I have a vector of length two and I add two units of orbital angular momentum. What are the possible configurations? The minimum is  $|2-2| = 0$ . The maximum is  $2+2 = 4$ . All of them will have parity plus.
*   For the F-wave, I bring an even longer stick,  $L = 3^-$ . Again, I look at the first row. It will give  $J = 1, 2, 3, 4, 5$  for the last one, all with parity minus.


::: callout-note
**Key Formula: Total Angular Momentum with Parity**
When including orbital angular momentum  $\vec{L}$ , the total angular momentum  $\vec{J}$  is  $\vec{J} = \vec{L} + \vec{S}$ . The possible  $J$  values range from  $|L - S|$  to  $L + S$ .

The total parity  $P$  for a system of two particles with intrinsic parities  $P_1$  and  $P_2$  is  $P = P_1 P_2 (-1)^L$ . For two vector mesons (each with parity  $-1$ ) and  $L = 0$ :  $P = (-1)(-1)(-1)^0 = +1$ , giving the s-wave states  $J^P = 0^+, 1^+, 2^+$ .
:::

Now look at what decays. First, that is the basic thing. Knowing that you can combine any particles with any spin and any orbital angular momentum, you can figure out the possible quantum numbers: total spin and orbital angular momentum for any  $J^P$  I give you. Just learn how to fill this table, how to construct it from the combination of the two quantum numbers. Then you know how to deal with spin.

The next step is we look at what is decaying and try to identify within this table what decays. I look at this list, and one that decays is  $1^-$ . I have it here, here, here, and here. So four combinations. The answer to this question: it decays into two. Let me remove identical particles, because identical makes it more difficult. There is also the rule that two identical particles cannot be in certain configurations of  $S$ . I already mentioned it. We will come back to this identical particle point at some point.

But identical particles will make this and this forbidden. For  $L = 3$  and the two you showed, I think I remember that  $L + S$  must be even for identical bosons. So  $3 + 2$  is odd. Two plus this is odd. This is why only one remains. So it will be only one state for identical particles, and four combinations for non-identical particles.


::: callout-note
**Selection Rule for Identical Particles**
For two identical bosons, the total wavefunction must be symmetric under exchange. This imposes the condition  $(-1)^{L+S} = +1$ , restricting combinations to those where  $L + S$  is even. For example, if  $L = 1$  and  $S = 2$ , then  $L + S = 3$  (odd) is forbidden.
:::

All right, second question. You read this and realize you need to draw a table like this, quickly fill it—it is super easy—and then identify what is the stable one. That is it. Questions? I promise this is a super skill you learn so that you never have trouble with combination numbers.



## Probing Hadron Structure with Electromagnetic Scattering

To understand the structure of hadrons, you need to study a standard, well-understood probe: a well-understood current insertion into the hadron.

In order to study strong interactions and how hadrons are organized inside, we will look at the electromagnetic interaction. We will scatter an electron off a proton and see how this reaction behaves in the phase space of the kinematic variables.

The reason is that on the side of the electron there is nothing interesting or complex. The electron is a point-like particle. It interacts with the electromagnetic field of the proton and scatters off. That's super well understood on the electron side of the reaction.

The process looks more interesting on the proton side. The electric charge that the electron sees originates from the proton charge if the interaction has a very low momentum transfer,  $Q^2$ . But then, for high  $Q^2$ , this current—this electron—starts feeling the charge of the quarks and the properties of the quarks inside the proton, instead of just the bare proton outer field.

So the problem here is like a large cucumber that you get smashed with the electromagnetic current. First, if the field the electron feels, or the transferred momentum  $Q^2$  in this reaction, is small, you get the characteristics of the proton itself. (see @fig-fg1) But then, if you go to the regime of high transferred momentum, where a lot of energy is taken from the proton, you start seeing internals. You can look at this regime by the scattering angle  $\theta$  of the electron, where  $Q^2 = 4 E E' \sin^2(\theta/2)$ . That's the idea behind **deep inelastic scattering**.

Large accelerator machines and facilities have been built to study that very process of scattering.

Now the proposal. Essentially, the hadron physics program for the next 10 years promises to be more or less that. You will have an **electron-ion collider**, so-called. That's what is largely discussed. Instead of the proton you will have heavier ions, like Carbon ions, and then you'll scatter electrons and then study quantum chromodynamics.

In this process there is a lot to understand about the proton. It's not just an object that I draw, but there are quarks, there are gluons, and they interact with each other. There are many dynamics, like they are also not static. They move.

We have many dimensions you can imagine in the proton characteristics. What we understand more or less right is how these quarks inside the proton are distributed, what fraction  $x$  of the proton momentum these quarks are carrying, as described by the sum rule:

  $$\sum_i \int_0^1 dx\, x f_i(x) = 1$$  

This is the **proton momentum sum rule**, where  $f_i(x)$  are the parton distribution functions (PDFs).

What we don't understand is what is the perpendicular fluctuation. The problem goes in one direction. Part of its momentum is carried by the quarks. But what's happening off the axis, the **transverse momentum**, is something not well understood. That's one of the key questions that people want to address by studying further these days.


::: callout-note
**Key Kinematics of Deep Inelastic Scattering (DIS):**

*   The **four-momentum transfer squared**,  $Q^2 = -(k - k')^2$ , sets the resolution scale of the probe. High  $Q^2$  lets the electron resolve internal quark structure.
*   The **Bjorken scaling variable**,  $x = Q^2 / (2p \cdot q)$ , represents the fraction of the proton's momentum carried by the struck quark in the parton model.
*   The scattering probability is described by structure functions  $F_1(x, Q^2)$  and  $F_2(x, Q^2)$  in the **DIS cross section formula**. For spin-1/2 quarks, these are related by the **Callan–Gross relation**:  $F_2(x) = 2x F_1(x)$ .
:::



## Mandelstam Variables and Center-of-Momentum Frame Quantities

This reaction is about the motivation to study it. But what are our observables essentially? A 2-to-2 reaction is very simple in terms of the observables.

There is the total energy in the system, determined by the energy of the colliding beams, and then the scattering angle of the electron. Essentially that's it.

More familiar quantities would be the total energy and momentum in the system and the scattering angle in the center of mass frame, the center of momentum frame.

But what are more natural and also very often used quantities? Our **Mandelstam invariants**, or **Mandelstam variables**, which are  $s$  and  $t$ .

*   The variable  $s$  is computed as the square of the sum of the four-momenta of the initial state particles:
  $$s = (p_{\text{electron}} + p_{\text{proton}})^2$$  
**Physics meaning:**  $s$  is the square of the total center-of-mass energy. (see @fig-fg2) In the CM frame,  $\sqrt{s}$  equals the total energy  $E_{\text{total}}$ .

*   The variable  $t$  is computed as the energy transfer from the initial to final state:
  $$t = (p_{\text{electron}} - p_{\text{electron}'})^2$$  
**Physics meaning:**  $t$  is the squared four-momentum transfer from the initial to the final electron (related to the scattering angle). It represents the invariant momentum transfer in the process. For spacelike momentum exchange, it is often related to the positive definite  $Q^2$  via  $Q^2 = -t$ .

So here you have electron prime, here I have electron. The difference of the four-momenta gives  $t$ , so that I can convince you that these two quantities are related.
I can write this quickly in the center of momentum frame. This is  $E_{\text{electron}}$ ,  $E_{\text{electron}} + E_{\text{proton}}$ . (see @fig-fg2) The star indicates that it's talking in the rest frame.

In that frame,  $\mathbf{p}_{\text{electron}}^{\star} = -\mathbf{p}_{\text{proton}}^{\star}$ . And  $\sqrt{s}$  is equal to  $E_{\text{total}}$ . Essentially,  $\sqrt{s} = E_{\text{total}}$ .

So the variable  $t$  we compute a slightly different way:  $t = (p_e - p_{e'})^2$ . What I've done here is to explicitly write this in the components.

The square of the difference of the four-vectors: the first four-vector squared gives the mass, the second four-vector squared gives the mass, and then twice the product, the scalar product of the two four-vectors.

I compute by multiplying energies and then subtracting the scalar multiplication of the vectors:
  $$t = m_e^2 + m_e^2 - 2(E_e E_{e'} - |\mathbf{p}_e||\mathbf{p}_{e'}|\cos\theta_{\text{CM}})$$  

And this is just absolute values squared, product of the absolute values and the cosine of the angle. Super straightforward.

But one thing to realize is that in the center of momentum frame all of these quantities are expressed in terms of  $s$ . So for example, the momentum  $|\mathbf{p}_e|$ .

And that you find by other algebra, by e.g. writing  $s$  as the proton plus electron squared. That's not what you want.

You want to write  $\sqrt{s} = E_{\text{proton}} + E_{\text{electron}}$ . So the  $\mathbf{p}_{\text{proton}}$ ,  $\mathbf{p}_{\text{electron}}$  is equal to...

The magnitude of the momentum  $p_{\text{CM}}$  in the CM frame is given by the **breakup momentum**:
  $$p_{\text{CM}} = \frac{\sqrt{[s - (m_p + m_e)^2][s - (m_p - m_e)^2]}}{2\sqrt{s}}$$  

Then you get the electron energy that you have here:
  $$E_e^{\text{CM}} = \frac{s + m_e^2 - m_p^2}{2\sqrt{s}}$$  

And in a similar way you get the momentum. Momentum is the square root of the energy squared minus the mass squared.


::: callout-note
The breakup momentum formula  $p_{\text{CM}}$  is sometimes called the **Chew function**. It appears in phase-space calculations, particularly for two-body final states.
:::

This expression is a Chew function because... Have you seen the Chew function before? The breakup momentum and the... When you calculate the phase space, I think the Chew function shows up. Phase space, two-body phase space.



## Kinematics of Elastic Scattering and the Role of  $Q^2$ 

One more thing to add for kinematics: let’s look once again at the variables.

The total energy is fixed by the beam of colliding particles. The scattering angle is something we measure.

Knowing the total energy, we know  $s$ . Knowing the scattering angle, we know through the kinematic relation that we can determine  $t$ .
In such an elastic scattering process, a common variable we encounter is  $Q^2$ , defined as (see @fig-fg2)

  $$Q^2 = -t .$$  

This definition comes from the fact that, at high energies, the dominant mechanism is an electron passing through and interacting with the target.

So  $t$ , or equivalently  $Q^2$ , is called the **transferred momentum squared**. This is the quantity that actually governs the physics—in fact, it is the only non‑trivial dynamical variable in the process.

The beam energies of the colliding particles are fixed; that is what we adjust in our accelerator. (see @fig-fg4) The only thing we measure is the angular distribution.

A bunch of electrons passes through a bunch of protons. If an interaction occurs, electrons change their trajectory—they scatter.

Before the interaction they fly in one direction; afterward their angle changes. **The change in angle tells us everything:** it reveals what happened inside the process and what momentum was exchanged.

You might wonder why the minus sign in  $Q^2 = -t$  is so crucial. For elastic scattering kinematics, if you examine the expression for  $t$ , you find that  $t$  is always negative—the transferred momentum is always **space‑like**.

That means the square of this four‑momentum transfer is negative. We can see this quickly in the lab frame with a fixed target:  $t$  is always negative.

That is why physicists prefer to use a positive quantity,  $Q^2 = -t$ .

 $Q^2$  is fixed by the scattering angle. This defines in what **regime** the reaction occurs:

* If  $Q^2$  is **small**, we have shallow electron scattering. The charge felt by the proton current characterizes the proton as a whole—its charge distribution, not its internal partonic content.
* If  $Q^2$  is **large**, we begin to probe internal structure.

Thus we can quickly realize: (see @fig-fg4)

* Small  $Q^2$  → small scattering angles.
* Large  $Q^2$  → large scattering angles.

If you want to become sensitive to the quarks inside the proton, you must look at events where scattering happened at a **large angle**. If you are interested in the charge distribution, charge radius, and overall characterization of the proton, you look at **small‑angle scattering**.

We will discuss two quantities that are characterized by small‑angle scattering:

1. **The charge radius of the proton** – how the proton appears as a cloud of charge when viewed from a distance.
A good approximation for the proton’s charge distribution is an exponential form:

  $$\rho(r) \propto e^{-r/R},$$  

where  $R$  is the charge radius.

2. **The magnetic moment** – how a particle behaves in a magnetic field, or how it interacts with a magnetic field.
If a particle has a magnetic moment  $\vec{\mu}$ , placing it in a magnetic field  $\vec{B}$  produces an extra force. This appears as an additional term in the Hamiltonian:

  $$\Delta E = -\vec{\mu} \cdot \vec{B}.$$  

For example, in a hydrogen atom placed in a magnetic field, the energy levels split (Zeeman splitting) because of the magnetic moment and the finite charge radius.


::: callout-note
**Key kinematic relations**

-  $s = (p_1 + p_2)^2$  is the fixed center‑of‑mass energy squared.
-  $t = (p_1 - p_3)^2$  is the momentum‑transfer squared (always negative for elastic scattering).
- In the lab frame,  $Q^2$  relates to the scattering angle  $\theta$  via
    $$Q^2 = 4 E E' \sin^2(\theta/2),$$  
  linking large  $Q^2$  to large angles.

- Small  $Q^2$  probes the extended charge cloud (exponential  $\rho(r)$ ); large  $Q^2$  resolves internal quark structure.
:::

We have discussed these points.



## Cross Section and Phase Space in Scattering Processes

Before moving to the details, let's relate quantum process observables with something that we measure in experiment. For that, let me introduce the **cross section**.

It's another key equation in this course: how to compute the cross section, the differential cross section, in terms of the matrix element of the reaction. You can think of the square of the matrix element,  $|\mathcal{M}|^2$ , as something that gives you the probability of a reaction happening at a certain kinematic point.

The cross section, if you measure it integrated over the whole kinematic domain, would be given by the matrix element squared summed over this domain and then the number of phase space configurations. The phase space, you can think of as the number of configurations in which the reaction can happen. It's rather intuitive.

In order to calculate the total probability you need to sum over all possible configurations. That configuration for the spins when you deal with discrete indices is a super intuitive concept. But when you deal with the kinematic manifold, it's less intuitive because the space is continuous.

An example you see here: one of the variables that defines the final state is  $\theta$ , the scattering angle. This is a continuous variable. If you want to calculate the total cross section, you have to sum over all possible  $\theta$ s. It turns out to be an integral over  $\theta$ . So that's what phase space takes care of: it sums over possible configurations.

Then there is a **flux factor**, which determines the normalization of the wave function so that your wave packets of the colliding particles are attributed correctly in the cross section. The flux factor is the simplest thing; it's the  $2E_1 2E_2 |v_1 - v_2|$  kinematic factor. Just put the right energies and velocities and then you have the flux.

The phase space is slightly trickier, but it's a standard expression. Phase space presents an integral over all possible configurations in continuous space.

For each particle in the final state you have a phase space with  $n$  particles. For every particle you want to write something like  $\frac{d^4p}{(2\pi)^4} 2\pi \delta(p^2 - m^2)$ . Every particle should be **on mass shell** (on-shell means energy and momentum are correlated with each other,  $p^2 = m^2$ ).

So you have an integral over all energy and momentum with the energy-momentum conservation. That 4-vector squared should give a mass squared. One can demonstrate that. Here is the energy-momentum conservation.

Phase space is nothing else but the continuous version of the counting of possible configurations. It's very easy—well, not once you've done this a couple of times. It's easy for the two-body phase space, a little bit trickier for the three-body phase space, and gets rather complicated for four-body, five-body. But it's always a standard integral.

We compute this numerically if we need to. But for two-body there was a classwork to compute this. We will meet this expression very often. That's why I will give the expression for two-body.

Let's first count the number of variables. You see that every delta function gives the energy-momentum constraint that I can remove by taking the differential. So you can count the number of the  $d$ 's that appear. This is the number of the variables I have to integrate. But then you subtract the number of constraints, because every constraint I can satisfy by removing one of the integration variables. That's how the math of the delta functions works.

So let's count for the two-body: how many  $d$ 's I have, how many dimensions in my integral before I remove constraints? **Six**. Now minus four constraints from energy-momentum conservation. **Two**. So if I proceed wisely, I should be able to trade every one of these constraints for one of the differentials.

At the end I can proceed by removing constraints, not actually doing integrals, but just trading constraints for the differentials. Then at the end I am left with two degrees of freedom.

So the expression, if I do this, is:

  $$d\Phi_2 = \frac{1}{8\pi} \frac{\lambda^{1/2}(s, m_1^2, m_2^2)}{s} \frac{d\cos\theta \, d\phi}{4\pi}$$  

where  $\lambda(s, m_1^2, m_2^2) = [s - (m_1 + m_2)^2] [s - (m_1 - m_2)^2]$  is the **Källén triangle function**.

It's a great exercise because it's totally analytic and it's a very nice answer. This has a lot of properties inside this expression. I really recommend everyone to do this three times: do it once, put it aside, do it a second time, you do it a third time, and then you understand it.

So the way how to trade these delta functions and the differentials and how to receive this expression. This expression has two differentials remaining and this is an integral over the phase space over the spherical angles.

When we do **2-to-2 scattering**, I said that there is one variable that determines the scattering. But I didn't tell you that there is yet another one of rotation around the axis: the particles collide and then, in case you don't have any polarization, if the initial and final states are not polarized, your matrix element squared does not depend on this azimuthal rotation.

That's why  $\phi$  here can be safely ignored. You have a z-axis, you have an x-axis here, you have a y-axis here. Your colliding particles: here is the electron, here is the scattered electron. Between the z-axis and the electron you have a  $\theta$  angle. The projection of this electron prime to the XZ plane gives you the  $\phi$  angle that is immutable. So that's  $\phi$  rotation.

If there is no spin external directions, there is no dependence on  $\phi$ , like in this expression, the matrix element does not depend on  $\phi$ . If you want to calculate the total integral here for the cross section, total cross section, we just get rid of this and replace this with  $2\pi$ . Because the  $\phi$  integral is equal to  $2\pi$ .

What is non-trivial is the  $\cos\theta$ . And that's the whole physics. The  $\cos\theta$  is related to the  $Q^2$  and that gives you sensitivity to the structure of the proton.

What you see here is a kinematic factor. It tells you the number of the configurations for a certain energy. If you have a little energy release, if you have an energy very small, like if your energy of the beam is very small, the number of configurations is sort of small.

This is sort of a non-relativistic effect that if you would count non-relativistically, the number of degrees of freedom is only given by the number of the configurations. Sort of show it: first configuration, second configuration. This outgoing particle: first configuration, second configuration, third configuration. So overall you get  $4\pi$  configurations.

But if you take into account that particles are relativistic, then you end up with this factor which is the suppression of the phase space close to the threshold as a function of the energy. This vanishes when energy is equal to the masses of the particles. If your energy of the system is very close to the threshold, your phase space is zero, is very small. Not surprising.


::: callout-important
The differential cross section formula that combines these elements is:
  $$d\sigma = \frac{1}{4E_1 E_2 |v_1 - v_2|} \times |\mathcal{M}|^2 \times d\Phi_n$$  
This relates the measurable cross section to the square of the matrix element  $|\mathcal{M}|^2$  (the transition probability), the flux factor, and the Lorentz-invariant phase space  $d\Phi_n$  for the final state.
:::



## Matrix Element in Scattering Theory

We discussed this in scattering.

Now let me quickly tell you what the **matrix element** is. The matrix element you see there is a key input to the reactions. That is something we gain either from a theory of interaction, from which we can derive it, or, if we don't have a theory—as is often the case in hadron physics—we can use general principles to come up with it.

For **electromagnetic processes**, we do have a theory: **QED plus QCD**. We know how to write an expression that, when squared and summed over final states and averaged over initial states, gives a mathematical form we can plug in and compare to experiment.

I also know this expression can only depend on one variable, which is one in two: the energy of the beam and another one. The matrix element is defined in the domain of my **phase space** variables. The phase space, as we just discussed, is a function of two variables, defined by  $\theta$ . Once I consider the **unpolarized case**, I don't have a  $\phi$  dependence, so only  $\theta$  remains.

Therefore, the matrix element in our case will be a function of the **scattering angle**. Of course, it will also depend on the total energy, but this is fixed by the energy of the colliding particles.

This mathematical expression is complex and is defined in field theory in a formal way as part of the **scattering matrix**. You have initial states asymptotically brought to minus infinity in time and a final state with non-interacting particles at  $T = +\infty$ . You then define the matrix element as the expectation of the interaction operator between the asymptotic initial state and the asymptotic final state.

It is a complex function, which is important for us. It gives a real value once I take its absolute value squared and sum. So it is a complex function of the two variables  $s$  and  $t$ . In the case where  $s$  is fixed, it is a complex function of one variable,  $t$ .


::: callout-note
The differential cross section, which is the experimental observable, is directly related to this matrix element. It is proportional to the squared matrix element,  $|\mathcal{M}|^2$ , multiplied by the Lorentz-invariant phase space factor. For unpolarized scattering at fixed center-of-mass energy  $s$ , the matrix element  $\mathcal{M}$  and thus the cross section depend only on the Mandelstam variable  $t$  (related to the scattering angle).
:::



## Form Factors and the Rosenbluth Formula

Let me write something you might have seen in field theory. I will not go through the details.

In field theory, the way we approach scattering is by using perturbation theory. We do it order by order, expanding in the number of interactions. Every interaction of an electron with the current gives you a factor of  $\frac{1}{137}$ . This is  $\alpha$ , the electromagnetic fine-structure constant. That's why you can do an expansion series: for example, a photon hitting an electron once versus a photon hitting an electron twice. Already the first term in this series gives a good bulk value of the total cross section.

Therefore, we will consider the first-order interaction in the electromagnetic process. We write this in the following expression. Every order, every mathematical expression has its equivalent in terms of the cartoon Feynman diagrams. So here I draw the diagram like this. I have a rule in field theory for how to translate the diagram into the mathematical expression. I draw a diagram, put an arrow, make a notation, and then I immediately write the expression.

Something here might not be familiar: these are  $F_1$  and  $F_2$ , the two form factors. These are two functions that are not given by the field theory and appear because the proton is not a point-like particle.  $F_1(q^2)$  and  $F_2(q^2)$  are form factors that characterize internal properties of the proton. If the proton were point-like,  $F_2$  would be equal to 0, but it is not. That's why we have to deal with them, introduce them, and actually measure them in experiment.

*    $u$  is a spinor.
*    $\Gamma$  is a gamma matrix.
*   The thing I discussed last time is that  $\sigma^{\mu\nu}$  is  $\frac{i}{2}[\gamma^\mu, \gamma^\nu]$ , the commutation of the gamma matrices.

It's really important that you can identify the dimensionality and prove that the expression one writes has the dimensionality one expects. What is the dimensionality of the matrix element? Is it a tensor, is it a scalar? All objects that appear here are tensors. One has to see that all indices match. For example, this  $\mu$  is contracted with this  $\mu$ . This is a  $2 \times 2$  matrix.

 $u$  is a spinor with indices, but it's contracted with a  $4 \times 4$  matrix. So this is a scalar in the spinor indices, but it's a vector in the Lorentz index. This is again a matrix, but then it's contracted by vector and by row and column, and then this is again a scalar. This one index  $\mu$  is the photon momentum.  $F_1$  and  $F_2$  are scalar functions.

I can proceed and derive the cross section. How I deal with spinors you also learn in field theory. The way I proceed with this expression is I find the squared amplitude and then I do spin summation. There are tricks to get rid of these spinors.

What I want to write is the final expression for the cross section. It's called the **Rosenbluth formula**. From here to here there are many steps, and I hope you allow me to skip them and I send you to a field theory course. In the book of Peskin and Schroeder it's derived step by step. It's not in the Mark Thomson book, but they also give this expression. I think in the field theory course you're also forced to do that.

What I want to stress is the physics of it. What you recognize quickly is the  $\frac{1}{\sin^4(\theta/2)}$  that comes from the  $\frac{1}{Q^2}$ .  $Q^2$  is proportional to  $\sin^2(\theta/2)$ . Then  $1/Q^2$  leads to the  $1/\sin^4(\theta/2)$ . That's a divergence for small angles. For very forward scattering, you have a very high dependence on  $\theta$ , like  $1/\theta^4$ . It's not integrable; you have to do regularization.

 $E_1$  and  $E_3$  are the electron energies. One more equation that I missed is how  $G_E$  and  $G_M$  are related to  $F_1$  and  $F_2$ . For convenience, to make expressions at the end a little nicer, we replace the  $F$ s with the  $G$ s and then get this answer. 




![This figure illustrates the experimental technique used to extract the proton's electric and magnetic Sachs form factors,  $G_E$  and  $G_M$ , from elastic electron-proton scattering data using the **Rosenbluth separation** method. On the vertical axis is the ratio of the experimentally measured differential cross section to the Mott cross section,  $\left( \frac{d\sigma}{d\Omega} \right)_{\mathrm{exp}} / \left( \frac{d\sigma}{d\Omega} \right)_{\mathrm{Mott}}$ , which removes trivial kinematic factors and highlights the dependence on the proton's internal structure. The horizontal axis is  $\tan^2(\theta/2)$ , where  $\theta$  is the electron scattering angle.  At fixed four-momentum transfer squared ( $Q^2$ ), the Rosenbluth formula predicts a linear relationship between this cross section ratio and  $\tan^2(\theta/2)$ , due to the separate contributions of  $G_E^2$  (electric) and  $G_M^2$  (magnetic) form factors to the angular dependence. The vertical intercept of the line is proportional to  $G_M^2$ , and the slope is directly related to  $G_E^2$ . By measuring the cross section at different scattering angles (i.e., for different values of  $\tan^2(\theta/2)$ ) but at fixed  $Q^2$ , one can extract the values of  $G_E$  and  $G_M$  for that  $Q^2$ . This process provides information about the spatial distribution of charge and magnetization inside the proton, which are key experimental evidences that the proton is **not point-like** but possesses internal structure described by these form factors.](2025-Lecture-03-images/fig9.png){#fig-fg9}




 That's what people measure. From the  $Q^2$  dependence of the  $G$  functions, one gets a property of the proton.


::: callout-note
The Sachs form factors  $G_E$  (electric) and  $G_M$  (magnetic) are linear combinations of the Dirac ( $F_1$ ) and Pauli ( $F_2$ ) form factors. They are defined as:
  $$G_E(Q^2) = F_1(Q^2) - \tau F_2(Q^2)$$  
 $$G_M(Q^2) = F_1(Q^2) + F_2(Q^2)$$  
where  $\tau = Q^2/(4M_p^2)$ . These are the quantities directly measured in electron-proton scattering experiments.
:::

I can say a few words next lecture on the extraction of the  $G$ s because that's a very nice experiment. There is a nice experimental technique for extracting these  $G$  and  $F$  quantities at small values of  $Q^2$ .

Let me show you something. The  $Q^2$  dependence is in fact a dual variable to the spatial coordinate in the sense of the Fourier transformation. If you know the  $Q^2$  dependence of these form factors, you can interpret this as the spatial distribution. These two are related by the Fourier transformation. Tell me how this depends on  $Q^2$ , and I can relate this to how the proton charge is distributed over large distances in space.

In fact, that's what people do. They assume an exponential dependence on the spatial coordinate. Once you put exponential dependence here, you get a pole-like dependence. Here it's called the **dipole parameterization**. You will see this in the homework. By measuring the  $Q^2$  dependence, for example on the lattice or from experiment, we get the parameter of the spatial distribution.

One of the questions that has been very hot in the field is: what is the charge radius of the proton? Many experiments have tried to measure this with various techniques. Lattice calculations are also trying to address that. One of the quantities you extract on the lattice when you do numerical computation of quantum chromodynamics from first principles is the  $Q^2$  dependence. A Fourier transformation gives you the spatial distribution, and you get the charge radius.



## Magnetic Moments and the Quark Model

This quantity is another interesting aspect. It is related to the **magnetic moment** of the hadron. I would like to discuss that quantity in the remaining time.

What I would like to argue is that  $G_M(Q^2 = 0)$  gives the magnetic moment. If you set  $Q^2 = 0$ , you get a total integral of the magnetic current over the whole space. That gives you the **total magnetic moment** of the hadron.

So, what is a magnetic moment? This is like the leading-order term you can derive. You can extend this to higher orders:

*   **Next-to-leading order (NLO)**
*   **Next-to-next-to-leading order (NNLO)**

The corrections come from the electron side, which we know how to handle, and from the proton side.

The expression involving the form factors  $F_1$  and  $F_2$  is the most general one you can write. While you could derive  $F_1$  and  $F_2$  at NLO, this is very challenging in physics and is typically not done. Instead, these functions are **parameterized**. We acknowledge that we cannot compute the detailed dynamics inside the interaction vertex (the "blob"), so we describe it with parameters.

In practical physics, this parameterized interaction is what we call the **magnetic moment**. You may have seen this in quantum mechanics: the interaction part of the Hamiltonian is given by the product of the particle's magnetic moment and the magnetic field. This affects the equations of motion, adds an extra energy term to the particle, and thus enters the Lagrangian.

The magnetic moment for a **point-like Dirac particle** is given by:
  $$\vec{\mu} = g \frac{e}{2m} \vec{S}$$  
Here,  $\vec{S} = \frac{1}{2} \vec{\sigma}$  is the spin operator for a fermion. The factor  $g$  is the **gyromagnetic ratio**. For a point-like Dirac particle,  $g = 2$ .

This equation implies that for a **neutral point-like particle** (charge  $e=0$ ), the magnetic moment would be zero.


::: callout-important
What we actually measure for the proton and neutron provides solid evidence that they are **not point-like particles**. The experimental facts are quite telling:

*   The magnetic moment of the **neutron is not zero**.
*   The magnetic moment of the **proton deviates from the point-like particle value** ( $g \neq 2$ ).
*   The ratio of the proton's magnetic moment to the neutron's is roughly  $-\frac{3}{2}$ .
:::

My hope was to demonstrate how this ratio arises in the **quark model**, but we will have to postpone that calculation to the next lecture. 




![This figure illustrates the behavior of the electromagnetic form factors  $G_E$  and  $G_M$  for the proton and neutron as functions of the squared four-momentum transfer  $Q^2$ .  - The **vertical axis** represents the form factor value ( $G$ ), and the **horizontal axis** represents  $Q^2$ , the momentum transfer squared. - The **black curve** labeled  $G_E^p$  shows the electric form factor of the proton. It starts at  $G_E^p(Q^2 = 0) = 1$ , reflecting the proton's unit electric charge, and falls off with increasing  $Q^2$ , demonstrating how the proton’s finite size affects the spatial distribution of its charge as probed by electron scattering. - The blue line labeled  $G_E^n$  for the neutron starts at zero ( $G_E^n(Q^2 = 0) = 0$ ), consistent with the neutron’s lack of net electric charge. - The right side lists the **measured values of the form factors at  $Q^2 = 0$ ** for both proton and neutron:   -  $G_E^p(0) = 1$  (proton charge)   -  $G_M^p(0) = 2.79$ , which corresponds to the proton’s magnetic moment in nuclear magnetons ( $\mu_p$ )   -  $G_E^n(0) = 0$  (neutron charge)   -  $G_M^n(0) = -1.91$ , corresponding to the neutron’s magnetic moment ( $\mu_n$ ) - The **experimental significance** highlighted in the lecture is:   - For a **point-like particle**, you would expect a different result, especially for the neutron magnetic moment, which would be zero.   - The nonzero and nontrivial values (especially for  $G_M$ ) show that the proton and neutron are **not point-like**, but have internal quark substructure. The deviation of  $G_M^p$  and  $G_M^n$  from naïve Dirac theory is direct evidence of composite structure, and their absolute values are key benchmarks for the success of the quark model calculations.  In summary, this figure visually connects the form factors measured in electron scattering to intrinsic hadron properties—electric charge and magnetic moment—and demonstrates the evidence that nucleons are composite objects made of quarks.](2025-Lecture-03-images/fig10.png){#fig-fg10}




 The result is remarkable: the neutron has a non-zero magnetic moment, the proton's  $g$ -factor is not 2, and their ratio is approximately  $-3/2$ . This ratio comes out exactly when you examine the flavor-spin wave function for the proton.

The procedure is to:

1.  Write the proton state as a composition of its quark wave functions.
2.  Act with the magnetic moment operator on the proton.
3.  Compute the proton's magnetic moment in terms of the magnetic moments of its constituent quarks.
4.  Repeat the process for the neutron.
5.  Find that the predicted ratio matches the experimental value.

Let me discuss the foundations of this approach. As we discussed previously, the reasoning stems from **confinement** in the strong interaction: the color interaction is confined within the small scale of the proton where the quarks reside.

Within the proton, quarks and gluons interact. The **emergent properties** and degrees of freedom appear when we consider multiplets and symmetries based on quarks. The quarks act as the leading degrees of freedom, but they gain an effective mass.

*   The **current quarks** in the Standard Model Lagrangian have very small masses.
*   The **constituent quarks** that emerge have a significant mass (roughly 300 MeV each) and carry most of the proton's degrees of freedom.

The quark model assumes we integrate out the gluonic degrees of freedom, and the effect of this integration is to give the quarks an effective, constituent mass. We start with nearly massless quarks, integrate out the gluons, and end up with a system where three massive quarks form a proton.

*   The *u* quark has a charge of  $+\frac{2}{3}e$  and the *d* quark has a charge of  $-\frac{1}{3}e$ .
*   Each carries 1/3 of the baryon number.
*   Together, they constitute and govern the degrees of freedom of baryons.

We can construct the proton wave function in a simplified manner by combining representations of the **flavor wave function** and the **spin wave function**, writing the proton in terms of these lower-level quark degrees of freedom. That is what we will do next time.

### Today's Lecture Summary

Today, we discussed the kinematics of **electron-proton scattering**, examining different regimes based on the momentum transfer  $Q^2$ :

*   **Forward Scattering ( $Q^2$  small):** The electron barely changes direction. This regime probes the proton as a whole, characterizing its total charge density and magnetic moment.
*   **Deep Inelastic Scattering ( $Q^2$  large):** High momentum transfer probes the proton's internal structure, providing clues about the quarks inside.

We covered the standard 2-to-2 scattering kinematics, which is essential to understand well: how to calculate phase space, flux, and, given a matrix element, how to obtain a scattering probability.

We examined the **Rosenbluth formula**, detailing how the scattering cross section is determined by form factors, and how these form factors relate to the proton's charge distribution and magnetic moment. We began introducing the quark model to explain these properties and will continue next time with the explicit calculation of the magnetic moments.



## Conclusion

---
**All right, thanks for your attention.**


::: callout-note
This concludes the current segment. The following section will build upon the concepts covered here.
Please ensure you have reviewed the material before proceeding. If you have any questions, note them for the upcoming discussion.
:::

