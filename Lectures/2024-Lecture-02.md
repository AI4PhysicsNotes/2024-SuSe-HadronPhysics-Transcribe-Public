---
title: (2024) Lecture 2
author: ''
presenter: Mikhail Mikhasenko
note_taker: Ilya Segal
date: '2024'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



## Estimating Hadronic Cross Sections

So how were the problems from the homework? I think when you study particle physics, you have several courses and some problems you do a few times because they appear first in nuclear physics and then maybe in particle physics or quantum field theory. You do Clebsch-Gordan coefficients four times because that's how it is; it's so important. So it will be homework for this week. There will be some Clebsch-Gordan coefficients and I hope you won't have troubles with that.

Today's lecture we will discuss more about the symmetries in hadron physics. We will start with QCD as we discussed before with the SU(3) group and then move to the phenomenology of the SU(3) flavor group. We will discuss isospin and then discuss SU(3) flavor by interchanging up and down quarks. We will connect this to the Lorentz group which has SU(2) as a subgroup responsible for rotations. You will see how the addition of spin has something to do with the addition of the quarks inside hadrons.

I will remind you of a lot of material from quantum mechanics that you've seen already and I hope it will be easy to follow. I particularly enjoy this part because this is something you can derive once you isolate yourself from books and the Internet. You can just sit and work through this really nice spin algebra.

Let me start by reminding you of the last lecture with a few questions. The first one I would like to ask is to remind you of the previous lecture. How would you estimate the typical cross section of hadronic reactions? Just an order of magnitude.

If I want just an order of magnitude, what would I do? You would take the integral over all possible configurations of the matrix element squared. If you know the matrix element, then you can calculate the cross section by summing over all final states:

  $$\sigma = \frac{1}{4\sqrt{(p_1\cdot p_2)^2-m_1^2m_2^2}} \frac{1}{N_i} \sum_{f} |\mathcal{M}_{if}|^2 d\Phi_n$$  

This will give you an exact value for the cross section in units of inverse GeV, which you can convert to centimeters squared. That's a good approach, and this is what we will do once we know the matrix element.

This is for a particular process. Here I assume that I know the initial state and the final state. This matrix element gives me the transition from the initial state to the final state. This is the particular cross section for the initial state scattering to that specific final state. If I want the total cross section, I sum over all possible final states. Since different final states are orthogonal to each other, there is no quantum coherence or interference between them, so I can just sum them up. This is the precise method.

But I want a number. What is the scale we are dealing with? What should we expect for the size of a cross section? The units of cross section is the barn. One barn is equal to  $10^{-24} \, \text{cm}^2$ .

So how do we get the order of barns? What is the cross section? Imagine that you fix your target particle, say a proton, at a certain point and you hit it with another proton. The cross section gives you the effective area in space. Once you hit this little area, the reaction happens. If you go outside, the reaction does not happen. So you can think of it literally as an area in space.

What would this area be? It is the effective area of the interaction. How do I estimate this? By the scale of the strong interaction, by the size of the proton. Think of it as a solid ball. The strong interaction range is about one fermi, which is  $10^{-15}$  meters or  $10^{-13}$  centimeters.

The cross section is on the order of  $\pi R^2$ . That's the area. For a radius  $R \approx 1 \, \text{fm}$ , we get  $\sigma \approx \pi \times (10^{-13} \, \text{cm})^2$ . This is on the order of  $10^{-26} \, \text{cm}^2$ , or about 10 millibarns. If you calculate the total cross section for hadrons, you're going to get values around that scale because the way they interact is by essentially overlapping their densities. If they are far away from each other, they never talk to each other. The strong interaction is really strong, but it's short-range.

::: callout-important
**Key Estimation:** The **geometric cross section** provides a quick order-of-magnitude estimate for hadronic reactions:  $\sigma \approx \pi R^2$ . For a proton radius  $R \approx 1 \, \text{fm} = 10^{-13} \, \text{cm}$ , this yields  $\sigma \approx 3 \times 10^{-26} \, \text{cm}^2$ , or about **30 millibarns**. This scale is typical because the interaction probability is essentially unity within the effective area defined by the particle's size.
:::


## Defining Charge via Conserved Currents

The second question I thought of is: how do I define charge in QED and QCD?

First, what is the charge in QED? We can pick the **electric charge** as the prime example.

### Defining Charge via Noether's Theorem

Do you remember how I defined the charge? If I'm given a field, say a spinor  $\psi$ , how do I figure out its charge?

The charge is a **conserved quantity** for the particles. For a free moving field, its charge isn't changing. This conservation arises from a symmetry, and Noether's theorem tells us there is a corresponding **conserved current**.

The charge is defined as the integral of the zero component (the time component) of this conserved current:
  $$Q = \int d^3x \, j^0$$  

For a Dirac field  $\psi$  in QED, this conserved current from the global U(1) symmetry is:
  $$j^\mu = \bar{\psi} \gamma^\mu \psi$$  
where  $\bar{\psi} = \psi^\dagger \gamma^0$  is the Dirac adjoint.

If we look specifically at the charge density  $j^0$ :
  $$j^0 = \bar{\psi} \gamma^0 \psi = \psi^\dagger \gamma^0 \gamma^0 \psi$$  
Since  $\gamma^0 \gamma^0 = I$  (the identity matrix), this simplifies to:
  $$j^0 = \psi^\dagger \psi$$  
This is a positive quantity for Dirac field solutions.

### Reconciling Theory with Convention

This leads to an implication: if my  $\psi$  field represents an electron, the Noether charge  $Q$  would be positive. At first, this seems like a contradiction because we know the electron has negative electric charge.

The resolution is that the **conserved quantity**  $Q$  from field theory is what's fundamentally conserved. How we match it to our physical observations—like the electron having charge  $-e$ —is a matter of convention.

We define the **observed charge** to match our conventions:
  $$Q_{\text{observed}} = -e \int d^3x \, \psi^\dagger \psi$$  

So, it doesn't matter what constant you put in front; the crucial point from field theory is that this quantity  $Q$  is conserved. Scaling it by a factor (like  $-e$ ) to match experiment is our choice.

::: callout-note
This discussion focuses on **electric charge in QED**, arising from a **U(1) symmetry**. A similar logic applies to **color charge in QCD**, but it originates from a more complex **SU(3) gauge symmetry**. The conserved currents in QCD involve color indices and matrices (like the Gell-Mann matrices  $T^a$ ), leading to eight conserved color charges.
:::


## Currents and Charges in QED and QCD

The electromagnetic current in QED is often denoted as  $J^\mu$  or  $j^\mu$ , where:
  $$j^\mu = -e \, \bar{\psi} \gamma^\mu \psi$$  
This is the **conserved Noether current** associated with the  $U(1)$  gauge symmetry of QED. 




![This figure represents the process of probing (measuring or interacting with) electric charge using a photon. In the context of the lecture, this illustrates how, in Quantum Electrodynamics (QED), a photon couples to a charged particle (such as an electron) via an interaction vertex, allowing experimental or theoretical access to the particle's electric charge. The wavy line corresponds to the photon, and the adjoining straight line represents the charged particle (like an electron or quark). This is a fundamental concept because the photon is the mediator of electromagnetic interactions, and its coupling directly measures the conserved electric charge associated with the U(1) symmetry of QED, as discussed when introducing conserved currents and Noether's theorem.](2024-Lecture-02-images/fig1.png){#fig-fg1}




 The factor  $-e$  is a convention to match our common definition of electric charge (electrons have negative charge). We could have defined electrons as positively charged, but that is not our standard convention.So, how do we define the analogous charge in Quantum Chromodynamics (QCD)? We follow a similar logic. In QED, a photon couples to a fermion via a vertex with  $\gamma^\mu$ , probing its electric charge through the current. (see @fig-fg1) For QCD, we want a vertex that probes **color charge**.

::: callout-note
The **color current** in QCD is the conserved non-Abelian current associated with the  $SU(3)$  gauge symmetry. It couples to the gluon fields and describes the flow of color charge, which has eight components corresponding to the eight gluons:
  $$j^{\mu,\,a} = g_s \, \bar{\psi}_i \gamma^\mu (T^a)_{ij} \psi_j$$  
Here,  $g_s$  is the strong coupling constant,  $\psi_i$  is the Dirac spinor field for a quark with a color index  $i = 1,2,3$  (representing red, green, blue), and  $(T^a)_{ij}$  are the Gell-Mann matrices (the generators of  $SU(3)$ ) with  $a = 1, \dots, 8$ .
:::
The construction is very similar:

* The quarks are still fermions, so we use the Dirac spinor  $\psi$ , but now it carries a **color index**.
* At the vertex, we still have a  $\gamma^\mu$ , but we must also include a **Gell-Mann matrix**  $T^A$  to account for the non-Abelian  $SU(3)$  structure.

Therefore, the QCD vertex factor becomes  $\gamma^\mu T^A$ . Given a specific quark field  $\psi$ , we can insert it into the current  $j^{\mu,\,a}$  to compute its **color charge**.

A key result is that the color charge of a quark is not a single number like "red," "green," or "blue." Instead, for a given quark state, you compute a **vector of eight numbers**, one for each gluon type (each generator  $T^a$ ).

*   **How many color charges does QCD have?** **Eight**, corresponding to the index  $a$  on the current  $j^{\mu,\,a}$ .

For example, consider a quark with a specific color state in the fundamental representation:
  $$\psi_{\text{color}} = \begin{pmatrix} 1 \\ 2 \\ i\sqrt{3} \end{pmatrix}$$  
To find its color charge, you compute the eight numbers given by the expectation value of the **color charge operator**  $Q^a_{\text{QCD}} = g_s \int d^3x \, \psi_i^\dagger \gamma^0 (T^a)_{ij} \psi_j$  for this state. Depending on which gluon (labeled by index  $a$ ) you use to probe the quark, you will get a different component of this charge vector. All eight components are computed using the same fundamental equation for the color current.



## SU(2) Group: Representations, Generators, and Physical Charges

So then this comes from group theory. Here we deal with U(1), U(2), SU(2), and SU(3). Today we will be discussing **SU(2)**. We are finishing here with a recap and moving to the discussion of today's SU(2) group.

The **SU(2) group** is a super important symmetry in particle physics. First, it's a group. Let's start by discussing a few words on what a group is.

A group is defined by a set of elements with a composition rule. For any element  $G$  in the group, there exists an inverse  $G^{-1}$  that is also in the group. For any two elements  $G_1$  and  $G_2$ , their composition  $G_1 \circ G_2$  also belongs to the group. Finally, there is an identity element.

SU(2) is a **special unitary** group. It is the group of  $2 \times 2$  unitary matrices with determinant one. An element  $U \in SU(2)$  satisfies:
  $$U^\dagger U = U U^\dagger = I, \quad \det(U) = 1$$  
The letter **S** stands for "special," meaning the determinant is exactly one.

::: callout-note
This is the **fundamental representation** of SU(2). A representation is a way of realizing the group's elements as matrices acting on a vector space. The fundamental representation acts on a 2-dimensional (complex) vector space.
:::
We could imagine listing all matrices in the group, but it's not possible because the group is continuous and infinite. However, if we could list them, we would know how they compose—multiplying two group elements gives another group element. To construct other representations, we find a correspondence where each group element is mapped to a matrix in a different dimension (e.g.,  $3 \times 3$  or  $4 \times 4$ ) while preserving the group multiplication rules. SU(2) is a nice group because it has a straightforward way of constructing representations of any dimension.

Another key concept from group theory is the **Lie algebra**. All group elements near the identity can be generated from the algebra. For SU(2), the generators are the **Pauli matrices**,  $\sigma_1, \sigma_2, \sigma_3$ . Any group element can be written in exponential form:
  $$U = \exp\left(i \sum_{i=1}^{3} \theta_i \sigma_i\right)$$  
where  $\theta_i$  are real parameters.

The matrix exponential is defined via its Taylor expansion:
  $$\exp(M) = I + M + \frac{M^2}{2!} + \frac{M^3}{3!} + \cdots$$  
For certain matrices where  $M^2 = 0$ , the series terminates at  $I + M$ . In general, you compute it by summing the series.

The generators obey the defining **commutation relations** of the  $\mathfrak{su}(2)$  algebra:
  $$[\sigma_i, \sigma_j] = 2i \epsilon_{ijk} \sigma_k$$  
These relations hold for the generators in any representation of SU(2). For the fundamental representation, the Pauli matrices satisfy this exactly.

This group is important in two major physical applications:

1.  **Spin**: Spin is a quantity that arises from the SU(2) symmetry related to rotations in space. For a three-vector, rotations are given by  $3 \times 3$  rotation matrices. For a spinor (like an electron's wavefunction), rotations are represented by the Pauli matrices.
2.  **Flavor Symmetry**: We can apply SU(2) to quark flavor, specifically mixing up and down quarks. Continuous transformations between up and down quark states are characterized similarly to rotating a spinor, but in flavor space.

The first application (spin) you've likely seen in quantum mechanics. Before moving on, let's connect these groups to a physical concept: **charge**.

*   In QED (U(1) symmetry), the conserved charge is **electric charge**.
*   In QCD (SU(3) symmetry), the conserved charge is **color charge**.

What is the charge for our SU(2) symmetries? We can compute it using Noether's theorem. For a symmetry with generators  $T^a$ , the conserved charge is:
  $$Q^a = \int d^3x \, \psi^\dagger T^a \psi$$  

*   **For the rotation (spin) group**: We replace  $T^a$  with the Pauli matrices. The resulting charges  $S_1, S_2, S_3$  correspond to the **projections of the spin** along the x, y, and z axes. They are related to the particle's **helicity**, which is the projection of spin along the direction of motion:  $h = \frac{\mathbf{S} \cdot \mathbf{p}}{|\mathbf{p}|}$ .
*   **For the flavor group**: We again use Pauli matrices, but now the wavefunction  $\psi$  describes quark flavor (up and down). The resulting conserved charge is a new quantity called **isospin**.

In summary, the SU(2) algebra, with its commutation relations  $[\sigma_i, \sigma_j] = 2i \epsilon_{ijk} \sigma_k$ , underlies the physics of both **spin** and **isospin**.



## SU(2) Representations and the Construction of Generators

I am given the commutation relation  $[J_i, J_j] = i \varepsilon_{ijk} J_k$ . This defines the Lie algebra of the **SU(2)** group, where  $\varepsilon_{ijk}$  is the Levi-Civita symbol.

Let me write it more quickly. Essentially, this means the generators  $J_1$ ,  $J_2$ , and  $J_3$  satisfy three fundamental relations. From this algebra, you get the three generators.

So  $\sigma_3$  is the one that will give you the Pauli matrices as well. Just to remind you, the Pauli matrices in the fundamental ( $j=1/2$ ) representation are:
  $$\sigma_1 = \begin{pmatrix} 0 & 1 \\ 1 & 0 \end{pmatrix}, \quad
\sigma_2 = \begin{pmatrix} 0 & -i \\ i & 0 \end{pmatrix}, \quad
\sigma_3 = \begin{pmatrix} 1 & 0 \\ 0 & -1 \end{pmatrix}.$$  
Fortunately, there is no different convention for these; we all use the same.

It's extremely important to ask: how many of the generators of the group have a diagonal form? This is a fundamental group theory question. All generators must be **traceless** because the condition for a matrix to have determinant one implies a relation between the determinant and the trace. Essentially, for these group elements, the determinant is equal to the exponential of the trace.

But it's important to know how many are diagonal, because this tells you what the eigenvalues and eigenvectors are that you are going to deal with. For **SU(2)**, there is just one matrix that is diagonal in the standard basis. That's why the group is called **rank one**. If you go to a group theory class, you will see fascinating classifications of all possible groups that heavily rely on the **rank** of the group. For SU(2) the rank is equal to 1.

This diagonal matrix will be used to construct and determine physical quantities from the states.

We are now going to act with these matrices on the states. We will use the ket notation  $|J M\rangle$  for the states, which implies a unit vector with only one non-zero component at the position corresponding to  $M$ .

We will use a lot of this notation. The label  $J$  gives you the dimension of the representation. We will discuss the spin applications of this group first, where  $J$  determines the dimension in the sense that every component corresponds to a certain possible value of the projection of the spin. There are  $2J + 1$  possible projections.

The physical picture is that we have a spin vector  $\mathbf{J}$  and a quantization axis. Along this axis, there are several possible projections:  $-J, -J+1, ..., +J$ . The number of them is  $2J+1$ .

*    $J = 1/2$  corresponds to the two-dimensional representation. That's fundamental. The basis states are  $|1/2, 1/2\rangle$  and  $|1/2, -1/2\rangle$ .
*   Those Pauli matrices (divided by 2) are the generators for this fundamental representation, where the matrix acts on the vector space spanned by these two states.
*   Any other state, like  $|3/2, -1/2\rangle$ , lives in a larger vector space. This is just notation for the vector space. We construct any group element acting on that space using our generators.
Okay, let's look quickly at the lowering and raising operators. We define:
  $$J_+ = J_1 + i J_2, \quad J_- = J_1 - i J_2.$$  
These are the **raising and lowering operators**. 




![This figure represents the mathematical expression for the construction of ladder operators, which are essential tools in the spin algebra of the SU(2) group discussed in the lecture. Specifically, it shows the definition of the raising and lowering operators: \[ J_+ = J_1 + i J_2 \] and \[ J_- = J_1 - i J_2 \] These operators act on quantum states labeled by total spin  $J$  and projection  $M$ , raising or lowering the value of  $M$  by one unit. They are fundamental for building the algebraic structure of angular momentum in quantum mechanics and are directly related to the manipulation of spin and isospin quantum numbers, as well as understanding how multiplets (like baryons and mesons) are constructed and how their quantum numbers combine. The ability to use these operators enables the calculation of Clebsch-Gordan coefficients and the systematic construction of higher spin and isospin representations, which are recurring themes of the lecture.](2024-Lecture-02-images/fig2.png){#fig-fg2}




 Their action on a state will lower or increase the projection quantum number  $M$ . 




![This diagram represents the action of the SU(2) spin algebra operators on angular momentum eigenstates labeled by the quantum number  $M$  (the projection of total angular momentum or isospin along the quantization axis). Along the horizontal axis, different  $M$  states are shown as points.  -  $J_3$  is the operator corresponding to the projection of the angular momentum; it leaves the state unchanged except for multiplying by  $M$ . - The upward arrow labeled  $J_+$  indicates the **raising operator**, which acts on a state  $|J, M\rangle$  to increase  $M$  by one unit ( $J_+ |J, M\rangle \propto |J, M+1\rangle$ ). - The downward arrow labeled  $J_-$  indicates the **lowering operator**, which decreases  $M$  by one unit ( $J_- |J, M\rangle \propto |J, M-1\rangle$ ).  This figure demonstrates the ladder structure of spin or isospin multiplets as dictated by the SU(2) Lie algebra: raising and lowering operators connect the different states within the same multiplet, illustrating how the total space of representations is constructed. This is crucial for understanding how quantum numbers change under these operators—an essential part of both spin and isospin algebra in particle physics.](2024-Lecture-02-images/fig4.png){#fig-fg4}




 The  $J_+$  operator acting on a lower state will move the vector to the upper one.

To demonstrate their properties, consider the product:
  $$J_+ J_- = (J_1 + i J_2)(J_1 - i J_2) = J_1^2 + J_2^2 - i[J_1, J_2].$$  
Using the commutation relation  $[J_1, J_2] = i J_3$ , this becomes:
  $$J_+ J_- = J_1^2 + J_2^2 + J_3 = \mathbf{J}^2 - J_3^2 + J_3.$$  

::: callout-important
The action of the operators on an eigenstate  $|J M\rangle$  is defined by:
  $$J_3 |J M\rangle = M |J M\rangle, \quad \mathbf{J}^2 |J M\rangle = J(J+1) |J M\rangle.$$  
These operators commute with each other and, in quantum mechanics, with a rotationally invariant Hamiltonian, making them conserved quantities.
:::
Therefore,  $J_+ J_-$  acting on  $|J M\rangle$  gives  $[J(J+1) - M(M-1)] |J M\rangle$ . From this, we find the action of the ladder operators themselves:

  $$J_+ |J M\rangle = \sqrt{J(J+1) - M(M+1)} \, |J, M+1\rangle,$$  
 $$J_- |J M\rangle = \sqrt{J(J+1) - M(M-1)} \, |J, M-1\rangle.$$  

The square root factors ensure the states remain normalized. This structure is very closely related to what we will see later with **Clebsch-Gordan coefficients**.

So, let's give the method to construct an arbitrary representation. Imagine you want an analog of the Pauli matrices for, say, a four-dimensional representation.

First, construct  $J_+$ . For a dimension  $d=4$  representation, the corresponding spin is  $j$ , where  $2j+1 = 4$ , so  $j = 3/2$ . The operator  $J_+$  acts on a state and moves the projection up by one. Therefore, its matrix will have non-zero elements only on the first off-diagonal. For example, one element would be  $J_+ |3/2, 1/2\rangle = \sqrt{3} |3/2, 3/2\rangle$ .

It's often easier to construct  $J_-$  first. For instance:
  $$J_- |3/2, 1/2\rangle = \sqrt{3} \, |3/2, -1/2\rangle.$$  
This tells you one specific matrix element. You fill the  $J_-$  matrix with the appropriate square-root factors on the first sub-diagonal, and then  $J_+$  is its Hermitian conjugate.

Once you have  $J_+$  and  $J_-$ , you recover the original generators:
  $$J_1 = \frac{J_+ + J_-}{2}, \quad J_2 = \frac{J_+ - J_-}{2i},$$  
and  $J_3$  is the diagonal matrix with eigenvalues  $m = -j, -j+1, ..., j$  on the diagonal.

::: callout-note
**General Algorithm**: For a representation of dimension  $d = 2j+1$ , the diagonal entries of  $J_3$  are  $m$  from  $-j$  to  $j$  in integer steps. Use the formula  $J_\pm |j, m\rangle = \sqrt{j(j+1) - m(m \pm 1)} \, |j, m \pm 1\rangle$  to populate the  $J_+$  and  $J_-$  matrices, then construct  $J_1$  and  $J_2$ .
:::
Now the fun part: to get finite rotations, you exponentiate these generators. A general **SU(2)** group element is given by:
  $$U(\boldsymbol{\alpha}) = \exp(-i \boldsymbol{\alpha} \cdot \mathbf{J}).$$  
You don't do this manually for large representations; you use a computer. What we have discussed so far is how to construct an arbitrary matrix representation of the **SU(2)** group.



## The Ξ Baryons and Isospin Symmetry

The **Ξ baryons** (the Greek letter *xi*) are found in the Review of Particle Physics (PDG). Their quark content consists of two strange quarks and one light quark (either up or down).

* The charged state is the **Ξ⁻**, with quark content  $(s s d)$ .
* The neutral state is the **Ξ⁰**, with quark content  $(s s u)$ .

If you look at the PDG, these two particles have very similar properties—their masses are very close, and they are essentially the same particle, just with different electric charge.

Another example is the **Ξ_c baryons**.

* The upper one in the isospin doublet is the **Ξ_c⁺**, with quark content  $(c s u)$ .
* The lower one is the **Ξ_c⁰**, with quark content  $(c s d)$ .

These are all well-known, discovered particles. They have very similar masses and very similar lifetimes; essentially, they look like the same particle.

The third member of this family is the **Ξ_cc baryon**, a doubly-charmed state.

* The upper state would be the **Ξ_cc^{++}**, with quark content  $(c c u)$ .
* The lower state is the **Ξ_cc^{+}**, with quark content  $(c c d)$ .

The **Ξ_cc^{++} $** has been discovered. However, the **Ξ_cc^{+}$ ** is frequently discussed at conferences. One experiment reported a signal-like bump, but another experiment, LHCb, did not find it at the expected mass. Moreover, LHCb found a candidate for the **Ξ_cc^{+} $** with a mass that was in conflict—about **40 MeV different** from the mass of the state seen previously.

::: callout-important
Why is this discrepancy scandalous? Because, so far, whenever you replace an up quark with a down quark (or vice versa), the particle's mass **almost does not change** and its properties remain the same. This is due to **strong isospin symmetry**, which arises because the strong interaction is essentially blind to the difference between up and down quarks, given their very similar masses:$ m_u \approx m_d \approx 3 \text{ MeV} $.
For the$ \Xi_{cc} $states, it would be impossible for them to have significantly different masses under this symmetry. They **must** have nearly identical properties.
:::
If you were to do a PhD on data analysis and discover the **Ξ_cc^{+}$ **, you would become a superstar in particle physics. There have been several PhD projects dedicated to searching for it. The search often involves a **blind analysis**: researchers define the reactions and a mass window to study, but they do not look at the data in that window until all selection criteria and procedures are optimized and fixed. Only then do they "unblind" the mass range.

Four PhD students completed this rigorous process, pressed the button to unblind their data, and unfortunately found nothing there. The challenge is likely in picking the right decay channel. The **Ξ_cc^{+} $** decays through many modes, and current statistics may be insufficient to see it in some of the rarer ones. The right decay mode probably exists—we just haven't found it yet.



## Symmetry, Isospin, and Combining Representations

### Symmetry of QCD

When we speak about the symmetries of the Lagrangian of QCD, we have in mind the Lagrangian itself. It has a term for the gluons and a term for the quarks. This term for the quarks—the Dirac term—contains a mass parameter. If the quark masses are not the same, this mass term will break the flavor symmetry.

For the **u** and **d** quarks, since they have almost the same masses, this symmetry is **not broken** by the mass terms, and it remains a good symmetry. In contrast, the mass of the strange quark is about **100 MeV**. Therefore, the symmetry between the **u**, **d**, and **s** quarks—the **SU(3) flavor** symmetry—is only **approximate**.

### Isospin SU(2) Symmetry

Let's focus on the **u** and **d** quarks. Their near-equal mass means rotations in this two-dimensional flavor space are a good symmetry. This is the **SU(2) isospin** symmetry.

The transformation under this SU(2) group for a doublet like$ (u, d) $is given by:
 $$U(\boldsymbol{\alpha}) = e^{-i \boldsymbol{\alpha} \cdot \boldsymbol{\tau} / 2}$$  
where  $\boldsymbol{\alpha}$  are the rotation parameters and  $\boldsymbol{\tau}$  are the Pauli matrices. This is mathematically identical to how we describe spin rotations in quantum mechanics.

::: callout-note
The particle historically named **cascade** is denoted by the Greek letter **Ξ (Xi)**. Because its decay chain resembled a cascade of particles, and the Greek name can be challenging to pronounce, it's commonly just called "cascade" in particle physics.
:::
In this framework, treating the **u** and **d** quarks as an isospin doublet (like spin-1/2), a particle like the cascade (**Ξ**) can be assigned an **isospin wave function**.

*   The dimension of the representation tells us the isospin quantum number. For a representation of dimension  $d$ , the isospin  $I$  is given by  $d = 2I + 1$ .
*   A **doublet** ( $d=2$ ) corresponds to isospin  $I = 1/2$ .
*   A **quartet** ( $d=4$ ) corresponds to isospin  $I = 3/2$ .

### Combining Representations: Higher Multiplets

A natural question arises: if we only have two quarks (**u** and **d**) in an  $I=1/2$  doublet, how do we get particles with higher isospin, like  $I=1$  or  $I=3/2$ ?

The answer is by **combining quarks**. When we build composite particles (like baryons and mesons) from multiple quarks, we must combine their individual isospins (and spins) to find the **total isospin** of the composite system. The rules for combining isospin are identical to the rules for combining angular momentum (spin).

**Angular Momentum Addition Rule:**
When combining two systems with spins  $j_1$  and  $j_2$ , the total spin  $j$  can take values:
  $$j = |j_1 - j_2|, \, |j_1 - j_2| + 1, \, \dots, \, j_1 + j_2$$  
This is written as  $j_1 \otimes j_2 = |j_1-j_2| \oplus \cdots \oplus (j_1+j_2)$ .

**Key Examples:**

*   Combining two spin-1/2 particles (e.g., two quarks in an isospin doublet):
  $$\frac{1}{2} \otimes \frac{1}{2} = 1 \oplus 0$$  
This yields a **triplet** ( $I=1$ , dimension 3) and a **singlet** ( $I=0$ , dimension 1).

*   Combining spin-3 and spin-2:
  $$3 \otimes 2 = 1 \oplus 2 \oplus 3 \oplus 4 \oplus 5$$  

A powerful consistency check is that the total dimension must be conserved:
  $$\text{Dim}(j_1) \times \text{Dim}(j_2) = \sum_{j=|j_1-j_2|}^{j_1+j_2} \text{Dim}(j)$$  
For example, with  $j_1=3$  (dimension 7) and  $j_2=2$  (dimension 5):  $7 \times 5 = 35$ , and  $1+3+5+7+9+11 = 35$ .

::: callout-important
Group theory tells us that when we combine representations, the resulting higher-dimensional space breaks into **blocks that do not mix** under symmetry transformations (rotations in isospin or spin space). Each block corresponds to a distinct total spin/isospin value. This is why, for instance, a system with total spin 3 can never rotate into a state with total spin 4.
### Practical Application & Final Notes
:::



![This figure illustrates the concept of angular momentum projection in quantum mechanics, specifically in the context of SU(2) symmetry, as used for both spin and isospin in particle physics. The arrow labeled "spin" represents the angular momentum vector  $\vec{J}$  (or "spin"), while the slanted line labeled "projection axis" represents the quantization axis—customarily chosen as the  $z$ -axis for calculations. The diagram emphasizes how, for a system with total angular momentum  $J$ , only certain discrete projections  $M$  along the chosen axis are allowed ( $M = -J, -J+1, ..., J$ ). This is a direct visualization of the concept behind the eigenstates  $|J\, M\rangle$ , with  $M$  being the quantum number corresponding to the component of  $\vec{J}$  along the projection axis. This foundational idea underlies much of the spin algebra, angular momentum addition, and isospin formalism discussed throughout the lecture.](2024-Lecture-02-images/fig3.png){#fig-fg3}






Before moving to practical combinations, let's briefly introduce the concepts of **parity** and **charge conjugation**.

**Crucial Distinction:** It is vital not to mix up **isospin** and **spin**.

*   We use **isospin SU(2)** when constructing the **flavor wave function** of quarks inside a hadron.
*   We use the **rotational SU(2)** (from the Lorentz group) when combining the intrinsic **spin** of particles to understand angular momentum and related dependencies.

The mathematical algebra and combination rules are identical for both; the only difference is the physical context in which they are applied.



## Parity, Charge Conjugation, and Excitations of the Λc Baryon

So parity and charge conjugation quickly number 3, 4, 5. The parity operator is doing inversion. Both parity and charge conjugation are operators that act on a state and produce another state.

The parity operator  $\hat{P}$  is space inversion with respect to the origin. Charge conjugation  $\hat{C}$  is the operator flipping all charges, turning a particle into its antiparticle.

Answer the question: how do wave functions of the particle change when you flip the wave functions through the origin? It's rather intuitive. You have a vector, you flip through the origin all of the spatial components, and you get the vector pointing in the opposite direction.

For any particle you can find out what its parity is. The parity acting on the state gives the eigenvalue. Since you act twice and get the same state—you do flip twice you get the initial configuration—the eigenvalue of this operator is modulus 1. By convention we say it's real and then we say it's plus or minus one, either  $+1$  or  $-1$ :  $\hat{P} | \psi \rangle = \pm | \psi \rangle$ .

Connecting to the charge conjugation operator, acting on this state you get the same state if the particle or the wave function that you consider here is neutral, and for the charged one you get a different one. That's what prime here stands for.

For any particle you can look up what its charge conjugation is, but not for every particle you find it. For every particle you can find parity. Let me give you the convention. Essentially, if the particle is the neutral one in the multiplet, the charge conjugation is the one that's C is a member of the multiplet.

So the charge conjugation  $C$  of  $\pi^+$  or  $\pi^0$  is equal to—the Particle Data Group is the book that has a lot of information on all particles—would tell you these quantum numbers. For any particle you find the  $J^{PC}$ , which is the spin, total spin of the particle, parity, and charge conjugation.

Think for all of them, for baryons, for the charged ones, for the neutral ones, you'll find that  $J^{PC}$  is—spin is equal to 0, minus, plus 1—and for the  $\pi^+$ ,  $\pi^-$  you also find that charge conjugation is positive, but it's not an eigenstate of the charge because acting with charge conjugation on  $\pi^+$  you get  $\pi^-$ . Still we assign the charge conjugation. It's convenient for many applications according to the charge conjugation of the neutral particle multiplet.

In order to find what are the charge conjugation, parity, and the spin, total spin for the combination of particles, you do the following:

1.  First you find the total  $J$  by doing the spin algebra.
2.  Second, parity is multiplicative.
3.  Third, charge conjugation is multiplicative.

For  $L$  equals one,  $(-1)^L$  is the orbital angular momentum contribution to the parity that one has to add. The total parity for a composite system is  $P_{\text{total}} = P_1 P_2 (-1)^L$ .

::: callout-important
**Key Formulas for Composite Systems**

*   **Total Parity:**  $P_{\text{total}} = P_1 P_2 (-1)^L$ , where  $P_1$  and  $P_2$  are the intrinsic parities of the constituent particles and  $L$  is their orbital angular momentum.
*   **Total Angular Momentum:**  $\mathbf{J} = \mathbf{L} + \mathbf{S}_1 + \mathbf{S}_2$ , obtained via vector addition of spins and orbital angular momentum.
*   **Charge Conjugation for Neutral Mesons:**  $C = (-1)^{L+S}$ , where  $S$  is the total spin of the quark-antiquark pair.
:::
I would like to give an example before you stop because it's one of the most important skills I would like you to have: to be able to determine what are possible combinations of the spin and parity when you combine two particles. I'm going to draw the table that would list  $J^{PC}$ ,  $J^P$ .

For the uncharged fermions, there is no charge conjugation, so I won't have charge conjugation here. So  $J^P$ , for the combination of particles I start following out with the orbital angular momentum equals zero. I just combine spin and charge. In that case I have  $1/2$ , I add a 0, I get only  $1/2$ . The charge is multiplicative. Parity is multiplicative.

I go to the first row adding 1 unit of angular momentum  $L = 1$ . Then I go to the second row by adding 2 and the parity follows from the rule of  $(-1)^L$ . 




![This figure schematically represents the excitation spectrum of a quantum system—such as the hydrogen atom or a hadron—organized by total angular momentum quantum number  $J$  and energy  $E$ . The horizontal axis shows  $J$ , the total angular momentum, while the vertical axis represents energy levels  $E$ .  Each box indicates a particular quantum state characterized by its principal and orbital quantum numbers (such as  $1S, 2S, 1P, 1D$ ) along with superscripts labeling the total spin/parity combinations (e.g.,  $1/2^+$ ,  $1^+$ ,  $3/2^-$ ,  $5/2^+$ ).   The figure illustrates how states with different total angular momentum (arising from combinations of orbital angular momentum  $L$ , spin  $S$ , and their Clebsch-Gordan addition) appear at distinct energy levels. For instance, the 1S state ( $J=1/2^+$ ) lies at the lowest energy, the 2S state ( $J=1/2^+$ ) at a higher energy, and the 1P multiplet splits into  $J=1/2^-$  and  $J=3/2^-$ , with the 1D state further splitting into  $J=3/2^+$  and  $J=5/2^+$ .  Physically, this diagram encodes the **spin algebra** and **angular momentum addition rules** discussed in the lecture. The vertical structure reflects how energy depends on the excitation (principal quantum number and angular momentum), and the splitting along the  $J$ -axis exemplifies how spin and orbital angular momentum combine according to SU(2) symmetry and group theoretical rules. This is crucial for understanding the spectrum of composite systems (like hadrons or atoms) and for deducing possible quantum numbers for excited states in experimental spectroscopy.](2024-Lecture-02-images/fig5.png){#fig-fg5}




 I start with 0, I run the angular momentum, it will be minus, minus, plus. That's pretty much the excitation spectrum for Lambda baryons.
I look at the Lambda baryon in the quark model. In the quark model means that now I consider my heavy quarks. There are no gluons any longer; they all condensate. Then quarks are heavy. Among these quarks there is a charm quark that's heavy and it's not part of our symmetry. There is  $u$  and  $d$  from the flavor consideration of the group can be in isospin 1, or it could be in isospin 0. That's how we combine the isospin. This is a flavor part of the group.

There is a symmetry that holds for baryons. Since they are the same particle,  $u$  and  $d$ , as we agreed, they have to be in symmetric combination. If they are in isospin zero, they are entered antisymmetrically. So isospin zero is minus sign here. That's why the spin combination must from the spin. They also have to be in the spin zero to have overall antisymmetry.

I'm mixing up overall wave function for the baryon. Since the fermions have to be antisymmetrical, there is a color wave function that we might discuss at one point; it gives a minus sign. There is the spin wave functions. As we found out for the eta and for the... So S wave is symmetric. I'm missing a minus sign somewhere. This is the right answer. I'm missing a minus sign somewhere.

The isospin wave function is there. Then spin wave functions would be good corresponds to that spin, spin zero of the  $u$  and  $d$ . And that's what.

Now we can consider how this baryon is excited. We discussed already that one way of making different particles out of this guy is to interchange U and D. But since the  $\Lambda_c$  is isospin zero, there are no other particles in this multiplet. It's only one  $\Lambda_c$ .

The other way to make different particles out of the  $\Lambda_c$  is to excite the system. You can excite it radially, like the hydrogen atom, to make the object bigger. You probably remember the hydrogen atom. There is an  $n$  quantum number, the principal quantum number that tells you how big the system is. Essentially, what are the orbitals of the electron. You can do the same for  $\Lambda_c$ . You can have 1s, 2s, and so on.

This one will be the ground state  $\Lambda_c$ . This next one will be an excited, bigger  $\Lambda_c$ . You would call it  $\Lambda_c^{**}$ . I think we found this one. It's pretty broad.

You can excite the system orbitally, putting orbital angular momentum between, let's say, the  $ud$  pair and the heavy center of this sigma. That would correspond to the orbital excitations. Then it gives these one P  $\Lambda_c$  states. We have found what the quantum numbers of these are.

Looking at this, this would be the ground state of  $\Lambda_c$ . These two are orbital excitations. It's important to realize that when we do excitation of the system, we obtain different particles.

If you look at the PDG, you will see the names that we know of. We have discovered in experiments around seven different  $\Lambda_c$ 's. So the ground one, these two guys, these two guys, and this one, I think six. Then there is one high-end spectrum that we don't know which multiplet it belongs to. These are, although listed as different particles, sort of excitations of the ground state  $\Lambda_c$ .



## Spin Algebra and Decay Partial Waves

**Super important.** Learn how to construct this table—essentially, how to do **spin algebra**.

### Constructing the S Wave and Angular Momentum Addition

We start by constructing the **S wave**, where the orbital angular momentum  $L = 0$ . Using **Clebsch-Gordan coefficients** is straightforward here. Adding one unit of angular momentum is also straightforward, but you must be careful not to mix up the procedure.

::: callout-important
When combining two systems with angular momenta  $j_1$  and  $j_2$ , the total angular momentum  $j$  can take values:
  $$j = |j_1 - j_2|, |j_1 - j_2| + 1, \dots, j_1 + j_2$$  
This is the **Clebsch-Gordan series**, fundamental for constructing spin wavefunctions and determining allowed states.
:::
If you are already in an orbital angular momentum zero combination—and there are only a few of them—you must consider them separately. One combination spans several states, and another will span several different states.

The same procedure applies when you want to **combine angular momenta** in a decay.

### Applying This to a Particle Decay

Consider the decay of a particle  $A$ :
  $$A \to B + C$$  
We know the quantum numbers:

* Particle  $A$  is  $0^+$ 
* Particle  $B$  is a vector,  $1^-$ 
* Particle  $C$  is  $2^-$ 

We can ask: **What is the orbital angular momentum  $L$  in this decay?** The decay is analyzed in the **rest frame of particle  $A$ **. Particle  $B$  goes in one direction, particle  $C$  goes in the opposite direction, defining a relative angle.

::: callout-note
In a decay  $A \to B + C$ , **parity is conserved**:
  $$P_A = P_B \, P_C \, (-1)^L$$  
where  $(-1)^L$  is the parity of the orbital state.
:::
If you combine the two final-state particles in an **S wave** ( $L = 0$ ), the possible total spin-parity  $J^P$  is only  $1^-$ .
In a **P wave** ( $L = 1$ ), the parity would be positive.
To reach the  $2^-$  state, you need a **D wave** ( $L = 2$ ).

Therefore, the **partial wave** for this decay is a **D wave**. I hope we get to practice this calculation—it’s very important.

### A Practice Problem: Hydrogen Atom in a Magnetic Field

Let’s work on a problem. We have a hydrogen atom placed in a **strong magnetic field**. The task is to determine the excitation spectrum.

Consider the following energy levels:
 $1s$ ,  $2s$ ,  $2p$ ,  $3s$ ,  $3p$ ,  $3d$ .

::: callout-tip
In the hydrogen atom, the orbital angular momentum quantum number  $l$  is restricted by the principal quantum number  $n$ :
  $$l < n$$  
This is why, for  $n=3$ , we have  $l = 0$  (s),  $1$  (p), and  $2$  (d), but **no f-wave** ( $l=3$ ).
:::
We will restrict ourselves to **s, p, and d waves only**, excluding the f-wave. This is a beautiful puzzle—you may have seen it before. It’s the same problem.

::: callout-important
In a **strong magnetic field** (Paschen-Back regime), the energy shift for a state with quantum numbers  $n, l, m_l, m_s$  is approximately:
  $$\Delta E = \mu_B B \, (m_l + 2m_s)$$  
where  $\mu_B$  is the Bohr magneton,  $B$  is the field strength,  $m_l$  is the orbital magnetic quantum number, and  $m_s = \pm 1/2$  is the spin projection.
:::
The skill of constructing and using the spin-algebra table is something we want to practice more. I think we’re done, except for this problem.

