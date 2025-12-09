---
title: (2025) Lecture 11
author: ''
presenter: Mikhail Mikhasenko
note_taker: Anna Zimmer
date: '2025'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



## Branch Points and Cuts in ππ Scattering Amplitudes

So the **threshold for ππ scattering** occurs at  $s = 4m_\pi^2$ .

Are there any other open channels? For this discussion, let's assume there are not.

The **position of the branch point** in the complex  $s$ -plane is precisely at  $s = 4m_\pi^2$ . The associated **branch cut** should be drawn from this branch point. While the exact direction is technically a matter of definition, the **physical branch cut** that satisfies causality is drawn along the real axis **to the right**, from  $s = 4m_\pi^2$  to infinity.


::: callout-important
**Physics of the s-channel branch point:**
This point,  $s_{\text{th}} = 4m_\pi^2$ , is the minimum squared center-of-mass energy needed to produce two real pions. In the complex plane, it is a **square-root branch point**. Placing the cut along the positive real axis defines the **physical Riemann sheet**, where the scattering amplitude is analytic except for discontinuities across this cut.
:::

We must also consider **crossing symmetry**. The reaction isn't only  $\pi\pi \to \pi\pi$  in the  $s$ -channel. If we consider the ** $t$ -channel** (the crossed channel), a different process becomes relevant.

For the specific process  $\pi^+ \pi^- \to \pi^+ \pi^-$ , the  $t$ -channel corresponds to the scattering  $\pi^+ \pi^+ \to \pi^+ \pi^+$  (or equivalently,  $\pi^- \pi^- \to \pi^- \pi^-$  after crossing).

This leads to **another branch point** in the complex  $s$ -plane, appearing at **negative  $s$  values** for physical momentum transfer  $t$ . This is the ** $t$ -channel threshold**.


::: callout-note
**Cross-channel analytic structure:**
Crossing symmetry implies the amplitude  $A(s,t)$  is analytic in  $s$  with cuts from both channels. The  $t$ -channel threshold at  $t = 4m_\pi^2$  corresponds to a branch point in the  $s$ -plane at  $s = 4m_\pi^2 - t$ . For physical  $t > 0$ , this point lies on the negative real  $s$ -axis, creating a **left-hand cut**. The full analytic structure—with a right-hand cut from the  $s$ -channel and a left-hand cut from the  $t$ -channel—is foundational for dispersion relations.
:::



## Analytic Continuation and Resonances in ππ Scattering

When we talk about scattering amplitudes, we are thinking of a blob connecting an initial to a final state. In that case, π₁ and π₂ scatter. We draw the blob and think of this as time going in that direction. This is the initial state. They come together, something happens, they come out of the blob, and that scattering process is referred to as a **channel**. This is well-defined kinematics and a physical process.

Once the energy in the initial state is higher than the threshold, the total energy of the system for this process to happen must be higher than  $4m_\pi^2$ . Then the pions in the initial state can fly and the pions in the final state can fly. It happens that there is another process.

### **Kinematic Variables and Analytic Continuation**

There are the variables that we defined here: it was  $s$  and here was  $t$ . For the physical process,  $s$  was positive above the threshold;  $t$  was negative because this is a transferred momentum, and for an elastic reaction it's actually less than zero. If we think of this amplitude as an analytic function of  $s$  and  $t$ , it is defined in the entire domain of the complex plane, in the entire domain of the variables  $s$  and  $t$ .

Once we define this object, it should be defined for any variable  $s$ , even negative, and for any variable  $t$ , even positive, despite them not being in the kinematics of this channel. We find out that the same amplitude would describe  $\pi_1 \bar{\pi}_3 \to \pi_2 \pi_4$ .

What I've done here is I took one particle, one leg here and said, let me just turn it, rotate this diagram. I take this leg, put it here, I take this leg, I put it here. It's the same blob, just in a different direction, so it must be the same object. We draw it and then we realize that it's just different variables of  $s$  and  $t$  that describe the kinematics for that process.

It's a  $t$  that has to be positive because it's above the threshold, because we are now in a different domain for this reaction. The  $t$  is defined as the sum of these two. The language that we use is that that is the **cross channel** for that.

*   In the **s-channel**,  $s = (p_1 + p_2)^2$  is the squared center-of-mass energy and must satisfy  $s > 4m_\pi^2$  for the physical process  $\pi\pi \to \pi\pi$ .
*   In the **t-channel**, the same analytic function  $A(s,t)$  describes the crossed process  $\pi_1 + \bar{\pi}_3 \to \pi_2 + \pi_4$ , where  $t$  becomes the positive squared center-of-mass energy. 




![This figure represents a schematic illustration of a **scattering process** in the context of scattering theory discussed in the lecture. The large circle can be interpreted as the "blob" denoting the interaction region or amplitude where an initial two-particle state (for example, two pions) interacts. The two darkened points on the circumference symbolize the **initial and final states** (or, more generally, the incoming and outgoing particles). The double-headed arrow connecting these points, with an "×" at the top, indicates the **scattering angle**, which is a key kinematic variable in the description of the process.  Physically, this diagram is used to visualize two particles approaching, interacting via the strong force inside the blob (the region where the amplitude is defined), and then emerging as outgoing particles. The **scattering angle** (as shown by the arrow) is directly related to the momentum transfer, which is often encapsulated by the **Mandelstam variable  $t$ ** in the lecture. This type of drawing is central to understanding **partial wave analysis** and to visualizing how the scattering amplitude depends on kinematic variables like  $s$  and  $t$ . The "×" at the top may indicate a measurement or a particular value of the angle of interest.   This picture is foundational for connecting graphical representations of reactions to formal analytic properties, such as branch points and cuts in the complex plane described in the lecture.](2025-Lecture-11-images/fig7.png){#fig-fg7}






In the  $s$  plane, once you do partial wave projections, you're going to see the reflection of the cross channels as the branch points on the other side. For physical positive and high value of  $s$ , it's an s-channel scattering. For negative  $s$ , it's a partial wave projection of the t-channel scattering or u-channel. The u-channel would be when you take this four and put it to the other side.

Just to remind you of what we discussed with this domain: if you draw here  $s$ , you put here  $t$ . Our physical reaction sits here. Then there is the cross channel positive  $t$ . There is a domain here and a domain here. That was for introducing this non-distant point.

### **Riemann Sheets and Resonance Poles**

In fact, this amplitude is a rather complex object. There are no singularities elsewhere in this plane. We discussed that we can come up with, in order to explore the full dimensionality or the full analytic structure, we can come up with another function, let's say not  $A$  but  $A_2$ , that analytically continues the amplitude on the other side of the branch point.

That was referred to as the **second sheet**, the second Riemann sheet. That's where the interesting and impactful physics is lying. These are the singularities I am talking about. Virtual states are on the other and physical. What I'm saying is that I can come up with the  $A_2$ ,  $\pi\pi \to \pi\pi$ , that analytically continues my amplitude from below the cut.

That amplitude will have a very similar analytic structure. We have the branch point here and this function will continue. The values right here above will be exactly the same as right below for that function. This is the location for the virtual state and this is the location for the resonances.


::: callout-important
The physical amplitude  $A(s)$  has a branch cut along the real axis for  $s \geq 4m_\pi^2$ . Analytic continuation through this cut leads to the **second Riemann sheet**, where resonance poles are located. Every particle corresponds to a pole in the complex plane of the scattering amplitude. For a resonance like the  $\rho$  meson, the pole is at  $s_p = M_\rho^2 - i M_\rho \Gamma_\rho$ , where  $M_\rho$  is the pole mass and  $\Gamma_\rho$  is the width.
:::

### **The ρ Meson in ππ Scattering and the Quark Model**

Which resonance is present in this scattering  $\pi\pi$  in P-wave? In fact, it's the  $\rho$  meson. I really like to think of mesons in terms of the quark model constitution. Let me just remind you what it is about:  $1s$ ,  $1p$ ,  $2s$ . Here I have a spin and  $\rho$  meson. I have a pion and another  $\rho$  meson. There's two  $s$  excitations.

Here I have states, four states. They're called a... On which axis would you put energy? And here they put angular momentum. Angular momentum. But in the quark model, angular momentum between quarks  $L_{q\bar{q}}$ . If you think of the quark of the hydrogen atom, this is what you find: the Bohr structure in the boxes,  $1s$ ,  $2s$ .  $1p$  is the sort of overall Bohr structure of the spectrum.

But then there is hyperfine splitting related to the spin-spin and spin-orbit interaction that makes splitting of the levels. Every time I'm talking about mesons, it's really helpful to think of this picture like this. I'm saying, you know,  $J/\psi$ ,  $\eta_c$ ,  $\chi_c$ . It's a  $c \bar{c}$ , right. And then where in the spectrum would it belong? It actually sits here. The first one is  $\eta_c$ . The second one is the  $J/\psi$ .

And then you say you hear  $\chi_{c2}$ . Where is that? Oh, this is again  $c \bar{c}$  but sits in this box because it's a  $1^+$  quantum numbers. This is the  $1P$  state in the quark model. That's super easy, and then you're able to relate to get a bigger picture. There are so many mesons and resonances, but they all map into this rather simple structure, well, if you don't talk about exotics, that's still a minority.

This was a side remark and that's... I would really like you to familiarize yourself with this type of representation for the mesons. For the baryons we can do the same. What is important for our discussion here is the singularities in the scattering amplitude.

I just said that the  $\rho$  meson decays to  $\pi \pi$ . This is one of the peculiarities of quantum chromodynamics because in the hydrogen atom, the transitions between states that are hyperfine, that are related within the same box, happen with radiation. In the hydrogen atom, the difference between these two states is actually the quark orientation.

The pion has the sort of the quark orientation disk like this one,  $q$  has the... So the wave function is like this. The  $\rho$  meson has a different spin wave function. That's the only reason, the only difference between the  $\rho$  meson and the pion in the quark model.

But the transition between  $\rho$  and  $\pi$ , despite that it can happen radiatively by emitting a photon and flipping the spin of the quark, it prefers to happen via emitting a pion. So  $\rho$  goes to the pion by emitting another pion. That's something unimaginable in a hydrogen atom. Imagine that the atom would decay by emitting another atom.

That's not how baryons... That's not how it works in electrodynamics, but in quantum chromodynamics it's sort of cheap to make quarks out of the vacuum, like quark-antiquark pairs. That's why the  $\rho$ -$\pi $transition happens with emitting another$ \pi $.

Therefore, a$ \rho $meson, while being a state, appears as a resonance in the$ \pi\pi $scattering system. If you bring one$ \pi $and another$ \pi $together, they feel that the$ \rho $meson can decay to this pair. So they resonate at a certain frequency, a frequency that is equal to the bare mass of the$ \rho $meson.

It's not only that a$ \rho $meson can decay to the pair, but also when you bring two pions together, they feel attraction due to the presence of this$ \rho $meson resonance. This attraction manifests as a peak in the spectrum when you measure the scattering amplitude, when you measure the scattering cross section. But also it manifests in a singularity in the complex plane, namely a pole.

Every particle is a pole in the complex plane in the scattering amplitude. In order to find this pole, we need to take the scattering amplitude with a rather clear, simple analytic structure and then look more closely at what's the origin of the peaking. This usually hides in the analytic continuation on the second sheet in the complex plane.



## Analytic Singularities and Cross-Section Signatures

Now this naturally continues our discussion. To wrap up the scattering theory, I would like to talk about **bound states, virtual states, and resonances**. We will introduce the complex plane that doesn't have any cuts—the key plane—and look quickly at the loop function for two-particle scattering. These concepts play a fundamental role not just in scattering theory, but also once you go to lattice field theory.

Today's lecture was meant to be dedicated to lattice field theory and how we use lattice computations to get a better understanding of resonances. I feel we will get to it in the last hour. So, we need to finish the classification of the states and their analytic properties before we go there.
Let's discuss virtual and bound states. Depending on where the singularity appears in the complex energy plane, we call the state differently. 




![This figure illustrates a potential well, which is used to explain the difference between continuum states and bound states in quantum mechanics, and by analogy, in scattering theory as discussed in the lecture. The vertical axis is the potential$ V$, and the horizontal axis is the position  $x$ .  - For energies  $E > 0$ , any energy is allowed, corresponding to **continuum states**. These are scattering states where the energy lies above the potential well, and the wavefunctions extend to infinity. - For energies  $E < 0$ , only **discrete energy levels** are allowed, corresponding to **bound states**. In this region, the wave number  $k$  becomes imaginary, leading to exponentially decaying wavefunctions (as indicated by  $e^{\pm ikx} \in \mathbb{R}$ ), signifying that the particle is localized within the potential well. - The dashed lines illustrate the quantization of energy levels for bound states, while a continuum of possible energies exists above the well for scattering states.  This relates to the lecture's discussion of **bound states** (poles on the physical sheet below threshold), **virtual states** (poles on the unphysical sheet), and **resonances** (poles above threshold in the complex energy plane). The diagram provides a conceptual and visual context for understanding how physical and mathematical properties of quantum systems manifest as different types of states, as classified by the analytic structure of the scattering amplitude.](2025-Lecture-11-images/fig1.png){#fig-fg1}




 It also appears differently in the measured mass spectrum.

*   If it's a bump **above** the threshold, we call it a **resonance**.
*   There are two more types: **virtual states** and **bound states**.
*   **Virtual states** are located on the **unphysical sheet** below the threshold.
*   **Bound states** are located on the **physical sheet** below the threshold. 




![This figure represents the energy spectrum of a quantum system, such as two particles interacting via a potential well—an important concept in scattering theory and resonance physics. The vertical axis is the energy  $E$ . The energy levels below zero ( $E < 0$ ) are labeled as "bound states (in potential well)," indicating discrete energy levels corresponding to stable or quasi-stable configurations where the particles are held together by the potential. These states manifest as poles on the physical sheet below threshold in the scattering amplitude.  Above zero energy ( $E > 0$ ), the spectrum becomes continuous—these are the "continuum states." Here, the particles are no longer bound and can propagate freely, representing scattering states. This continuum starts at the threshold (here,  $E=0$ ) consistent with the discussion of branch points in the analytic structure of the S-matrix at threshold (e.g.,  $s=4m_\pi^2$  for  $\pi\pi$  scattering).  Physically, this separation between bound and continuum states underlies key aspects of reaction theory: bound states relate to sharp spectral lines (e.g., stable particles), while continuum states enable phenomena like scattering, resonances, and virtual states near threshold. The energy threshold itself is a branch point in the analytic properties of the amplitude, and the nature of these states (bound, virtual, resonance, continuum) determines the analytic structure observed in physical processes.](2025-Lecture-11-images/fig2.png){#fig-fg2}






Let's think for a second what implication the pole's position has, and let's sketch how the measured spectrum would look in the presence of each: a bound state, a virtual state, and a resonance.


::: callout-important
**Classification of Poles in Scattering Theory**

*   A **bound state** (e.g., deuteron) corresponds to a pole on the **physical sheet** below the two-particle threshold, representing a stable particle.
*   A **virtual state** (e.g., neutron-neutron singlet state) corresponds to a pole on the **unphysical sheet** below threshold, leading to an enhancement near threshold without a true bound state.
*   A **resonance** corresponds to a pole in the complex plane **above** threshold, with an imaginary part related to its width.
:::

The cross section  $\sigma(s)$  that we measure in an experiment for scattering two particles is connected to the scattering amplitude  $A(s)$ . If the amplitude is dominated by a single partial wave, we can perform the angular integration analytically. For the simple case of scalar particle scattering, the angular dependence is given by a Legendre polynomial.

What remains is the following expression for the cross section in the presence of one partial wave with total angular momentum  $J$ :

  $$\sigma(s) = \frac{2J + 1}{k^2} |A(s)|^2 \rho(s).$$  

Here,  $k$  is the center-of-mass momentum, and  $\rho(s)$  is the phase space factor. For a two-body final state, this factor is:

  $$\rho(s) = \frac{2p}{\sqrt{s}}.$$  

This function  $\rho(s)$  starts from zero at the kinematic threshold and approaches a constant ( $\frac{1}{8\pi}$ ) at high energies. This factor causes the cross-section to rise from zero at threshold.


::: callout-note
**Threshold Behavior**
The cross-section for a partial wave with angular momentum  $L$  is suppressed near threshold by a factor proportional to the center-of-mass momentum:  $\sigma_L(s) \propto p^{2L}$  as  $s \to s_{\text{thr}}$ .

*   For an **S-wave** ( $L=0$ ), the cross-section is finite at threshold.
*   For a **P-wave** ( $L=1$ ), like the  $\rho$  meson in  $\pi\pi$  scattering, it vanishes at threshold.
:::

What we are exploring is how the number of interaction counts changes when you collide particles. The cross-section is essentially this probability. On the x-axis, we have the center-of-mass energy  $\sqrt{s}$ , and on the y-axis, we have  $\sigma(s)$  (or  $|A(s)|^2$ ). This probability reflects the properties of the amplitude and, internally, what singularities are present in the complex plane.

1.  **Resonance Case:** We collide two particles. If the energy is adjusted to the resonance mass, the probability to interact grows sharply. We see a peak in the cross-section. For example, the  $\rho$  meson decays to  $\pi\pi$ , making the  $\pi\pi$  scattering amplitude resonate at the  $\rho$  mass. The amplitude near a resonance often follows a Breit-Wigner form:
  $$A(s) \propto \frac{1}{s - M^2 + iM\Gamma}$$  
The distance of the pole from the real axis is related to the width  $\Gamma$  of the resonance. A smaller width means a narrower, taller peak.

2.  **Bound State Case:** A bound state corresponds to a pole on the real axis **below** threshold on the physical sheet. In the amplitude, this is a **strong singularity** (a pole, where the amplitude becomes infinite). Since we only measure **above** threshold, we don't see the infinity directly, but it produces a sharp enhancement or peak **right at the threshold** in the cross-section. A bound state is a real, stable particle (e.g., a deuteron). In a perfect world with only strong interactions and conserved flavor, particles like the proton or pion would be such bound states.

3.  **Virtual State Case:** A virtual state corresponds to a pole on the real axis **below** threshold, but on the **unphysical sheet**. Its influence is weaker than a bound state pole. It typically does not produce a sharp peak but rather a **cusp or a broad enhancement** very close to the threshold in the cross-section.

In contrast to poles, a **branch point** (like the one at the kinematic threshold from  $\rho(s)$ ) is a weaker singularity. The function is continuous, but its derivative is not. You might observe a slight change in slope—a cusp—but not a divergent peak.



## Analyticity and the Breakup Momentum Plane

Another convenient representation of the singularity of the scattering amplitude is the **breakup momentum plane**. This is because the scattering amplitude is an analytic function of the breakup momentum  $p$  in non-relativistic scattering.

In a non-relativistic problem, you do not have a square root of  $s$  anywhere. You only deal with  $p$ . If you look at the expression for  $\rho$ , where  $\rho = 2p / \sqrt{s}$ , in the non-relativistic limit this denominator becomes  $2\mu$ .

What you can do is expand the amplitude near the threshold. You expand the amplitude in  $\sqrt{s}$  near the first branch point, and then you arrive at the expression for  $p$ :

  $$p = \sqrt{2\mu (E - E_{\text{th}})}$$  

This quantity has a branch point at  $s = s_{\text{th}}$  because it is under a square root, and that matches the branch point of the amplitude.

You can do the inverse relation and find how  $s$  is related to  $p$ . The point is that if the amplitude is an analytic function of  $p$ , the square root will never appear. There is no square root of  $p$  in the amplitude. The amplitude is actually an analytic function of  $p$ .

What we have discussed with the first and second sheet now gets merged to a single complex plane. The upper part represents  $A(p)$  or  $A(s)$ , and the lower part is  $A_2(s)$ . The real physics—where  $p$  is real and positive—corresponds to the physical values of  $s$ .

I want to quickly sketch where the bound and virtual states are. In that representation:

*   A **bound state** is sitting on the real axis just below the threshold.
*   A **virtual state** is on the real axis, above the threshold.
*   **Resonances** appear as poles off the real axis in the complex plane.

This is the breakup momentum plane. You often see this representation; people who do non-relativistic field theory always use the  $p$ -plane. 




![This figure represents the analytic structure of the scattering amplitude in the complex energy (E) plane, focusing on the physical meaning of singularities in scattering theory. The horizontal axis is the real part of energy, with the "threshold" marked as the point where the two-particle continuum begins (e.g.,  $E = 2m_\pi$  for  $\pi\pi$  scattering, or generally  $E_{\text{th}}$ ).   To the left of the threshold, the X's denote **bound states**—these correspond to poles of the scattering amplitude that lie on the real axis below the threshold. Such poles signal true stable particles or bound states of the two-body system.   From the threshold onward, the wavy line indicates the **branch cut**, which corresponds to the onset of **continuum states**: the region where two real particles can be produced and propagate freely. This branch cut arises from the multi-particle (continuum) nature of the spectrum above threshold, reflecting the analytic (non-pole) singularity structure of the amplitude.   The figure thus illustrates the key idea that the amplitude is analytic except for isolated poles (bound states) and a branch cut starting at threshold (continuum states), which together determine much of the physical and analytic behavior of scattering processes.](2025-Lecture-11-images/fig3.png){#fig-fg3}




 It is somewhat simpler because you draw one picture and you see all objects there. But it works as an expansion around the threshold. It will not work once you have higher thresholds and more branch points.


::: callout-note
The breakup momentum can also be expressed relativistically in terms of the Mandelstam variable  $s$ :
  $$p = \sqrt{2\mu (\sqrt{s} - \sqrt{s_{\text{th}}})}$$  
This shows the branch point at  $s = s_{\text{th}}$  explicitly.
:::

Let me summarize to close this chapter. We considered scattering theory or reaction theory that is widely used in hadron spectroscopy. This approach, in contrast to field theory, does not start from the Lagrangian, but rather uses general properties of scattering theory to study hadron-hadron scattering.

It relies on the principles of **unitarity, analyticity, and crossing symmetry**, and interprets and identifies resonances as the poles of the scattering amplitudes. The main object in this approach is the amplitude. The amplitude is something one has to construct satisfying these general principles.

Once it is constructed and fixed by experiment, it can further be studied to quantify resonance properties as pole positions and pole strength, which is the residues of the pole. The function  $A(s)$ , once fixed by the experimental data, provides us with its rich analytic structure, access to all of the artifacts that are in there, namely branch points, but also unphysical sheets where the resonance is sitting.

What I do in experimental particle physics is constrain this amplitude using experimental data, and then continue it analytically. I find the poles and quantify them with the position of the pole as well as the Cauchy integral around it that gives me a residue—how strong the pole couples to a particular channel.

These variables, once measured, get tabulated in the Particle Data Group. The next time I want to know something about the scattering of two particles or a particular decay of a particle to a system, these numbers provide me the answer.

*   The **mass** is the real part of the pole position.
*   The **width** is related to how deep the pole is in the complex plane.
*   The **coupling** is how strong this resonance couples to this particular system or the residue of the pole.

  $$A(s) \approx \frac{g^2}{s - s_{\text{pole}}}, \quad \text{where } s_{\text{pole}} = M^2 - iM\Gamma$$  

All right, so questions here. What will change in all these things if we add spin to the particle? For example, you have explained how we explain  $\pi\pi$  scattering into  $\pi\pi$ . But if I want to describe  $\rho\rho$  scattering to  $\rho\rho$ , will the presence of spin interaction pop up somewhere? The short answer is no.

What will change is just **kinematics**. Properties and analyticity—properties of the amplitudes. Kinematics is a good word to say that what will happen is the amplitude will have extra kinematic factors at threshold and it will not be a single amplitude, but rather a vector of amplitudes because there are different helicities.

If you sum over helicities for the cross section you sum over them. But amplitudes are still carrying the index. So if it is  $\rho\rho$  scattering, then you can scatter  $\rho\rho$  with different helicities. So there is not a single amplitude, but several amplitudes. But otherwise, that is right. Everything holds for spin.

Since it is a very wide subject and there are a lot of technicalities, let me start by first covering the program and what we are going to overview and how lattice field theory helps in understanding QCD. Then we will fill in the details.



## Lattice QCD: Discretizing Confinement

Quantum Chromodynamics (QCD) is the gauge theory with the **SU(3)** gauge group that is notoriously difficult to deal with. It has the defining properties of **confinement** and **asymptotic freedom**, driven by the self-interaction of gluons described by the Lagrangian:

  $$\mathcal{L}_{\text{QCD}} = \bar{\psi}_i \left( i \gamma^\mu D_\mu - m_i \right) \psi_i - \frac{1}{4} G^a_{\mu\nu} G_a^{\mu\nu}$$  

where the covariant derivative is  $D_\mu = \partial_\mu - i g_s t^a A^a_\mu$  and the gluon field strength tensor is  $G^a_{\mu\nu} = \partial_\mu A^a_\nu - \partial_\nu A^a_\mu + g_s f^{abc} A^b_\mu A^c_\nu$ .

### **Asymptotic Freedom and Confinement**

*   **Asymptotic Freedom:** When the momentum with which we probe the system becomes very large, quarks appear as nearly free objects. This is described by the **running** of the strong coupling constant:
  $$\mu \frac{d\alpha_s}{d\mu} = \beta(\alpha_s) = -\frac{\beta_0}{2\pi} \alpha_s^2 - \frac{\beta_1}{4\pi^2} \alpha_s^3 + \mathcal{O}(\alpha_s^4)$$  
where  $\alpha_s = g_s^2/(4\pi)$ . The negative sign of the  $\beta$ -function at leading order causes the coupling to decrease at high energies.

*   **Confinement:** At low energy, the system confines. This is the reason for the appearance of all composite particles called **hadrons**. The interaction strength becomes large at a scale of roughly **1 femtometer**, which is set by the **confinement scale**:
  $$\Lambda_{\text{QCD}} = \mu \, \exp\left( -\frac{2\pi}{\beta_0 \alpha_s(\mu)} \right)$$  
This is the scale where color exchange happens, and only color-neutral (colorless) objects are observed.

The property of confinement, driven by a large coupling  $\alpha_s$  at low energy, makes QCD very difficult to study analytically. Our standard methodology of **perturbation theory** and Feynman diagrams fails because there is no small parameter to order the diagrams—producing two or three gluons can be more probable than producing one.

### **Lattice QCD: A Computational Framework**

To study QCD non-perturbatively, we must use alternative methods. The most productive method over the last 30 years has been **lattice QCD**. This is a computational framework that takes the theory of strong interactions as it is and computes its properties by discretizing space-time onto a grid.


::: callout-important
The core idea is to create a **finite "laboratory" box** in space-time (e.g., 2 fm × 2 fm × 2 fm in space), fill it with quantum fields, solve the equations to evolve these fields in time, and then evaluate any quantum properties of the objects within this box. We can place theoretical "probes" inside this laboratory to measure their properties.
:::

To make the problem tractable for a computer, we discretize both space and time. Instead of a three-dimensional box evolving in time, we work with a **four-dimensional box** where time is simply another axis. This makes the problem symmetric with respect to all coordinates.

*   The step size in all directions (an **isotropic lattice**) is a small distance  $a$ , typically **0.1 fermi or less**.
*   The physical box size is typically a few fermi (2 fm is common), though sometimes a larger box is needed.

The gauge part of the QCD action on this discrete lattice is given by the **Wilson gauge action**:

  $$S_G[U] = \frac{2}{g_0^2} \sum_{x} \sum_{\mu < \nu} \text{Re}\, \text{Tr} \left[ 1 - U_{\mu\nu}(x) \right]$$  

where  $U_{\mu\nu}(x) = U_\mu(x) U_\nu(x+\hat{\mu}) U_\mu^\dagger(x+\hat{\nu}) U_\nu^\dagger(x)$  is called a **plaquette**, and  $g_0$  is the bare lattice coupling. This formulation maintains gauge invariance on the discrete grid.



## Lattice QCD: Mesons, Boundary Conditions, and Quark Mass Tuning

Since the size of a meson is on the order of a Fermi, we want it to fit inside the simulation volume. Therefore, the lattice must be larger than one fermi to contain the meson and allow us to evaluate its properties.

We implement **periodic boundary conditions**, which is like mirroring the entire setup on all sides. The primary meson is placed inside this box. The lattice must be large enough so the meson fits comfortably but is also sufficiently small compared to the total box size. This prevents the meson from feeling significant forces from its mirrored images created by the periodic boundaries, an interaction we aim to neglect.


::: callout-note
Periodic boundary conditions mean the field value at one coordinate equals the field value at the mirrored coordinate. This is equivalent to filling all of space with identical copies of the primary lattice cube.
:::




![This figure represents the **spectrum of energy levels in a finite volume** (such as a finite-size box in lattice QCD), depicted along the "energy plane." The **threshold** marks the point at which two-particle states can be produced (e.g., the  $\pi\pi$  threshold in  $\pi\pi$  scattering). To the left of threshold, discrete "bound states" are shown.   When space is made finite with periodic boundary conditions (of spatial extent  $L$ ), the momenta—and therefore the energies—of the system become **quantized** rather than continuous. This is illustrated by the sequence of discrete x-marks (energy eigenvalues) above the threshold, with a characteristic spacing determined by the box size: the allowed momenta are separated by  $2\pi/L$ .   **Physical meaning:** In a finite volume, such as on a lattice, energy levels are no longer a continuum but become discretized. The spacing between these allowed energy levels is set by the finite size of the box. Bound states remain as isolated discrete levels below the threshold, while above threshold (where, in infinite volume, one would have a continuum of scattering states), the energy spectrum consists of a series of discrete, closely spaced levels. The analysis of these discrete spectra on the lattice allows the extraction of infinite-volume scattering amplitudes via techniques like Lüscher's method.](2025-Lecture-11-images/fig6.png){#fig-fg6}






The evolution of fields, like a pion, happens within this lattice. While the pion itself may not propagate far, we observe the dynamics of fields bubbling in the vacuum. The typical setup uses isotropic spacing, but sometimes anisotropic lattices are used, with different spacing in time versus space.

The computational program proceeds as follows:

1.  Start from the QCD Lagrangian.
2.  Perform a **Wick rotation** to Euclidean time,  $t_E = -i t$ , to define fields in Euclidean space.

The resulting Euclidean action is:
  $$S_E = \int d^4x_E \left[ \frac{1}{4} F_{\mu\nu}^a F_{\mu\nu}^a + \sum_f \bar{\psi}_f (\gamma_\mu D_\mu + m_f) \psi_f \right].$$  

3. Physical observables are computed as expectation values via the path integral:
  $$\langle \mathcal{O} \rangle = \frac{1}{Z} \int \mathcal{D}[U] \mathcal{D}[\bar{\psi}, \psi] \, \mathcal{O} \, e^{-S_E[U,\bar{\psi},\psi]}.$$   




![This figure illustrates the setup for **two-particle scattering in a periodic box**, as is common in lattice QCD calculations. The potential  $V$  sits in the center of a finite spatial region of length  $L$ , represented by the box. The wavefunction  $\psi(x)$  describing the relative motion of the two particles is subject to **periodic boundary conditions**:  $\psi(-L/2) = \psi(L/2)$  and  $\psi'(-L/2) = \psi'(L/2)$ . These boundary conditions mean the system is placed in a finite, repeating (periodic) spatial volume, mimicking the setup used in lattice QCD. The physical meaning is that in this finite box, the allowed energy levels become discrete, and by analyzing these discrete levels, one can infer information about scattering phase shifts and resonance properties in infinite volume using methods like Lüscher's formula. This technique underpins how one extracts scattering amplitudes and resonance parameters from lattice simulations of QCD.](2025-Lecture-11-images/fig5.png){#fig-fg5}






This formulation makes the integrand real and enables the use of Monte Carlo integration techniques. From here, we can approach problems like two-particle scattering on the lattice. While direct scattering is not possible in a finite volume, we can infer interaction information using finite-volume methods like **Lüscher's formula**.

The QCD Lagrangian has few parameters: a coupling strength  $g$  and the quark masses. In the lattice setup, we define the lattice spacing  $a$  and grid size  $L$ , and tune these parameters. For an operator with pion quantum numbers, a bound state will appear at a specific energy level, giving the pion a mass for that parameter set.

This mass does not have to be the physical 140 MeV. We have parameters to tune—the up, down, and strange quark masses, and the coupling  $g$ —to adjust the pion mass to its physical value. This tuning is possible because hadronic phenomena change continuously with quark mass.


::: callout-important
The QCD Lagrangian and strong interactions are continuous functions of quark masses. By varying masses in simulations, we can continuously observe how hadron properties evolve, providing a powerful tool for understanding phenomena like the transition of resonances into bound states.
:::

For example, the  $\rho$  meson is a resonance in the  $\pi\pi$  system. If we make the quark masses heavier in the simulation, the resonance width becomes smaller. Eventually, the pole moves to the real axis in the complex plane, and the  $\rho$  becomes a bound state. This trajectory is described by:
  $$\sqrt{s_\rho}(m_q) = M_\rho(m_q) - \frac{i}{2} \Gamma_\rho(m_q).$$  

Lattice QCD allows us to perform this numerical experiment, tracing the pole position as a function of quark mass across different lattice sizes and discretizations.

The computational cost depends heavily on the quark masses. Calculations become more expensive as the pion becomes lighter because the pion mass appears in a denominator in relevant uncertainty relations. The uncertainty grows as quark masses decrease.

This is tied to the pion's role as a Goldstone boson. In the chiral limit, its mass vanishes according to the relation from chiral perturbation theory:
  $$m_\pi^2 = 2B m_q + \mathcal{O}(m_q^2).$$  

Therefore, computations near the chiral limit could become infinitely expensive, necessitating the use of approximations like chiral perturbation theory to extrapolate results.



## Lattice QCD: From Continuum Fields to Euclidean Path Integrals

For example, what does it mean that the quark mass is very large? Does it have dimension? On the lattice, we work with dimensionless variables. How do we define the mass? It should be something dimensionless—specifically, the ratio to the lattice spacing  $a$ .

The computational cost depends on the magnitude of  $a$ . We use  $a$  as a natural scale, so everything is expressed in units of the discretization spacing. For instance, to have a pion at 140 MeV, we can choose different  $a$  parameters. What is optimal? A finer lattice is better but more expensive. Therefore, what constitutes a good lattice depends on your specific goals.

There is also the notion of the continuum limit on the lattice. When discussing computational cost, the  $a$  parameter is not the only factor. For the same value of  $a$ , different pion masses lead to different convergence rates. The number of samples needed to control statistical uncertainties varies. I will clarify this point further.

The **QCD Lagrangian in Minkowski spacetime** is a scalar quantity written as  $G_{\mu\nu} G^{\mu\nu}$ , where  $G_{\mu\nu}$  is the gluonic field strength tensor. This represents the gluonic field tensor contracted with itself, with all repeated indices summed over. There are eight gluonic fields. Here,  $\mu$  and  $\nu$  are Lorentz indices, reflecting the relativistic Lorentz group properties of the fields.

Gauge invariance is enforced by extending the ordinary derivative to include the gluonic field. The fermionic fields represent the quarks, which interact with the gluons. This interaction is prescribed by gauge theory through a specific term coupling quarks and gluons. The quark mass term is present explicitly. The parameters are the coupling constant  $g$  and the quark masses; everything else is fixed.


::: callout-note
The full QCD Lagrangian density is:
  $$\mathcal{L}_{\text{QCD}} = -\frac{1}{4} G_{\mu\nu}^a G_a^{\mu\nu} + \sum_f \bar{\psi}_f (i \gamma^\mu D_\mu - m_f) \psi_f$$  
where  $D_\mu = \partial_\mu - i g A_\mu^a T^a$  is the covariant derivative and  $G_{\mu\nu}^a = \partial_\mu A_\nu^a - \partial_\nu A_\mu^a + g f^{abc} A_\mu^b A_\nu^c$ . The index  $f$  runs over quark flavors.
:::

We have fields: the gluonic fields  $A_\mu$  and the quark fields  $\psi$ . By "fields," we mean that both  $\psi$  and  $A_\mu$  are functions of a point in spacetime. Any physical observable can be computed as an **expectation value** of an operator:
  $$\langle \mathcal{O} \rangle = \frac{\langle 0 | T \mathcal{O} | 0 \rangle}{\langle 0 | 0 \rangle}$$  
This operator depends on the fields. You construct it from quarks and gluons, and its expectation value is computed by "sandwiching" it with the vacuum state; the result is an observable number, not a function of coordinates.

*   **Local operators** are evaluated at a single spacetime point.
*   **Non-local operators** are evaluated at multiple points.

Following Feynman's ideas, the **path integral technique** provides a way to compute this expectation value using a functional integral:
  $$\langle \mathcal{O} \rangle = \frac{1}{Z} \int \mathcal{D}A_\mu \mathcal{D}\psi \mathcal{D}\bar{\psi} \, \mathcal{O} \, e^{i S}$$  
where  $Z$  is the partition function (the same integral without  $\mathcal{O}$ ) and  $S = \int d^4x \, \mathcal{L}_{\text{QCD}}$  is the action.

The action  $S$  weights different field configurations. For any given configuration—a complete map of what  $A_\mu$ ,  $\psi$ , and  $\bar{\psi}$  are at every point in spacetime—you can compute this weight factor by integrating the Lagrangian. The functional integral sums over *all possible* such configurations. Here,  $\psi$  and  $\bar{\psi}$  are independent **Grassmann variables** (anti-commuting numbers).

This formulation is impractical for direct computation because the weight factor  $e^{iS}$  is a complex function that oscillates rapidly, preventing convergence in numerical sampling.

The essential trick for lattice QCD is the **Wick rotation to Euclidean time**. We change from Minkowski time to Euclidean time  $t_E$ , defined by  $t_E = -i t$ . This transforms the metric and the Lagrangian.


::: callout-important
Under the Wick rotation, the Minkowski action  $S = \int d^4x \, \mathcal{L}$  becomes a Euclidean action  $S_E$ . The factor  $e^{iS}$  becomes  $e^{-S_E}$ , which is a **real, positive weight** between 0 and 1 (for a positive action). This allows configurations to be interpreted probabilistically and enables Monte Carlo sampling.
:::

For example, in a simple scalar field theory, the transformation introduces an overall minus sign, making the Euclidean Lagrangian real. For QCD, the time derivatives and gamma matrices must be adjusted accordingly, but the outcome is the same: we obtain a real, positive weighting factor  $e^{-S_E}$ .

Finally, another key trick is to **integrate out the fermionic fields**. The original path integral involves three types of fields:  $\bar{\psi}$ ,  $\psi$ , and  $A_\mu$ . The fermionic part of the action has a Gaussian form in the Grassmann variables. Performing this functional integral yields the **determinant of the Dirac operator matrix  $M$ **.

The gluonic field, which drives confinement and thermodynamics, remains and is the most challenging part. Integrating out the fermions simplifies the problem to working with an effective theory involving only the gluon fields, weighted by  $e^{-S_g} \det(M)$ . This is the basis for **quenched approximations**, where  $\det(M)$  is set to a constant.

I will put the details of the quenched calculation on the board and continue this discussion next time.



## Grassmann Variables and Lattice QCD Computations

One thing to consider is to look at the simple example of the Grassmann variable. Grassmann means that they are anticommuting. So if  $X$  and  $Y$  are Grassmann variables, it means  $XY = -YX$ .

For every Grassmann variable,  $X^2 = Y^2 = 0$ . That is clear because  $(XY)^2$  is also equal to zero. If you write  $XYXY$  and anticommute, you will see  $X^2$  and  $Y^2$ , which are zero. So this is also zero.

In fact,  $e^{1 - XY} = 1 - XY$ . Isn't it amazing? You do a fermion expansion just like that. We do not cut any higher power terms.

For Grassmann variables, integration is introduced as differentiation. That's mind-blowing. It's a definition: integration for Grassmann variables is defined as differentiation.

So,  $\int dX \, X = 1$  and  $\int dX \, 1 = 0$ . Therefore,  $\int dX \, dY \, e^{-XY} = 1$ . If you put any constant  $a$  here, it's equal to  $a$ .

You didn't explain how that determinant pops up from  $M$ . There is a formula. One can do this trick by considering two variables, say  $x_1, x_2$ . Even in that case you get a determinant. Probably there is some expansion; it's a determinant.

If we integrate over the gluonic fields, what remains of the fermionic field is that integral over all possible configurations of the quark fields. Our operator depends only on the gauge fields; the determinant remains from the quark fields and a weight factor that has the action expression.

This determinant represents the effect of virtual quarks. All quarks are integrated. Therefore, the only effect we see is  $Q \bar{Q}$  popping up from the vacuum. It's purely an expression that only cares about gluons. The only effect quarks can have in this expression is popping up in loops.

Now another piece of important terminology: **quenched** and **unquenched** calculations refer explicitly to this term. This is used almost as slang.

*   Every time you hear in lattice calculations that they do **quenched** calculations, it simply means that this determinant term has been ignored. You literally throw it; there are no quarks in loops.
*   In fact, this universe where there are no quarks in loops is not that different. These computations already provide valuable insights into what QCD looks like. And it's much cheaper computationally. This integral converges numerically much quicker if you throw the term.

I want you to hear the words **quenched** and **unquenched** and immediately map them to the determinant that remains from the fermionic field integral.

The last thing I wanted to say is how we proceed with computing this integral. The naive way is to just discretize space, and then all possible values on the side of the lattice are your integration variables. The lattice is 100 by 200; this is time, this is space.

How many variables do we need to keep on every site?  $A$  is a function of  $x$ , and how many variables does this  $A$  have? It's  $A_\mu$ . Therefore, it's 4 times 9, plus maybe times 2 for complex. So how many? I've got 60. If I take this approach, I need to replace this  $DA$  with 10 billion integrals because every lattice site has four variables. It's going to be a huge amount of integrals.

If every integral has a certain dimension, like from  $A$  to  $B$ , numerically this integral could be computed by discretizing this  $A$  to  $B$  space. Therefore, if I put two points or three points in every dimension, I'm going to get  $3^{10 \text{ billion}}$  evaluations. That's much more than the age of the universe. If an evaluation takes a nanosecond, you will probably have to wait still  $10^{20}$  universe times. It's impossible.

So that's not what we are going to do. Instead, people use the **Monte Carlo sampling** method where different configurations are sampled randomly with a certain weight. That technique allows us to calculate this integral more efficiently. For lattice calculations, discretize space and space-time, use Minkowski transformations and the Monte Carlo sampling technique for the weights. You can also come to that trick of getting rid of the fermions.


::: callout-note
**On Splitting the Action and the Matrix  $M$ **
How is it possible that we can split the fermionic and gluon part of the action? We don't split. The fermionic part is  $\int e^{\int d^4x \, \bar{\psi} (D\!\!\!\!/ + m) \psi}$ . Once you integrate over  $\psi$ , the matrix  $M$  that appears still depends on the gluon fields  $A$ .

*    $M$  is a discretized version of the  $D\!\!\!\!/ + m$  matrix.
*   Why is it  $+m$  and not  $-m$ ? This sign happens when we flip the derivative. The  $D_\mu$  operator: we flip the time derivative so that  $dt$  becomes  $-dt$ . We also flip the gamma matrices differently for space and time. For time it doesn't get flipped at all; for space it gets flipped with an  $i$ . Overall, the effect is that you have a  $D_4$  with a minus sign here. So the minus appears here.
:::

**Historical & Conceptual Questions:**

*   **On the Limit of Quenched/Unquenched:** Is there a limit where quenched and unquenched calculations converge into one? I don't see a limit. So it's just two independent approaches.
*   **On Grassmann Algebra:** How was Grassmann algebra developed and how did it come to physics? I know that it existed independently in mathematics. I would also be curious to learn. It's a trick, but it turns out to be very useful. You can do quite a bit with that.
*   **On the Usefulness of Grassmann Variables:** What still confuses me: it looks like these variables are quite limiting. From those properties you cannot do much with them; they truncate series. You cannot square them, but apparently you can use this variable to describe fields. Even so, I do not know how, but maybe I learn one day.



## Neutron-Nucleus Interaction and Cross-Section

The next thing we need to do is to look at the interaction of the neutron with the nucleus.

The neutron is a neutral particle, so it does not feel the **Coulomb barrier**. It can get very close to the nucleus, meaning the interaction is purely **nuclear**.

Consequently, the cross-section for the neutron to interact with the nucleus is essentially the **geometric cross-section** of the nucleus:
  $$\sigma \approx \pi R^2$$  
where  $R$  is the nuclear radius.

For a typical nucleus, the radius is given by:
  $$R \approx 1.2 \, A^{1/3} \, \text{femtometers}$$  
This results in a cross-section on the order of **barns**, where one barn is defined as  $10^{-28}$  square meters.

Now, if the neutron has **very low energy**, we enter the regime of **s-wave scattering**. In this regime, the cross-section can become **much larger than the geometric cross-section** due to:

*   Resonance effects.
*   The presence of bound states near zero energy.

This enhanced low-energy interaction is quantitatively described by the **scattering length**.


::: callout-note
The geometric cross-section  $\pi R^2$  provides a useful baseline. However, the actual neutron-nucleus interaction cross-section, especially at low energies, is governed by quantum scattering theory and can deviate significantly from this simple geometric picture.
:::




![This figure illustrates the quantum mechanical scattering of a particle (such as a neutron) off a potential well, as applied to low-energy neutron-nucleus interactions discussed in the lecture. The horizontal axis is position  $x$ , while the vertical axis represents the potential  $V(x)$ . The central feature is a potential well of width  $R$  and depth  $u_0$ , representing the nuclear force region.   Above the well, a blue curve marked  $E > 0$  indicates the energy of an incoming neutron, which is positive, corresponding to a scattering state rather than a bound state. The blue (and yellow) wavy lines indicate the wavefunction of the incoming and outgoing neutron: outside the potential well, the wavefunction oscillates with constant amplitude, representing a free neutron; inside the well, the wavefunction is modified by the attractive potential.  The figure shows that for a neutral particle like the neutron (which does not face a Coulomb barrier), the particle can approach arbitrarily close to the nucleus and interacts with the nuclear potential. If the neutron energy is low (as in the s-wave regime), it is highly sensitive to the details of the potential, which can lead to enhanced scattering cross-sections, particularly if a bound or virtual state is near threshold.  The potential well depth  $u_0$  and width  $R$  correspond to the geometric parameters of the nucleus, with the cross-section scaling as  $\sigma \sim \pi R^2$  at high energies, but possibly rising much higher at low energies due to quantum mechanical effects such as resonance or the presence of near-threshold states described in the lecture.](2025-Lecture-11-images/fig4.png){#fig-fg4}






