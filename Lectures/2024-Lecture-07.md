---
title: (2024) Lecture 7
author: ''
presenter: Mikhail Mikhasenko
note_taker: Ilya Segal
date: '2024'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



## PCC Mass, Binding Energy, and Lifetime Constraints

The particle is a hadronic molecule formed by the  $\Sigma_c$  and  $D^*$ . Neglecting inelastic channels, its internal structure is that of a molecular bound state. 




![This image represents the internal structure of a **hadronic molecule**, specifically illustrating a bound state of two hadrons. In the context of the lecture, it shows two color-singlet clusters (hadronic "bags"), each containing three quarks—one on the left with quark content  $cud$  (likely a  $\Sigma_c$  baryon) and one on the right with  $u\bar{c}$  (likely a  $\bar{D}$  meson). The connection between them indicates they are held together by residual strong forces, similar to the nuclear force binding nucleons in the deuteron. This depicts the concept of **hadronic molecules** discussed in the "Pentaquark State" section, where such states are interpreted as loosely bound systems of two hadrons (rather than five-quark bags), with their total mass close to the sum of the constituent hadron masses, and small binding energy.](2024-Lecture-07-images/fig1.png){#fig-fg1}






### Naming and Notation

<b>Q:</b> Should the particle be called PCC?
<b>A:</b> No, it is the **PCC bar** (formerly PC, updated last year). The C indicates charm content. In the notation, indices list heavy quarks because they are conserved in decay; light quarks are not listed. They can be recovered from the capital letter. For example,  $\Sigma$  indicates two light quarks (isospin). The S in SACC denotes a pentaquark (five quarks). SACC contains CC plus three others. The  $PCC^+$  has light‑quark content  $UG$ . The states we see in this particular channel are of this type.

<hr>

### Mass and **binding energy**

Roughly, the mass of the PCC bar is the sum of the masses of its constituents:

  $$M_{PCC} \approx m_{\Sigma_c} + m_{D^*}$$  

That defines the **binding energy**:

  $$B = m_{\Sigma_c} + m_{D^*} - M_X$$  

Neglecting **binding energy**, the mass is simply the sum of the constituent masses, which defines the threshold. Since the **binding energy** is small, the state sits at the threshold.

<b>Q:</b> What is the scale of the **binding energy**? Approximately 10 MeV? 100 MeV? Less than 10? More than 1?
<b>A:</b> Yes.

The mass of  $\Sigma_c$  is about  $2.5$  GeV, and the mass of  $D^*$  is about  $2$  GeV, so the sum is about  $4.5$  GeV:

  $$M_{\text{threshold}} = m_{\Sigma_c} + m_{D^*} \approx 4.5\;\text{GeV}$$  

This is roughly where one would search for such formations.

<hr>

### Quantum Numbers — spin algebra, my favorite exercise

The system is in an **s‑wave**, so **parity** is  $--$  (minus‑minus). We have a spin‑ $1/2$  $\Sigma_c $and a spin‑$ 1$  $D^*$ . Their composition gives two possible states:

  $$\frac12 \otimes 1 = \frac12 \oplus \frac32$$  

| State |  $J^P$  |
|-------|-------|
|  $1/2 \oplus 1$  →  $1/2$  |  $\frac12^-$  |
|  $1/2 \oplus 1$  →  $3/2$  |  $\frac32^-$  |

Both have a lower bound on the lifetime.

<hr>

### Decay and Lifetime Bound

Why would this state ever decay? I would love to say "no". Splitting it into two constituents requires at least the sum of their masses, which is already larger than the particle's mass. In the rest frame, all the energy is the particle's mass. If the constituents fly apart, the energy is even higher—that decay is forbidden by energy conservation.

The charm and anti‑charm can annihilate electromagnetically, but that process has very low probability. Strong annihilation (if they have different colors) can produce other quarks, but that is also suppressed for heavy particles.

If inelastic channels are neglected, the dominant decay is **weak decay**: one of the charm quarks transitions to a strange quark, emitting a  $W$ . Because the particle is a bound state of a  $\Sigma_c$  and a  $D^*$ , one of these constituents decays weakly. The lifetime can be computed from that process.

However, there is another process: the  $D^*$  is not the ground state—it can decay to  $D$  by emitting a  $\pi^0$  or a  $\gamma$ . This gives a lower bound on the lifetime:

  $$\Gamma_X < \Gamma_{D^*}$$  

Since lifetime  $\tau = 1/\Gamma$ , we have  $\tau_X > \tau_{D^*}$ .

Consider the deuteron: it is made of a proton and a neutron. The proton is stable; the neutron is not stable but lives long. The deuteron is stable because the neutron is so bound inside that it cannot decay. The binding mechanism suppresses the phase space for decay. Similarly, the  $D$  meson inside the molecule lives longer than an isolated  $D^*$  meson.

<hr>

### Cascade and Dissociation

<b>Q:</b> Will the  $\Sigma_c D^*$  molecule survive by stepping down one energy level instead of falling apart?
<b>A:</b> Yes, it can cascade down via one energy step. But it can also dissociate into  $\Sigma_c D \pi$  or  $\Sigma_c D \gamma$ , because the energy is available.

The **binding energy** and decay situation are actively discussed in the field; at every conference you see about five talks. This is a hot subject.



## Signs of Mandelstam Variables for Different Processes

#### Plane of Invariants 




![This figure schematically represents a generic 2 → 2 scattering process in particle physics, as discussed in the context of Mandelstam variables and kinematics. The central blob denotes an unspecified interaction ("something happens") between four particles, labeled  $X$ ,  $A$ ,  $B$ , and  $C$ , each with arrows indicating their directions. All arrows are pointing outward from the interaction, which is a standard convention indicating final states (except for  $X$  if it is considered an initial state).   In the context of the lecture, this setup is used to define the Lorentz-invariant Mandelstam variables ( $s, t, u$ ): -  $s = (p_A + p_B)^2$ , the invariant mass squared of particles  $A$  and  $B$  -  $t = (p_A - p_C)^2$ , the squared momentum transfer between  $A$  and  $C$  -  $u = (p_A - p_D)^2$ , the squared momentum transfer between  $A$  and  $D$   This diagram is crucial for understanding how these invariants are assigned based on the flow of momenta, to analyze particle reactions and kinematic domains for scattering and decay processes. It forms the basis for further analysis of the physical kinematics, such as the allowed regions in Dalitz plots, and is central to the discussion of unitarity and analytic properties of the scattering amplitude.](2024-Lecture-07-images/fig2.png){#fig-fg2}

 




![This figure represents the **Dalitz plot** or *plane of Mandelstam invariants* for a 2 → 2 scattering process as discussed in the lecture. The triangle in the center illustrates the kinematically allowed region for the Mandelstam variables  $s$ ,  $t$ , and  $u$ . Each vertex and side of the triangle corresponds to one of the channels (s, t, u). The labeled arrows indicate the directions and relationships between the Mandelstam variables:  -  $s$ : total energy squared for the incoming system, -  $t$ : squared momentum transfer between certain legs, -  $u$ : squared momentum transfer for the cross-channel.  The shaded areas outside the triangle represent physically forbidden regions, while the interior triangle (Dalitz plot) is the physically allowed region for the process, where the transitions and resonance formations happen. The letters  $b$ ,  $c$ , and  $d$  correspond respectively to the external particles, aligning with the notation  $A, B, C, D$  from the text. The points where the boundaries are marked indicate kinematic thresholds determined by the masses of the particles, and the triangle’s edges are defined by the zeros of the Källén function  $\lambda$ . This diagram visualizes how scattering amplitudes span different kinematic domains and how all physical observable processes for the 2 → 2 system are confined within the Dalitz plot.](2024-Lecture-07-images/fig3.png){#fig-fg3}

 




![This figure illustrates the kinematics of a  $2 \to 2$  scattering process in particle physics, as described in the lecture. The top part of the figure shows a generic Feynman diagram with two incoming particles (labeled  $p_1$ ,  $p_2$ ) and two outgoing particles ( $p_1'$ ,  $p_2'$ ), all connected via a central blob which represents an unspecified interaction. This visual encapsulates the general scenario discussed when introducing Mandelstam variables and the scattering amplitude.  The bottom part of the figure provides a depiction of the momenta in the center-of-momentum frame. Here, the incoming momenta  $p_1$  and  $p_2$  are directed towards each other, while the outgoing momenta  $p_1'$  and  $p_2'$  are shown with the angle  $\theta$  between  $p_1$  and  $p_1'$ . The angle  $\theta$  represents the scattering angle, the primary observable that characterizes the final state in elastic  $2 \to 2$  scattering. This geometric arrangement is essential for defining variables such as the Mandelstam  $s$ ,  $t$ , and  $u$ , and for expanding the scattering amplitude in terms of partial waves, where the amplitude depends on the collision energy and the scattering angle. The figure thus directly links the abstract formalism of scattering theory to concrete physical kinematics and observables.](2024-Lecture-07-images/fig4.png){#fig-fg4}






For any 2→2 process (a central interaction vertex with four external legs  $X, A, B, C$ ), invariant variables characterize the kinematics.

<b>Definition of Mandelstam variables:</b>

  $$s = (p_A + p_B)^2,\qquad
t = (p_B + p_C)^2,\qquad
u = (p_C + p_A)^2$$  

Here:

-  $s$  is the mass squared of the system of  $A$  and  $B$ ;  $\sqrt{s}$  is the invariant mass.
-  $t$  is the mass squared of the system of  $B$  and  $C$ .
-  $u$  is the mass squared of the system of  $A$  and  $C$ .

Two variables suffice to characterize the kinematics of a four‑point process (counting degrees of freedom). Any pair –  $s$  and  $t$ ,  $s$  and  $u$ , or  $t$  and  $u$  – can be used because the three invariants are related by mass constraints. The scattering amplitude depends on only two variables and is defined on the **plane of invariants**. Different domains on this plane describe different processes.

<hr>

### Sign analysis for processes  $a$ ,  $b$ ,  $d$ 

The following table summarises the sign conditions (positive/negative) for the Mandelstam variables in each process.
(For simplicity, “positive” means larger than the physical threshold; “negative” means unphysical.)

| Process |  $s$  |  $t$  |  $u$  |
|---------|------|------|------|
|  $a$  (all particles incoming or outgoing) |  $s > (m_A+m_B)^2$  |  $t > (m_B+m_C)^2$  |  $u > (m_C+m_A)^2$  |
|  $b$  (one particle crossed) |  $s < 0$  |  $t > 0$  |  $u < 0$  |
|  $d$  (one particle crossed) |  $s < 0$  |  $t < 0$  |  $u > 0$  |

<b>Example Socratic exchange:</b>

<b>Q:</b> For process  $a$ , is  $s$  positive?
<b>A:</b> Yes, because  $s$  is the mass squared of the real two‑particle system. It is well‑defined and at least  $(m_A+m_B)^2$ . The same applies to  $t$  and  $u$ .

<b>Q:</b> Is that simply the sum of masses?
<b>A:</b> No, it is the sum of four‑vectors, not the sum of masses. Since the particles have momentum in the rest frame, the energy of the system is larger than the sum of masses.

<hr>

#### Crossed‑channel interpretation

For process  $b$ ,  $t$  is the physical mass of  $B$  and  $C$  (positive, above threshold), while  $s$  and  $u$  are combinations of particles on different sides of the diagram and become negative.
Similarly, for process  $d$ ,  $u$  is positive, but  $s$  and  $t$  are negative.

To describe crossed‑channel reactions with the same invariants, one modifies the definition by swapping momenta with a minus sign for particles that move to the other side of the diagram.


::: callout-note
The exact numerical thresholds depend on the specific masses of the particles, but for the purpose of placing processes on the plane of invariants, the sign of each variable is sufficient.
:::



## The Analytic Connection Between Scattering and Decay Amplitudes

When calculating the real physical contours for kinematics, it is necessary to determine the physical ranges of the scattering variables. For the cosine of the scattering angle, the restriction  $-1\le\cos\theta\le1$  shows that only a certain region of the  $(s,t,u)$  space is allowed. The true boundary is often given by a sixth‑order polynomial; at the center lies the **Dalitz plot**.

The Mandelstam variables are defined as: (see @fig-fg2) (see @fig-fg3)

  $$s=(p_A+p_B)^2,\qquad t=(p_A-p_C)^2,\qquad u=(p_A-p_D)^2$$  

There are four distinct physical regions where reactions can occur:

| Region | Conditions |
|--------|------------|
| **a** |  $s>(m_A+m_B)^2,\; t>(m_B+m_C)^2,\; u>(m_C+m_A)^2$  |
| **b** |  $s<0,\; t>0,\; u<0$  |
| **c** |  $s<0,\; t<0,\; u<0$  |
| **d** |  $s<0,\; t<0,\; u>0$  |


::: callout-note
A single amplitude matrix element describes **all four** reactions. If you obtain that function and constrain it properly, it gives the transition amplitude for every physical process in the domain. For a given point you compute a complex number (e.g.,  $1+3i$ ), which is the value of the quantum transition amplitude. The same matrix element, evaluated at different points, yields complex transition amplitudes for decays as well. I think that is super cool. Without an infinite number of resonances, the amplitude cannot be simultaneously analytic and consistent across all physical regions. This is the core difficulty in modelling hadronic processes.
:::

This unification works very well in QED. Consider Compton scattering:  $\gamma e^- \to \gamma e^-$ . This is a compound process. The same matrix element also describes  $e^+e^-$  annihilation into two photons and the two‑photon production of an  $e^+e^-$  pair.

<hr>

In hadron physics the situation is more complicated. Because we use perturbation theory, we always model. When we describe the Dalitz plot we model it as a sum of resonances. If you try to compute the amplitude on the scattering domain, it **blows up** – it has infinities, i.e., unphysical behaviour. The reason is that we employ only a finite number of resonances, but the physics requires **analyticity**. The fact that the amplitude is defined on all four regions implies that an infinite number of resonances must be included. As seen from the lines in the Dalitz plot, these lines represent resonances. To relate the different domains, one must work with infinite sums; the infinite terms then compensate and give a reasonable result.

For 30 to 50 years there has been an effort to find a set of functions that works everywhere analytically and reasonably. The hardest part is describing the data, because data are described by **Regge theory**. In this approach one constructs a complex function with the required analytic properties that works in both scattering and decay domains. However, it lacks an exact description of resonance properties; for example, Regge theory predicts resonances with zero width. An important development is now to implement resonances with finite widths.



## The Kibble Function and the Dalitz Plot Boundaries

The contours of the physical domain are described by a single expression: the **Kibble function**  $\Phi(s,t,u)$ . Solving  $\Phi(s,t,u)=0$  gives the boundaries of the Dalitz plot. For any fixed  $s$  (e.g.,  $-50$  or  $+20$ ), a solver returns two solutions. (see @fig-fg3) This function is easy to code.

The building block is the **Källén function** (also called the *Klein* or *Chalng function*):
  $$\lambda(x,y,z) = x^2 + y^2 + z^2 - 2xy - 2yz - 2zx.$$  
It is almost a complete polynomial but misses more terms of this table.

The Kibble function is formed from three Källén functions, each corresponding to a different channel:
  $$\Phi(s,t,u) = \lambda(\lambda_1, \lambda_2, \lambda_3),$$  
where
  $$\lambda_1 = \lambda(s, m_C^2, m_B^2),\quad
\lambda_2 = \lambda(t, m_X^2, m_A^2),\quad
\lambda_3 = \lambda(u, m_X^2, m_B^2).$$  

| Channel | Källén argument | Masses involved |
|---------|----------------|-----------------|
|  $s$ -channel |  $\lambda_1 = \lambda(s, m_C^2, m_B^2)$  |  $m_C$ ,  $m_B$  |
|  $t$ -channel |  $\lambda_2 = \lambda(t, m_X^2, m_A^2)$  |  $m_X$ ,  $m_A$  |
|  $u$ -channel |  $\lambda_3 = \lambda(u, m_X^2, m_B^2)$  |  $m_X$ ,  $m_B$  |

To explore the function, open Wolfram Alpha and ask for a contour plot. The full discussion of the Kibble function and its properties is found in the book by **Byckling and Kajantie** — the best reference on particle kinematics. (Have we discussed this book? The authors’ names are famously unspellable, but the book is excellent.) It covers the very peculiar properties of both the Kibble and Källén functions.



## Unitarity and Its Constraints on Scattering Amplitudes

### Unitarity in Scattering Amplitudes

Unitarity is a constraint on scattering amplitudes. In high energy physics, the scattering amplitude is not computed from first principles; instead it is modeled, guided by principles of what the amplitude can and cannot be. You cannot simply write an arbitrary expression that fits the data. A key principle is **probability conservation**, which transforms into a mathematical statement on the amplitude known as **unitarity**.

A consequence of unitarity is the **optical theorem**, which relates the imaginary part of the amplitude to the total cross section:

  $$\operatorname{Im} A = \frac{1}{2} \sigma_{\text{tot}}.$$  

This principle alone already gives a decent lineshape for a scattering amplitude that describes resonance phenomena — you see a bump in the spectrum due to probability conservation. Unitarity tells what expression to take to describe this phenomenon. For example, using the **K‑matrix** formalism or the **Breit–Wigner** form:

  $$a = \frac{K}{1 - i K \mathcal{P}}, \qquad K \text{ real}
\qquad\text{or}\qquad
a = \frac{g^2}{m^2 - s - i g^2 \mathcal{P}}.$$  

<hr>

Unitarity also concerns the analytic properties of the amplitude: it determines the analytic structure, including the location of singularities such as cuts and branch points in the complex plane. Scattering amplitudes are real analytic functions, and unitarity fixes the positions of cuts from the imaginary part.

<hr>
#### Deriving the Unitarity Equations 




![This figure represents the unitarity condition for the scattering amplitude in diagrammatic form. On the left side, there is a difference between the full amplitude and its complex conjugate (depicted as two blobs), illustrating the left-hand side of the unitarity equation. On the right side, the diagram shows the "cut" through the intermediate state, representing the sum over all possible intermediate on-shell states in the phase space. The equality reflects the mathematical expression  $T - T^\dagger = i \int d\Phi \, T^\dagger T$ , where the imaginary part of the full amplitude is generated by the sum over amplitudes involving all possible intermediate configurations. This is a pictorial way to represent probability conservation (unitarity) at the level of Feynman diagrams.](2024-Lecture-07-images/fig5.png){#fig-fg5}






We will derive three equations, all dealing with scattering amplitudes. The first tells how unitarity acts on the **full amplitude**:

  $$A - A^* = i \int d\Phi \, A^* A,$$  

where  $\int d\Phi$  denotes integration over the phase space of intermediate states.

For **partial waves**, the amplitude  $a$  is a function of a single variable. The two‑body phase space simplifies to

  $$\mathcal{P} = \frac{1}{2} \cdot \frac{1}{8\pi} \cdot \frac{2p}{\sqrt{s}}.$$  

Essentially,  $a - a^* = 2i \operatorname{Im} a$ , and unitarity gives

  $$\operatorname{Im} a_l = |a_l|^2 \, \mathcal{P}.$$  

<hr>
#### Step‑by‑Step Derivation

Consider a  $2\to 2$  elastic process. In the interaction diagram, a **blob** represents some interaction with two incoming and two outgoing particles.

### Kinematics in the Center‑of‑Momentum Frame

In this frame the total momentum is zero, so the lengths of the momentum vectors are equal. Even if particles have different masses, their momenta have the same magnitude: (see @fig-fg4)

  $$p = |\vec{p}_1| = \frac{\sqrt{\lambda(s, m_1^2, m_2^2)}}{2\sqrt{s}},$$   (see @fig-fg2)

where  $\lambda$  is the **Källén function**. For elastic scattering, the final particles are the same as the initial ones, so the masses and the break‑up momentum are the same. The only quantity that changes is the **scattering angle**.

### The Observable: Angular Distribution

The observable for the interaction is the angular distribution of the outgoing particles. Whatever happens inside the interaction manifests itself only through the angular distribution. For a  $2\to 2$  process at fixed energy, the only remaining variable is the scattering angle. Thus we have two variables: the energy of the system and the scattering angle. The two‑particle state is characterized by the momenta  $\vec{p}_1$  and  $\vec{p}_2$ ; we use the scattering angle  $\theta$ .

### Definition of the Scattering Amplitude

Define the scattering amplitude as the transition matrix element between initial and final two‑particle states:

  $$\langle p_1' p_2' | T | p_1 p_2 \rangle .$$  

Energy‑momentum conservation gives a factor  $(2\pi)^4 \delta^{(4)}(p_1+p_2 - p_1'-p_2')$ . We insert the **identity operator** as an integral over intermediate states. The two‑body phase space element is

  $$d\Phi = \frac{1}{2} \cdot \frac{1}{8\pi} \cdot \frac{2p}{\sqrt{s}} \, d\cos\theta \, \frac{d\phi}{2\pi}.$$  

### State Description

The two‑particle state is defined with particles back‑to‑back. Choose a coordinate system with axes  $x$ ,  $y$ ,  $z$ . In this system the two‑particle state is described by angles  $\theta$  and  $\phi$ , and the momentum of particle 1 is characterized by those angles. The same state appears on both sides of the matrix element, and we integrate over all possible angles. The two‑body phase space integration covers all possible directions over the  $4\pi$  solid angle.

### Verifying the Identity

We must verify that the inserted identity operator acts as an identity. This follows from the normalization of states. Inserting the identity leads to an integration over intermediate momenta. Everything is now in place to derive unitarity.

<hr>
#### Summary of Key Formulas

| Equation | Interpretation |
|----------|----------------|
|  $A - A^* = i \int d\Phi \, A^* A$  | Unitarity condition for the full amplitude |
|  $\displaystyle \mathcal{P} = \frac{1}{2} \cdot \frac{1}{8\pi} \cdot \frac{2p}{\sqrt{s}}$  | Two‑body phase space factor |
|  $\operatorname{Im} a_l = |a_l|^2 \, \mathcal{P}$  | Unitarity for partial waves, where  $a_l$  is the partial‑wave amplitude |



## Unitarity and Partial-Wave Expansion of the Scattering Amplitude

This is the two-particle **scattering amplitude**. It is defined by **unitarity**. (see @fig-fg4)
<hr>

<b>Q:</b> Shouldn't there also be from **unitarity** the option that  $P_1' = P_2$ ?
<b>A:</b> They are distinguishable scalar particles of different types to avoid cross terms.

<hr>
<b>Unitarity</b> of the full scattering operator  $\hat{S}$  is the statement  $\hat{S}\hat{S}^\dagger = \hat{I}$ . The identity part of  $\hat{S}$  describes the transition without interaction. (see @fig-fg5) By subtracting the identity, we introduce the interaction operator  $\hat{T}$ :

  $$\hat{S} = \hat{I} + i\hat{T}$$  

This operator  $\hat{T}$  defines the **scattering amplitude**. In field theory, when we deal with these amplitudes, we always refer to the non‑trivial part.

From  $\hat{S}\hat{S}^\dagger = \hat{I}$  we derive the condition on  $\hat{T}$ :

  $$\hat{T} - \hat{T}^\dagger = i \hat{T}^\dagger \hat{T}$$  

This critical statement constrains the **partial waves** and the **scattering amplitude**.

To obtain a more practical form, we insert a complete set of intermediate states between  $\hat{T}^\dagger$  and  $\hat{T}$ . For two‑body initial and final states, the intermediate states are themselves two‑particle states. Inserting the identity and integrating over the four‑momentum yields, after imposing energy‑momentum conservation via delta functions, the **unitarity** relation:

  $$T - T^\dagger = i \int T^\dagger T \, d\Phi$$  

where  $d\Phi$  is the two‑body phase space element:

  $$d\Phi = \frac{1}{8\pi} \frac{2p}{\sqrt{s}} \frac{d\cos\theta}{2} \frac{d\phi}{2\pi}$$  

| Form of **unitarity** | Equation |
|-------------------|----------|
| Operator          |  $\hat{T} - \hat{T}^\dagger = i \hat{T}^\dagger \hat{T}$  |
| Integral          |  $T - T^\dagger = i \int T^\dagger T \, d\Phi$  |
| **Partial wave**      |  $a_j - a_j^* = i \frac{1}{8\pi} \frac{2p}{\sqrt{s}} a_j^* a_j$  |

The most general form sums over all possible intermediate states (any number of particles  $n$ ) integrated over  $n$ ‑body phase space. Diagrammatically, the amplitude minus its conjugate equals a sum over all intermediate steps, with each loop corresponding to an integration over all configurations.

We then simplify variables in terms of the center‑of‑mass energy  $s$  and the momentum transfer  $t$ , or equivalently the scattering angle  $\theta$ .

<hr>

The **scattering amplitude**  $A(s,t)$  can be expanded in **partial waves**:

  $$A(s,t) = \sum_{j=0}^\infty (2j+1) a_j(s) P_j(\cos\theta)$$  

This series converges rapidly, especially in low‑energy physics. There is a natural suppression of high **partial waves** due to the finite size of hadrons. In experiment, only a few **partial waves** (two to ten) are needed to describe data. If one keeps the entire sum to infinity, as in Regge theory, the expansion is exact.

<hr>

The **partial‑wave** amplitude  $a_j(s)$  is a function of a single variable  $s$  and carries fixed quantum numbers. A major advantage of **partial waves** is that they do not mix: conservation laws ensure that a **partial wave** in the initial state only connects to the same **partial wave** in the final state.

In the **unitarity** constraint, each **partial wave** satisfies its own equation:

  $$a_j - a_j^* = i \frac{1}{8\pi} \frac{2p}{\sqrt{s}} a_j^* a_j$$  

which implies

  $$\operatorname{Im} a_j = -|a_j|^2 \mathcal{P}$$  

where  $\mathcal{P} = \frac{2p}{8\pi\sqrt{s}}$  is the phase space factor. Thus, different **partial waves** do not influence each other.



## Partial Wave Expansion and the K-Matrix Approach to Resonances

We insert the Legendre polynomial expansion into the partial-wave decomposition and use the  $d$ -function to rewrite the angular dependence. The initial state has scattering angle zero, so  $P_J(1) = 1$ ; the final state has angle  $\theta$ , and  $P_J(\cos\theta) = d^J_{00}(\theta)$ . This yields a cool and powerful expression.

The amplitude expansion is

  $$A(s,t) = \sum_{j=0}^\infty (2j+1)\, a_j(s)\, P_j(\cos\theta).$$  

We integrate over the intermediate-state angles, and both amplitudes are expanded in partial waves. The result is the partial‑wave expansion; the numerical coefficients are the base case.

<hr>
### Unitarity and the imaginary part 




![This figure represents the behavior of the imaginary part of the inverse partial wave amplitude, as constrained by unitarity in two-body scattering. The key relation shown in the lecture is  $\operatorname{Im} a_J^{-1} = -i \rho$ , which leads to a prediction for how the imaginary part of the amplitude,  $\operatorname{Im} a_j$ , depends on the kinematic variable  $s$  (the square of the total energy in the center-of-mass frame).  Physically, the plot shows that as the invariant mass  $\sqrt{s}$  increases from the two-particle threshold (where  $\sqrt{s} = m_1 + m_2$ ), the phase space factor  $\rho(s)$  also increases. This function  $\rho(s)$  is proportional to the breakup momentum of the two outgoing particles and characterizes the available phase space for the reaction.   The curve in the diagram starts from zero at the threshold (where the particles just begin to be produced), rises sharply with a square-root behavior, and then gradually saturates to a constant value  $1/(16\pi)$  at high energies, as described by the expression \[ \rho(s) = \frac{1}{16\pi} \frac{\lambda^{1/2}(s, m_1^2, m_2^2)}{s} \] where the Källén function  $\lambda$  encodes kinematic constraints.  This plot highlights how unitarity fixes the imaginary part of the partial wave amplitude as a function of energy: it is determined entirely by kinematics and phase space, not model-dependent details. This is crucial for constructing amplitudes that respect probability conservation in scattering theory.](2024-Lecture-07-images/fig6.png){#fig-fg6}






From the unitarity condition we obtain the relation

  $$a_j - a_j^* = i \frac{1}{8\pi} \frac{2p}{\sqrt{s}} \, a_j^* a_j,$$  

which leads to

  $$\operatorname{Im} a_j = -|a_j|^2 \mathcal{P}, \qquad \mathcal{P} = \frac{1}{8\pi} \frac{p}{\sqrt{s}}.$$  

The phase‑space factor  $\mathcal{P}$  behaves as follows:

| Region | Behavior |
|--------|----------|
| Near threshold  $s \to (m_1+m_2)^2$  |  $\mathcal{P} \propto \sqrt{s-(m_1+m_2)^2}$  (square‑root onset) |
| High energy  $s \to \infty$  |  $\mathcal{P} \to \dfrac{1}{16\pi}$  (constant) |
| General expression |  $\mathcal{P} = \dfrac{1}{16\pi} \dfrac{\lambda^{1/2}}{s}$  with  $\lambda$  the Källén function |

The imaginary part of the inverse amplitude takes the simple form

  $$\frac{1}{a} = \frac{1}{K} - i\mathcal{P},$$  

where  $K$  is a real function that encodes the interaction dynamics.

<hr>

### Modeling the real part: the K‑matrix and Breit‑Wigner

<b>Single‑pole (Breit‑Wigner) model</b> 




![This figure shows the typical shape of the absolute value of the resonance scattering amplitude,  $|A|$ , as a function of the center-of-mass energy squared,  $s$ . The peak occurs near the "bare mass," marked as  $m^2$ , and the height of the peak is related to the coupling squared,  $g^2$ . This diagram represents a resonant phenomenon described by the relativistic Breit-Wigner amplitude, which is commonly used in particle physics to model resonance behavior. When two particles scatter, if the energy matches the resonance mass, the scattering probability rises sharply—this is visible as the large peak in the amplitude. Away from this energy, the amplitude is small, resulting in a characteristic bump. This behavior is a direct manifestation of creating an intermediate unstable particle (a resonance), and the width of the peak encodes the lifetime (inverse of the decay width) of that resonance. The plot thus visualizes how the unitarity constraint and resonance modeling describe experimental observations in particle collision experiments.](2024-Lecture-07-images/fig7.png){#fig-fg7}

 




![This figure illustrates the decomposition and diagrammatic expansion of the two-body scattering amplitude in the **K-matrix formalism**. The equation  $a = (K^{-1} - i\rho)^{-1}$  expresses the amplitude  $a$  as the sum of iterated elementary interactions (K), each connected by insertions of the two-particle phase space factor ( $i\rho$ ). The expansion  $K + K(i\rho)K + K(i\rho)K(i\rho)K + \ldots$  represents the resummation of all possible repeated scatterings between two particles, where each term corresponds to an additional loop (propagator) in the intermediate state.  The diagrams underneath the terms show the corresponding Feynman-like representations: - The first term (K) is a single point-like interaction (no intermediate states). - The second term (K $i\rho$ K) describes two consecutive point-like interactions separated by a loop, indicating propagation through an intermediate two-particle state. - The third term (K $i\rho$ K$i\rho $K) corresponds to three such interactions connected by two intermediate propagations, and so on.  Physically, this expansion encapsulates the unitarity constraint discussed in the lecture, showing that the imaginary part (and analytic structure) of the amplitude arises from the possibility of these intermediate on-shell two-particle states, as enforced by the phase space factor$ \rho $. This formalism guarantees probability conservation in the scattering process and models resonant phenomena, such as the formation of intermediate bound or quasi-bound states (resonances). The approach is foundational in constructing amplitudes that respect the analytic properties and unitarity required by quantum field theory.](2024-Lecture-07-images/fig8.png){#fig-fg8}






The simplest choice for$ K$ is a single pole:

  $$K = \frac{g^2}{m^2 - s},$$  

which gives the relativistic Breit‑Wigner amplitude

  $$a = \frac{g^2}{m^2 - s - i g^2 \mathcal{P}}.$$  

The parameter  $m$  is the bare mass; the width is determined by  $g^2\mathcal{P}$ . This describes a resonance: two particles collide, form an intermediate state, then decay. The cross section peaks when the collision energy equals the resonance mass.

<b>Two‑pole model</b>

If we take two poles,

  $$K = \frac{g_1^2}{m_1^2 - s} + \frac{g_2^2}{m_2^2 - s},$$  

the amplitude  $a = \dfrac{K}{1 - iK\mathcal{P}}$  exhibits two peaks and a zero in between. The zero arises because  $K$  itself vanishes between the poles. The actual peak positions are not exactly  $m_1$  and  $m_2$  – those are bare masses that become dressed by the self‑energy.

| Feature | Single‑pole | Two‑pole |
|---------|-------------|----------|
|  $K$  form |  $\dfrac{g^2}{m^2 - s}$  |  $\dfrac{g_1^2}{m_1^2 - s} + \dfrac{g_2^2}{m_2^2 - s}$  |
| Amplitude |  $a = \dfrac{g^2}{m^2 - s - i g^2 \mathcal{P}}$  |  $a = \dfrac{K}{1 - iK\mathcal{P}}$  |
| Cross‑section shape | One peak near  $s = m^2$  | Two peaks with a zero between |
| Interpretations | Simple resonance | Two resonances;  $K$  vanishes → amplitude zero |


::: callout-note
The Taylor expansion of  $a = K/(1 - iK\mathcal{P})$  yields
  $$a = K + i K^2 \mathcal{P} - K^3 \mathcal{P}^2 + \cdots$$  
Diagrammatically,  $K$  is the point‑like interaction and  $\mathcal{P}$  (or  $\rho$ ) is the two‑particle propagator – an infinite series of dressing loops.
:::

The real part of the amplitude must be computed or modeled (from lattice, experiment, or theory). Unitarity fixes the imaginary part in terms of phase space, but the real part is genuinely interaction‑dependent.



## Unitarity and the Argand Diagram

"""
The vertex amplitude is a complex function. The magnitude of this complex amplitude has been discussed previously; what remains is the angle—the **scattering phase**, i.e., the argument of the scattering amplitude.

This phase traces a circle in the complex plane. From threshold, the amplitude increases: it starts small, rises to its largest value, then decreases to zero, and then makes a second loop, where the imaginary part of  $A$  is shown. The behavior is a function of  $s$ , the squared center-of-mass energy. The maximal value is approached around  $(m_{1,0})^2$ . The second loop corresponds to another full circle. This plot is called an **Argand diagram**.

As mentioned in the homework, an Argand diagram is a plot of the amplitude  $A$  or  $A$  times  $\rho$ , where  $\rho = \frac{p}{8\pi\sqrt{s}}$  is the phase space factor. Define  $F = A \rho$ , which is more convenient to plot in the complex plane.

<hr>
Unitarity of the  $S$ -matrix,  $S S^\dagger = I$ , leads to: (see @fig-fg5) (see @fig-fg6)

  $$T - T^\dagger = i T^\dagger T$$  

and imposes for partial-wave amplitudes: (see @fig-fg7) (see @fig-fg8)

  $$\text{Im } a_j = \rho |a_j|^2, \quad \rho = \frac{p}{8\pi\sqrt{s}}$$  


::: callout-important
Amplitude unitarity is an important constraint from probability conservation, giving a tool to model the amplitude. It fixes the imaginary part, so only the real part needs to be modeled.
:::

The real part corresponds to a point-like interaction that must be resummed to all orders. Several modeling techniques exist:

| Technique | Description | Example |
|-----------|-------------|---------|
| **K‑matrix formalism** | Unitarity is enforced by writing  $a = \frac{K}{1 - i K \rho}$ , with  $K$  real. | For a resonance,  $K = \frac{g^2}{m^2 - s}$ , giving  $a = \frac{g^2}{m^2 - s - i g^2 \rho}$ . |
| **Polynomial (scattering length) approximation** | The real part is modeled as a low‑energy polynomial expansion. | — |

<hr>

