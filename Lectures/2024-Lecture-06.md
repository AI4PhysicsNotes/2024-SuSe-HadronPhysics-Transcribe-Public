---
title: (2024) Lecture 6
author: ''
presenter: Mikhail Mikhasenko
note_taker: Ilya Segal
date: '2024'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



## Lambda Decay: Kinematics and Unpolarized Width

Let’s start with the recap. The physics reaction to consider is the lambda baryon decay into the proton and a pion.

We go through a standard list to understand any reaction:

1.  **What type of interaction is responsible?**
2.  **What variables describe the process?**
3.  **Write the matrix element.**
4.  **Calculate the unpolarized decay width.**
### 1. Identifying the Interaction 




![This figure presents a schematic representation of the decay process  $\Lambda \rightarrow p + \pi^-$  in the context of particle physics. The initial state is a  $\Lambda$  baryon, with spin-parity  $J^P = \frac{1}{2}^+$  and quark content  $uds$ , decaying into a proton ( $p$ ) with quark content  $uud$  and the same spin-parity, and a negatively charged pion ( $\pi^-$ ) with quark content  $\bar{u}d$  and spin-parity  $0^-$ .   The diagram includes notations identifying each particle’s quantum numbers and quark composition. Importantly, the vertex connecting the initial and final states is labeled as "weak," highlighting that this process proceeds via the weak interaction rather than the strong force. This distinction is physically significant because the decay involves a change in strangeness ( $\Delta S = 1$ ), which is only possible through weak interactions due to flavor conservation by the strong interaction.  The figure visually reinforces key lecture themes: the necessity of the weak force for strangeness-changing decays, and the role of quantum numbers (spin, parity, strangeness) and quark content in determining allowed interactions. The physical meaning, as discussed in the text, is that the  $\Lambda$  baryon’s comparatively long lifetime and the observation of flavor-changing decays are direct evidence for the weak interaction’s unique properties, including parity violation.](2024-Lecture-06-images/fig1.png){#fig-fg1}






We have a  $\Lambda$ , a proton, and a pion. This is a flavor-changing process:

*   Initial state ( $\Lambda$ ): quark content  $uds$ , strangeness  $S = -1$ .
*   Final state ( $p + \pi^-$ ): quark content  $uud + \bar{u}d$ , strangeness  $S = 0$ .

**Strangeness-changing transitions can only proceed via the weak interaction**, as strong and electromagnetic interactions conserve flavor. Since the weak interaction violates parity, this decay will not conserve parity.


::: callout-note
The key identifier is the strangeness change:  $\Delta S = 1$ . This uniquely specifies the interaction as weak.
:::

### 2. Kinematics and Variables

This is a one-to-two body decay:  $\Lambda \to p + \pi^-$ . The simplest approach is to work in the **center-of-mass frame**, which is the rest frame of the decaying  $\Lambda$ .

In this frame:

*   The  $\Lambda$  is at rest.
*   The proton and pion are emitted back-to-back.
*   The magnitude of their momentum  $|\mathbf{p}|$  is **fixed entirely by the particle masses** via energy-momentum conservation:

  $$|\mathbf{p}| = \frac{1}{2M_\Lambda} \sqrt{ [M_\Lambda^2 - (m_p + m_\pi)^2] [M_\Lambda^2 - (m_p - m_\pi)^2] }$$  

Since there is no preferred direction when the  $\Lambda$  is at rest, there are **no free angular variables**. The only remaining degrees of freedom are the **discrete spin projections** of the particles involved.

**Particle Spins and Parity:**

*    $\Lambda$ : Spin  $J=\frac{1}{2}$ , Parity  $P=+$  ( $J^P = \frac{1}{2}^+$ )
*   Proton:  $J^P = \frac{1}{2}^+$ 
*   Pion:  $J^P = 0^-$ 

### 3. The Matrix Element and Helicity Amplitude

The transition amplitude  $H$  describes the process. Given the kinematics,  $H$  cannot depend on angles, but it **does depend on spin projections**.

Let the spin projection (helicity) of the  $\Lambda$  be  $\lambda_\Lambda$  and of the proton be  $\lambda_p$ . The pion is spinless. **Angular momentum conservation along the decay axis requires**:
  $$\lambda_\Lambda = \lambda_p$$  
We denote this common value simply as  $\lambda = \pm\frac{1}{2}$ .

Therefore, the helicity amplitude is:
  $$H_{\lambda} = \langle p(\mathbf{p}, \lambda), \, \pi^-(-\mathbf{p}) \, | \, \mathcal{T} \, | \, \Lambda(\mathbf{0}, \lambda) \rangle$$  
We have two independent amplitudes:  $H_{+1/2}$  and  $H_{-1/2}$ .

### 4. Unpolarized Decay Width

The decay width  $\Gamma$  for a spin- $\frac{1}{2}$  particle is given by:
  $$\Gamma = \frac{1}{2M_\Lambda} \times (\text{Spin-Averaged } |\mathcal{M}|^2) \times (\text{Phase Space})$$  

*   **Spin Average/Sum:** We average over the 2 initial  $\Lambda$  spin states and sum over the 2 final proton spin states. The condition  $\lambda_\Lambda = \lambda_p$  means only two terms survive:  $|H_{+1/2}|^2$  and  $|H_{-1/2}|^2$ .
*   **Phase Space:** For a two-body decay in the parent's rest frame, the Lorentz-invariant phase space integrates to  $\frac{|\mathbf{p}|}{8\pi^2 M_\Lambda^2} \int d\Omega$ . With no angular dependence,  $\int d\Omega = 4\pi$ .

Putting it all together, the unpolarized width simplifies to:
  $$\Gamma = \frac{|\mathbf{p}|}{8\pi M_\Lambda^2} \left( |H_{+1/2}|^2 + |H_{-1/2}|^2 \right)$$  

This width, for the dominant decay  $\Lambda \to p \pi^-$ , determines the  $\Lambda$  baryon's lifetime:
  $$\tau_\Lambda = \frac{\hbar}{\Gamma} \approx 10^{-9} \, \text{s}$$  
This lifetime is long enough that the  $\Lambda$  travels measurable distances (e.g., meters in a detector) before decaying, creating a **displaced secondary vertex**—a key experimental signature.

### 5. Extension: The Helicity Frame for a Moving  $\Lambda$ 

The discussion so far assumed a  $\Lambda$  at rest. If the  $\Lambda$  is moving in the lab frame, its momentum defines a **preferred axis** (the helicity frame). By boosting to the  $\Lambda$ 's rest frame along this axis, we can now measure decay angles ( $\theta, \phi$ ) relative to it.

This introduces angular dependencies into the decay distribution. For a polarized  $\Lambda$ , the differential decay rate takes the form:
  $$\frac{d\Gamma}{d\cos\theta} \propto 1 + \alpha \, P_\Lambda \cos\theta$$  
where  $P_\Lambda$  is the  $\Lambda$  polarization and  $\alpha$  is the **decay asymmetry parameter**, which encodes the parity violation in the weak decay and is related to the helicity amplitudes:
  $$\alpha = \frac{|H_{+1/2}|^2 - |H_{-1/2}|^2}{|H_{+1/2}|^2 + |H_{-1/2}|^2}$$  
This angular analysis allows experiments to extract spin and parity-violation information.



## Spin States and Helicity Transformations

I would like to start giving a bit more detail on the topic from last time.
### **Canonical Spin States and Rotations** 




![This figure illustrates the concept of rotating a particle's state in the context of canonical spin states. The particle, initially at position  $M$  on the  $Z$ -axis, is subjected to an **active rotation**—meaning the particle itself is rotated, not the coordinate system. The curved arrow represents a rotation about the  $Y$ -axis, changing the direction of the particle's momentum from the  $Z$ -axis towards the  $X$ -axis by an angle  $\theta$ . This visualization directly connects to the discussion in the lecture about how canonical spin states  $|J, M\rangle$  transform under rotations, and how Wigner D-functions describe the resulting mixture of spin projections after such a rotation. This process is fundamental for constructing helicity states and understanding how the spin quantization axis changes relative to the particle's motion.](2024-Lecture-06-images/fig2.png){#fig-fg2}






The state  $|J, M\rangle$  is the base state of a particle with spin  $J$  and has a projection onto the Z-axis equal to  $M$ . If you act with the  $J_z$  operator, you find that this is an eigenstate of  $J_z$  with eigenvalue  $M$ .

  $$J_z |J, M\rangle = M |J, M\rangle$$  

This defines the **canonical spin state**, where the quantization axis is fixed as the Z-axis. The picture to have in mind is the  $2J + 1$  possible projections of the state, which could be in a mixed state.

All transformations we will apply are **active transformations**. It's easier to think of them as transformations applied to the particles themselves, not to the coordinate system. The coordinate system remains fixed. If I boost or rotate and show you a direction, that operation is applied to the physical object.

*   If I boost a particle in the Z direction, the particle gets faster and moves along Z.
*   If I rotate my particle by an angle about the Y axis, I rotate the particle, not the coordinates. Rotations about the Y axis are often the most nontrivial and are what we will focus on.

When we rotate a spin state with a definite projection  $M$ , we find it becomes a combination of states with different projections:

  $$R(\theta) |J, M\rangle = \sum_{M'} D^J_{M'M}(\theta) |J, M'\rangle$$  

The coefficients  $D^J_{M'M}(\theta)$  are the **Wigner D-functions**. They are tabulated, often alongside Clebsch-Gordan coefficients.


::: callout-note
Since we discussed SU(2) extensively with Isospin, the group theory here is exactly the same. To compute these rotations, you can either look up the Wigner D-functions or perform a matrix exponentiation:  $R(\theta) = e^{-i J_y \theta}$ . The matrix form of  $J_y$  depends on the spin  $J$ .
:::

### **Explicit Rotation Matrices**

For a spin-1/2 particle, the generator  $J_y$  is  $\frac{1}{2}\sigma_y$ , where  $\sigma_y$  is the Pauli matrix. The rotation operator is:

  $$R_{1/2}(\theta) = e^{-i \frac{\theta}{2} \sigma_y}, \quad \text{where } \sigma_y = \begin{pmatrix} 0 & -i \\ i & 0 \end{pmatrix}$$  

Exponentiating this gives the explicit 2x2 rotation matrix:

  $$e^{-i \frac{\theta}{2} \sigma_y} = \begin{pmatrix} \cos\left(\frac{\theta}{2}\right) & -\sin\left(\frac{\theta}{2}\right) \\ \sin\left(\frac{\theta}{2}\right) & \cos\left(\frac{\theta}{2}\right) \end{pmatrix}$$  

Note the **half-angle**  $\theta/2$ , which is characteristic of spinor representations. For higher spins (e.g., spin-1), the matrix in the  $|J, M\rangle$  basis is more complicated, involving terms like  $(1 - \cos\theta)$  instead of just  $\cos\theta$ .

### **Constructing Helicity States for Moving Particles**

Now, let's understand what happens to spin states when we boost them. The goal is to define spin quantization for a **moving particle**. 




![This figure illustrates the concept of a **moving particle** and the definition of its spin state in the context of Lorentz transformations, as discussed in the provided lecture notes.  - **Top Panel:** Shows a coordinate system with axes  $x$  and  $z$ , and a momentum vector  $\vec{p}$  pointing in the  $xz$ -plane. This represents a particle moving with momentum  $\vec{p}$  in a given direction, not aligned with the coordinate axes.  - **Bottom Panel:** Depicts the same coordinate system, with the momentum vector  $\vec{p}$  again in the  $xz$ -plane. Additionally, a vector labeled  $m$  appears, likely representing the **spin projection direction** (or magnetic quantum number orientation) with respect to the axes.  **Physical Meaning:**   The image demonstrates that for a moving particle, there are two important directions to consider: 1. **Momentum direction ( $\vec{p}$ )** – the direction of the particle's motion. 2. **Spin quantization axis ( $m$ )** – the direction along which the particle's spin projection is specified.  The key concept depicted is the difference between the **canonical basis** (spin projection along the fixed  $z$ -axis, regardless of the particle's momentum) and the **helicity basis** (spin projection along the direction of motion, i.e., the momentum  $\vec{p}$ ).   This figure corresponds to the lecture's discussion on constructing helicity and canonical states for moving particles: - **Helicity State:** Spin is quantized along the momentum direction ( $\vec{p}$ ). - **Canonical State:** Spin is quantized along a fixed axis (typically  $z$ ), irrespective of the actual momentum direction.  The illustration sets up the need to relate these two descriptions (basis choices) using appropriate Lorentz transformations (boosts and rotations). This is foundational for understanding how spin states transform for moving particles and is essential for analyzing decays and scattering processes in relativistic (high-energy) physics.](2024-Lecture-06-images/fig3.png){#fig-fg3}






Consider a particle moving in the XZ plane. There are two common ways to define its spin state:

1.  **Helicity Basis:** Quantize the spin along the **direction of motion**.
2.  **Canonical Basis:** Define the state with non-zero momentum but quantize the spin along the **fixed Z-axis**.

These two bases are **not equal**, but they are related. A state with definite helicity (spin projection along momentum) will be a mixed state in the canonical basis, and vice versa.

The **helicity state**  $|p, \lambda\rangle$  is constructed systematically:

1.  Start with a particle at rest in a canonical state  $|0, \lambda\rangle$ , with spin projection  $\lambda$  along the Z-axis.
2.  Boost it along the Z-axis with a boost  $B_z(\beta)$  to give it momentum.
3.  Rotate the entire system using a rotation  $R(\phi, \theta, 0)$  to point the momentum in the desired direction  $p$ .

This construction is summarized by the formula:

  $$|p, \lambda\rangle = R(\phi, \theta, 0) \, B_z(\beta) \, |0, \lambda\rangle$$  

### **Key Properties and Lorentz Algebra**

Helicity states have an important property: **helicity is invariant under rotations**.

  $$R(\alpha) |p, \lambda\rangle = |p', \lambda\rangle$$  

where  $p' = R(\alpha) p$ . Rotating the state simply rotates the momentum vector, but since the spin quantization axis is tied to the momentum direction, the helicity eigenvalue  $\lambda$  remains the same.

The most demanding part of working with these states is managing the algebra of boosts and rotations. A key relation in the Lorentz group is that any combination of a boost, a rotation, and another boost can be rewritten as a different combination of a rotation and a boost:

  $$B' R B \Leftrightarrow R^{-1} B' R$$  

When you apply this to a canonical state, you get a linear combination of helicity states,  $\sum C_{\lambda'} |p, \lambda'\rangle$ .

We know how Lorentz transformations act on 4-vectors like momentum. For example, a boost along the Z-axis is represented by the matrix:

  $$B_z(\beta) = \begin{pmatrix}
\gamma & 0 & 0 & \gamma\beta \\
0 & 1 & 0 & 0 \\
0 & 0 & 1 & 0 \\
\gamma\beta & 0 & 0 & \gamma
\end{pmatrix}, \quad \gamma = (1-\beta^2)^{-1/2}$$  

The remaining task is to track how the **spin projection** mixes with the directional motion under these transformations. The result is intuitive: a transformation generally produces a linear combination of different spin projections, not a single one. The exact coefficients are found by applying the boost-rotation composition rules.



## Boost-Rotation Relations and State Notation

What will happen here is that we started with a vector. Instead of boosting this vector directly—which would make it a little more inclined forward—you could start from the particle's rest frame.

The **boost-rotation-boost** sequence applied to the particle's thrust is equivalent to this long vector expression. This is the same as rotating and then boosting. The boost I apply to the particle at rest directly produces my vector with the desired momentum magnitude. The only additional operation needed is a rotation to orient it. So, instead of boosting twice, I can boost only once to achieve a vector of a specific speed or length. That's the essence of the relation shown.

Now, let's examine the second type of state: the **canonical state**, and how we obtain it.

The canonical state is defined by the following combination of operations. First, consider the recipe for achieving a state where the momentum  $\mathbf{p}$  is rotated by an angle  $\theta$  from the z-axis:

1. Begin in the particle's rest frame.
2. Apply a rotation  $R^{-1}$  so that the state has a specific projection onto the z-axis. After this rotation, you can visualize the spin arrow pointing slightly downward.
3. Then, boost this state forward along the new direction.
4. (see @fig-fg3) Finally, apply the rotation  $R$ .

Let me visualize this: We have the initial state, we boost it to give it momentum, then we perform the final rotation, and *voila*, we arrive at the desired configuration.


::: callout-note
**On Notation:** When I write  $|\mathbf{p}, j, m \rangle$ , you must ask: is this a canonical state or a helicity state? Strictly speaking, seeing  $\mathbf{p}$ ,  $j$ , and another number doesn't tell you.

In general notation,  $m$  usually refers to the **z-axis projection** (canonical), while  $\lambda$  refers to the **helicity**. It is much better to indicate this explicitly, for example, by adding a subscript like  $_{\text{can}}$  or  $_{\text{hel}}$ . I will sometimes be less precise when rushing, but clear notation is important to avoid confusion.
:::

It is now clear how the two types of states are related. But before discussing that relation, let's look at the transformation property of canonical states.

**Transformation of Canonical States**

I want to apply a rotation  $R$  to a canonical state  $|\mathbf{p}, j, m \rangle_{\text{can}}$ . According to the definition, this state is constructed as  $R B R^{-1}$  acting on the rest state  $|0, j, m \rangle$ .

So, we compute:
  $$R |\mathbf{p}, j, m \rangle_{\text{can}} = R (R' B R'^{-1}) |0, j, m \rangle$$  
where  $R'$  and  $B$  are the specific rotation and boost used to create  $|\mathbf{p}, j, m \rangle_{\text{can}}$  from the rest state.

To proceed, I insert an identity ( $R'^{-1} R'$ ) in a strategic spot:
  $$= (R R') B (R'^{-1} R) R^{-1} |0, j, m \rangle$$  

By grouping the operations, the combination  $(R R') B (R'^{-1} R)$  becomes a new boost-rotation sequence that generates a canonical state with a **rotated momentum**  $\mathbf{p}' = R\mathbf{p}$ . The remaining operation  $R^{-1}$  acts directly on the rest state.

We know how a rotation acts on a rest-state spin projection: it's given by the **Wigner D-matrix**. Therefore, the result is a linear combination:
  $$R |\mathbf{p}, j, m \rangle_{\text{can}} = \sum_{m'} D^j_{m'm}(R) |\mathbf{p}', j, m' \rangle_{\text{can}}$$  
where  $\mathbf{p}' = R \mathbf{p}$ .

*Does the momentum change?* Yes, it gets rotated to  $\mathbf{p}'$ . In the construction, after the initial boost along the z-axis, the momentum is  $p\hat{z}$ . The subsequent rotation  $R$  then rotates this momentum to its final direction  $\mathbf{p}'$ .



## Helicity States and Parity Violation in Lambda Decay

I learned you to boost yourself in the exercises, and now let's discuss their relation to **boosted states**.

So, have a look at them and tell me how you would relate them. If you need to relate one to another: this is a **boosted state**, and this is a **canonical state**.

Here we have the sequence  $B, J, N, C, T, N, J, M, \text{can}$ . What I want to write clearly is: they are not equal to each other, but one can express the boosted state  $|\psi(p, j, \lambda)\rangle$  as a linear combination of canonical states. These coefficients are then—I would like you to have a clear understanding of how we find them.

### **1. Relating Boosted and Canonical States**

This state is defined according to a specific transformation. What that means: on the left side, we have  $R^{-1}$ , a rotation. In order to apply "rotation, boost, rotation minus one" to the state, I like to introduce  $R^{-1} R$  (the identity). Once I do that, I have something like this, but then  $R B R^{-1}$  will be my **boost** that makes the canonical state. What remains is to apply the  $R$  to this state, and you know how to apply  $R$ . This is simply it.


::: callout-note
**Physics meaning:** A boosted state  $|\psi(p, j, \lambda)\rangle$  with definite momentum  $p$  and helicity  $\lambda$  is connected to a rest-frame canonical state  $|\psi(0, j, m)\rangle$  via Lorentz transformations:  $|\psi(p, j, \lambda)\rangle = R(B) |\psi(0, j, m)\rangle$ , where  $R(B)$  is the rotation associated with the boost direction.
:::

### **2. Revisiting Lambda Decay and the Helicity Frame**

I wanted to quickly come back to the  $\Lambda$  decay and tell a little more about how we derived the formula. The large peak formula involves many  $D$ -functions and  $H$ 's from the last lecture.

I'm going to consider now a  $\Lambda$  that moves in the wave frame. It has a helicity, and then it decays. To define the  $z$ -axis, we need the direction of motion of the  $\Lambda$  in the lab frame. 




![This figure illustrates the **decay of a polarized  $\Lambda$  baryon**, focusing on the transformation between different reference frames using the concept of the **helicity frame**.   - **Leftmost:** A  $\Lambda$  baryon is moving with its spin polarization (indicated by  $\lambda_\Lambda$ ) along the  $z$ -axis. This represents the **initial state**, where the  $\Lambda$  is in motion (lab frame). - **Center:** Upon decay, the  $\Lambda$  produces a proton ( $p$ ) and a pion ( $\pi$ ). Their momenta ( $\vec{p}_p$  and  $\vec{p}_\pi$ ) and spin projection  $\lambda_p$  for the proton are shown lying in a specific plane, which is crucial for defining the decay kinematics. This plane is set by the  $\Lambda$ 's momentum and the outgoing proton/pion momenta. - **Rightmost:** The diagram is labeled by the operation  $B^{-1}$ , representing a **Lorentz boost to the  $\Lambda$  rest frame** (i.e., the "helicity frame"). In this frame, the decay products' momenta become back-to-back and lie in the same decay plane, with the definitions of the  $z$ -axis and the **helicity angle  $\theta$ ** relative to the polarization direction preserved.  **Physical meaning:**   The sequence demonstrates how, for a **polarized  $\Lambda$  baryon decay**, one defines the quantization axis (the  $z$ -axis) by the  $\Lambda$ 's motion. Then, by boosting into the  $\Lambda$  rest frame (helicity frame), the angular distribution of the proton (or pion) can be analyzed relative to the polarization vector. This enables measurement of the **decay asymmetry** and **parity violation** in the process, as encoded in the  $\cos\theta$  dependence of the decay products in the helicity frame. The figure clarifies the importance of boosting to the correct frame and defining the correct angles for extracting physical information, such as the polarization and analyzing power  $\alpha$  in weak decays.](2024-Lecture-06-images/fig4.png){#fig-fg4}




 After the boost, that direction gives us the  $z$ -axis. This way of defining the  $z$ -axis is called the **helicity frame** for the  $\Lambda$ .

*   You always have to describe from which frame you are boosting, because it depends. In different frames, the direction of the  $\Lambda$  will be different, leading to differences when you arrive at the  $\Lambda$ 's rest frame.
*   The **helicity frame** is defined as the rest frame of a particle obtained by boosting from the frame where it was moving.
*   The angle of the decay particle, when you take one of the particles (e.g., particle number one) and use it to define the angle, is called the **helicity angle**. That's common jargon in hadron physics.

When we talk about the helicity angle, it implies that we:

1.  Boosted to the particle's rest frame.
2.  Took one of the decay products as a reference.
3.  Measured the angle from there.

All the motion is still in the same plane as before. The boost and the two particle momenta are now exactly opposite. So here, the boost inverse has happened.

**Let's visualize the process:**

1.  We start with a  $\Lambda$  flying in the  $z$ -direction with a certain velocity.
2.  It decays into a proton and a pion in some plane.
3.  We invert the boost (go to the  $\Lambda$  rest frame).
4.  The proton and pion are still in the same plane, with exactly opposite directions.

If I removed the original  $\Lambda$  momentum from this picture, you would no longer have a defined plane. The plane is formed by three vectors: I need the original direction of motion of the  $\Lambda$  to define the axis with respect to which I measure the angle, and then I have a plane.

### **3. Calculating the Decay Amplitude**

This was our recap exercise. We started without knowing that, so we only had one axis. But now we have a plane and one more variable on which the amplitude depends—the scattering or helicity angle  $\theta$ —in addition to the discrete helicity variables.

We have to compute a final state, which will be a two-body decay. On the right side, we have configurations of the  $\Lambda$  sitting in its rest frame with the proton and pion. On the left side, we have the configuration of the moving  $\Lambda$ .

The way to proceed is to apply a rotation to this configuration to align it. The answer for the transition matrix element in the helicity basis is  $H_{\lambda_p, \lambda_\Lambda}$ .

  $$\mathcal{M}_{\lambda_p, \lambda_\Lambda} = \langle p, \pi^-; \lambda_p | T | \Lambda; \lambda_\Lambda \rangle$$  

This is the equation we had last time, describing the matrix element for the decay sequence. The way we get there is by applying the transition operator  $T$  on the final state to simplify it. This  $T$  acts on the proton-pion state.

We want to evaluate the application of the transition operator that takes a pion-proton state and transforms it into a  $\Lambda$ . This operator acts on the pion-proton state that has momentum  $\vec{P}=0$ . We notice this state is rotated about the  $y$ -axis by the angle  $\theta$ . We want to align it because, on the left, the state has aligned combinations. So, we have a rotation.

We pull out the rotation, and then we have the same combination now along the  $z$ -axis: the proton goes forward, the pion goes backward, and the rotation is explicit. Since these operators commute (strong interactions conserve spin), we can compute the transition operator and rotation, acting first with the transition and then by the rotation.

Essentially, this transition operator transforms a pion-proton state into a  $\Lambda$ . We explicitly do this by inserting an identity (a sum over  $\Lambda$  states) here. This matrix element we just evaluated is related to LS coupling. The inserted identity should have all possible combinations, giving a sum over  $\lambda_\Lambda$ , which results in delta functions. Therefore, we select only one state.

The last step is to apply the rotation. Once you get the idea, it's easy to see that for every bit of the transition, you have the product of a helicity transition matrix element and a rotation matrix (a Wigner  $D$ -function).


::: callout-important
**Rotation of Helicity States:** Under a rotation  $R(\theta, \phi)$ , a helicity state transforms as:
  $$R(\theta, \phi) |p, j, \lambda\rangle = \sum_{m'} D_{m'\lambda}^j(\phi, \theta, 0) |p', j, m'\rangle$$  
where  $D_{m'\lambda}^j$  are the Wigner D-matrices. For spin-1/2, this matrix is:
  $$D^{1/2}_{m'm}(\phi, \theta, 0) = \begin{pmatrix} e^{-i\phi/2}\cos(\theta/2) & -e^{-i\phi/2}\sin(\theta/2) \\\\ e^{i\phi/2}\sin(\theta/2) & e^{i\phi/2}\cos(\theta/2) \end{pmatrix}$$  
:::

### **4. Differential Cross Section and Parity Violation**

Now, the differential cross section exists as a function of the angle  $\theta$ . We know these are our cosine and sine matrices. For spin-1/2, we just had an explicit matrix, and we have two coupling constants measured in experiment. You can take them to compute the angular distribution.

The answer is the same as before because  $\sin^2 + \cos^2 = 1$ . In front of one term, you have  $\sin^2 + \cos^2$ ; in front of the other, you have  $-\sin^2 + \cos^2$ .

What we learned in this example is that if you have an **unpolarized** particle, you will not observe any interesting angular distribution. We summed over the final and initial states, and no non-trivial angular distribution remains for  $d\Gamma/d\Omega$  before integrating over  $\cos\theta$ .

Now we have a **differential cross section**. Before, we just wrote that  $\Gamma$  is equal to something, and the phase space has  $d\Omega/(4\pi)$ , an integral  $d\cos\theta/2$ ,  $d\phi/(2\pi)$ . 




![This diagram represents the angular distribution of an **unpolarized two-body decay** in the particle's rest frame, specifically showing the **differential decay rate**  $\frac{d\Gamma}{d\cos\theta}$  as a function of  $\cos\theta$  for a decay like  $\Lambda \to p \pi^-$  when the initial particle is unpolarized.  - The **horizontal axis** runs from  $-1$  to  $+1$ , which corresponds to the allowed range of  $\cos\theta$ , with  $\theta$  being the decay angle between the decay product's momentum and some fixed axis (normally, the direction of the parent particle's spin or momentum). - The **vertical axis** represents the value of the differential decay rate,  $\frac{d\Gamma}{d\cos\theta}$ . - The height of the boxes (constant for all  $\cos\theta$ ) indicates that the decay distribution is **isotropic**, i.e., independent of angle, which occurs when there is **no initial polarization** and **no parity-violating asymmetry** ( $\alpha = 0$ ) in the decay.  Physically, this tells us that for an unpolarized initial state, the decay products are emitted **equally likely in all directions**, resulting in a **flat angular distribution** of  $\frac{d\Gamma}{d\cos\theta}$  versus  $\cos\theta$ . This matches the expectation from weak decays with no preferred direction due to polarization or parity violation.](2024-Lecture-06-images/fig5.png){#fig-fg5}




 Now I just move this  $\cos\theta$  dependence to the other side.

**Polarized decay:** You get non-trivial distributions if you polarize your particle. When the  $\Lambda$  was flying, it had a spin projection  $\lambda_\Lambda$ . Now we have a formula that tells us how this looks.

Let's think about what we see in an experiment. The  $\Lambda$  travels with a certain momentum, and the projection of its spin onto its direction of motion is  $\pm 1/2$ . When it decays, we will find that it's more likely for the proton to travel forward than backward relative to the  $\Lambda$  spin direction. This angle is the proton's helicity angle.

**This violates parity.** If you apply parity to the initial and final states, you flip the momentum but not the spin. Parity implies there cannot be such a forward-backward asymmetry. This is consistent with the fact that we consider the decay amplitude inside the interaction to be from the weak force. 




![This figure illustrates the **angular distribution of the decay products** in the weak decay of a polarized  $\Lambda$  baryon, such as  $\Lambda \rightarrow p + \pi^-$ . The vertical axis represents the differential decay rate  $\frac{d\Gamma}{d\cos\theta}$  as a function of the cosine of the decay angle  $\theta$  (measured relative to the  $\Lambda$  spin or polarization axis).   The diagram shows a **forward-backward asymmetry**, where the decay rate is higher in the forward direction (along the spin or polarization) than in the backward direction. This kind of asymmetry is a hallmark of **parity violation** in weak decays. The strength of the asymmetry is governed by the decay asymmetry parameter  $\alpha$  and the polarization  $P$ :    $$\frac{d\Gamma}{d\cos\theta} \propto 1 + \alpha P \cos\theta$$    A nonzero slope indicates  $\alpha \neq 0$ , meaning that the angular distribution can be used to measure the polarization of the parent  $\Lambda$  baryon. The regions labeled in the plot correspond to the fraction of events moving "forward" vs. "backward", and the observable **forward-backward asymmetry**  $A_{FB}$  can be extracted by comparing these event counts. This asymmetry is a direct probe of parity violation and the polarization transfer in the decay.](2024-Lecture-06-images/fig6.png){#fig-fg6}






The parity violation appears explicitly if the two helicity amplitudes  $H_{1/2}$  and  $H_{-1/2}$  are not equal. If they were equal,  $\sin^2 + \cos^2$  gives 1, and there is no angle dependence.

  $$\frac{d\Gamma}{d\cos\theta} = \frac{\Gamma_0}{2} \left(1 + \alpha P_\Lambda \cos\theta\right)$$  

The **decay asymmetry parameter**  $\alpha$  quantifies this parity violation:

  $$\alpha = \frac{|H_{1/2}|^2 - |H_{-1/2}|^2}{|H_{1/2}|^2 + |H_{-1/2}|^2}$$  

If  $\alpha = 0$ , the angular distribution is symmetric (parity conservation). If  $\alpha \neq 0$ , it indicates parity violation, as in the weak decay of the  $\Lambda$ .



## Polarization, Analyzing Power, and Polarimetry in Lambda Decay

Thanks for the question. That's really important to know, and in fact they are not.

Moreover, we consider the **polarized decay**: if the 100% polarization  $P = 1$  is a pure state, it is a spin projection  $1/2$  and it's a fully polarized state. One can consider a mixed state where you don't have that, where it's not fully polarized.

Most realistically, the degree of polarization for the lambda hyperon is not 100% but let's say 60%. That's what we have. In the BES experiment case, the lambda is produced with a polarization of about 60%, and in that case the asymmetry is smaller.

So one finds that the differential decay rate is given by:
  $$\frac{d\Gamma}{d\cos\theta} = \Gamma_0 ( 1 + \alpha P \cos\theta )$$  

**Physics Meaning:**

*    $\frac{d\Gamma}{d\cos\theta}$  is the differential decay rate.
*    $\Gamma_0$  is the total decay rate or normalization constant.
*    $\alpha$  is the **analyzing power** (or decay asymmetry parameter).
*    $P$  is the degree of polarization of the parent particle (e.g., Λ hyperon).
*    $\cos\theta$  is the cosine of the angle between the decay product's momentum and the polarization axis.

We can rewrite these equations by contracting the matrix element with the polarization matrix and find out that the difference between the two hemispheres defines how well this particular decay reflects polarization.

The quantity  $\alpha$ , the **analyzing power**, tells you how well this decay is suited to measure the initial polarization. If the scalar and pseudoscalar coupling constants  $g_S$  and  $g_P$  are equal to each other  $|g_S| = |g_P|$ , you don't have sensitivity to the initial polarization. The decay is insensitive.


::: callout-note
This condition  $\alpha = 0$  when  $|g_S| = |g_P|$  means parity violation may not be observable via the angular distribution, even if the decay intrinsically violates parity. For most decays, however, there is a non-zero analyzing power.
:::

It can happen even for big decays that the couplings are equal. Parity can be violated, but it's not measured. But for most of them there is a non-zero analyzing power. So this  $\alpha$  is non-zero.

And that's why by looking at the angular distribution you see parity violation. But you can also measure the initial polarization. That's called a **polarimetry technique** and that's actively used.

The polarization  $P$  can be extracted from the measured forward-backward asymmetry:
  $$A_{FB} = \frac{N(\cos\theta > 0) - N(\cos\theta < 0)}{N(\cos\theta > 0) + N(\cos\theta < 0)} = \frac{\alpha P}{2}$$  
where  $N$  denotes the number of decays in the forward or backward hemispheres.

Look at the angular distributions. All particles have known spin, the couplings are known. But these parameters have to be measured in advance. And in that case you can measure polarization.

This initial polarization is a **super powerful observable**. So particles like lambda hyperons with a spin carry polarization out of the interaction point, which is part of the information.

*   How the lambda is produced
*   With what momentum
*   With what polarization

This tells us about the internals of the interaction. For example, imagine that a lambda hyperon is produced in the quark-gluon plasma. Its polarization can now be related to the properties of that plasma.

This is a kind of **free carrier of information** out of the mess of the quark-gluon interaction. So polarization plays an important role, if not more than other observables. And this particle is not only carrying it, but also by decaying gives us a way to measure that polarization.



## A Pedagogical Pause

We have time.
Instead of beginning a new topic, I would like to pose a question I have in mind for this lecture.
This is as if I were to explain the material to you already—you would know it, but I haven’t explained it yet.
Therefore, I’ll just give you a question and see if you know it without my lecture.
Please let me know if you have any questions about this approach.


::: callout-note
The speaker is introducing a pedagogical exercise. While no specific physics formulas are presented here, if the lecture proceeds into topics like **nuclear physics**, common formulas you might encounter include:

*   **Radioactive Decay Law**:  $N(t) = N_0 e^{-\lambda t}$ 
*   **Binding Energy per Nucleon**:  $B = \frac{\Delta m c^2}{A}$ 
*   **Cross-Section for Nuclear Reactions**:  $\sigma = \frac{\text{Number of reactions per unit time}}{\text{Incident flux} \times \text{Number of target nuclei}}$ 
:::



## Analytic Structure and Contour Integration in the Complex Plane

Next lecture, we will move on to discussing **analytic functions** and properties of amplitudes in the complex plane. This requires you to have a little bit of complex analysis. We'll discuss this, and even the next problem sheet has a bit of discussion on the complex plane. So we need a little bit of complex algebra.

Let me just say where it comes from. What is written here is obtained by doing a **contour integral**. I started with a little circle. My function is analytic and I'm going to extend and stretch the circle in all directions. This is my **x-plane**, the complex plane.

Consider the **Cauchy integral** of  $F(x)$ . If no singularities occur inside my integration contour, for any analytic function, the contour integration is zero. Then there is **Cauchy's theorem** that tells me I can insert explicitly a singularity inside the circle. If I integrate  $\frac{F(x')}{x' - x} dx'$  around the contour, the integral was zero. But now let me put a pole explicitly inside like this. When I integrate, my integral is not zero any longer. It's equal to the function evaluated at the pole, and that's my  $F(x)$ .


::: callout-note
This is the essence of **Cauchy's Integral Formula**. For an analytic function  $f(z)$  and a point  $a$  inside a simple closed contour  $C$ , the formula is:
  $$f(a) = \frac{1}{2\pi i} \oint_C \frac{f(z)}{z - a} \, dz$$  
This represents inserting a pole at  $z = a$  inside the contour, leading to a non-zero integral equal to the function's value at that point.
:::

Now I have this expression here. It's something similar. I started from a little contour, stretched it to infinity. This part of the contour dropped and the one thing that remained is the integral from 1 to 7. I'm integrating the **imaginary part** of  $F(x)$  from 1 to 7 and asking: can this equation be satisfied? The second question is: what is the **analytic structure**? What do you mean by analytic?

*   **Cut both branch points.** This is super maybe unusual for math courses, but that's what we use all the time in physics is this type of integral where the leftover of the contour is from 1 to 7.
*   Since the integral comes from both sides of the cut, and they have opposite signs, what remains is the imaginary part. The real part is the same and cancels. So the thing that remains is the integral of the imaginary part.

This leads to a **dispersion relation**:
  $$F(x) = \frac{1}{\pi} \int_{1}^{7} \frac{\operatorname{Im} F(x')}{x' - x} \, dx' + \text{(possible subtractions)}$$  
Here, the function  $F(x)$  is reconstructed from its imaginary part along the cut from 1 to 7.

It's just guessing. Yes, three is a solution. You can just take the constant three because it has no imaginary part. So the real question is if you remove the constant, are there **non-trivial solutions**? Sometimes we use words like non-vanishing. If I just say  $F(x) = 3$ , then the imaginary part is not present anywhere. The question is about solutions beyond this constant.

I think you're completely right. But I was actually thinking of non-trivial solutions. Do they exist or not? You can probably put power expansions in. It might work, it totally could work. Correct, it can be satisfied. The answer is: give me any function  $\rho(x)$  you want. I put it here. Any function  $\rho(x)$ , that integral actually converges for any value.

Let's do  $\rho(x) = \sqrt{x}$ . Put it here and it's satisfied. Just anything put inside the imaginary part, it's satisfied. The reason we're satisfied is this. It's a way to construct the function. Let me show you this: I put  $\sqrt{x}$  here instead of the imaginary part expression. Then this way I compute my function  $F(x)$ . Now this is a super special function. Its imaginary part is equal to  $\sqrt{x}$  in the region from 1 to 7. If I evaluate, the imaginary part is equal to that. In the rest of the complex plane the function is non-zero, but there are no singularities.

This insertion that I made is actually done by introducing some non-trivial analytic structures.

So let's now we have three candidates. What kind of non-analytic structures have I introduced? Well, I'd say it's like a continuous stretch of poles, a stretch of poles. What is meant by a cut? They just end somewhere. Exactly. So the cut is this non-analytic structure where the function on one side is different from the function on the other side.

It's like  $\sqrt{-1 + i\epsilon}$  and  $\sqrt{-1 - i\epsilon}$ . We see that this one is equal to  $+i$  and this one is equal to  $-i$ . So on different sides I have different values. This is a cut. So it's not really anything else than a spectrum of poles. Poles have a divergence, and this thing does not have a divergence.

So what will you say? You go for poles. Okay, so you say that here I introduce poles. Are you attracted by the concept of branch points or cuts? I was thinking about cuts, but now I'm convinced both solutions are not poles. In the integral, there are no poles. Oh, you mean the integrand? Yeah, the integrand has poles, but they are at zero and  $x$ . You have to analytically continue something. Something like I say, it's like you probably have to take it above the complex line or the real line, and below, probably differently. And I think you probably get different branches.

We say this and this. I'm not sure what the branch point is, to be honest. Oh, the branch point is where the cut starts and where it ends. So you forget about, let's say the branch work for the elements. And then you get... Okay, what if, say, poles. So the analytic structure of my function in the x-plane, if I... This is the x-plane. My function has a **branch point at 1**, a **branch point at 7**, and then they're connected by a **cut**. There are no poles. The function doesn't have any poles.

That's the way how we, I mean, the way of constructing the function here in this way, you introduce on the castle, you don't do your space. It's really funny to think, I mean, where this didn't come from, go where. And then it appears that what you can do, you can look at this plane and then take a walk here. So here you walk, you never experience any poles, any singularities.

What we can do, we can dive under. I mean, there. And you end up in a different world that has a gate. So it goes through the gate to the other world. And then you find that here there are poles, this is zero, it has poles. And then it has  $\sqrt{x}$ , so it has another cut. The function has an interesting and complicated structure.

The complex plane on the regular complex plane where we call the function doesn't have any singularities except one gate. Through the gate you can go to the other so-called **sheet** and there you have a lot of stuff going on. That's it. I mean you just get used to it. And it's really fun to think of this. We will discuss a little bit more of the complex chart structure and how scattering, what is actually the complex structure of the scattering amplitudes.



## Complex Analysis and Multivalued Functions

We have a two-week break next week, so we don't have class. Have a nice holiday, everyone.

Let's make it simpler. The integral will always converge from 1 to 7. So this is what we have, and this is a logarithm. The logarithm itself can have a pole.

Let's evaluate the function at 8:  $\log(1 - 8) - \log(17 - 8)$ . So I'm going to say  $8^+$  and  $8^-$ , and then  $\log(1) = 0$ .  $\log(-1 - i0)$  is equal to  $\log(-1) - i\pi$ .

We arrived at the result that they equal each other. So  $dy$  is at  $-i0$  and  $+i0$ , but in the equation there is no... I mean, this is continuous. Here is the jump.

From the difference here, the real part of  $x$  cannot be between 1 and 7 because we want to have a structure around it. We cannot have an  $x$  from 1 to 7 because we have the structures looping around it. Exactly. So the structure is looking around.

You introduced the branch point at the edges and then a cut connecting these points. It's explicitly clear on the Riemann surface by doing a simple integral. You see this expression has this structure: a cut, a branch point at one, a branch point at seven, and then a cut.

But the branch point is it. Is it anything else but a pole? No. A branch point can have a divergence; the function could be infinity there. But this function doesn't have one. So this function's branch point is at zero and there is... Okay, but the function is zero. Here the function is infinity.

*   A **pole** is something like  $1/x^3$ , which is a pole of third order.
*    $1/(x - c) \log(x - c)$  is **not** a pole. The pole is something you can get rid of by adding an infinitesimal value in the denominator in the unique complex plane, but it would stay infinity. A pole is an **isolated singularity**. It means it's just one point.
*   And the **branch point** is a... Where did you hear these words? Of course, I only heard of poles for like your residue theorem and stuff like that. Probably some mathematics course, mathematics for physicists, I suppose, and I guess theoretical minimum, but quite a while ago. I've never heard of branch points. Well, you know this by other means, like for square root or  $\log(x)$ . I guess I knew it existed, but I didn't know like I... Now I fear that I scared people.


::: callout-note
**On Branch Cuts and Discontinuities**
The discussion of evaluating  $\log(-1 - i0)$  relates to the **discontinuity across a branch cut**. For a logarithm, this is formally:
  $$\text{Disc} \, \log(z) = \log(z + i0) - \log(z - i0) = 2\pi i \, \Theta(-\text{Re}(z))$$  
This formula describes the jump of the logarithm across its branch cut along the negative real axis, which is essential for analyzing singularities in scattering amplitudes.
:::

I think for us your lectures are a bit unstructured and you're like a bit all over the place. But it also makes it a bit more fun because your sketches of boosts, beasts, and rotations are just sketches. You don't really prove anything in other courses; it's like a strict or rigorous proof of everything, which is just not fun for a while.

I wouldn't be afraid regarding this course. I would rather be afraid regarding first semester courses. But you might confuse them obviously. So for teaching advanced people I'm fine, but you have to be more structured for younger students.

We go through the gate, but outside the gate. You said that function is fine, it's continuous. But here you said it's another gate. This is the first world, second world enter. Here we can walk around the gate, it's fine. But then it goes through the gate and ends up another. This is another gate. This is because of how we choose; this is our first road.

So you can go through the gate and then appear on that world. And it has many more gates. You can go actually around this and enter on the other side; that's where you come out here. It would somewhat make huge sense. At least you know what happens when you just return and go and then you appear here.

But if you do this, you are not in the end. It's a third world. And then it's an infinite number of worlds because it's a logarithm. This gives an infinite number of worlds, but this one is a bit simpler. So we come here, you go to the first world. This is another world, and this guy has a gate still. You appear here and you can go around and then you appear here. So for this one, yes, it works because this one is a square root and this is logarithmic.

But imagine really taking the VR glasses and walking. That would be quite fun. You can suggest this to the Matrix Netflix. Make it an escape room: you only get out if you find the first gate. Escape room quest to this.

And where does this function appear? **All scattering amplitudes are like this.** All of the scattering amplitudes as functions of Mandelstam variables have energies in the ** $s$ -channel**.


::: callout-note
**Connection to Physics**
This "multi-world" analogy describes the **Riemann sheets** of a complex function. In physics, scattering amplitudes  $\mathcal{A}(s, t)$  are analytic functions of Mandelstam variables like  $s$ . They have:

*   **Branch points** at physical thresholds (e.g.,  $s_{\text{th}}$ ).
*   **Branch cuts** along the real axis, corresponding to where particle production can occur.
The integral structure discussed, similar to a dispersion relation  $F(s) = \int_{s_{\text{th}}}^{\infty} \frac{\rho(s')}{s' - s - i0}  ds'$ , gives rise to this exact analytic structure.
:::

