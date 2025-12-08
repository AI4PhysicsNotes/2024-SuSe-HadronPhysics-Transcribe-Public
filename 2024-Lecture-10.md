---
title: (2024) Lecture 10
author: ''
presenter: Mikhail Mikhasenko
note_taker: Ilya Segal
date: '2024'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



## Cross Section Calculation and Spin Algebra in Scattering Problems

---
**First, calculate the cross section for the scattering of two massless particles.** The matrix element is given for spin-zero scalar particles. The task is to calculate the cross section and give the answer in millibarns.

So, number one: calculate the cross section. That's to remember the equation for how we compute the cross section. Essentially, putting the numbers in, the whole computation is straightforward.

Let's do that before moving on. The cross section is given by flux, the matrix element squared, and an average over phase space. The matrix element squared gives you  $3 + 9 + 4$ , which is  $13$ .

Here is the flux factor. Here is the phase space factor. The phase space is  $\frac{1}{8\pi^2} \times \frac{2p}{\sqrt{s}}$ . You have to calculate  $\frac{2p}{\sqrt{s}}$  knowing the masses and the energy. For this case, the momentum is  $p = \sqrt{s}/2$ . So this factor is actually equal to  $1$ . The phase space simplifies to  $\frac{1}{8\pi^2}$ .

Now, what about flux? Flux is  $\frac{1}{2E_1 2E_2 |v_1 - v_2|}$ . In the center-of-mass frame, both energies are half of the total energy,  $E = \sqrt{s}/2$ . For massless particles, their velocities are the speed of light, so  $|v_1 - v_2| = 2$ . This gives a flux factor of  $\frac{1}{2s}$ .

Putting things together, the cross section is  $\sigma = \frac{1}{2s} \times 13 \times \frac{1}{8\pi^2}$ . This simplifies to  $\frac{13}{16\pi^2 s}$ .

Now, for  $\sqrt{s} = 3$  GeV, we have  $s = 9$  GeV². So  $\sigma = \frac{13}{16\pi^2 \times 9}$  GeV⁻². Using the conversion  $1 \text{ GeV}^{-2} = 0.389$  mb, we can compute the numerical value. The π is approximately 3.14. This gives a result around **0.01 millibarns**.

What's important is that you start from the right equation, use the right formulas for the cross section, for the phase space, and for the flux, and then arrive at the hopefully correct result. The starting point and knowing what to use for each factor is key.


::: callout-note
**Key Formulas for Cross-Section Calculation:**

*   **General 2→2 Scattering:** The differential cross section is given by
      $$\frac{d\sigma}{d\Omega} = \frac{1}{64\pi^2 s} \frac{|\mathbf{p}_f|}{|\mathbf{p}_i|} |\mathcal{M}|^2$$  

*   **Flux Factor:** In the center-of-mass frame,  $F = 4 |\mathbf{p}_i| \sqrt{s}$ .
*   **Two-Body Phase Space:**  $d\Phi_2 = \frac{1}{8\pi^2} \frac{|\mathbf{p}|}{\sqrt{s}} d\Omega$ .
:::

**Please start with the equation where you have the imaginary part of the matrix element.** We didn't end up with the final result from that. When you start with the imaginary part, you use the optical theorem. You say, "I know the imaginary part, and then I can calculate the total cross section from it." The optical theorem states:

  $$\sigma_{\text{total}} = \frac{1}{|\mathbf{p}_i| \sqrt{s}} \operatorname{Im} \mathcal{M}(0^\circ)$$  

It would give you the total cross section. Actually, it won't give you the cross section for just the elastic process. That's a different problem. That's actually a cool question for an exam: give you this expression and ask you to calculate the elastic cross section and the total cross section. For elastic, you use the full squared matrix element. For the total, you use the imaginary part.

A short question: why could the total cross section be different than the elastic? Physically, what one describes is just one scattering channel, and the other describes all possible processes. So it's not just  $AB \to AB$ , but  $AB \to CD$  and  $AB \to EF$  as well. All of them. Of course, the total cross section should be bigger.

I'm curious now. After the lecture, I'm going to sit and calculate what happens if I take the imaginary part, calculate the total cross section, and find out that it's smaller. Is the equation for the total cross section the absolute value of the imaginary part? Because otherwise, it would be negative, and that was a bit confusing. It's not the absolute value. It should give a positive result. The imaginary part is related to the total cross section, so the imaginary part must be positive.

If I'm thinking of the Breit-Wigner function, its imaginary part goes up and then goes down, but it stays positive. Also, remember the Argand diagram? On the x-axis, we have the real part of the matrix element. On the y-axis, we have the imaginary part of the amplitude. Only positive values were allowed. So, giving a negative value here is illegal.

Moreover, in the last exercise, we started discussing which are legal values and which are not. I might end up giving you a value that is not in the elastic scattering regime. If I've done the calculation correctly, it should be all right. Not necessarily. Well, if I'm outside the resonance, it's fine.

**Number two quickly. This is simple spin algebra, but I want you to be very sure what you're doing.** How do you add spins together, and how do you compute the partial waves? Something you take from this course at least is spin algebra.

First, you need to calculate the quantum numbers in combination. In boson routes, you draw the table, and then you see which column of the tables has the right counting numbers. It's as simple as that. But what's the spin and parity of the  $\pi_1$ ? Minus, minus, plus. That's straightforward.

I don't want you to look at the C-parity for now. When we do spin algebra and the spin composition of representations, we only care about the spin. Parity is simple to compute for every multiplet:

  $$P = P_1 P_2 (-1)^L$$  

We combine  $1^-$  and  $1^+$  to get  $1^-$  in an S-wave. So the S-wave works. Is there another wave that works? In an S-wave, we have only spin-1. In a D-wave, we have spins 0, 1, and 2. In an F-wave, we have spins 1, 2, and 3. The parity is given by  $(-1)^L$ , so it would be different for different partial waves.

What I was confused about is the charge conjugation. I got the numbers here correctly, I'm pretty sure. I just checked. The  $\pi$  is  $0^{-+}$ . The  $b_1$  is  $1^{+-}$ . I'm confident that the decay is possible. The charge conjugation for the  $\pi_1$  is plus. Therefore, it's a charge conjugation eigenstate.

Isospin is violated in this decay. Yep, it's okay. I mean, no, it's fine. Isospin does get violated. I will think a little bit more on that because I didn't expect it. I saw that it's listed as a regular strong decay.

What is peculiar about that is the  $\pi_1$  has the quantum numbers  $1^{-+}$ , which are **not allowed in the quark model**. So this is not a regular hadron. The picture that people have for the  $\pi_1$  is something like a gluonic excitation inside the meson. The string or gluon interaction that connects the quark and anti-quark pair in a mesonic picture also has degrees of freedom and can be excited. So it's not sitting in the regular confined potential, but in the excitations of this real interaction. That's how people understand it. This particle is called a **hybrid meson**.

The same for the  $P_1(1400)$  with similar quantum numbers. It's the same idea, the same state. Finally, it was removed from the PDG because it was first seen in old data around 1400 MeV. But then, with new data and more accurate analysis, it has been realized that it's actually around 1600 MeV that shows up, and in the  $\eta\pi$  channel for number three.



## Relating Relativistic and Non-Relativistic Scattering Lengths

I thought it's important to clarify. The notations got a little bit confused at the last lecture concerning the scattering length.

The scattering length is indeed measured in **Fermi (fm)**. However, when you use **relativistic notations**, it appears **dimensionless**.

In quantum mechanics, the scattering length is defined from the expansion of the amplitude in terms of the breakup momentum  $K$ . The breakup momentum  $K$  has units of **GeV**. Therefore,  $1/a$  has units of GeV, and  $a$  itself is in Fermi.

The standard **non-relativistic amplitude** has the form:
  $$f_{\text{NR}}(K) = \frac{1}{a^{-1} - iK}$$  
This is the leading-order **effective range expansion**.

In a **relativistic formulation**, unitarity tells us that the imaginary part of the amplitude is related to the **dimensionless phase space**. The first expansion term is again something like a scattering length, but it is dimensionless. A common parameterization is:
  $$f_{R} = \frac{1}{\tilde a^{-1} - i\,\frac{2k}{\sqrt{s}}}$$  
where  $\tilde{a}$  is the **dimensionless relativistic scattering length**.

You still want to talk about the physical scattering length in **Fermi**. Therefore, you have to relate the relativistic amplitude to the non-relativistic one, and the relation happens **at the threshold**. Since it's a threshold expansion, you would like these amplitudes to match up to a numerical constant at threshold.

In this exercise, I want you to relate these two at threshold and determine what the relativistic amplitude looks like near threshold. I'll give you the answer. The only thing that's missing is the value of  $\tilde{a}$ . The scattering length  $a$  is **three Fermi**. Knowing that, you need to compute  $\tilde{a}$ .

The way to do that is: you **cannot** just make the amplitudes equal at threshold. If you set the non-relativistic amplitude equal to the relativistic one, you miss the point.

If you evaluate the non-relativistic amplitude at threshold, where  $K = 0$ , you get:
  $$f_{\text{NR}} = \frac{1}{a^{-1}} = a$$  
This would just suggest  $\tilde{a} = a$ , which is not helpful. They are not equal; there is a **numerical constant** that you need to figure out.

The correct way to equate them is to match their structure—either equate numerators or denominators up to a numerical constant—and then compare the coefficients in front of  $K$ . One method is to perform a Taylor expansion of the relativistic expression where  $s$  is a function of the momentum and equate the first terms.

Alternatively, just notice that the key difference in the numerators is the **phase space factor**. The matching condition at threshold is:
  $$\mathcal{A}_{\text{rel}}(s_{\text{thr}}) \propto \frac{1}{8\pi^2 s} \cdot (-iK)$$  


::: callout-important
To solve for  $\tilde{a}$ , you need the masses and the threshold value. The threshold  $s_{\text{thr}}$  for  $\pi^0 \pi^0$  scattering is:
  $$s_{\text{thr}} = (2m_{\pi^0})^2$$  
The conversion between the scattering lengths is given by:
  $$\tilde a = \frac{a}{8\pi\sqrt{s_{\text{thr}}}} = \frac{a}{8\pi\,(2m_{\pi^0})}$$  
Given  $a = 3 \,\text{fm}$ , you substitute the pion mass to find the numerical value of  $\tilde{a}$ . This is a low-energy relation.
:::

So,  $\tilde{a}$  is equal to  $a$  divided by this phase-space factor. You put them together and then you find the value of  $\tilde{a}$ .



## Chirality, Spin, and Solutions of the Dirac Equation

This concept is used widely and provides very interesting insights into hydrodynamics. It relies on the extra symmetry we observe when the mass of the particles is equal to zero, called **chirality**.

That's related to the spin orientation for particles with spin one-half. So that's why we now come back to our consideration of particles that carry spin information and look particularly at **spin 1/2** and their field theoretical representation.

Spin 1/2 particles obey the equation of motion given by the **Dirac equation**:
  $$( \mathrlap{/}p - m ) u(p) = 0$$  
Here,  $\mathrlap{/}p = p^\mu \gamma_\mu$  is the contraction of the four-momentum with the Dirac gamma matrices.

There are two common conventions used to solve the Dirac equation:

*   The standard **Dirac convention**.
*   The **Weyl convention**.

Various spinors are slightly different and are more convenient when you deal with right-handed and left-handed particles. Since the Dirac convention is more commonly used, I will stick to that and proceed with the standard convention.


::: callout-note
The Dirac equation in momentum space is  $( \mathrlap{/}p - m ) u(p) = 0$ . The term  $m$  is a scalar mass, but it is implied to be multiplied by the  $4 \times 4$  identity matrix. The object  $u(p)$  is the **Dirac spinor**, a four-component object that depends on the particle's momentum and spin orientation.
:::

The  $\gamma^\mu$  are four-dimensional matrices and  $p$  is the four-vector. Therefore, when you contract the two, with summation over  $\mu$  performed, you have a four-dimensional matrix for  $\mathrlap{/}p$ .

The Dirac equation has two independent solutions. Let's consider  $p$  as a vector that has a component in space, a momentum  $\vec{p}$ . You put this expression into the equation and have a matrix expression that has two solutions,  $u_1(p)$  and  $u_2(p)$ .

These correspond to the **canonical states**. We have an axis: X, Z, Y. We have a state with spin quantized along the Z axis. You might remember these objects:  $|p; j, m\rangle_{\text{can}}$ , which is a state that has a spin momentum pointing to a certain direction in space, with the spin quantized along the Z axis and its projection equal to  $+1/2$  or  $-1/2$ .

*   The solution  $u_1$  corresponds to a state with projection  $+1/2$ .
*   The solution  $u_2$  corresponds to a state with projection  $-1/2$ .

You find this by applying the spin operator, where the eigenvalue for the first one is  $+\frac{1}{2}$  and for the second one is  $-\frac{1}{2}$ . These are two independent solutions. Any linear combination of the two is also a solution of the Dirac equation.

I am now going to go to the linear combinations that correspond to the spin quantized along the direction of momentum, which is also a solution. A reminder for how the canonical state is defined: it is a pure boost acting on the rest frame state,  $|p; j, m\rangle_\text{can} = B_{\vec{p}} |0; j, m\rangle_\text{can}$ .

The way you relate canonical to **helicity states** is by introducing an extra rotation  $R^{-1}$  to match the transformation of the canonical state, and you put the rotation  $R$  that is needed. You apply  $R$  to the state. What  $R B R^{-1}$  is doing is acting on the new transformed canonical states, or states in the rest frame. Then you have the canonical state once you apply  $R B R^{-1}$ . This is a pure boost, and it's a linear combination of canonical states with the coefficients given by these special matrices, the **Wigner D-matrices**:
  $$|p; \lambda\rangle = \sum_{m} D^{(1/2)}_{m\lambda}(R) \, |p; m\rangle_{\text{can}}$$  
Here,  $\lambda = \pm 1/2$  is the helicity, and  $R$  is the rotation that aligns the z-axis with the momentum direction.



## Conventions and Definitions of the D Function in Rotations

I want to mention something tricky related to **conventions**. Once you discuss conventions, they can't be helped, but it's a good moment to see that there are two different conventions for how the **Wigner D-matrix** is defined for the spherical angles.

### **Convention 1: The Standard Euler Rotation**
The first definition is the standard one, using three Euler angles. If you look at the Review of Particle Physics or the Particle Data Group booklet, they use this convention. The rotation is defined as:
  $$R(\phi, \theta, \psi) = R_z(\phi) \, R_y(\theta) \, R_z(\psi)$$  
So you rotate by  $\phi$  around the z-axis, then by  $\theta$  around the y-axis, and then by  $\psi$  around the z-axis again. The matrix elements of this rotation for angular momentum states are given by:
  $$D^j_{m'm}(\phi, \theta, \psi) = \langle j, m' | R(\phi, \theta, \psi) | j, m \rangle$$  

### **Convention 2: Simplified for Helicity States**
The second definition, which appears much simpler for constructions using **helicity states**, uses only two angles:  $(\theta, \phi)$ . This corresponds to a different ordering of rotations, such as  $D^j_{\lambda' \lambda}(0, \theta, \phi)$  or  $D^j_{\lambda' \lambda}(\phi, \theta, 0)$ .


::: callout-note
The choice of convention affects an extra, unobservable phase in the states. If you start with a vector that has only a z-component, both conventions give the same result because the first rotation around z does nothing. However, for general states, the phase difference is important.
:::

### **What the D-Matrix Actually Is**
I should have started with a reminder. The **capital D function** is the rotational matrix in the representation of the rotation group. Rotations about the Z-axis just give phase coefficients, while rotations about the Y-axis require tabulated functions.

This D-matrix gives you the weight coefficients for the transformation of a state  $|j, m\rangle$ . When you apply a rotation and project onto  $\langle j', m'|$ , these matrix elements are given by  $D^j_{m'm}(\phi, \theta, \psi)$ .

Coming back to our problem: we want to rotate a momentum vector from the z-axis to a general direction. This rotation produces the momentum vector:
  $$\mathbf{P} = P \, (\sin\theta \cos\phi,\; \sin\theta \sin\phi,\; \cos\theta)$$  
or, as a four-vector:
  $$\mathcal P = \bigl(E,\;P\sin\theta\cos\phi,\;P\sin\theta\sin\phi,\;P\cos\theta\bigr)$$   




![This figure represents the definition of the momentum vector  $\mathbf{P}$  in three-dimensional space with respect to the coordinate axes  $x$ ,  $y$ , and  $z$ . The vector  $\mathbf{P}$  is shown at an angle relative to the axes, which corresponds to its parametrization using spherical coordinates  $(\theta, \phi)$ , as described in the lecture. This depiction is physically significant because it illustrates how a rotation is needed to bring a canonical state (with momentum along the  $z$ -axis) to a general helicity state aligned along the direction of  $\mathbf{P}$ . The angles  $\theta$  and  $\phi$  specify the orientation of the momentum, which is crucial for building the explicit form of spinor and helicity states and for the use of Wigner D-matrices, as discussed in the context of spin, helicity, and chirality in quantum field theory.](2024-Lecture-10-images/fig1.png){#fig-fg1}






When we apply this rotation to a helicity state, the D-matrix pops up, parameterized by the two angles  $\theta$  and  $\phi$ . Depending on which convention we use, this D-matrix will include an extra phase or not.

### **Explicit Helicity Spinors for a Massive Spin-1/2 Particle**
Applying the transformation gives us an expression for the helicity state. For a particle with spin 1/2, projected onto the direction of motion, the state is given by a Dirac spinor.

I introduced the normalization constant  $N$ :
  $$N = \sqrt{E + m}$$  
This is a standard normalization that appears everywhere to ensure the correct density of states.

*   **For helicity  $+1/2$ **, the explicit spinor is:
  $$u_+(\mathbf{P}) = \sqrt{E + m}
\begin{pmatrix}
1 \\\\
0 \\\\
\dfrac{P}{E+m} \cos\theta \\\\
\dfrac{P}{E+m} \sin\theta \, e^{i\phi}
\end{pmatrix}$$  

*   **For helicity  $-1/2$ **, the spinor is:
  $$u_-(\mathbf{P}) = \sqrt{E + m}
\begin{pmatrix}
0 \\\\
1 \\\\
-\dfrac{P}{E+m} \sin\theta \, e^{-i\phi} \\\\
\dfrac{P}{E+m} \cos\theta
\end{pmatrix}$$  

The lower part of the spinor has the common factor  $\frac{P}{E + m}$ .

### **The High-Energy Limit**
That factor  $\frac{P}{E + m}$  is important. In the high-energy limit, when the mass is small compared to the energy  $(m \ll E)$ , we have  $P \approx E$ . Therefore:
  $$\frac{P}{E+m} \longrightarrow 1 \quad \text{as} \quad m/E \to 0$$  
In this ultrarelativistic limit, the spinors simplify significantly. The upper and lower components become comparable, and the state approaches a form like  $(\cos, \sin, \cos, \sin)$  up to a phase and the overall normalization factor  $\sqrt{E}$ .



## Chirality, Helicity, and the Chiral Limit

Now let me introduce **projection operators**, which will allow us to move forward. The  $\gamma^5$  matrix is defined as the product of the four gamma matrices:
  $$\gamma^5 = i \gamma^0 \gamma^1 \gamma^2 \gamma^3$$  
This is the convention we choose. It is very convenient when considering interactions to introduce right-handed and left-handed projection operators.

### **Properties of the Projection Operators**

Why are they called projection operators? Because acting twice on a state gives the same result as acting once:
  $$P_R P_R = P_R, \quad P_L P_L = P_L$$  
It’s instructive to check this explicitly. For example:
  $$P_L = \frac{1 - \gamma^5}{2}, \quad \text{so} \quad P_L P_L = \frac{(1 - \gamma^5)(1 - \gamma^5)}{4} = \frac{1 - 2\gamma^5 + (\gamma^5)^2}{4}$$  
Since  $(\gamma^5)^2 = 1$ , this simplifies to  $\frac{2 - 2\gamma^5}{4} = \frac{1 - \gamma^5}{2} = P_L$ .

Furthermore, the subspaces they project onto are **orthogonal**:
  $$P_R P_L = 0$$  
If you first project onto the left-handed space, there are no remaining right-handed components. Projecting next onto the right-handed space then yields zero.

Another crucial property stems from the fact that  $\gamma^5$  **anti-commutes** with any  $\gamma^\mu$ :
  $$\{\gamma^\mu, \gamma^5\} = 0$$  
This anti-commutation implies that the gamma matrices swap chirality. For instance:
  $$\gamma^\mu P_L = P_R \gamma^\mu$$  
Consequently,  $P_R \gamma^\mu P_L = P_R (P_R \gamma^\mu) = P_R \gamma^\mu$ , but also, by swapping order, this equals  $(\gamma^\mu P_L) P_L = \gamma^\mu P_L$ . The orthogonality  $P_R P_L = 0$  leads to the important result that certain chiral combinations vanish.

### **Decomposing a Spinor**

Any Dirac spinor  $\psi$  can be decomposed into right-handed and left-handed chiral components:
  $$\psi = \psi_R + \psi_L, \quad \text{where} \quad \psi_R = P_R \psi \quad \text{and} \quad \psi_L = P_L \psi$$  

To give explicit meaning to these states, we can connect them to helicity states (spin aligned or anti-aligned with the direction of motion). The decomposition is performed by using an explicit matrix representation.


::: callout-note
In the **chiral representation**, the projection operators have a simple block form:
  $$P_R = \frac{1}{2} \begin{pmatrix} I & I \\ I & I \end{pmatrix}, \quad P_L = \frac{1}{2} \begin{pmatrix} I & -I \\ -I & I \end{pmatrix}$$  
Using this representation makes the decomposition of a spinor into  $\psi_R$  and  $\psi_L$  more concrete, though working with  $4 \times 4$  matrices can be cumbersome.
:::

When projecting a helicity state, one finds that for a massive particle, each helicity state contains a small component of the opposite chirality. This mixing becomes negligible at high energies where the mass is much smaller than the energy  $(m \ll E)$ .

### **Physical Interpretation: Chirality vs. Helicity**

There is no single, always-valid intuitive picture for right-handed and left-handed chiral states. However, they are closely related to **helicity** (spin orientation along the direction of motion) in the limit of zero mass.

*   For a **massless particle** (or in the high-energy limit), **chirality equals helicity**.
*   **Right-handed** means spin is aligned with the momentum.
*   **Left-handed** means spin is opposite the momentum.
*   When the mass is significant  $(m \sim E)$ , chirality and helicity are **not the same**. A massive particle's state is a mixture of both chiral components, and its helicity can change under a Lorentz boost (like moving to its rest frame).

This distinction is fundamental in particle physics. For example, in the **electroweak interaction** of the Standard Model, the  $W$  boson couples only to **left-handed chiral fermions** and **right-handed chiral anti-fermions**.
### **Connection to the Weak Interaction** 




![This figure illustrates the weak interaction vertex, specifically the decay of a  $W$  boson into an electron ( $e^-$ ) and an electron neutrino ( $\nu_e$ ). The diagram on the left shows the Feynman diagram with a  $W$ -boson (denoted by the wavy line) decaying into an outgoing electron and neutrino. The label "Vector - Axial" refers to the  $V - A$  (vector minus axial-vector) nature of the weak interaction, which is described by the term  $\bar{\psi} \gamma^\mu (1-\gamma^5) \psi$  in the Lagrangian, or equivalently  $2 \bar{\psi} \gamma^\mu P_L \psi$ , where  $P_L$  projects onto left-handed chiral states.  The diagram on the right illustrates the chirality and helicity properties of the particles involved: the electron is labeled as left-handed (LH), indicating that only the left-handed chiral component of the electron participates in the weak interaction, while the neutrino is represented as right-handed (RH) for the outgoing antineutrino—or, in standard convention, as a left-handed neutrino for the incoming channel. The arrows labeled  $\frac{1}{2}$  and direction of spin indicate the spin projection (helicity) relative to the direction of motion. This representation reflects the maximal parity violation of the weak interaction: only left-handed electrons and right-handed antineutrinos are produced in the decay, underscoring the connection between chirality, helicity, and weak processes discussed in the text.](2024-Lecture-10-images/fig2.png){#fig-fg2}






The weak interaction vertex is described by the ** $V-A$  (Vector minus Axial-vector)** structure. The corresponding term in the Lagrangian is proportional to:
  $$\bar{\psi} \gamma^\mu (1 - \gamma^5) \psi$$  
This can be rewritten using the left-handed projection operator:
  $$\bar{\psi} \gamma^\mu (1 - \gamma^5) \psi = 2 \bar{\psi} \gamma^\mu P_L \psi$$  


::: callout-important
This mathematical structure has a direct physical consequence: **maximal parity violation**. In processes like  $W$  boson decay, it produces only left-handed electrons and right-handed antineutrinos.
:::

For **neutrinos** (traditionally treated as massless in the Standard Model), this means:

*   All **neutrinos** are left-handed.
*   All **anti-neutrinos** are right-handed.

This is why, before neutrino masses were established, the possible existence of **right-handed neutrinos** was a major topic in new physics searches, with connections to theories of dark matter.

### **Key Conceptual Takeaways**

1.  **Orthogonality & Decoupling:** Due to  $P_R P_L = 0$ , right-handed and left-handed chiral states are orthogonal. 




![This figure illustrates the concept that **for particles with mass, it is possible to flip the spin** by changing frames of reference. The drawing shows a sequence where a massive particle's spin orientation (represented by the smaller arrow above the momentum arrow,  $\vec{p}$ ) can be changed relative to its direction of motion when a Lorentz boost ( $B_z^{-1}$  or  $B_z$ ) is applied. This effect is possible because for massive particles, **helicity** (the projection of spin along the momentum direction) is not Lorentz-invariant; a suitable boost can reverse the direction of momentum while leaving the intrinsic spin unchanged, thereby flipping the helicity.   This physical property distinguishes massive from massless particles in relativistic quantum field theory: for **massive particles**, helicity and chirality are not identical, and helicity depends on the observer’s frame. In contrast, for **massless particles**, helicity is frame-independent, and spin cannot be flipped by a boost. This is a central concept discussed in the lecture, especially in the context of chirality, helicity, and their relation in various energy regimes for spin-1/2 particles.](2024-Lecture-10-images/fig3.png){#fig-fg3}




 For massless particles, they are completely independent and do not "talk" to each other.

2.  **Frame Dependence:**
*   **Helicity** is frame-dependent for massive particles (you can "flip" the spin by overtaking the particle).
*   **Chirality** is a Lorentz-invariant property for *massive* particles. A left-handed chiral state remains left-handed under boosts and rotations.
3.  **The Chiral Limit:** The limit  $m \to 0$  is called the **chiral limit**. In this limit, chiral symmetry is restored, and chirality becomes identical to helicity.
4.  **Practical Use:** While helicity is easier to visualize, **chirality** is often easier to work with in Lagrangian field theory because projection operators provide a clean, frame-independent way to separate components.



## Flavor Symmetry and Chiral Limit in QCD

Here is the enhanced lecture transcription.

Let’s look at the **QCD Lagrangian**. This describes the dynamics of quarks and gluons; we are not including the electroweak sector of the Standard Model here.

The Lagrangian has two main parts:

*   The **gauge part**, involving the gluon field strength tensor  $G_{\mu\nu}^a$ , describes the pure gluon interactions.
*   The **matter part**, involving the quark fields  $\psi_i$ , contains their kinetic and mass terms, as well as their interactions with the gluons.

In more detail:

*   The term  $\bar{\psi}_i i \mathrlap{/}\partial \psi_i$  is the **kinetic term** for the quarks.
*   The term  $m_i \bar{\psi}_i \psi_i$  is the **flavor-dependent mass term**.
*   The interaction with the gluon field  $G_\mu^a$  comes from the **covariant derivative**  $D_\mu = \partial_\mu - i g_s T^a G_\mu^a$ , which replaces the ordinary derivative in the kinetic term.

The indices here are important:

*   The index  $i$  is for **flavor** (e.g.,  $u, d, c, s, t, b$ ). There are six flavors.
*   The index  $a$  is for **color**. The matrices  $T^a$  are the generators of the local  $SU(3)_c$  gauge symmetry.

The **local  $SU(3)_c$  gauge symmetry** is fundamental. "Gauge" means we can modify the phase of the color part of the quark wave function at every point in spacetime. The quark field  $\psi$  is a wave function whose color components form a three-state vector.

The local transformation is:
  $$\psi(x) \rightarrow U(x) \psi(x), \quad U(x) = \exp(i \alpha^a(x) T^a)$$  
where  $\alpha^a(x)$  are parameters that depend on the spacetime point  $x$ . This local symmetry dictates how quarks and gluons interact and is precisely why we must use the covariant derivative  $D_\mu$  instead of the ordinary derivative  $\partial_\mu$ .

Now, let's consider **flavor symmetry**. For the light quarks— $u$ ,  $d$ , and  $s$ —their masses are very small compared to the characteristic energy scale of QCD,  $\Lambda_{\text{QCD}} \sim 1 \text{ GeV}$ .


::: callout-note
In the **chiral limit**, where we set the light quark masses to zero, the QCD Lagrangian gains an approximate **global  $SU(3)_f$  flavor symmetry**. The transformation acts on the flavor triplet  $\Psi = (u, d, s)^T$  as:
  $$\Psi \rightarrow U \Psi, \quad U = \exp(i \theta^a \lambda^a)$$  
where  $\theta^a$  are constants (global) and  $\lambda^a$  are the Gell-Mann matrices. This symmetry is not exact in nature due to the small, non-zero quark masses, but it provides a powerful organizing principle for low-energy expansions.
:::

This symmetry is straightforward to check in the Lagrangian. The flavor transformation matrix  $U$  acts on  $\psi$  and  $\bar{\psi}$ . Their phases cancel in the mass term  $\bar{\psi} \psi$ . For the kinetic term  $\bar{\psi} i \gamma^\mu D_\mu \psi$ , we must check the covariant derivative. The  $T^a$  inside  $D_\mu$  belongs to the **color  $SU(3)_c$ ** group. In flavor space, it is just the identity matrix and does not mix flavors. Therefore, the flavor transformation commutes with  $D_\mu$ , and the Lagrangian is invariant.

Finally, we can decompose the theory by **chirality**. We project the quark field into its left- and right-handed components using:
  $$\psi_{L,R} = P_{L,R} \psi, \quad P_{L,R} = \frac{1}{2}(1 \mp \gamma_5)$$  

*   In the chiral limit ( $m \rightarrow 0$ ), the kinetic term separates cleanly:
  $$\bar{\psi} i \mathrlap{/}\partial \psi = \bar{\psi}_L i \mathrlap{/}\partial \psi_L + \bar{\psi}_R i \mathrlap{/}\partial \psi_R$$  
There is **no interaction term mixing left- and right-handed quarks**.

*   The mass term  $m \bar{\psi} \psi$ , however, is the only term that mixes these chiralities:
  $$m \bar{\psi} \psi = m (\bar{\psi}_L \psi_R + \bar{\psi}_R \psi_L)$$  

This chiral decomposition reveals that in the massless limit, the global flavor symmetry is enhanced to  $SU(3)_L \times SU(3)_R$ , acting independently on the left- and right-handed fields. The small quark masses break this chiral symmetry explicitly, which is the starting point for constructing effective low-energy theories like Chiral Perturbation Theory.



## Chiral Symmetry and Its Breaking

We consider a possible symmetry: **chiral symmetry**. This is the transformation of the right- and left-handed components independently. We want to consider a chiral symmetry.

Let's check if everything is fine. Here is the three-component vector in the flavor space,  $SU(3)$ . Here is a  $3 \times 3$  matrix. The parameter  $\alpha$  does not depend on the coordinates; it's a **global transformation**.

We import the parameters for the left-handed rotation and the right-handed states rotation, weighted by  $i$ . We count eight numbers here and eight numbers there, for an overall 16 random numbers.

We apply this transformation and the Lagrangian doesn't change unless it has mass. How do we see that it doesn't change if the mass is zero? Because left-handed and right-handed states don't talk to each other. There is an extra phase that appears here and an extra phase that appears there; they cancel each other. The same happens here. The symmetry is only broken when a mass term appears.

This is the chiral symmetry. The mass term has a mixture of the two components. A phase will appear. Here is one combination of the  $\alpha$  parameters and here is the other one, and therefore it does not disappear. The mass term **breaks chiral symmetry explicitly**.


::: callout-important
**Explicit Breaking by Mass:**
The quark mass term mixes left- and right-handed components:
  $$\mathcal{L}_{\text{mass}} = -m \bar{\psi} \psi = -m (\bar{\psi}_L \psi_R + \bar{\psi}_R \psi_L)$$  
Under a chiral transformation, the phases from  $\psi_L$  and  $\psi_R$  do not cancel, making the Lagrangian non-invariant. For light quarks ( $u, d, s$ ), this explicit breaking is a small effect because  $m_q \ll \Lambda_{\text{QCD}}$ .
:::

Now, something I won't derive, but you might have heard earlier, is that the chiral symmetry is **spontaneously broken**. Apparently, if you look at QCD at low energy, even if you start with no mass term, the quarks by their interactions generate a non-zero expectation value. The quarks appear massive even if you don't put mass in the Lagrangian. That's quite spectacular.

I have a picture in mind. We have a space in vacuum. Let me share the plane of the field expectation value. In this plane, if you are sitting at zero, we have a chiral symmetry exact in the Lagrangian and we can rotate left and right states independently. But what appears is that the vacuum where we live in is not at zero; it's at a location different than zero.

That happens because if you look at the sort of potential of the theory, it has a similar shape as the Higgs potential. It appears that for quantum chromodynamics, quark-antiquark pairs acquire, by interacting with each other, a non-zero expectation value. Therefore, we live in this plane of expectation not at zero, but at a certain shifted location.

One sees this continuous symmetry breaking effect in many domains of physics:

* In **superconductors**, when electron pairs form Cooper pairs.
* In the **Higgs mechanism**.

These are other examples of spontaneous symmetry breaking. It's always the same mechanism.

You have an exact theory when you sit at zero of the sort of coordinate space. Once you acquire a non-zero distance from the origin in the coordinate space, and this appears—think of a **Mexican hat potential**—once you see it moves to the minimum... and this, what is spontaneous, actually is the shape of the potential.

The interaction is such that when you integrate over gluons, what you have is the core part interaction potential. It appears to have this shape. We could have lived in another vacuum that is located here with perfect chiral symmetry, but it appears that energy-wise it's better to be in a vacuum that has a non-zero expectation value. That's the effect of spontaneous symmetry breaking.

That's all consideration of the mass scale. In addition to spontaneous symmetry breaking, the chiral symmetry has explicit symmetry breaking. That's done by introducing non-zero masses. The spontaneous symmetry breaking is a major effect, however, it's captured by the theory.

Explicit symmetry breaking is a small effect since the masses of the quarks are much smaller than the scale of  $\Lambda_{\text{QCD}}$ . You can use perturbation theory. That's what **chiral perturbation theory** is about.

The theory builds on the fact that there is a chiral symmetry. Spontaneous symmetry breaking comes as the outcome of this consideration. This symmetry breaking is introduced as a perturbation parameter. We won't go to the detailed consideration of chiral perturbation theory.

I will start next lecture by just writing the chiral Lagrangian and then we move on. We won't have time to consider it, and I would invite you to dedicated courses. We have experts in the theory department, people who work on chiral perturbation theory and they are world experts on this consideration.

I wanted to give you the general concepts and introduce a sort of experimentalist view to this. So thanks for... Well, let's maybe spend two minutes for questions.

**Student Question:** What is the variable you have in this plane? Is it the vacuum? When you write this, when you roll like this, this like...

**Answer:** Yes. The number  $\langle \bar{\psi} \psi \rangle$ . So is the point that you choose the correct state always? It's the expectation value for this correlation. This is the **chiral condensate**, the order parameter for spontaneous symmetry breaking.

**Student Question:** What's on the axis? What should I imagine them to be?

**Answer:** You can't write it down easily. I really want to talk about this value because that's what acquires a non-zero expectation value. The axis that I mean on display is the value of the expectation. But there must be better coordinates for that. It's a field expectation. We draw the potential of the interaction. Strictly speaking, it's undefined in a naive sense. In quantum field theory, what is defined is the expectation value of this operator. You can draw for the theory a potential as a function of the expectation value. That expectation value is along the x-axis, and then I have my potential  $V$ .

What I'm not entirely happy with my explanation, with my analogy now, is that this... I would like this thing to have also complex space, and expectation that you expect this to be real. So let me think of an analogy. It's called the quasi-classical expansion of field theory. I've seen it once in a couple of books.

I'm talking about the strict definition of this. You always see these nice potentials, but how to define these starting from the graduate street? I think it's related to the  $1/N$  expansion. You have your  $N$  and then you expand with respect to this parameter to obtain that. What I will do is find the source and point you to that. Maybe we discuss it.

Another way to understand this is to look at a simpler model. There are a few models, one of them related to spontaneous symmetry breaking in superconductors, where this thing has a simpler meaning. You don't need quantum field theory to see it, and then that potential appears explicitly. Maybe then we find a better meaning.

**Student Question:** You said that there was an interaction between particles and antiparticles, and you said like electrons and positrons. But it's two electrons. Two electrons form the Cooper pair. Did you have a particle physics course, right? And the electroweak and Higgs mechanism was a part of the course?

**Answer:** Some of it. No. Generally at the particle physics course. Okay. It's really strong. We can track. Yeah, that makes sense, right? Maybe that you're talking about QED, right? QED. No, but I mean we talked about QED but we didn't talk about electricity. That was also strange a little bit. But maybe we did. Maybe we did. That's it. Yeah. Thanks a lot.

Any more questions?

**Student Question:** What do you even do about the heavy quark?

**Answer:** Oh, there is another expansion, so it's the other way around. It's not  $m_q / \Lambda_{\text{QCD}}$ , but rather they are non-relativistic and you can use **pNRQCD**—potential non-relativistic QCD. The expansion parameter there is the quark velocity  $v/c$ , which is small for heavy quarks.

All right. Thanks.

