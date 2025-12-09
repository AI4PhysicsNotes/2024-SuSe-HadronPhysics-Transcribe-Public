---
title: (2025) Lecture 13
author: ''
presenter: Mikhail Mikhasenko
note_taker: Anna Zimmer
date: '2025'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



## Hadronic Contributions to Muon Anomalous Magnetic Moment and Scattering Theory

So let’s start.
**What are the two terms in the muon’s anomalous magnetic moment,  $a_\mu = (g-2)/2$ , that receive hadronic contributions?**
The first is the **hadronic vacuum polarization (HVP)**. 




![This figure illustrates the two key types of hadronic contributions to the anomalous magnetic moment of the muon,  $a_\mu = (g-2)/2$ , discussed in the lecture. On the left, the first two diagrams show the **hadronic vacuum polarization (HVP)** contribution: a muon interacts with a photon, and in the photon line, a hadron loop (such as a pion loop) dresses the photon and modifies the vertex, representing the hadronic correction to the photon propagator. On the right, the diagram represents the **hadronic light-by-light (HLbL)** contribution: multiple photons interact with a hadron loop, where hadronic states (like pions or other mesons) couple to the photons inside the loop. Both types of diagrams encode how nonperturbative effects from QCD (hadron physics) affect precision observables such as the muon's magnetic moment. These hadronic effects are a significant source of theoretical uncertainty in precision tests of the Standard Model using  $g-2$ .](2025-Lecture-13-images/fig4.png){#fig-fg4}




 The second is **hadronic light-by-light (HLbL)**.

**What is the vacuum polarization diagram?**
The solid line is the fermion—the muon. The wavy line is the photon. That diagram shows how the probe (the muon) interacts with the photon. What sits in the loop is something that dresses the photon and then changes the vertex. 




![This figure represents the **hadronic vacuum polarization (HVP) diagram**, which is a key contribution to the muon's anomalous magnetic moment,  $a_\mu$ . In the context of this lecture, the wavy lines correspond to photons, and the internal loop contains a quark-antiquark ( $q\bar{q}$ ) pair. The quarks inside the loop "dress" the photon propagator, modifying the way the photon interacts with the probe (e.g., the muon). This process encapsulates the effect of hadronic (strong-force) physics on electromagnetic observables, and is a significant source of theoretical uncertainty in precision calculations of  $g-2$ . The HVP is distinct from the hadronic light-by-light (HLbL) contribution, but both reflect how hadronic physics enters precision electroweak measurements.](2025-Lecture-13-images/fig3.png){#fig-fg3}




 This is the hadronic vacuum polarization contribution,  $a_\mu^{\text{HVP}}$ .

HVP is one piece. The other contribution is **hadronic light-by-light**,  $a_\mu^{\text{HLbL}}$ . This is another place where hadrons enter.

If we expand further, where exactly in hadronic light-by-light do hadrons enter? Precisely in the loop. It could be a loop of pions or a loop of kaons. The particles that matter are those that couple to the photon. Mesons that couple strongly to two photons contribute the most—for example, the  $\eta$  and  $\eta'$ . So all mesons with a strong two-photon coupling are important.

That’s important to realize: **hadron physics gives the precision input to precision physics**. That’s the hadronic contribution to  $g-2$ . It’s very important to get  $a_\mu$  to 10 digits, as shown last time. Experiment has measured it to this precision, but theoretical calculations rely on our understanding of these vertices—whatever happens inside these blocks.

I believe these days I hear less discussion about hadronic light-by-light. The main uncertainty comes from the hadronic vacuum polarization.

**Second question: What’s the time dependence of correlation functions computed on the lattice once we transform from Minkowski space to Euclidean?**
The expectation between the vacuum and any operator  $\mathcal{O}_I$  for a state that’s not the vacuum, as a function of time, shows an exponentially falling dependence.

In the Heisenberg representation, the time dependence of the operator is given by its commutation with the Hamiltonian. When we change to Euclidean space, the time dependence becomes:

  $$\mathcal{O}(\tau) = e^{H\tau} \mathcal{O}(0) e^{-H\tau}$$  


::: callout-note
This Wick rotation  $t \to -i\tau$  converts oscillatory time evolution into exponential decay, making lattice path integrals well-defined. The Euclidean correlation function decays as
  $$C_I(\tau) = \langle 0 | \mathcal{O}_I(\tau) \mathcal{O}_I^\dagger(0) | 0 \rangle = \sum_n |\langle 0 | \mathcal{O}_I | n \rangle|^2 \, e^{-E_n \tau},$$  
where  $E_n$  are energy eigenvalues. At large  $\tau$ , the ground state dominates.
:::

Today in the lecture I plan to connect the scattering problem in quantum mechanics—the scattering theory we’ve discussed during the course—and see how resonance phenomena and complex structure emerge. Then I will connect this to the methods used in lattice field theory in a finite box to obtain useful results on scattering properties of particles.

I’ll start with the scattering problem in quantum mechanics on the basis of wave functions. The main equation for scattering is the time-independent Schrödinger equation:

  $$H \psi = E \psi$$  

The Hamiltonian is the sum of two terms:

* The kinetic term, where momentum maps to the derivative of the coordinate,
* and the potential  $V(x)$ .

Most of the time in quantum mechanics we work in coordinate space, and the potential is a function of a single variable—the one-dimensional  $x$  coordinate.

For simplicity, let’s drop all constants; we can recover them from dimensionality later. The equation then reads:

  $$\left[ -\frac{d^2}{dx^2} + V(x) \right] \psi(x) = E \psi(x)$$  



## Closed-Form Solutions and Bound States in the Pöschl–Teller Potential

That's a differential equation that can be solved numerically. However, there are several types of potentials for which a **closed-form solution** exists. I would like to examine one of them to gain physical insight.

Before that, let's discuss the variables. The energy of the system,  $E$ , is a fixed parameter in the differential equation. This is a quantity we must probe, fix, and then solve for.

The general approach to investigate a system with a given potential  $V(x)$  is as follows:

1.  Fix the energy  $E$  (or the related breakup momentum).
2.  Solve the **time-independent Schrödinger equation**:
  $$-\frac{\hbar^2}{2m} \frac{d^2\psi(x)}{dx^2} + V(x)\psi(x) = E\psi(x)$$  

3.  Find the eigenvalues and eigenfunctions (wave functions  $\psi(x)$ ) that satisfy it.

We can also frame the problem differently: the solution will not exist for arbitrary values of  $E$ . We can treat  $E$  as a parameter and ask: **for which energy values does this differential equation have a physically acceptable solution?** This leads us to identify the possible energy regimes of the system.

I will look at potentials with a closed-form solution. One example is the **Pöschl–Teller potential**:
  $$V(x) = -\frac{U_0}{\cosh^2(\alpha x)}$$  
It is advantageous to have a closed form because it allows for quick visualization and coding.

The claim is that for this potential, an algebraic change of variables leads to an analytic, closed-form expression for the wave function, formulated in terms of hyperbolic functions and the **hypergeometric function**. Special functions are not a problem, as implementations exist in programming languages like Mathematica, Python, and Julia, so we can plot everything.

The physics is very interesting. This potential has two parameters:

*    $U_0$  controls the **depth** of the well.
*    $\alpha$  controls the **width** of the well.

Depending on these parameters, many rich physical phenomena emerge.

### Scattering and Bound States

In the scattering problem ( $E > 0$ ), the wave function's **asymptotic form** far from the well is a superposition of incoming and reflected plane waves:
  $$\psi(x) \sim e^{ikx} + R e^{-ikx} \quad \text{as } x \to -\infty$$  
where  $k = \sqrt{2mE}/\hbar$ . For a symmetric potential, this can also be written as  $\psi(x) \sim \cos(k|x| + \delta_0)$  for  $|x| \gg R$ , where  $\delta_0$  is the scattering phase shift.


::: callout-important
A physically acceptable wave function must be **finite everywhere**. We cannot allow exponential growth at infinity. This asymptotic condition restricts the allowed solutions.
:::

The energy spectrum arises from solving the differential equation and imposing this **finiteness condition**. We must ensure the wave function does not blow up exponentially at both  $x \to \pm \infty$ .

*   **Continuum of States (Scattering):** For energies **above** the asymptotic value of the potential ( $E > 0$ ), all energy values are allowed. This is called the **continuum**. The Schrödinger equation has a solution for any positive  $E$ .
*   **Bound States:** For energies **below** the potential threshold ( $E < 0$ ), solutions exist only at specific, discrete energy levels. These are **bound states**.

A bound state wave function is localized: it has oscillatory behavior inside the well and **exponentially suppressed tails** outside it.

### Bound States in the Pöschl–Teller Potential

For the Pöschl–Teller well, the properties of the bound states are known exactly.

The **number of bound states**  $N$  is finite and given by:
  $$N = \left\lfloor \sqrt{\frac{2mU_0}{\alpha^2 \hbar^2}} \right\rfloor$$  

*   If the well is very deep (large  $U_0$ ),  $N$  is large, and there can be many bound states (e.g.,  $n = 0, 1, 2, ...$ ).
*   If the well is made narrower (large  $\alpha$ ), the denominator increases and  $N$  decreases, meaning fewer states can fit inside.

The **energy eigenvalues for these bound states** are quantized and given by:
  $$E_n = -\frac{\hbar^2 \alpha^2}{2m} \left( \sqrt{\frac{2mU_0}{\alpha^2 \hbar^2}} - n \right)^2$$  
where  $n = 0, 1, 2, \dots, N-1$ . The energy is always negative and is limited by the well depth  $U_0$ .

The corresponding **bound state wave functions** are expressed in terms of hypergeometric functions:
  $$\psi_n(x) \propto \left( \cosh(\alpha x) \right)^{-\lambda} \cdot {}_2F_1\left( -n, \lambda + s; \frac{1}{2}; 1 - \tanh^2(\alpha x) \right)$$  
where  $\lambda$  and  $s$  are parameters derived from the potential and energy.



## Analytic Structure of Scattering Amplitudes and Boundary Conditions

Now I want to look at this picture once again and then transform it to the way we have seen in scattering theory. We used to write energy on the x-axis. This was called the **energy plane**, and the continuum in scattering theory was represented by a **branch cut**. The bound states were appearing as **poles**.

It is actually very instructive to map what we call the scattering amplitude in scattering theory to the potential problem. In fact, that analytic structure is exactly the same for the transmission and reflection coefficients. To make it very accurate, we have to consider the different problem where we have a clear incoming wave, a reflected wave, and a transmitted wave.

As a side remark, consider a potential like this. We have an incoming wave,  $e^{ikx} + R e^{-ikx}$ . Then we have a transmitted wave on the other side. Here,  $T$  is the transmission coefficient and is related to the probability for the flux from the left to go to the right.  $R$  is the reflection coefficient. When you just want to solve the scattering problem, that's the setup that you would use.

On the left you would send in the wave, there will be reflection. You solve the boundary conditions. You can reverse the setup, send the wave from the right and then solve the other equations. There is the relation that the probability to pass from the left is equal to the probability to pass from the right, expressed by **probability flux conservation**:

  $$|T|^2 + |R|^2 = 1$$  

Here we could also do this, but it's not this type of potential. It is actually easier for a symmetric potential to use symmetric functions with odd and even parity, like the cosine and sine. That's why I will get to that. It is important to realize that the role of the scattering amplitudes is played now by these coefficients. They are functions of the momentum and energy.

We are dealing with the coordinate space;  $e^{ikx}$  is a plane wave and the scattering amplitude is the coefficient in front that depends on energy. What we discuss here is the possible solution for  $E$ . But we can also ask the question: what is the analytic structure of our transmission coefficients in the complex plane? We are going to discover exactly that.

In the area where there is the continuum, any value of the energy is possible. You have a branch cut. Then there are bound states that are trapped in the well. The scattering amplitude has a **pole structure**:

  $$\mathcal{A}(E) \sim \frac{1}{E - E_{\text{pole}}}$$  

When we deal with the symmetric potential, instead of using that basis, we can switch to the cosine and sine basis. We can use either one or another. Let's stick to the even wave, such wave functions that have a positive parity.

Now I want to give you an intuitive understanding of the **scattering phase shift**  $\delta_0$  that appears here. We will look for the solution with positive energy. Say here is our potential, that's the energy that's fixed. What is the wave function like? It's given by this function.

This satisfies the equations outside of the well asymptotically. Let's say the well is localized in the area of radius of the size  $R$ . Outside of the well, when there is no potential, the **free-particle Schrödinger equation** applies:

  $$\psi''(x) + E \psi(x) = 0 \quad \text{for} \quad |x| > R$$  

Its solution is given by a cosine. It's clear that this is a solution. If you take a second derivative, the  $k^2$  comes out of the cosine, you still have a cosine with a minus sign. Then  $k^2$  is  $E$  and you get exactly the terms.

What I would like to argue is that this phase shift  $\delta_0$  is something that doesn't spoil the solution. It's still a solution and it reflects asymptotically the properties of the potential. Despite that the potential is localized, the functions at infinities feel the properties of the potential.

That's actually the essence of scattering theory. You send a plane wave to your potential from minus infinity from the asymptotic regime. Then you check the properties of the wave on the other side asymptotically. It comes as a plane wave, but with a slightly different phase. This difference in the phase reflects the properties of the potential.


::: callout-note
The **asymptotic wave function** for a symmetric potential well is:
  $$\psi(x) \sim \cos(k|x| + \delta_0) \quad \text{for} \quad |x| \gg R$$  
The modulus  $|x|$  ensures symmetry, and  $\delta_0$  is the scattering phase shift encoding the potential's effect at large distances.
:::

I believe one intuitive picture that I have in mind is that imagine you have a slider and you can tune the depth of the well. Here is  $-U_0$  and you can tune this up, that becomes flat. So  $U_0$  to zero. If  $U_0$  is not there, the plane wave without this, any  $\delta$  is a solution to this equation. Just  $\cos(kx)$ , with  $\delta = 0$ , is a solution.

What happens when  $U_0$  appears? You make it bigger so the wave gets shifted. Essentially when  $U_0$  is there, you have that solution. It's not valid to use the same cosine inside of the well, because there is the x dependence of the potential. It's only asymptotically valid.

What we see is that on both sides there is the shift of the period of our wave function. That shift is exactly this  $\delta_0$ . The stronger your potential, the more it's going to shift asymptotically the period of the wave. Since this is valid, to make it valid on both sides we have to put the modulus. The asymptotic wave function is  $\psi(x) \sim \cos(k|x| + \delta_0)$  for  $|x| \gg R$ . For positive  $x$  this is like this. For the negative it's a minus  $x$  to have it symmetric.

Maybe that's also a good moment to think what happens with these **poles** when we change the potential, that we had our slider right to move up and down the depth of the well. What happens with these poles? Clearly they are going to move continuously with the depth of the potential.

When we make the potential shallower and shallower, these bound state poles are going to move towards the threshold and then disappear there. But in fact they don't disappear. You know what happens? They're going to wrap around the branch point and appear on the other analytic sheet. We know that function, due to this branch cut, has several Riemann sheets.

Essentially what they do is to flip, go to the non-physical sheet and become **virtual states**. As soon as this pole wraps around the cut, it appears on the same location, but on the physical sheet we call them virtual states. It's interesting actually.

It's important to realize that as soon as the potential is in a regime that is already finite, it has a certain depth, but it cannot yet host a bound state. There are only virtual states. If attraction is not strong enough, there are no bound states in the potential. But still attraction could be felt by particles. That probably indicates that there are virtual states. With a certain depth there are 1, 2 and then even more states.

What are **resonances** then? If you follow this logic, resonances are phenomena where particles with low energy feel the attraction more. What we want is that at certain energies we want to have peaks in the amplitudes. I think this potential does not have any resonance phenomena.

But the resonance phenomena could be seen if the probability to pass through the well increases for certain energies. If we have an energy here that is low, the probability to pass or the reflection—let's maybe think of the reflection coefficient. Any wave gets reflected and this probability of reflection changes with the energy of the particle.

The resonance phenomena would correspond to the phenomena when you change the energy, the probability of reflection gets lower or higher and then back to the same value. If you have a strong dependence of the probability to get reflected on the frequency of the wave, you have a resonance phenomenon that corresponds to the poles that are in the traditional amplitude in the complex plane. A **resonance corresponds to a pole at complex energy**:

  $$E_{\text{res}} = E_0 - i \frac{\Gamma}{2}$$  

where  $E_0$  is the resonance energy and  $\Gamma$  is the width.


::: callout-important
The analytic structure of the scattering amplitude is key:

*   The **continuum** of scattering states corresponds to a **branch cut** along the positive real energy axis.
*   **Bound states** correspond to **poles** on the negative real axis.
*   **Resonances** correspond to **complex poles** (e.g.,  $E_0 - i\Gamma/2$ ) on unphysical Riemann sheets, leading to peaks in cross-sections.
:::

Now we are ready to actually put this problem into the box. Solving in the box is also an academic problem. I'm not sure for this potential you can solve this in a closed form. But what changes is that you impose yet another condition.

We say a particle at the value  $L$  has to be the same as the one on the other side, as well as the derivative. These **periodic boundary conditions** are quite strong and change dramatically the phenomena that we observe:

  $$\psi(L) = \psi(-L), \quad \psi'(L) = \psi'(-L)$$  

Periodic boundary condition also can be seen as mirroring this picture on the left and on the right an infinite number of times. In the previous lecture I was talking about a lattice as a sort of this periodic boundary condition, as a sort of grid of repeated cells in which we do computations. Essentially this is a periodic boundary condition.

We will assume that the size of the well is much smaller than  $L$ . That's important to use asymptotic formulas at the value of  $L$ . Let me do this.



## From Continuum to Discrete: Finite Volume Effects and Lattice Spectroscopy

The first condition does nothing—the function is symmetric, so it is already the same on both sides of the lattice.

But the second condition is actually important. We are still dealing with energies that are positive. From this boundary condition we realize that now, in fact, not every energy is possible. Since the energy is related to momentum by  $E = k^2$ , only certain discrete values are allowed. In the continuum, most values become forbidden, and only a discrete spectrum appears.

Let me first draw it as a line. I'm still going to have a bound state below the threshold crossing. 




![This figure illustrates the energy spectrum of a quantum system in a finite box with periodic boundary conditions. On the left, the "bound states" are indicated by isolated crosses at negative energies, representing discrete, localized energy levels below the threshold ( $E < 0$ ) of the potential well. To the right, along the positive energy axis ( $E > 0$ ), there is a set of regularly spaced ticks labeled as the "discrete spectrum," separated by intervals approximately  $2\pi/L$ , where  $L$  is the size of the box.   Physically, this captures the replacement of the continuum of scattering states in infinite volume (where all positive energies are allowed) with a discrete set of allowed energies when the system is put into a finite periodic box. The spacing between these levels is inversely proportional to the box size, and as  $L \to \infty$  the spectrum approaches the continuum limit. The figure encapsulates the key idea that in finite volume, the energy spectrum consists of both bound states and a set of quantized scattering states—each energy level corresponds to a pole in the scattering amplitude, and their positions are shifted from the non-interacting values by the phase shift  $\delta_0(k)$  associated with the underlying interaction potential. This setup is essential for applying the Lüscher method to extract scattering information from lattice simulations.](2025-Lecture-13-images/fig5.png){#fig-fg5}




 But now, even above the threshold, I have a discrete spectrum. You see how this transition happens.

So what effectively happens is that our branch point and the cut that starts from zero and goes to the positive real axis of energy gets replaced by a set of poles. Every allowed value of energy, if it's isolated, corresponds to a pole in the scattering amplitude. A bizarre thing happens: we used to have a cut in the complex plane, and now it becomes an infinite number of poles along the real axis.

As the lattice size  $L$  increases, in the limit  $L \to \infty$ , we resemble the continuous limit—the limit of an infinite box. In this limit, we recover the infinite volume and the continuous spectrum. The distance between poles in the region that used to be continuous scales with  $1/L$ , so they become very, very close to each other.

Another term I would like to highlight is the  $\delta_0$  term. That term, at asymptotic distances, remembers properties of a potential of infinite range. This term actually changes the discrete spectrum we have in the continuum, in the area that used to be continuous—there is a shift.

That's related to the exercise we did. We took our potential and made it flat, setting  $U = 0$ ; the phase shift  $\delta_0$  vanished. Then we pulled the potential down, and  $\delta_0$  became significant. What you see is that the spectrum of the energy—these states not only below the threshold but also above—gets adjusted and shifted.

This shift is related to the properties of the potential. That's a key idea for our computations of scattering in finite volume. We have a way to solve the Schrödinger equation numerically, look at the asymptotic values, and find  $\delta_0$ .

We don't need to do that manually, but what if we can set up… It's critical when the potential is not analytically solvable. If we can perform a scattering experiment and only have access to the asymptotic form and the energy spectrum of the system, we can deduce the properties of the potential from the energy spectrum.

We check what energies are possible in the system when there is no interaction—a simple problem. We know the answer: for free particles in a periodic box of size  $L$ , the momenta are quantized as
  $$k_n = \frac{2\pi n}{L}, \quad n \in \mathbb{Z}.$$  
Then we check numerically what the possible energies are when there is an interaction. By comparing these two spectra, we can deduce the value of the scattering phase shift  $\delta_0(k)$ . So  $\delta_0$  depends on energy, and you probe it with different values of  $k$ .


::: callout-important
This connection is encapsulated in the **Lüscher quantization condition** for finite-volume scattering. In a periodic box of size  $L$ , the discrete momenta  $k$  are determined by the scattering phase shift  $\delta_0(k)$ :
  $$\delta_0(k) = n\pi - \phi(kL), \quad n \in \mathbb{Z},$$  
where  $\phi$  is a geometric function from the periodic boundary conditions. This formula allows us to extract infinite-volume scattering data from the finite-volume energy spectrum.
So far, despite quantum mechanics being a very well taught course, the connections with material that comes after—like quantum field theory and particle physics—are maybe not that easy to grasp.
:::




![This figure illustrates the concept of a **quantum field** as it manifests on a space-time lattice in lattice field theory. Each box represents a spacetime site on the lattice. At every site, the quantum field can create or annihilate a  $\pi$  meson (pion), as sketched within the circles labeled “π”. The arrows indicate how the quantum field links adjacent sites, encoding the propagation and interactions of pions across the lattice. This setup models how, in a discretized spacetime (the lattice), the quantum field provides the dynamical degrees of freedom that give rise to all possible particle configurations at each site, allowing for the calculation of correlation functions and ultimately the extraction of properties like the energy spectrum and scattering amplitudes, as discussed in the lecture. The annotation clarifies that what is being represented at each site is indeed the **quantum field**.](2025-Lecture-13-images/fig2.png){#fig-fg2}




 I think it's important to spell out and discuss all shared points to make the connection clear.

If you think of a finite box with periodic boundary conditions, like having two marbles interacting on a ring, then what plays the role of the lattice size  $L$  is the full circumference of the ring. The variable  $x$  is the distance between the two marbles. If there is an interaction potential, that's precisely the setup we have. A periodic boundary condition means it doesn't matter where they are; only the distance matters.

In lattice field theory, the quantity computed is the correlation of operators. This is the vacuum expectation value of the product of two operators:
  $$C_{ij}(t) = \langle 0 | O_i(t) O_j^\dagger(0) | 0 \rangle.$$  
Here  $i$  and  $j$  label operators. Say we have five of them, or one, two, three, or four. We compute a  $5 \times 5$  matrix of correlation functions as a function of Euclidean time  $t$ .

The expected form for this correlation is a sum over energy eigenstates:
  $$C_{ij}(t) = \sum_n \langle 0 | O_i | n \rangle \langle n | O_j^\dagger | 0 \rangle e^{-E_n t}.$$  
If we insert a complete basis of states  $|n\rangle$ , we get a combination of exponential functions with coefficients  $z_i^n = \langle 0 | O_i | n \rangle$ .

*   To get the meson spectrum, you would take  $O$  as a combination of quark and antiquark fields—with appropriate gamma matrices to match the desired quantum numbers—to create an object that looks like a meson. You compute its correlation as a function of time, extract the energy  $E$ , and that gives you the energy of the system. All possible meson energies appear, starting with the ground state.
*   For example, take a  $u\bar{u}$  operator, run this correlation on the lattice, and the lowest energy that appears will be the mass of the  $\pi$  meson.

An important aspect is that the higher the energy of a state, the faster its contribution decays. Therefore, if you wait long enough in time  $t$ , all higher-state contributions drop exponentially. What remains is only the ground state of the system:
  $$C(t) \xrightarrow{t \to \infty} A_0 e^{-E_0 t}.$$  
In the meson case, this works fine. For baryons, it can be more challenging due to noisier signals.

However, there is more information stored in these correlations if your operator basis is larger. We can treat this as a general eigenvalue problem—a technique used to extract exponentials of the higher states.

It's not overly complicated. You take the correlation matrix  $C_{ij}(t)$ , and for different values of  $t$ , you solve a **generalized eigenvalue problem**:
  $$C(t) v_n(t, t_0) = \lambda_n(t, t_0) C(t_0) v_n(t, t_0).$$  
The eigenvalues behave as  $\lambda_n(t, t_0) \propto e^{-E_n (t - t_0)}$  for large  $t$ , allowing you to access excited-state energies  $E_n$ .

*   By diagonalizing this matrix, you optimize the overlap of different operators with the true energy eigenstates. The diagonal elements of the diagonalized matrices give the time dependence of those higher states.
*   There are specialized algorithms to make these calculations less noisy.

For the operator that creates mesons, the operators must carry specific quantum numbers. If you want the spectrum of light spin-one mesons, the operators have  $1^-$  quantum numbers. For other quantum numbers, you need different operators.

What happens in practice on a finite lattice is that spin is not a good quantum number because you don't have full rotational symmetry. The lattice has a discrete rotation group, so different spins mix. In practice, the whole meson spectrum is computed simultaneously.

By using a large matrix—with hundreds of operators spanning different sectors—you include overlaps between different spins in the off-diagonal elements. You then solve for a large number of eigenvalues (say, 30–40) and map the resulting energy values to the masses of the mesons.



## Extracting Resonances from Finite-Volume Spectra

There is one problem with that approach. The problem is that we know that in hadronic interactions most of the resonances above the thresholds decay. They are in fact not bound states; they are resonances. Excited mesons, like the rho meson and higher states, are resonances in the  $ππ$  interaction.

Strictly speaking, the method of extracting eigenvalues from the exponential decay of correlators is **not applicable above the two-pion threshold**. If you wait long enough, you will see the ground state, so the mass of the pion is easy to measure. But as soon as you extract an energy above  $2m_π$ , what you measure are the states of the two-pion system rather than a single stable particle. Therefore, values extracted above the open flavor threshold, above  $2m_π$ , are not trustworthy or reliable.

A different method is used to address the physics of resonances, such as determining what resonances appear in  $ππ$  scattering.

Instead of using two-quark operators for single mesons, **four-quark operators** are used that represent meson-meson combinations, schematically  $O \sim \bar{q} Γ q \; \bar{q} Γ' q'$ . The energy spectrum of a meson-meson combination in a finite box is very rich and resembles the discrete spectrum we expect for two particles in a box. Above the threshold, in the continuum region, the spectrum is discrete with a small spacing on the order of  $2\pi/L$ .

The position of these discrete states deviates from the spectrum of a non-interacting two-particle system by a small value. This energy shift,  $\Delta E_n = E_n - E_n^{(0)}$ , encodes the scattering information and is related to the **scattering phase shift**  $\delta(k)$ .


::: callout-important
This is where **Lüscher's finite-volume method** is applied. It provides a direct link between the discrete energy levels  $E_n$  measured on the lattice and the infinite-volume scattering phase shift  $\delta(k)$ .
:::




![This figure depicts a finite, periodic box—a three-dimensional cubic lattice of size  $2 \, \mathrm{fm} \times 2 \, \mathrm{fm} \times 2 \, \mathrm{fm}$  (where "fm" means femtometer or fermi, a common unit of length in nuclear and particle physics). In the context of the lecture, this box represents the finite spatial volume used in lattice field theory calculations. The grid illustrates the discretization of space (the "lattice"), with periodic boundary conditions implied on all sides. Physically, this setup mimics the environment for two particles (such as mesons or nucleons) interacting inside a finite, periodic domain. The box imposes discrete momentum values for the particles, modifies the energy spectrum (replacing the continuum by discrete levels), and enables the extraction of scattering information (such as phase shifts) via finite-volume methods like the Lüscher formalism. This mirrors the core idea discussed in the lecture: by confining particles to a finite box and analyzing the resulting discrete energy spectrum, one can infer properties of scattering and hadronic interactions relevant to QCD.](2025-Lecture-13-images/fig1.png){#fig-fg1}




 For a single channel in a periodic box, a simplified form of the quantization condition is:
>   $$k \cot \delta(k) = \frac{1}{\pi L} S\left( \eta \right), \quad \eta = \left( \frac{kL}{2\pi} \right)^2$$  
> where  $S(\eta)$  is a known kinematic function and  $k$  is the scattering momentum related to the total energy  $E$ .

Computations are done, extracting all these discrete levels  $E_1, E_2, E_3, \ldots$ , and then comparing them to the predictions for non-interacting particles. By looking at the difference between the non-interacting spectrum and the interacting spectrum, you deduce the asymptotic scattering phase shift  $\delta(k)$ .

A classical example using this technique is **P-wave  $ππ$  scattering**, where one extracts the phase shift and obtains a curve showing a tangent dependence characterizing a resonance. For physical quark masses, this resonance peaks at a specific value. The pion mass is 140 MeV, and the second threshold is at a value where the momentum  $k$  equals zero. The nominal mass, where the phase shift passes  $\pi/2$  (or 90 degrees), is **770 MeV**. This is the nominal mass of the  $ρ$  meson.

*   **Resonance Condition:** Near a resonance, the phase shift follows a Breit-Wigner form:  $\tan \delta(k) = \frac{\Gamma/2}{E_R - E}$ , where  $\Gamma$  is the width.
*   **Resonance Pole:** The fundamental property of a resonance is a pole in the complex energy plane:  $E_{\text{res}} = E_0 - i \frac{\Gamma}{2}$ .

This is more or less the machinery used these days to study hadron spectroscopy on the lattice. The method is accurate as long as you can take into account all relevant channels. It works as follows:

1. Construct a large basis of operators with the appropriate quantum numbers.
2. Extract the eigenvalues to get the energy spectrum of the two-meson system.
3. Compare it to the non-interacting spectrum to extract  $\delta(k)$  for different scattering momenta  $k$ . 




![This figure illustrates the extraction of the **scattering phase shift**  $\delta(k)$  as a function of the breakup momentum  $k$  in a finite volume—specifically as encountered in lattice QCD calculations. The phase shift curve (vertical axis) rises sharply with  $k$ , exhibiting a rapid change near a particular momentum, labeled  $k_{\rm nominal}$ , where  $\delta_0 = 90^\circ$ . This point is associated with the **resonance condition** in scattering theory, corresponding to the physical mass of a resonance (for example, the  $\rho$  meson in  $ππ$  scattering).  The **yellow X’s** mark discrete energy levels  $\Delta E_1, \Delta E_2, \Delta E_3, \ldots$  determined from the finite-volume spectrum in the box. Each energy level gives a quantized value of  $k$ , and through the **Lüscher quantization condition**, each can be mapped to a value of the phase shift  $\delta_0(k)$  at that  $k$ . The dashed line shows the characteristic tangent-shaped dependence of  $\delta_0$  on  $k$  near a resonance.  The upward curvature represents the rapid change in the phase shift due to the presence of a **resonance pole** in the scattering amplitude, with  $k_{\rm nominal}$  indicating the resonance energy where the phase shift passes through  $90^\circ$ . This construction allows lattice theorists to connect the finite-volume discrete energy spectrum to infinite-volume scattering observables, such as the location and width of a resonance.](2025-Lecture-13-images/fig6.png){#fig-fg6}






You then plot these points, either on an Argand diagram or as the phase shift dependence on the breakup momentum  $k$ . From first principles—from the QCD Lagrangian—we thus obtain the spectrum of two-particle scattering and the properties of resonances.

There are many complications to this problem that come from **coupled channels**. As soon as another threshold opens, for example when the energy is above the two-kaon threshold, you have to take into account that the channels are coupled. The operator basis must then include not just pions, but also kaons and  $η'$  mesons. If you are above the three-pion threshold, you also have to include three-pion operators. It becomes large and complicated, but the core idea of using the energy shift remains the key.

For multi-channel scattering, the analysis generalizes to the ** $K$ -matrix formalism**, where the scattering matrix  $S$  is related to a Hermitian  $K$ -matrix by  $S = (1 + iK)(1 - iK)^{-1}$ . This formalism is used by both lattice practitioners and experimental analysts to parameterize data and extract physical resonance poles and couplings.

The raw energy levels from the lattice are not yet the final properties of the resonances. Further analysis involves parameterizing the data to extract the pole position  $E_{\text{res}} = E_0 - i\Gamma/2$  and the couplings. This final information—the pole positions and couplings—is what is important and what gets published in the Particle Data Group (PDG) for comparison between theory and experiment.



## Lecture Conclusion

---
**All right then, that's all for today.**

::: callout-note
This concluding remark marks the end of the lecture segment. As noted in the supporting material, this specific chunk contains no substantive technical discussion, such as formulas related to nuclear physics concepts like decay rates, binding energy, or reaction cross-sections.
**This concludes the lecture for this session.**
:::

