---
title: (2025) Lecture 7
author: ''
presenter: Mikhail Mikhasenko
note_taker: Anna Zimmer
date: '2025'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



## Helicity Formalism and Problem Review

Welcome everyone. Today we have the seventh meeting on hadron physics. In today’s lecture we will expand on the previous lecture on helicity formalism. We will discuss **partial wave expansion**, which you have already seen in homework, and also move toward general principles discussing the **Mandelstam plane** and **analyticity**. 




![This figure represents the expansion of the scattering amplitude  $\mathcal{M}$  in terms of multiple contributions, illustrating both the mathematical series and the corresponding Feynman diagrams. The first term shows a direct transition from the initial ( $i$ ) to final ( $f$ ) state, corresponding to the simplest process, often called the "Born term." The subsequent terms add the effects of intermediate states: the second term represents a process with a single intermediate state ("rescattering" or "loop" correction), and the third term includes two such intermediate interactions, and so on.   Physically, this expansion encodes the idea that the total amplitude for a scattering process includes not only the direct transition but also all possible pathways involving one or more intermediate states, corresponding to multiple exchanges or rescatterings. This iterative structure is central to the understanding of **unitarity** and **analyticity** in quantum scattering theory, as each term contributes to the full, analytic amplitude in line with principles discussed in the lecture, such as the requirements imposed by the Lorentz group and the Mandelstam plane. The formalism shown here lays the groundwork for constructing amplitudes that respect these fundamental symmetries, providing the basis for resonance models and partial wave expansions described throughout the lecture.](2025-Lecture-07-images/fig10.png){#fig-fg10}

 




![This figure is an Argand diagram illustrating the complex scattering amplitude  $f$  in partial wave analysis, key to understanding resonance behavior in hadron physics. The horizontal axis represents the real part of  $f$ , Re( $f$ ), and the vertical axis represents the imaginary part, Im( $f$ ). The black circle, centered at  $(0,\,1/2)$  with radius  $1/2$ , reflects the unitarity condition for the scattering amplitude in a single partial wave. This means that as energy varies, the amplitude  $f$  must remain within or on this circle, encoding probability conservation.   The arc  $\mathcal{R}$  drawn in red shows how the amplitude associated with a resonance moves through the complex plane as a function of energy. As the energy sweeps through the resonance, the point representing  $f$  traces out this characteristic arc. In the context of the lecture, this geometric representation is fundamental for visualizing how resonances manifest in scattering: the circular trajectory and its tangency to the unitarity circle demonstrate crucial connections between analytic properties, unitarity, and resonance phenomenology, all of which underpin the Breit-Wigner parameterizations and the more advanced analytic models discussed.](2025-Lecture-07-images/fig12.png){#fig-fg12}





### 📝 Review of Previous Problems

At the beginning, as always, I invite you to look at the problems to recap the material from the previous lecture. I will give you five minutes to think about them, and then we will discuss together.

We will go through them in this order: Problem 1, then Problem 3, and finally Problem 2.

**Problem 1:** Which interaction is responsible for the  $\Lambda$  decay to a proton and a pion? Is isospin conserved? Is parity conserved? Is angular momentum conserved?

**Problem 3:** This involves analyzing a Dalitz plot to determine which decay is occurring.

**Problem 2:** This demonstrates that the rotations we discussed are part of the same  $SU(2)$  group structure as isospin rotations. The question asks: what is the 30‑degree isospin rotation about the  $Y$  axis, and how does it act on the  $\Delta^+$  state?

### ✅ Discussion of Problem 1

Let's start with the first problem. The weak interaction is responsible for the decay  $\Lambda \to p + \pi^-$ .


::: callout-note
The decay involves a flavor change: the  $\Lambda$  contains a strange quark ( $s$ ), while the final-state proton and pion contain only up ( $u$ ) and down ( $d$ ) quarks. In the Standard Model, **flavor-changing processes are mediated exclusively by the weak interaction**. For ground-state baryons, most decays are indeed weak.
:::

The reasoning is correct: a flavor change always indicates the weak interaction. For ground state baryons, they all decay weakly—or at least, most of them do.
### 🔧 Relevant Theoretical Context 




![This figure illustrates the basic kinematic structures for two-to-two particle scattering processes ( $A + B \to C + D$ ) as discussed in the lecture. At the top, it shows a generic  $2 \to 2$  scattering diagram with incoming particles  $A$  and  $B$  and outgoing particles  $C$  and  $D$ . Below, it shows two specific "channel" diagrams labeled  $s$  and  $t$ :  - The ** $s$ -channel** (left diagram) corresponds to the situation where particles  $A$  and  $B$  annihilate or interact to form an intermediate state, which subsequently decays into  $C$  and  $D$ . This configuration is directly related to the Mandelstam variable  $s = (p_A + p_B)^2$ , which represents the square of the total energy in the center-of-mass frame.  - The ** $t$ -channel** (right diagram) illustrates a different process where  $A$  exchanges a particle with  $B$ , resulting in  $C$  and  $D$ . Here the relevant Mandelstam variable is  $t = (p_A - p_C)^2$ , representing the squared momentum transfer between the initial and final states.  Physically, these diagrams represent different ways the scattering can occur, or equivalently, different regions of the Mandelstam plane. The figure emphasizes how the full amplitude for the process can receive contributions from multiple kinematic configurations, each characterized by its corresponding Mandelstam variable ( $s$ ,  $t$ , or  $u$  channels, with  $u$  not shown). These considerations are fundamental to the partial wave expansion, crossing symmetry, analyticity, and the broader analytic structure of the scattering amplitude being discussed in the lecture.](2025-Lecture-07-images/fig6.png){#fig-fg6}

 




![This figure represents the **Mandelstam plane**, a key tool in scattering theory used to visualize and analyze the kinematics of  $2 \to 2$  scattering processes. The axes correspond to two of the three Mandelstam variables  $(s, t, u)$ , which are Lorentz-invariant quantities that fully specify the kinematics.   The colored regions indicate the physically allowed regions for different scattering channels: - The **upper blue shaded region** labeled "s-channel" corresponds to physical values where  $s$  is positive and the process describes direct  $2 \to 2$  scattering. - The **left blue shaded region** labeled "t-channel" corresponds to kinematics where  $t$  is positive and describes exchange processes. - The **right red shaded region** labeled "u-channel" represents the physical region for the  $u$  channel.  The lines labeled  $s=0$ ,  $t=0$ , and  $u=0$  denote the boundaries between different kinematic regions. The areas marked "unphysical" lie outside the regions allowed by energy-momentum conservation for real particles, but can be accessed in analytic continuations of the scattering amplitude. The central green region indicates an overlap of physical boundaries.  Physically, the Mandelstam plane illustrates the domains where each scattering channel (s, t, u) is physical, a concept crucial for understanding particle processes, crossing symmetry, and the analytic properties of scattering amplitudes discussed in this lecture.](2025-Lecture-07-images/fig7.png){#fig-fg7}

 




![This figure shows the physical setup of a generic  $2 \to 2$  scattering process, which is a fundamental context for partial wave expansion and the use of Mandelstam variables in hadron physics.  - **Left Panel:** This diagram represents a generic scattering process, where particles with initial 4-momenta  $p_1$  and  $p_2$  scatter via some interaction (potentially mediated by resonances, as in strong interaction processes) into final-state particles with 4-momenta  $p_1'$  and  $p_2'$ . The blob indicates that the interaction can be complex and model-independent.  - **Right Panel:** This is the same process drawn in the center-of-mass frame and projected onto the scattering plane. It shows how the initial particle momenta are oriented, and how, after the collision, the outgoing particles are deflected by an angle  $\theta$ . This angle  $\theta$  is the **scattering angle**, a key variable in describing differential cross sections and in the **partial wave expansion** of the amplitude:     $$f(E, \theta) = \frac{1}{k} \sum_\ell (2\ell+1) e^{i\delta_\ell(E)} \sin\delta_\ell(E) P_\ell(\cos\theta)$$     The scattering angle is thus fundamental in decomposing the amplitude into components of definite orbital angular momentum.  This image provides the kinematic basis for introducing the **Mandelstam variables** ( $s$ ,  $t$ , and  $u$ ), which are Lorentz-invariant and fully characterize the process. It underpins the analysis of resonance production, angular distributions, and the formal structure of amplitudes discussed in the lecture, including their expansion in terms of Legendre polynomials as dictated by rotational symmetry.](2025-Lecture-07-images/fig8.png){#fig-fg8}

 




![This figure illustrates the **Mandelstam plane** for the three-body decay process  $\pi^-(1800) \to \pi^- \pi^0 \omega$ . The axes represent the squared invariant masses of two different pairs in the final state:  $m^2_{\omega\pi^-}$  and  $m^2_{\omega\pi^0}$ . The Mandelstam variables  $s$ ,  $t$ , and  $u$  are labeled along corresponding directions in this plane. The hatched red regions denote the **kinematical boundaries** associated with each channel—these are the physically accessible regions for the respective invariant mass combinations.   The diagram emphasizes how the amplitude for this process is defined over the entire Mandelstam plane but physical decay events are restricted to a particular domain (with the allowed phase space marked). Internal loops or resonant contributions, depicted by circles with arrows, indicate the presence of intermediate resonances or rescattering effects in specific channels. This setup is crucial for understanding the analytic structure of the amplitude, as discussed in the lecture, especially when considering **partial wave expansions** and analytic continuation across the Mandelstam variables. Such visualization is foundational for modern approaches to amplitude analysis, like the **Khuri-Treiman formalism**, where constraints of analyticity and crossing symmetry are imposed using the geometry of the Mandelstam plane.](2025-Lecture-07-images/fig13.png){#fig-fg13}

 




![This figure illustrates the unitarity condition for the scattering amplitude in quantum field theory, specifically showing how the **imaginary part of the two-to-two scattering amplitude** is related to the sum over all possible **on-shell intermediate states**.   On the left, "Im" denotes the imaginary part of the full amplitude (indicated by the blob diagram with two incoming and two outgoing legs), which is fundamentally connected to the physical processes allowed by the system's quantum numbers and kinematics.  On the right, the diagram shows this imaginary part decomposed into a product of amplitudes for **all possible intermediate state contributions**, where the amplitude  $A$  for the process is paired with its complex conjugate  $A^*$ , and the intermediate states are indicated by a vertical cut through the loop. This cut signifies that the particles in the loop go on-shell—a process known as "cutting" the diagram in the context of the **optical theorem** or **Cutkosky rules**.  In the context of the lecture, this is a graphical representation of a **unitarity relation** or **discontinuity equation** for the scattering amplitude. It states that the imaginary part (or discontinuity across the real axis in the complex energy plane) can be expressed as a sum over products of amplitudes involving all possible intermediate states. This underpins the concept of **analyticity** in the Mandelstam plane: the physical amplitude is constrained by the requirement of unitarity and is analytic except for known cuts and poles corresponding to physical processes like particle production and resonances.  This relation is fundamental in constructing **partial wave expansions** and in understanding the analytic structure of amplitudes, and serves as the starting point for more sophisticated theoretical models such as the **Khuri-Treiman model**, which imposes these constraints on three-body decays using dispersion relations.](2025-Lecture-07-images/fig14.png){#fig-fg14}






The topics for today—partial wave expansion and the Mandelstam plane—are built on foundational formulas from scattering theory.

**Partial Wave Expansion** expresses the scattering amplitude in terms of angular momentum eigenstates:
  $$f(E, \theta) = \frac{1}{k} \sum_{\ell=0}^{\infty} (2\ell + 1) e^{i\delta_\ell(E)} \sin \delta_\ell(E) P_\ell(\cos \theta)$$  
where  $k$  is the momentum,  $\ell$  is the orbital angular momentum,  $\delta_\ell(E)$  is the phase shift, and  $P_\ell$  are Legendre polynomials.

**Mandelstam Variables**  $s$ ,  $t$ , and  $u$  are the Lorentz-invariant quantities that describe  $2 \to 2$  scattering kinematics:
  $$s = (p_1 + p_2)^2, \quad t = (p_1 - p_3)^2, \quad u = (p_1 - p_4)^2$$  
with the constraint  $s + t + u = m_1^2 + m_2^2 + m_3^2 + m_4^2$ . These define the **Mandelstam plane**.

**Isospin Rotations**, mentioned in Problem 2, are described by the  $SU(2)$  rotation operator:
  $$U(\theta, \hat{n}) = \exp\left(-i \theta \, \hat{n} \cdot \vec{I}\right)$$  
where  $\vec{I} = (I_1, I_2, I_3)$  are the isospin generators,  $\theta$  is the rotation angle, and  $\hat{n}$  is the rotation axis.



## Parity, Angular Momentum, and Isospin in Weak Decays

Is parity conserved in the decay  $\Lambda^0 \to p + \pi^-$ ? I would say yes, **for the strong interaction**. On the left side, the proton has parity  $1/2^+$  and the pion has parity  $0^-$ . How is it conserved? Due to angular momentum. You introduce orbital angular momentum  $L = 1$ . That works. So the process *can* proceed as a parity-conserving process, but parity is **not** conserved in that decay because it also happens in S wave ( $L=0$ ).

The sensitivity to the polarization of the  $\Lambda$  in this decay arises because there are two components: a parity-conserving and a parity-violating one. In a weak decay, parity is always broken. It doesn't have to be 100% broken; in this case, 99% might proceed via the parity-conserving channel, but there will always be about 1% from the parity-violating part. So in weak decays, parity does not have to be conserved. In fact, it's not; here there is a significant fraction of the  $L = 0$  component.


::: callout-important
The general rule is: **In weak decays, parity is not conserved.** The total parity in a decay is given by the product of the intrinsic parities and the parity from orbital angular momentum:
  $$P_{\text{total}} = P_{\text{initial}} = P_{\text{final}} \times (-1)^L$$  
:::

Is angular momentum conserved? For hadron physics, in the course of particle physics events, angular momentum is **always** conserved. This is due to Lorentz group symmetry. If you don't violate Lorentz symmetry, angular momentum is always conserved. You make it conserved by putting in the correct orbital angular momentum, but you don't destroy the Lorentz invariance.

Is isospin conserved? **No.** How do we see that it's not conserved? Simply counting the number of light quarks is not reliable because  $u\bar{u}$  pairs can pop up from the vacuum. It's better to check isospin the same formal way we check for spin and parity.

*   The isospin of the  $\Lambda^0$  is  $0$ .
*   The isospin of the proton is  $1/2$ .
*   The isospin for the pion is  $1$ , because there are three pions of different charges in the multiplet.

Isospin is related to charge partners; the multiplicity is  $2I + 1$ . The proton exists in two species (proton and neutron), so its isospin is  $1/2$ . The  $\Lambda$  exists alone, so it is the only particle in its multiplet. For the transition  $\Lambda^0 \to p + \pi^-$ , you cannot combine a vector of length  $1/2$  and a vector of length  $1$  to make  $0$ . Therefore, isospin is broken.

In fact, this is also a property of the weak interaction. Isospin is always broken in weak decays, similar to parity. It could be broken severely or just a little bit.

All right, let's move to the three-body decay shown in the Dalitz plot.

*   **How many particles are in the final state?** Three.
*   **How many in the initial state?** One.
*   Therefore, it's a **1-to-3 decay**. That's why we represent it on a Dalitz plot.

**What is the final state?** The particles are a proton ( $p$ ), a kaon ( $K^-$ ), and a pion ( $\pi^-$ ). How do you know? Because those are the three particles mentioned on the axes. On the X-axis you have the invariant mass squared of one pair,  $m^2(pK^-)$ , and on the Y-axis the other pair,  $m^2(K^-\pi^-)$ . A Dalitz plot always shows the mass squared of one subsystem versus the mass squared of the second subsystem.

**What remains to figure out?** We need to identify the decaying mother particle. There are a few clues:

1.  **Resonance bands:** The Dalitz plot shows a horizontal band, which is the strongest resonance. The particle that decays into the proton and  $K^-$  is that resonance. That line projects into a peak in the  $m(pK^-)$  dimension. Similarly, vertical bands would correspond to resonances in the  $K^-\pi^-$  system (these are  $K^*$  states).
2.  **Mass from phase space borders:** The phase space is limited by the mass of the decaying particle  $M_0$ . The borders on the plot are given by:
  $$m_{ij,\text{min}}^2 = (m_i + m_j)^2, \quad m_{ij,\text{max}}^2 = (M_0 - m_k)^2$$  
You can find  $M_0$  by looking at the highest value on an axis. For example:
  $$M_0 = \sqrt{m^2(pK^-)_{\text{max}}} + m_\pi$$  
From the plot, this gives a mass around 2.4 - 2.6 GeV.

3.  **Quark content and interaction type:** The final state is  $p\,(uud)$ ,  $K^-\,(s\bar{u})$ ,  $\pi^-\,(u\bar{d})$ . The  $\bar{u}u$  and  $\bar{d}d$  pairs could come from the vacuum. The net quark content is  $u d s u \bar{d}$ . Could this be a pentaquark decaying strongly, or is it a weak decay? The presence of both parity and isospin violation points to a **weak decay**.

Putting it together—the mass near 2.6 GeV and the weak decay into  $p K^- \pi^-$ —identifies the mother particle as the **charmed baryon  $\Xi_c^+$ **. Its weak decay allows for the observed violation of parity and isospin, and the Dalitz plot reveals the intermediate resonant substructure ( $\Lambda^*$  and  $K^*$  states) in the three-body final state.



## Isospin Operators and Rotations in SU(2)

**Question 2: Isospin Operators**

We are given isospin operators. Let's check the statements:

1.  **Is it true that  $\hat{I}^2$  acting on  $\Delta^+$  gives  $15/4$ ?** Yes, this is true. The  $\Delta$  baryon has total isospin  $I = 3/2$ . The operator  $\hat{I}^2$  acting on an eigenstate yields  $I(I+1)$ .
*   For the  $\Delta$ , this is  $\frac{3}{2} \times \frac{5}{2} = \frac{15}{4}$ .

2.  **Is it true that  $\hat{I}_z$  acting on  $\Delta^+$  gives  $1/2$ ?** This is also true. The  $\Delta$  multiplet contains four states with different projections  $I_3$ :
*    $| \frac{3}{2}, \frac{3}{2} \rangle$ 
*    $| \frac{3}{2}, \frac{1}{2} \rangle$  ← This is the  $\Delta^+$  state.
*    $| \frac{3}{2}, -\frac{1}{2} \rangle$ 
*    $| \frac{3}{2}, -\frac{3}{2} \rangle$ 

The operator  $\hat{I}_z$  gives the projection  $I_3$ , so acting on the  $\Delta^+$  state yields  $\frac{1}{2}$ .

**Applying a Rotation in Isospin Space**

What happens if we apply a rotation? This connects to how states transform under SU(2). If you act with a rotation (e.g., a 30° rotation around the y-axis) on the  $\Delta^+$  state, you get a **mixed state** of different  $\Delta$  states.

The transformation is governed by the **Wigner D-matrices**:

  $$\mathcal{R}(\theta) |J, M\rangle = \sum_{M'} D^J_{M',M}(\theta) |J, M'\rangle$$  

The coefficients  $D^J_{M',M}(\theta)$  are known functions, often found in tables alongside Clebsch-Gordan coefficients. They are trigonometric functions.

For example, to find the specific coefficient  $D^{3/2}_{3/2, 1/2}(30°)$ , you would consult such a table. The key point is that applying a rotation not aligned with the quantization axis produces a superposition.


::: callout-important
The transformation preserves total probability. For a given initial state  $|J, M\rangle$ , the sum of the squared magnitudes of the D-matrix coefficients is one:
  $$\sum_{M'} |D^J_{M',M}(\theta)|^2 = 1$$  
This is the unitarity condition, ensuring probability is conserved under rotation.
:::

This demonstrates that rotations in isospin space work identically to regular angular momentum rotations because both are governed by the group **SU(2)**.

**Symmetry Relations for Wigner D-Matrices**

A question arose about a specific coefficient,  $D^{3/2}_{3/2, -3/2}$ , which might not be directly listed in standard tables. Such elements can be found using symmetry relations derived from the unitary nature of the rotation matrices.

One useful relation is:

  $$D^J_{-M_1,-M_2}(\theta) = (-1)^{M_1 - M_2} D^J_{M_2,M_1}(\theta)$$  

This allows you to compute coefficients with negative indices from those with positive indices (or vice versa) by swapping the lower indices and applying a phase factor. If this approach doesn't yield a tabulated value, another method is to use the property that for a unitary matrix, a negative sign in the arguments can be related to complex conjugation and transposition, which effectively swaps indices.

*The core takeaway is that these various relations all stem from the unitarity of the transformation.*

**Transition to Today's Topic**

Today's lecture will focus on the **Källén calculation**. We will discuss the application of the helicity formalism to scattering amplitudes.

**A major goal is to avoid confusion** between general, model-independent statements and the specific approximations we will introduce to build and simplify our expressions.



## Two-Body Decay Matrix Elements and Cascade Decay Construction

I would like to start with a reminder: for the two-body case we have a particle decaying into two, and in its rest frame we have the following configuration. 




![This figure illustrates the kinematic setup for a two-body decay in the context of the helicity formalism.   On the left, a Feynman-like diagram represents the decay of a parent particle (labeled "0") into two daughter particles (labeled "1" and "2").   On the right, the physical configuration in the rest frame of the parent particle (labeled "0-rest frame") is shown. The z-axis is chosen as the quantization axis for spin. The outgoing particles 1 and 2 emerge back-to-back, with their momenta and helicities (λ₁ and λ₂) indicated. The angles θ (polar) and φ (azimuthal) specify the direction of particle 1 in spherical coordinates with respect to the z-axis.   The figure encapsulates the geometric meaning of the helicity formalism: the matrix element for the decay depends on the spin projections and the angular orientation of the outgoing particles, captured here by θ and φ. The angular dependence of the decay amplitude is encoded in the Wigner D-matrix, reflecting how spin and momentum are coupled in the rest frame of the decaying particle. This diagram provides the foundational visualization for expanding amplitudes in terms of partial waves and for connecting angular momentum conservation to observed decay distributions.](2025-Lecture-07-images/fig1.png){#fig-fg1}






We are sitting in the rest frame of the decaying particle, and the quantized spin with respect to the z-axis is represented by the canonical state. We use helicity states for particle 1 and particle 2.

The matrix element represents a transition amplitude between the initial and final state. It must carry all dependencies on the kinematic variables and on the configuration of the particles with respect to the quantization axis. So it must depend on the initial spin projection  $M_0$ , the helicities  $\lambda_1$ ,  $\lambda_2$ , as well as the angles.

The total spin of the system controls the angular dependence of the final state particles. In that case, it is given by the Wigner D-matrix that comes with the angles of the decay products in this rest frame.

Particle one and two go back-to-back, and we pick one of them. We call it particle number one. We measure its spherical angles, polar  $\theta$  and azimuthal  $\phi$ , and they enter as an argument of the D function. This comes from the same algebra as we just discussed for the isospin.

These functions are the same functions that you find on the page of the Clebsch-Gordan coefficients. The capital D as a matrix is just a little d with a phase factor. 




![This figure schematically represents the decay of a parent particle into two daughter particles, labeled 1 and 2, within the helicity formalism framework. Each arrow denotes the direction of momentum of the outgoing particles, and the accompanying symbols  $\lambda_1$  and  $\lambda_2$  denote their helicities in their respective rest frames.  The relation  $m = \lambda_1 - \lambda_2$  indicates the conservation of angular momentum along the quantization (typically  $z$ ) axis in the parent's rest frame: the difference in the helicities of the two final-state particles equals the spin projection  $m$  of the parent particle along that axis.  In the helicity formalism, this physical configuration underpins the angular dependence of the decay amplitude. Specifically, it determines which element of the Wigner D-matrix encodes the angular correlations between the spin projections of the initial and final states, a key concept that translates into the general partial wave expansion discussed in this lecture.](2025-Lecture-07-images/fig2.png){#fig-fg2}




 Here it comes in the expression for the matrix element:

  $$\mathcal{M}^{M_0}_{\lambda_1, \lambda_2}(\theta, \phi) = H_{\lambda_1, \lambda_2} \, D^{J_0*}_{M_0,\, \lambda_1 - \lambda_2}(0, \theta, \phi)$$  


::: callout-note
**Physics meaning:** This formula describes the decay amplitude for a particle with spin  $J_0$  and spin projection  $M_0$  along the z-axis, decaying into two particles with helicities  $\lambda_1$  and  $\lambda_2$ . The Wigner D-matrix  $D^{J_0*}$  encodes the angular dependence, while  $H_{\lambda_1, \lambda_2}$  is the **reduced matrix element** that contains dynamical information (like coupling constants and mass dependencies) and is independent of angles.
:::

It comes conjugated because the particles in the final state are rotated with the rotation  $\theta$  and  $\phi$ . We use active transformations, active rotations. In order to obtain the configuration of the final state we have to apply  $R_y$  and  $R_z$ .

Here's an example for the regular rotations. In order to obtain the particle with the spherical coordinates  $\theta$  and  $\phi$ , you have to apply to something aligned along the Z axis the rotation first about Y by angle  $\theta$  and then about Z by angle  $\phi$ . That's exactly what you see in arguments of the D function.

That's just a series of transformations: first apply rotation about Z. These arguments of the D functions follow the Z-Y-Z convention of the Euler angles. The first is the Z rotation by angle 0, then Y rotation by angle  $\theta$ , and then Z rotation by angle  $\phi$ . You don't need to apply this first Z rotation.

One of the simplest conventions that is used often is to have no angle for the first rest frame rotation, and then you have  $\theta, \phi$ .

What also appears in the expression is this  $H$  with indices  $\lambda_1$  and  $\lambda_2$ . That's something that depends on the mass parameters only and does not depend any longer on angles. This is what remains as the reduced matrix element, computed as the projection of the z-aligned particle 1 and 2 with the initial state.

Here we don't have any angles any longer. We are dealing with the configuration of particle 1 with the helicity  $\lambda_1$  going in the z direction and particle 2 with the helicity  $\lambda_2$  going in the minus Z direction. We are projecting this into the particle 0 canonical state with the spin projection  $M$  equal to  $\lambda_1 - \lambda_2$ . (see @fig-fg2)


::: callout-important
**Helicity Constraint:** In the parent rest frame, the z-component of angular momentum is conserved. For back-to-back decay products, the difference in helicities equals the initial spin projection:  $M_0 = \lambda_1 - \lambda_2$ . This constraint is embedded in the Wigner D-matrix indices.
:::

That's a short reminder. Now we're going to apply the same construction to the more complicated decays. I want to demonstrate that this essentially gives us a recipe for how to construct any cascade decay with particles with spin.

To illustrate and make it easier to follow, for the reaction that proceeds through an intermediate state, I'm going to put around the vertices the blocks and apply formulas that I have for every specific block. The general structure is like this.

But now we have to insert the indices. The first D function has two indices. First of all it has a spin. The spin will be of the decaying particle always conjugated. 




![This figure represents a typical **cascade decay process** in hadron physics involving resonances and intermediate states, as discussed in the lecture. The initial interaction is a **photon ( $\gamma$ ) scattering off a proton ( $p$ )**, which leads to the production of an **intermediate resonance**—in this case, the ** $\Delta$  baryon** (illustrated by the triangle symbol in the diagram). The  $\Delta$  resonance then decays into a **proton ( $p$ )** and a **pion ( $\pi$ )**.   Physically, this diagram illustrates a  $2\to 2$  scattering process ( $\gamma p \to \Delta \to p\pi$ ), which is a concrete example of a reaction where a resonance (here, the  $\Delta$  with isospin  $I=3/2$ , spin  $J=3/2$ ) appears as an **intermediate state**. In the context of the lecture, this process is used to motivate the **helicity formalism** and the **factorization of amplitudes**: the total matrix element is constructed by combining the production amplitude of the  $\Delta$  (via  $U(\theta, \hat{n})$ , rotational properties, and group theory) with the decay amplitude of the resonance, which is characterized by its **Breit-Wigner propagator** and spin-dependent angular distributions (Wigner  $D$  or  $d$  functions).  The diagram shows how the **partial wave expansion** and resonance modeling (using Breit-Wigner distributions for the propagator and Wigner matrices for the angular structure) are applied in hadron spectroscopy, connecting the discussion of isospin, angular momentum conservation, and resonance dynamics from the lecture to an explicit scattering scenario.](2025-Lecture-07-images/fig5.png){#fig-fg5}




 The first index is of the particle that decays and then the difference of the helicities of particle one and particle two.

The reduced matrix element that appears here and there is going to have indices only of the particles that are combined. We don't need the third one, because that comes the same from the conservation of angular momentum of the helicity.

So here we will go. We have a transition of particle 0 going to the intermediate state (12) and particle 3. And here we have (12) going to 1 and 2. What is missing is a dynamic function that represents the propagation of the intermediate resonance.

This is the model and it is a model not because of the angular functions, they are precise and exact, but because of the factorization. We are assuming that the matrix element is able to factorize the first decay from the second decay.

The fact that we split the interaction matrix element into the two here—here is the reduced matrix element of the first transition, here is the second—is our modeling assumption: **factorization**.

What is missing here is that we didn't introduce the helicity  $\lambda$  of the intermediate state. You see that intermediate state that appears here also has a spin projection  $\lambda$ . That's the one that will be carried by one of the particles.

This is something up to a sum over the angles that appear as arguments. They are not the same, but they are specific to particular transitions here and there. Therefore we better label them differently.

That's always tricky to keep consistent labeling. When you apply this cascade decay parameterization, you have a million different angles. Labeling them we need to have some rule to start labeling.

For example, for the pair of particles that go back to back—reason this is IJ—I can use IJ index here. They will have indices 1, 2,  $\theta_{1,2}$ . Here is the 1, 2, 3 and here I would like to invite you to do some 3D imaging.

I want to now sketch on the board in 2D, how it looks in 3D. The definition of the axis. And we need to access. That's how it starts.

Here is the representation that I think it's easy to visualize what's going on. We start with particle 0 in the lab frame. It flies in this frame. The particle has the helicity  $\lambda_0$ .

This particle decays into a combination of the particles 1 and 2 and 3. Then we can boost the system to its rest frame following this axis. In the rest frame, this  $\lambda$  that used to be the helicity of the particle becomes the canonical spin projection.

If you think of this and here is the z axis. Here's  $m_0$ , that is the zero. This is the zero particle rest frame. The spin is quantized along the z axis by our construction. Since we boost in this direction, and in this frame 1, 2 and 3, they go back to back.

Now, in order to apply the second part, you have to follow the combination of particles 1 and 2. It's exactly the same as we started from. In this frame it flies in a certain direction and it decays into two particles.

What we need here is to boost to its rest frame where it decays into particle one and going back to back. 




![This figure illustrates the kinematic construction and reference frames relevant for the helicity formalism in cascade decays, as discussed in the lecture. It shows how to define the angles and axes necessary for correctly describing the spins and momentum directions of multiple particles in sequential decays.  - The **lab frame** (upper left, in purple) depicts the flight of the parent particle "0" with helicity  $\lambda_0$ . As particle 0 decays, its spin quantization axis is defined in this frame. - The event is boosted to the **rest frame of particle 0** (center), where the decay  $0 \to (12) + 3$  is considered. Here, the helicities of outgoing particles (e.g.,  $\lambda_3$ ) are defined with respect to the z-axis in this frame, and the relevant angles  $(\theta_{12,3}, \varphi_{12,3})$  specify the orientation of the (12)-3 system. - A further boost (indicated by "boost $^{-1}$ ") brings us to the **(12) rest frame** (top right, red/blue), where the pair (1,2) is at rest, and their decay kinematics can be fully described by  $(\theta_{12}, \varphi_{12})$ . The quantization axes and the definition of helicities  $\lambda_1$ ,  $\lambda_2$  are with respect to the new z-axis in this frame. - The diagram shows how each particle's momentum and spin orientation are defined in the appropriate rest frame along a specific z-axis, and emphasizes how the definition of the kinematic angles ( $\theta$  and  $\varphi$ ) depends on these sequential boosts and rotations.  **Physical Meaning:**   The figure provides a geometrical visualization of how to construct the angular variables and reference frames needed for a full helicity amplitude calculation in a decay chain. It clarifies that: - **Helicity quantization axes** are defined in different rest frames (a key caveat discussed in the lecture). - **Angles** such as  $\theta_{12}$ ,  $\varphi_{12}$ ,  $\theta_{12,3}$ , and  $\varphi_{12,3}$  specify the orientation of momentum vectors after appropriate boosts. - This construction is essential for writing decay amplitudes in terms of Wigner D-functions, ensuring that rotational properties and conservation of angular momentum are properly encoded in the matrix element for sequential decays.  The diagram is an explicit, practical guide for defining kinematic variables when applying the helicity formalism and partial wave expansions to multi-body (e.g., three-body) decays in particle physics.](2025-Lecture-07-images/fig4.png){#fig-fg4}




 So let's define the angles. Angles are taken as spherical angles of one of the decay products.

*   **First Decay (0 → (12) + 3):** The spherical angles of one of the decay products (e.g., the combined system (12)) would be  $\theta_{12,3}$  and  $\phi_{12,3}$ .
*   **Second Decay ((12) → 1 + 2):** The angles will be found as the angle with respect to the z axis in the rest frame of the particle (12). These are  $\theta_{12}$  and  $\phi_{12}$ .

When you deal with this practically, you follow the chain and introduce angles while approaching certain rest frames. In experimental physics we are given the four-vectors. You're literally given three four-vectors for particle one, particle two, particle three, and they are in the lab frame.

To make this transformation, you first find out what are the spherical angles of this combination 1 to 3 and you rotate to have a 1, 2, 3 vector pointing in the z direction. Then you boost your particle in this frame.

You take, find  $\theta$ , the angles of the 1, 2, align this with the z axis and you boost in that direction and then apply appropriate rotations. It's it.



## Helicity Formalism and Partial Wave Expansion in Resonance Decays

Now, in fact, the topology that we draw here is not the only one possible. One can imagine the same transition happening through the combination of particle 2 and 3 or 3 and 1, and one would write the same expression.

To incorporate the resonances in other channels, let's first discuss this expression a little bit, because there are caveats and things to note.

### **Caveat 1: Helicity Quantization Axes**

The main caveat, and something that I really want you to appreciate, is that the helicities that appear in the expressions are taken from **different rest frames**. In order to apply our helicity formalism and to replace an expectation value by the reduced matrix element—the so-called helicity coupling—we need to be in the rest frame of the decaying particle. Therefore, when we apply this formalism, the values of the  $\lambda$  that appear are taken in the rest frame of the particle pairs.

This means the quantization axis is the z-axis of the appropriate frame. From the last homework, we've seen that helicity is affected when you boost not along the direction of quantization, but off-axis. Consequently, if I were to write the amplitude where all  $\lambda$  are defined in the same frame— $\lambda_1, \lambda_2, \lambda_3, \lambda_0$ —I would get a linear combination of my amplitudes. This is a somewhat bizarre outcome.

The only reason we don't use this formalism literally is that we often don't care about the individual  $\lambda$  values themselves. We are going to sum over them once we add things together. So the consistency of the quantization axis is not a concern unless you are dealing with **coherent processes** that use different quantization axes.

What is important, and what I would like to draw your attention to, is identifying on which axis in this matrix element the spins are quantized.

*    $\lambda_0$  comes from the lab frame (helicity in the lab frame).
*    $\lambda_3$  and the others are defined in their respective resonance rest frames.

As soon as I square the matrix element and sum over the helicities, I don't care which axis I quantize them on; they are going to be summed or averaged anyway.


::: callout-important
**However**, if I want to add this amplitude to something else—for example, an amplitude from a different topology—I have to be careful with the helicity quantization axis. That's the first important note: **watch your helicity quantization axis**.
:::

### **Caveat 2: Factorization of Vertices**

The second important note is that we are implicitly assuming the vertices are **factorized**. This is usually a really good assumption, especially when discussing a narrow resonance. Even for a broad resonance, when the dynamics are driven by the resonance in the particle 1 and 2 combination, it's a good assumption.

The Wigner *d*-functions here are a property of the rotations; they are **not** model assumptions. We know Lorentz symmetry is a good symmetry, so these functions must be present.

If we took the expression without the factorization assumption—if we treated the matrix element together with the propagator as a single entity requiring theory input—we would be computing a more complex product. The form we use is a model-independent expression for the matrix element. It is safe to pull out the rotational functions, but **not** safe to break their structure.

### **Angular Dependence and the Scalar Case**

In general, what we've done here is explicitly find the angular dependence if a particle with spin  $J$  is present in the combination of particles 1 and 2. The helicity formalism is a simple way to identify the dependence of the matrix element on the angles.

The only thing I'm interested in is what spin particles 1 and 2 have. Using this form doesn't directly give me the answer; it simply gives a  $D^J$  function of the appropriate angles. Dealing with spin is more complicated, as you might have appreciated already.

For further discussion, let's reduce the situation to **scalar particles**. Consider a scalar particle decaying to three scalar particles—the scalar case. The matrix element in that case has no helicity indices. It is simply a function that depends on the kinematic variables.

Looking at the general helicity amplitude formula, we quickly realize that for scalars, there is no value for  $\lambda$  except zero. You have a single state in the multiplet for spin zero. Therefore, the Wigner *D*-function term simplifies to a delta function for  $\lambda=0$ , which we can propagate through the calculation.

The expression becomes very simple, and we find that the matrix element in the scalar case does not depend on any angles except one polar angle,  $\theta$ . In the rest frame of two particles, all other angles drop out.

A convenient way to write this is using a partial wave expansion in Legendre polynomials  $P_J$ :

  $$\mathcal{M}(m_{12}, \theta) = \sum_{J} (2J+1) \, a_J(m_{12}) \, P_J(\cos \theta)$$  

I'm moving towards matching the expression we derived to the partial wave expansion series you see in the homework. That's why I pulled the terms related to the helicity couplings and the reduced matrix element into the function  $a_J(m_{12})$  and introduced the  $(2J+1)$  coefficient.

### **Interpretation and Practical Truncation**

We started by writing the matrix element for a decay that proceeds via a resonance with spin  $J$ . We found that its angular dependence is given by  $d_{00}^J$ , which are in fact Legendre polynomials. We can match this to a general technique: for any matrix element with angular dependence, we can expand it in a series of Legendre polynomials and analyze the coefficients, with the only remaining dependence being on the mass variable  $m_{12}$ .

The argument is that the coefficients  $a_J(m_{12})$  in this expansion then represent dynamics corresponding to a specific spin  $J$  of a resonance. So we started from a model, but it gives us an interpretation and intuition for what the coefficients in a partial wave expansion represent.

The total matrix element in the scalar case depends on only two variables: the scattering angle  $\theta$  and the invariant mass  $m_{12}$ . This is exactly what we see in a Dalitz plot.

*   The expansion is an **exact** representation if you keep the upper limit of the series to infinity.
*   It becomes an **approximation** as soon as you truncate the series.

In experiment, we often use a **truncated series** of partial waves. This is because, due to the identification we've made, we can apply physical intuition:

*   Every term corresponds to a particle with spin  $J$ .
*   High-spin particles are not abundant. Looking at the PDG, particles with high values of  $J$  are rare.
*   Amplitudes with high  $J$  are typically suppressed.

This gives a natural limit to the expansion. We don't actually know particles with a spin greater than 6. Spin-6 particles exist, but spin-7 or higher have never been observed experimentally (though they are possible in quark models).

The reason is simple: such high-spin states are very high in the excitation mass spectrum, are very broad, and thus their effect is small and hard to observe. Practically, we truncate this series at  $J_{\text{max}} = 6$ .

  $$\mathcal{M}(m_{12}, \theta) \approx \sum_{J=0}^{J_{\text{max}}=6} (2J+1) \, a_J(m_{12}) \, P_J(\cos \theta)$$  



## Resonance Models in Multi-Channel Decays

Once you deal with a channel where resonances appear in a specific pair, like (1,2), the partial wave expansion is a good model to analyze the data.

When we deal with situations where a resonance can appear in **different** two-body channels—(1,2), (2,3), or (3,1)—instead of writing a partial wave expansion for just one pair, we use a different, more comprehensive model.

Looking at Dalitz plots for three-body decays, we see resonances can be present in any of these pair combinations. 




![This figure illustrates an example of an **experimental topology** for a three-body decay commonly found in hadron physics analyses. The diagram shows the decaying particle at the interaction point, producing three final-state particles labeled 1, 2, and 3, each with momentum vectors radiating outward. The colored boxes, labeled here as  $b_1$  and  $b_2$ , represent two different possible intermediate resonant subsystems (for example, the combinations of particles 1+2 and 2+3, respectively). This reflects how, in an experimental context—such as a Dalitz plot analysis—multiple two-body resonant channels can contribute to the final state.  From the perspective of the **helicity formalism** and **partial wave expansion** discussed in the lecture, this topology visually encodes how the decay amplitude is constructed as a sum over possible intermediate states, each described by its own angles and rest frame. The two boxes illustrate “blocks” where specific two-body resonances may appear, as in the **cascade decay/isobar model**: the decay can proceed via an intermediate resonance formed by a pair of particles (e.g., 1+2 or 2+3) before decaying to the observed three-body final state. The orientation of the outgoing particles also emphasizes the need to define angles (such as  $\theta$  and  $\phi$ ) in the appropriate rest frames when applying the helicity formalism, as different decay chains (topologies) require consistent and careful bookkeeping of kinematic variables and spin quantization axes.](2025-Lecture-07-images/fig3.png){#fig-fg3}




 Therefore, instead of writing the infinite partial wave series for just the (1,2) channel, we write the **sum of three truncated series**, one for each possible pair.

  $$\mathcal{A}_{\text{Isobar}}(s_{12}, s_{23}, s_{31}) = \sum_{\ell=1}^L (2\ell + 1) \, a_\ell^{(12)}(s_{12}) \, P_\ell(\cos\theta_{12}) + \text{cyclic permutations for (2,3) and (3,1)}$$  

In fact, this model, once projected onto any single channel, still contains contributions from an **infinite number of partial waves**. This is a key, non-trivial point.

The reason we cover an infinite number of partial waves in every channel is that the angles in each expansion are defined in different rest frames. For example, the angle  $\theta_{23}$  in the (2,3) rest frame is different from  $\theta_{12}$  in the (1,2) rest frame. Consequently, every term in the full three-body expansion projects onto the (1,2) partial wave expansion as an infinite series of Legendre polynomials.

This approximated amplitude—the sum of three truncated partial wave series—is known by different names in hadron spectroscopy.

*   It is often called the **Isobar model**.
*   In this model, the dynamical functions  $a_\ell^{(ij)}(s_{ij})$  for the propagator are typically parameterized with simple **Breit-Wigner amplitudes**:

  $$a_\ell^{(ij)}(s_{ij}) \propto \frac{g_\ell \, \Gamma_\ell(s_{ij})}{m_R^2 - s_{ij} - i m_R \Gamma_\ell(s_{ij})}$$  

This is a simple, phenomenological parameterization of resonance peaks that works quite well, but it is a **simplistic approximation** without strong theoretical constraints from unitarity or analyticity.

I prefer to call it a **cascade decay model**, which refers to more general constructions. The core idea is writing the full matrix element not as a single infinite sum, but as three separate, truncated series. This same ansatz is also the starting point for the more advanced **Khuri-Treiman model**.

The **Khuri-Treiman model** is a theoretical framework that incorporates final-state interactions and rescattering between different decay channels. It begins with the same three-series ansatz but then introduces theoretical constraints—primarily from **dispersion relations**—so that the amplitudes in each channel "talk to each other" and receive corrections through rescattering processes.


::: callout-important
The Khuri-Treiman model starts with the Isobar/cascade decay ansatz but adds unitarity and analyticity constraints via integral equations. This accounts for rescattering, leading to a more rigorous description of three-body decays where channel coupling is important.
:::

This model takes into account data and different types of rescattering diagrams. The starting expression is the same, and it relates to what is known in some contexts as a **reconstruction theorem**, derived from dispersion relations. While powerful, for higher spins and partial waves, the Khuri-Treiman approach still involves modeling assumptions, so it is not a complete first-principles solution.



## Modeling Dalitz Plots with Helicity Formalism

The last thing for today is to come back to the Dalitz plot distribution and discuss how we would model this distribution using the helicity formalism.

If you look at these blue Dalitz plots, let's try to identify the components you see by eye. What kind of expansion would you put there? We will describe the decay  $X \to p K \pi$ .

Looking at the plot, we are focusing not on the kinematic borders but on the **dynamics**. All inhomogeneities within the phase space are driven by the physics. They are produced by either resonances that create bumps, or by structures within the bands that reflect the **spin and angular distributions**. All these can be built in using the helicity formalism.

Let's quickly list what we need to incorporate to apply the helicity formalism. We need to know:

*   The **spins of the particles**.
*   What to put for the **reduced matrix elements**.
*   What to put for the **resonance propagator**. (see @fig-fg3)
In the isobar model, the propagator is parameterized by a relativistic Breit-Wigner function:
  $$\mathcal{P}_R(s) = \frac{1}{m_R^2 - s - i m_R \Gamma_R(s)}$$  
Therefore, we need the **mass** ( $m_R$ ) and **width** ( $\Gamma_R$ ) for each resonant state. The formalism also requires the resonance spin  $J$ .

Let's look at the plot and identify, for every two-particle combination, the masses, widths, and spins of the prominent resonances.

*   ** $K\pi$  combination (horizontal bands):**
*   How many bands do you see? One clear horizontal band.
*   This is the  $K^*(892)$ . Its spin-parity is  $1^-$ . It's the first radial excitation, essentially the rho meson of the strange sector.

*   ** $K p$  combination (vertical bands):**
*   How many do you see? Two.
*   The first is the  $\Lambda(1520)$ , with spin-parity  $3/2^-$ .
*   The second is likely the  $\Lambda(1690)$ , also  $3/2^-$ . (see @fig-fg5) These negative parity states belong to the P multiplet, meaning there is orbital angular momentum between the quarks. 




![This figure shows a schematic representation of a resonance in a two-body invariant mass spectrum, as described in the context of the lecture's discussion of resonance propagators and the Breit-Wigner parameterization. The horizontal axis represents the invariant mass of a two-particle system,  $(m_1 + m_2)$ , while the vertical axis corresponds to the event rate or probability amplitude.  The resonance manifests as a prominent peak, centered at the resonance mass  $m_R$ . The width of the peak, denoted by  $\Gamma$ , characterizes the decay width (or inverse lifetime) of the intermediate resonance state. This shape is modeled by the Breit-Wigner resonance amplitude, a key dynamic function used in the isobar and cascade decay models to describe intermediate resonances in multi-body decays.  Physically, this plot illustrates how a resonance like  $K^*(892)$ ,  $\Lambda(1520)$ , or  $\Delta(1232)$  appears in the invariant mass spectrum of its decay products, with the position and width of the peak directly encoding the resonance’s mass and decay properties.](2025-Lecture-07-images/fig9.png){#fig-fg9}

 




![This figure illustrates the characteristic behavior of a resonance amplitude’s real and imaginary parts as a function of the Mandelstam variable  $s$ , which typically denotes the invariant mass squared of a two-body subsystem in a decay or scattering process.   On the left, the plot shows the imaginary part of the amplitude,  $\text{Im}(a)$ . It displays a peak at  $s = m_R$ , where  $m_R$  is the mass of the resonance. This reflects the fact that, according to the Breit-Wigner parameterization, the imaginary part of the amplitude becomes largest when the invariant mass of the system matches the resonance mass, representing the maximal probability for the resonance to be produced on-shell.  On the right, the plot shows the real part of the amplitude,  $\text{Re}(a)$ , versus  $s$ . Here, as  $s$  increases through the resonance region, the real part exhibits a characteristic "phase motion," smoothly crossing zero at  $s = m_R$  and changing sign. This behavior is a direct consequence of the analytic properties of the Breit-Wigner (or more generally, resonant) amplitude and is closely related to the unitarity and analyticity constraints discussed in the lecture. The total amplitude thus traces out a circular trajectory in the complex plane as  $s$  varies, resulting in a rapid change in phase (typically by about  $\pi$ ) as the system passes through the resonance.  Physically, these features—peak in  $\text{Im}(a)$  and phase motion in  $\text{Re}(a)$ —are signatures of resonant behavior and are used to identify and characterize hadronic resonances in Dalitz plot analyses and partial wave expansions. The figure matches the lecture’s context, where these generic features of resonance line shapes and their relation to analytic properties of amplitudes are discussed as foundational concepts for parameterizing dynamic functions using the Breit-Wigner form.](2025-Lecture-07-images/fig11.png){#fig-fg11}






*   ** $\pi p$  combination (diagonal band):**
*   You can see a diagonal line. This is the  $\Delta(1232)$  with spin-parity  $3/2^+$ .


::: callout-important
The total amplitude for the decay  $X \to p K \pi$  is a **coherent sum** over these intermediate resonance channels ( $R$ ):
  $$\mathcal{A}(X \to p K \pi) = \sum_{R} \mathcal{A}(X \to R + \text{spectator}) \times \mathcal{A}(R \to \text{final particles})$$  
Each resonance amplitude is built from a Breit-Wigner propagator, a reduced matrix element, and Wigner rotation matrices  $D^J$  that encode the spin and angular distributions via the helicity formalism.
:::

In principle, you are now equipped to take the equations and draw the Dalitz plot. You would insert the mass and width from the PDG for these three resonances, use their spins, and construct the amplitude.

However, a complication arises because we have a proton with spin in the final state. If you incorporate this particle blindly using the helicity formalism for different decay chains—each quantized along a different axis—it won't be done correctly. If all final-state particles were scalars, the procedure would be straightforward.



## Preview of Advanced Parameterizations

So, any questions? We are approaching the end of our current topic.

I believe the next lecture will focus on **dynamic functions**, specifically discussing the **Breit-Wigner parameterization**.

We will cover:

*   More advanced parameterizations of the **phase shift**.
*   The constraints on **line shapes** imposed by **unitarity** and **analyticity**. (see @fig-fg11)

::: callout-note
This segment concludes the current lecture chunk (Chunk 7). The upcoming discussion on the Breit-Wigner form will build upon the foundational concepts of resonance parameterization introduced earlier.
:::

