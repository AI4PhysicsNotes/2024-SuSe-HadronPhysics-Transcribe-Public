---
title: (2024) Lecture 3
author: ''
presenter: Mikhail Mikhasenko
note_taker: Ilya Segal
date: '2024'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



## Lecture Recording and Isospin Review

So my experiment with recording lectures has been relatively successful, so I could recover what I was saying. There is an open large language model from OpenAI that can translate audio to text called Whisper. Since the architecture is known, there is a C implementation that even runs parallel on Mac. You just download and execute it, and then you have a transcript of your speech.


::: callout-note
I record the lecture for myself, but it might be converted to a document. If someone would volunteer to type the questions and the equations there and check them, that would be helpful. But I don't know what to do with that. Just for fun and for exploring the technologies, I will keep the recordings. It records only me in the sense that it's mostly me who speaks, so don't hesitate to talk back because this will not appear in the recordings anyway.
:::

We will talk today about **structure functions**, the structure of hadrons, their internal composition, and how we know about them. But before going there I would like to start with a recap and have a few questions.

**Question 1:** Without looking at the PDG, just from the quark content, tell me the isospin of these particles. The quark content here is:  $c \bar{s}$ ,  $b \bar{q}$ ,  $b \bar{s}$ ,  $q \bar{q}$ .

**Question 2:** What is the dimensionality of the isospin matrix that acts in a space of three quarks? If I treat the quarks as a wave function in two dimensions where spin up corresponds to the  $u$  quark and spin down corresponds to the  $d$  quark, what is the dimensionality of the matrix that acts in this space?

**Question 3:** What are the irreducible representations of this matrix acting on these quarks? Essentially, how does my matrix from the previous point split into independent blocks that don't talk to each other?

When we talk about isospin we talk about light quarks.

*   The first meson,  $c \bar{s}$ , doesn't have light quarks, so it has isospin  $I = 0$ .
*   The  $B$  meson,  $b \bar{q}$ , has one light quark and therefore we deal with  $I = \frac{1}{2}$ . (Here,  $q$  means a light quark. Often people use notations: capital  $Q$  is a heavy quark, little  $q$  or  $l$  is a light quark.)
*   The  $b \bar{s}$  meson: if you talk about  $SU(3)$ , it belongs to the light quarks. If you talk about isospin,  $s$  is not included. So again, one light quark means isospin is  $\frac{1}{2}$ .
*   Next,  $P_c$ , which is the pentaquark observed in  $J/\psi p$ . If you speak generally about pentaquarks that have three light quarks, what is the isospin? That means it can have the same as the delta group. The three quarks are the same as the delta group. What is the isospin of  $\Delta$ ? It is  $\frac{3}{2}$ . It's the length of the vector, not the projection.

When we assign isospin to a particle, we don't yet speak about the charge. Different charge versions of the particle form a multiplet. When we say the  $B$  meson has isospin  $\frac{1}{2}$ , it implies there are two  $B$  mesons:  $B^+$  ( $b \bar{u}$ ) and  $B^0$  ( $b \bar{d}$ ). For the antiparticle doublet, you fully conjugate:  $\bar{b} u$  is  $B^-$  and  $\bar{b} d$  is  $\bar{B^0}$ .

Now, the cascade  $b$  has isospin  $\frac{1}{2}$ . The dimensionality is  $2I + 1 = 2$ , so there are two particles of this type. The charges:  $u$  quark has charge  $+\frac{2}{3}$ ,  $d$  quark has charge  $-\frac{1}{3}$ . When I combine three of the lower row like  $ddd$ , I get charge  $-1$ . If I combine three of the upper one like  $uuu$ , I get charge  $+2$ . For  $b \bar{s}$ , the combination gives charge zero.

Now we come to the last one which has three quarks, so there are several combinations. For isospin  $\frac{1}{2}$ , the possibilities are  $P_c^+$  and  $P_c^0$ . For isospin  $\frac{3}{2}$ , there are four particles in the multiplet, like for  $\Delta^{++}$ .


::: callout-important
For a particle with isospin  $I$ , the number of charge states is given by:  $\text{Number of states} = 2I + 1$ . This arises from the quantization of isospin in analogy with angular momentum.
:::

An interesting question: what is the antiparticle for the  $P_c^+$ ? For baryons especially, it's important to distinguish baryon to anti-baryon. They have a different quark component. You put a bar under the quarks.

Let's go to the irreducible representation of the three quarks. We already have essentially the dimensionality of the isospin matrix acting on three quarks. How do you get to the  $P_c^+$  and  $P_c^0$  with isospin? We only talk about  $SU(2)$ . For  $SU(2)$  there are no decuplets; decuplets and octets are for  $SU(3)$ .

If you're mixing  $uud$ , you can't get  $I = \frac{3}{2}$  because of the third component. There is the total isospin. The state  $uuu$  has  $I_3 = +\frac{3}{2}$ . We also get  $I_3 = -\frac{3}{2}$ ,  $I_3 = +\frac{1}{2}$ , and  $I_3 = -\frac{1}{2}$ . We also have  $uud$  and  $ddu$ . In order to construct these, we are going to act with a lowering operator on the combination.

We expand. What we would like to do now is ask: what is the quark flavor wave function? To do that we need to construct the basis of the irreducible representations. The easiest way is to start with the state you know for sure, which is the maximum spin. For isospin, this is the  $I = \frac{3}{2}$  state. I can talk about spin or flavor; the notation is equivalent.

I would like to act with the isospin lowering operator  $I_-$ . What comes here is  $\sqrt{j(j+1) - m(m-1)}$ . Since  $j = m$  here, it simplifies to  $\sqrt{2j}$ . So, acting with  $I_-$  on  $|u u u\rangle$  gives a combination. This operator is a sum where these operators act only in the space indicated by the index. So I write  $I_- = I_-^{(1)} + I_-^{(2)} + I_-^{(3)}$ .


::: callout-note
For a state with total angular momentum  $j$  and projection  $m$ , the action of the lowering operator  $J_-$  is:
  $$J_- |j, m\rangle = \sqrt{j(j+1) - m(m-1)} \, |j, m-1\rangle$$  
This is used to construct states with lower isospin or spin projections from the highest-weight state.
:::

To ensure we are dealing with a normalized state  $|\frac{3}{2}, \frac{1}{2}\rangle$ , we calculate the product with itself. You use the fact that  $\langle u|d \rangle = 0$  and  $\langle u|u \rangle = \langle d|d \rangle = 1$ . Same flavor is normalized and different flavors are orthogonal.

We've got that combination and we can follow by acting with more lowering operators. Essentially, that way you find the wave function. It is  $\frac{1}{\sqrt{6}}(2|uud\rangle + 2|udu\rangle + 2|duu\rangle - |uud\rangle' - ...)$ . It's super easy with the highest spin.

Remember we discussed last time the spin of  $\frac{4}{2}$ . That gave us the dimensionality  $2S + 1 = 5$ . Imagine I want to build this from spin  $\frac{1}{2}$  particles. How many spin  $\frac{1}{2}$  particles do I need? Essentially, I have many legs. If I ask you to give me  $S = \frac{3}{2}$ , you use the creation and apply the lowering operator many times. One can automate the process.

It gets trickier when I ask for  $\frac{9}{2}$ . Out of this combination I can have different spins. We agreed that simple spin algebra works. Essentially, when I combine many spin  $\frac{1}{2}$  particles, possible combinations of the total spin have different multiplicities. The dimensionality of the matrix that acts on this space is  $2^n$ , because each spin  $\frac{1}{2}$  gives a two-dimensional representation. This  $2^n$  is written as a tensor product.

We use different notation that comes from  $\frac{1}{2} \otimes \frac{1}{2} \otimes ...$ . Last time we saw this can be decomposed into irreducible representations as different combinations of spins. For a large  $n$ , this is a huge number. But one of these numbers is the spin  $\frac{n}{2}$  plus different spins. Constructing a specific state like  $|\frac{n}{2}, \frac{3}{2}\rangle$  is more difficult.

Let's come back to reasonable numbers. I would like to continue with question number two: the dimensionality of the isospin matrix that acts on the space of three quarks. This is for the isospin group, the same as adding  $\frac{1}{2}$  three times.

Every quark brings a doublet. When we talk about dimensionality, we count the basis vectors in the representation. For every product space, there are two basis vectors. To count how many basis vectors I have in the tensor product, I multiply the number of basis vectors. In the space of three quarks there are  $2^3 = 8$  basis functions. One of them is  $|u d u\rangle$ . Another is  $|u u u\rangle$ , a third is  $|d d u\rangle$ , and so on.

The dimensionality of the isospin matrix that acts on this space is 8, so we have an  $8 \times 8$  matrix. But we can arrange these combinations so they transform under isospin rotations together without talking to other combinations. That's called splitting into irreducible representations by grouping the basis functions into multiplets.

To answer the last question, we do spin algebra:  $\frac{1}{2} \otimes \frac{1}{2} \otimes \frac{1}{2}$ . We combine  $\frac{1}{2}$  and  $\frac{1}{2}$ , which gives  $0 \oplus 1$ . Then we combine this result with another  $\frac{1}{2}$ . We check the dimensionality:  $2 \times 2 \times 2 = 8$ . The decomposition is  $\frac{3}{2} \oplus \frac{1}{2} \oplus \frac{1}{2}$ , with dimensions  $4 + 2 + 2 = 8$ . So our  $8 \times 8$  matrix can be split into blocks of 2, 3, and 4 dimensions.


::: callout-important
The tensor product of three  $I = \frac{1}{2}$  representations decomposes into irreducible representations of  $SU(2)$ :
  $$\frac{1}{2} \otimes \frac{1}{2} \otimes \frac{1}{2} = \frac{3}{2} \oplus \frac{1}{2} \oplus \frac{1}{2}$$  
The dimensions satisfy:  $2 \times 2 \times 2 = 4 + 2 + 2 = 8$ .
:::

It's super clear how to construct the basis for the highest isospin state. You start with  $|u u u\rangle$  and act with lowering operators. But how to construct the others? I'll follow this. The basis for  $I = \frac{3}{2}$  has 4 states. For  $I = \frac{1}{2}$  we're going to have two states. The principle we use is simple: the vectors we build should be totally orthogonal to what we've built already.

Looking at the available quark combinations with  $I_3 = \frac{1}{2}$ , we can construct an orthogonal combination by putting different signs between them. For example, a combination like  $\frac{1}{\sqrt{2}}(|u u d\rangle - |u d u\rangle)$ . You ensure normalization by calculating the scalar product. To construct the basis function for  $I = \frac{1}{2}, I_3 = -\frac{1}{2}$ , take the upper one and act with a lowering operator.

That way you find the wave function is  $\frac{1}{\sqrt{6}}(|u d d\rangle + |d u d\rangle - 2|d d u\rangle)$ . Now that we figured out that out of our eight states, the  $8 \times 8$  matrix acting on them splits into a block of four, a block of two, and another block of two.

I look at my representation. I have two basis vectors and I need to construct the third one that is orthogonal to both. Essentially, if I have vectors  $(1,1,1)$  and  $(1,-1,0)$ , the one orthogonal to both is something like  $(1,1,-2)$ . Therefore, the first one is  $|u d u\rangle - |u u d\rangle$ . The lower one I get by applying the lowering operator. It's typical spin algebra.

With spins we have discussed, it works not only for half-integer spins but also for integer spins. When I combine two spins, I'm dealing with spin 1. Using spin algebra, what I can get ranges from lowest to highest. The lowest would be 0, the highest is 2. I check the dimensionality:  $3 \times 3 = 1 + 3 + 5 = 9$ . I can start constructing the representation basis. I start with the easiest one, which is a vector.

Again, the lowering operator gives four combinations. For total spin  $S = 2$ , the state is symmetric. For  $S = 1$ , I need a vector orthogonal to that. I just put a minus sign. Be careful when you do this for realistic examples or homework; you have to use Clebsch-Gordan coefficients when you lower operators. Clebsch might appear different here and there.

For the basis, Clebsch are the same. It's  $\frac{1}{\sqrt{2}}$  always. These are typical ladder operators. You can check in the  $SU(3)$  chapter. Let's figure out this line. I want to construct two for my  $Y$  and write this as combinations. You can look at the Clebsch-Gordan table and find these coefficients; they appear to be  $\frac{1}{\sqrt{2}}$ .

We are not done with writing the flavor and spin wave functions, but I would consider this. It's just a matter of practicing spin algebra. This comes in many courses: quantum mechanics, particle physics, and group theory. For  $SU(2)$  it's simple spin algebra. You need to think about dimensionalities and how you add spin to each other, and know a few recipes to construct these coefficients.

In order to proceed and talk about structure functions, we need the proton wave function, because that's where the understanding of the internal structure of hadrons comes from. In the homework there will be other questions related to the delta internal structure. It is easier to start with the delta wave function.

We start with the symmetries of the baryon wave function. We have to operate in four spaces: color, space, isospin, and spin. The baryon wave function has color indices and must be color neutral, as all hadrons are. We have a space wave function that describes distribution in  $x$  and  $t$ . We have to operate with isospin and spin.

It is important to realize they are not simply factorizable in the general case. The wave function lives in the product of the four spaces and can mix them. You need a sum of components. The color wave function is a singlet, meaning it's a scalar. Therefore, the color wave function can be factored out. There is a good argument why the space wave function is a scalar and can be factored out as well. I am not convinced myself, but one should find the argument in the literature.

What remains is spin and isospin, and these two do not factorize. That's a large dimensional representation. We deal with baryons with three quarks, and every quark has a spin. Every quark is the product of flavor and spin. It's a product of three quarks, so we deal with a basis in six dimensions. It's the same thing as before.

To build the representation of particles in these six dimensions, we act with the lowering operator. Starting with something we know with no ambiguities: the delta, which has spin  $\frac{3}{2}$ . When Delta has spin  $\frac{3}{2}$ , the only combination is  $|u u u\rangle$ . The  $\Delta^{++}$  with  $J_z = +\frac{3}{2}$ .  $\Delta^+$  with  $J_z = +\frac{1}{2}$  is obtained by acting with a lowering operator in the spin space. If we act with the lowering operator in the flavor space, we reduce the charge and obtain a different particle.

We need to act twice with the lowering operator in flavor space and once in spin space to get  $\Delta^0$  and  $\Delta^-$ . The proton appears to be a wave function that is orthogonal. The decomposition is  $\frac{1}{2} \otimes \frac{1}{2} \otimes \frac{1}{2} = \frac{3}{2} \oplus \frac{1}{2} \oplus \frac{1}{2}$ . This is 4 states plus 2 states plus 2 states. The proton is made of the same quarks as delta but has isospin  $\frac{1}{2}$  and spin  $\frac{1}{2}$ . Therefore, we need a wave function orthogonal in both spin and isospin spaces.

We are not going to do that because it's technically complicated. What we will do is explore symmetry. The baryon wave function must be totally antisymmetric under quark exchange. This is a new symmetry not related to  $SU(2)$  directly. We now swap dimensions: take one particle with its spin and isospin and swap with another.

We have a basis function we constructed, and we can examine them to see if they have certain permutation symmetry. For most, there is no symmetry; they are not eigenstates of permutation. Let's see what we demand from the function. The total  $\Psi$  must be antisymmetric under permutation:  $\Psi(1,2,3) = -\Psi(2,1,3)$ .

The color wave function is antisymmetric. To see this, you need to see how it looks. Color is transformed under  $SU(3)$ . In three dimensions there are three colors. The representation of  $SU(3)$  is more complicated. There are decuplets and octets from combining three quarks:  $\mathbf{3} \otimes \mathbf{3} \otimes \mathbf{3} = \mathbf{1} \oplus \mathbf{8} \oplus \mathbf{8} \oplus \mathbf{10}$ . The dimensions match:  $27 = 1 + 8 + 8 + 10$ .

The singlet is  $\mathbf{1}$  and its wave function can be constructed. It's easiest to start with the highest weight state for the decuplet. For the components that have red, green, and blue, you need a totally antisymmetric combination:  $\frac{1}{\sqrt{6}}(|rgb\rangle + |gbr\rangle + |brg\rangle - |rbg\rangle - |grb\rangle - |bgr\rangle)$ . All even permutations have a plus sign, odd permutations a minus sign. The color wave function is antisymmetric; swapping two gives a minus sign.

The space wave function is symmetric for the ground state baryons. They are all in the simplest symmetric configuration. Therefore, the combined spin and isospin wave function must be symmetric.

Let's do an example. To construct a wave function for a proton, we combine isospin  $\frac{1}{2}$  and spin  $\frac{1}{2}$ . Let's examine some basis functions. Is it symmetric under permutation? If I swap particles 1 and 2, the function changes; it doesn't have a certain symmetry. However, it might be symmetric under permutation of quarks 2 and 3.

We construct a spin wave function that has symmetry only on the permutation of 2 and 3. The proton wave function can be guessed by combining symmetric flavor with symmetric spin. But the total wave function must be antisymmetric under any two-particle exchange. If we use just one term, that would be illegal. The wave function goes into another function.

When we combine three quarks, we get the spin  $\frac{3}{2}$  representation and two spin  $\frac{1}{2}$  representations. If I apply the permutation operator to the  $\frac{1}{2}$  multiplet, it mixes with the other  $\frac{1}{2}$  multiplet. The permutation operator is external to the rotation group. Therefore, to construct the proton, we need both of the two-dimensional multiplets.

The delta lives in the  $\frac{3}{2}$  multiplet. Applying a permutation stays within the same multiplet. But for the proton, it lives in a mixture of the two  $\frac{1}{2}$  multiplets. One has to do the algebra to find the answer.

The proton wave function is a combination. I memorize these components. The proton spin-up wave function is a combination of terms like  $|u u d\rangle$ ,  $|u d u\rangle$ ,  $|d u u\rangle$  with different spin orientations. The coefficients in the basis come from ensuring overall symmetry. The normalization comes by summing the squares of coefficients:  $4 + 4 + 4 + 6 = 18$ , so the normalization factor is  $\frac{1}{\sqrt{18}}$ .


::: callout-tip
The proton wave function (spin-up, isospin-up) is a combination of quark spin-flavor states, ensuring overall symmetry under exchange when combined with antisymmetric color and symmetric spatial parts. For example:
  $$|p \uparrow\rangle = \frac{1}{\sqrt{18}} \left[ 2|u\uparrow u\uparrow d\downarrow\rangle + 2|u\uparrow d\downarrow u\uparrow\rangle + 2|d\downarrow u\uparrow u\uparrow\rangle - |u\uparrow u\downarrow d\uparrow\rangle - |u\uparrow d\uparrow u\downarrow\rangle - |d\uparrow u\uparrow u\downarrow\rangle - |u\downarrow u\uparrow d\uparrow\rangle - |u\downarrow d\uparrow u\uparrow\rangle - |d\uparrow u\downarrow u\uparrow\rangle \right]$$  
This reflects the mixed symmetry in spin and isospin spaces required by the Pauli exclusion principle.
:::

We have the wave function of the proton. Now we can evaluate cool properties of the proton. That came as a surprise.

Now, let's discuss studies of structure. One way we experimentally probe structure is to use electron scattering. The simplest first question we can answer is: what is the charge distribution inside the hadron? That's done with an electron probing the charge.

When we scatter an electron off a hadron, almost all variables are fixed. The center-of-mass energy is fixed, and one variable remains: the scattering angle. Therefore, the experiment on structure functions is electron-proton scattering. We measure the angular distribution. From it, we get insights on the proton charge distribution and magnetic moment. That's called a scattering experiment.

It's important to realize we write many variables, like  $Q^2$  (momentum transfer squared), but it's all related to one angle. You need the probability for the electron to scatter. The kinematics in the lab frame: the electron collides with the proton, and the electron goes to some direction. This is simple two-body kinematics. The only variable is the angle.

What's the probability for the electron to scatter with almost no change in direction compared to going perpendicular? Rutherford scattering gives a term like  $1/\sin^4(\theta/2)$ , a huge peak at zero angle. Most of the time, the electron prefers to go straight. 




![This figure illustrates the difference between **elastic** and **inelastic electron-proton scattering**, key processes in probing the internal structure of hadrons discussed in the lecture.   - The top two diagrams depict **elastic scattering**, where an incoming electron ( $e$ ) scatters off a proton ( $p$ ), and both emerge as the same particles ( $e'$ ,  $p'$ ) after the interaction. In elastic scattering, the proton remains intact, and the kinematics (like the scattering angle  $\theta$ ) determine the momentum transfer  $Q^2$ . The angular diagram shows the initial and final directions of electron and proton, emphasizing the one-variable (angle) dependence of such experiments.  - The lower diagram shows **inelastic scattering**, where the electron scatters off the proton, but the proton breaks up, producing a set of hadrons denoted by  $X$ . This process allows the study of the proton’s internal structure by measuring how the energy and momentum are distributed among the outgoing particles. Inelastic electron-proton scattering leads to the extraction of **structure functions**  $F_1(x,Q^2)$  and  $F_2(x,Q^2)$ , which reveal information about the distribution and dynamics of quarks inside the proton.  Together, these diagrams summarize how scattering experiments are used to access information about hadron structure: elastic scattering measures overall charge and magnetic form factors (related to the proton's charge and magnetic moment distributions), while inelastic scattering provides evidence for point-like constituents (quarks) inside the proton through the observation of deep inelastic structure functions.](2024-Lecture-03-images/fig1.png){#fig-fg1}




 The deviation from that behavior tells us about structure. That process is elastic scattering, where initial and final particles are the same.

In contrast, inelastic scattering is where the proton is dissociated. In elastic scattering, the proton stays intact. In inelastic scattering, the final state is many particles  $X$ . The differential cross section for elastic scattering of point-like particles is  $d\sigma/d\Omega \propto 1/\sin^4(\theta/2)$ . An example is electron-muon scattering.

In QED, you calculate diagrams. The matrix element is  $\mathcal{M} = \bar{u}_3 \gamma^\mu u_1 \cdot (g_{\mu\nu}/Q^2) \cdot \bar{u}_4 \gamma^\nu u_2$ . For this course, we analyze it generally. The matrix element is a scalar. It's obtained by contracting different Lorentz structures. The spinor has four components, contracted by gamma matrices.

This is point-like scattering. When we deal with the proton, we extend the vertex function with form factors. The dimensionality of this object is a simple function of  $Q^2$ . It is convenient to introduce a combination: the electric form factor  $G_E(Q^2)$  and magnetic form factor  $G_M(Q^2)$ . They both are functions of  $Q^2$ .

In non-relativistic theory, there is a straightforward interpretation. Those factors show the charge distribution.  $Q$  is momentum. There is a transformation:  $Q^2 = -q^2$ , so  $q$  is the three-momentum transfer. We can transform to coordinate space by Fourier transform. The charge density  $\rho(r)$  is the Fourier transform of  $G_E(q^2)$ :  $\rho(r) = \int \frac{d^3q}{(2\pi)^3} e^{i \vec{q} \cdot \vec{r}} G_E(q^2)$ .


::: callout-note
The charge distribution  $\rho(r)$  is obtained from the electric form factor via Fourier transform:
  $$\rho(r) = \int \frac{d^3q}{(2\pi)^3} e^{i \vec{q} \cdot \vec{r}} G_E(q^2)$$  
This relates the momentum-space form factor to the spatial charge density.
:::

When I put  $q = 0$ , the Fourier transform gives the normalization. So the normalization of the form factors is fixed:  $G_E(0) = 1$  (the proton charge), and  $G_M(0) = \mu_p$  (the magnetic moment). 




![This figure represents the basic Feynman diagram for **elastic electron-proton scattering**. An incoming electron ( $e$ ) interacts with a proton ( $p$ ) via the exchange of a virtual photon (the vertical line connecting the two). The diagram highlights one of the main experimental probes of **proton internal structure** discussed in the lecture.   In this process, the electron scatters off the proton by exchanging a photon, allowing physicists to study the **charge distribution** and **form factors** ( $G_E$  and  $G_M$ ) of the proton. The amplitude for this process is modified by the proton's internal structure, which is encapsulated in the form factors. Measurement of the angular distribution of the outgoing electron in such experiments reveals information about the **spatial distribution of charge and magnetization** inside the proton, providing crucial evidence for the non-point-like, composite nature of hadrons as described by the **quark model** and confirmed by analyses of **structure functions** in **deep inelastic scattering**.  The process depicted here is foundational for understanding the **structure functions**  $F_1$  and  $F_2$ , and their relationship to the proton's internal constituents (quarks) and the necessity of introducing symmetry concepts like isospin and color.](2024-Lecture-03-images/fig2.png){#fig-fg2}






The magnetic moment is a quantity that reacts in a magnetic field. It is proportional to the spin of the particle:  $\vec{\mu} = g \frac{e}{2m} \vec{S}$ . For a point-like Dirac fermion,  $g = 2$ . For the electron, the magnetic moment is  $\mu_e = \frac{e}{2m_e}$ . The same for a muon.

But for the proton, it's not. The proton has spin  $\frac{1}{2}$ , charge  $+e$ , mass  $m_p$ . That relation is completely different. There is a correction due to internal structure. The magnetic moment can be measured by analyzing  $G_M$  at  $Q^2 = 0$ . One finds it's quite an amazing number: approximately 2.79, not 1. It's a large correction.

It comes from the quark model and is easy to see if you analyze the proton wave function. What could have gone wrong in our naive consideration? We know the proton is made of quarks. How will the equation be modified? Instead of the proton charge, we should use the charges of quarks ( $+\frac{2}{3}e, -\frac{1}{3}e$ ). Instead of the proton mass, we should use the masses of the quarks. The spin is the same.

The answer is a combination. When we analyze the magnetic moment, we see internal structure. Therefore, what we put as charge and mass in the naive model is not correct. This number can be obtained by looking at the wave function.

Let's act with the magnetic moment operator on the proton. The operator for a baryon is the sum of quark contributions:  $\hat{\mu} = \sum_{i=1}^3 \frac{q_i}{2m_i} \vec{\sigma}_i$ . Act on  $|u u d\rangle$ . The  $u$  quark has charge  $+\frac{2}{3}e$  and mass  $m_u$ , the  $d$  quark has charge  $-\frac{1}{3}e$  and mass  $m_d$ .

When you act with the  $\mu_z$  operator, you get a number. Doing the algebra for the full proton wave function, you figure out that once you act this operator, you don't get the proton wave function back. The proton is not an eigenstate of the individual quark magnetic moment operator. You have to take the expectation value.

Let's make it clear with the quark model. Assume  $m_u \approx m_d \approx 300 \text{ MeV}$ , and  $m_p \approx 1 \text{ GeV}$ . The calculation yields  $\mu_p = \frac{e}{2m_u} \cdot \frac{3}{2}$ . Comparing to the naive expectation  $\mu_p^{\text{naive}} = \frac{e}{2m_p}$ , we get a factor of  $\frac{m_p}{m_u} \approx 3$ . So we've got a factor of about three.

We can compare this result: part of it is three. Cool. We managed to understand the anomalous magnetic moment of the proton. But basically, this number is the ratio equal to mass of proton over mass of quark? It just turns out to be like this because for the neutron, the answer is approximately -1.91. So the anomalous magnetic moment for neutron is -1.91, for proton it's +2.79. It's not simply a ratio of masses; it's an algebra of the charges and masses together.


::: callout-important
The magnetic moment operator for a baryon is the sum of the magnetic moments of its constituent quarks:
  $$\hat{\mu} = \sum_{i=1}^3 \frac{q_i}{2m_i} \vec{\sigma}_i$$  
For the proton, using  $m_u \approx m_d$ , the magnetic moment is:
  $$\mu_p = \frac{4}{3} \mu_u - \frac{1}{3} \mu_d = \frac{4}{3} \cdot \frac{2e}{3 \cdot 2m_u} - \frac{1}{3} \cdot \left(-\frac{e}{3 \cdot 2m_d}\right) = \frac{e}{2m_u} \cdot \frac{3}{2}$$  
This yields  $\mu_p \approx 2.79 \, \mu_N$ , where  $\mu_N = e/(2m_p)$  is the nuclear magneton.
:::

I found it amazing. Essentially, what we showed today, just knowing  $SU(2)$  and spin algebra, we can build the proton wave function. Using this function, we can figure out the magnetic moment—something that experimentally shows the proton is not a point-like particle. In the homework, we have an exercise for delta, which is relatively similar, as well as dealing with the magnetic moment operator for the delta particle.



## Evidence for Three Quarks and Color

Another interesting point is understanding that there are **three parts inside a proton**. This evidence comes from scattering experiments.

From **deep inelastic scattering**, we observe the distribution of form factors. The cross section is described by structure functions  $F_1(x, Q^2)$  and  $F_2(x, Q^2)$ , which reveal the proton's internal structure:

  $$\frac{d^2\sigma}{d\Omega\, dE'} = \frac{\alpha^2}{4E^2\sin^4(\theta/2)} \left[ \frac{F_2(x, Q^2)}{\nu} \cos^2(\theta/2) + \frac{2F_1(x, Q^2)}{M} \sin^2(\theta/2) \right]$$  

Here,  $\nu = E - E'$  is the energy transfer,  $\theta$  is the scattering angle,  $M$  is the proton mass, and  $\alpha$  is the fine-structure constant. The key observation was that  $F_2$  scales with the **Bjorken variable**  $x = \frac{Q^2}{2M\nu}$ , which provided direct evidence for **point-like constituents**—quarks.

So, how do we arrive at **three quarks** in the proton? It's not about three colors yet, but three quarks.

The **quark model magnetic moment of the proton** can be calculated from three constituent quarks (two up and one down):

  $$\mu_p = \frac{4}{3}\mu_u - \frac{1}{3}\mu_d$$  

where  $\mu_u$  and  $\mu_d$  are the magnetic moments of the up and down quarks. Explicitly, this is approximately:

  $$\mu_\text{proton} \approx \frac{2}{3} \frac{2}{3 m_u} + \frac{1}{3} \frac{1}{3 m_d} + \frac{1}{3} \frac{1}{3 m_u}$$  

This magnetic moment calculation was an early piece of evidence for three quarks, though the exact historical observable might be debated.


::: callout-note
The **Gell-Mann–Okubo mass formula** from the **Eightfold Way** provided further evidence for quark organization. It relates the masses of hadrons within an SU(3) flavor multiplet:
  $$M = M_0 + aY + b\left[ I(I+1) - \frac{1}{4}Y^2 \right]$$  
where  $M_0$  is a base mass,  $Y$  is the hypercharge, and  $I$  is the isospin. This successful classification of mesons and baryons into octets and decuplets suggested an underlying three-quark structure.
:::

Why does the model require exactly **three quarks**? This connects to the concept of **color charge**. The requirement for a totally **antisymmetric baryon wavefunction** under quark exchange forces the introduction of a new quantum number: color.

The total wavefunction is a product:

  $$\Psi_{\text{total}} = \psi_{\text{space}} \otimes \psi_{\text{spin}} \otimes \psi_{\text{flavor}} \otimes \psi_{\text{color}}$$  

The color part  $\psi_{\text{color}}$  must be the antisymmetric singlet state:

  $$\psi_{\text{color}} = \frac{1}{\sqrt{6}} \left( RGB - RBG + BRG - BGR + GBR - GRB \right)$$  

This ensures the total wavefunction obeys  $\Psi_{123} = -\Psi_{213}$  under particle permutation, satisfying the Pauli exclusion principle for identical quarks. So, the need for three colors arose from spectroscopy and symmetry, not directly from the early scattering experiments, which at the time were not precise enough to reveal color.

