---
title: (2024) Lecture 1
author: ''
presenter: Mikhail Mikhasenko
note_taker: Ilya Segal
date: '2024'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



### Foundations of Hadron Physics

# Lecture 1: Introduction to Hadron Physics

## Course Introduction and Structure

**Lecture one** will be dedicated to the introduction of **hadron physics**.
I would like to start by explaining the **origin of hadron physics** and how it appeared at the earlier stages of the universe, where it matters in the course of evolution of our universe.
Then we will discuss the **matter composition** and how **quark physics** plays its own role.
We will briefly discuss the **Standard Model** and then **equations that describe the motion of fields**.
We will talk about the **gauge groups** and move to the important property of the **strong interaction** that is the key to matter formation, known as **confinement**.
I will write the **basic equations** that will help you to solve exercises.

Today is the 8th.
This course is being offered for the **second time**.
I will be reusing material from the last lecture from last year as well.
Last year we made an experiment of **recording the lectures** and transforming them into text.
There is a project we are working on to have this more **automatic way**.
We are experimenting to gain more material to work with.
This iPhone is the recording device.
I have recordings from last year.
That will benefit you as well, because the idea is that I provide you with the **text of the lecture**.
Another thing is that if someone makes **pictures of the board**, it will also be included.
We will input this into the language model and have it formally typed.
So probably I will ask you to make a picture once we fill the board.

## Cosmic Timeline and Scales

It is good to start the lecture course by establishing the **timeline for the universe** and the numbers for different epochs and stages.
They are really hard to imagine—either **very small or very large**.
That is why we need this on a **human scale** first.
The number where we are now is **14 billion years**, which is what we believe is the **age of the universe**.

Starting from the **Big Bang** there will be many points.
To have a human scale, consider an exercise where a **clap represents the Big Bang**.
The sound comes to different rows at different times.
If the clap was a Big Bang from that moment, the universe started evolving.
By the time when the sound came to you, most of the stages had already passed.
**Hadron physics** is actually around this time.

Key time scales in early universe evolution:

- **10⁻⁶ seconds**: Matter production begins
- **10⁻¹² seconds**: Electroweak scale passed, Planck scale passed
- **1 second**: Nuclear synthesis starts

We need $10^{-6}$, $10^{-12}$, $10^{-12}$, $10^{-6}$.
At about **one second** at the beginning, **matter is produced**.
We do not know what kind of matter is there, but we assume that the **structures started forming already**.
The **seeds of the structure** were already produced during **inflation**, inflation of the space and time.
We have little idea about what is going on here.

We will advance the time to $10^{-12}$, where already the **electroweak scale** is passed.
The **Planck scale** is passed.
The **Higgs potential** developed its minimum, the universe collapsed to the lower second minimum of the Higgs potential, and we arrive at $10^{-12}$, where the matter itself is the equivalent **plasma**.

::: callout-note
The **quark-gluon plasma (QGP)** is a state of matter where quarks and gluons are not confined within hadrons but exist freely in a hot, dense soup.
:::
The dots here are **quarks**.
They are constituents of the matter.
The fields that operate in this space are **gluons**.
With this abbreviation, **QGP**, we refer to **quark gluon plasma**.
There is no matter as we know it.
It is just a **soup** in which fields are acting.
The **equation of motion** at high temperature in place around $10^{-6}$, this soup starts evolving into structure.
In the interval somewhere here you have got the **hadronization process**.

When the sound came to you, what happened with our universe is that it already has **elementary matter blocks**, which are **mesons and baryons**.
Quarks are now **confined** and gluon fields are almost entirely sitting inside of these objects.
Essentially that is all we need from this picture.
What happens further is another **14 billion years of evolution**.

Somewhere here mark **one second**, which is a good mark, where the **nuclear synthesis** starts.
Another visually pleasant indication is when **radiation separates from the matter**.
Big Bang nuclear synthesis and then radiation separates from the matter is around, does not have a scale.
It happens for **400,000 years** after the Big Bang.
We have got **pions and baryons**.

For the rest of the semester, what will happen with our universe, which we just created?
There will be some **nuclear synthesis** starting.
We will not get to the forming of the **atoms** as we know them with **electron shells** until **400,000 years** after.

## Atomic Structure and Scales

So what I have here is the **electron**, right?
So atom is what?
Let us now go to the second item.
What is the **matter**?
What is the most abundant element in the crust of the earth?
By mass, the most abundant element is **iron** and the most abundant in the crust it seems is **oxygen**, so oxygen.

**Oxygen** is an element with **eight protons** and **eight neutrons** and they form rather **compact objects** in the center of the atom which is the **atomic nucleus** and they are actually packed to each other very, very tightly.
What is the size of a single nuclear proton or neutron?
It is roughly **one fermi**.
So a little gold.
And yet you have **16 balls** of one fermi packed together.
If you think of this setup, you get roughly the size of the nucleus and this is **6 fermi in diameter**.
So we do measure that a **radius of 3 fermi** is what naive calculation tells you.
That is why I multiply by two and I get the diameter of six fermi.

And then **electrons** are another part of the atom and how many of them do we expect?
They occupy **shells** of the atom which is $1s^2 2s^2 2p^4$, where $s$ stands for $s$ orbital circular, $p$ stands for the $p$ orbital which are what is the shape of it?
It is not banana shape, it is what exactly like a **dumbbell shape**.
If you remember that there was the energy of electrons versus the angular momentum in the lower one was $1p$ was $2 1s$ and here.
Right, something like that.

::: callout-important
The **Schrödinger equation** for hydrogen-like atoms:
$$
\left[-\frac{\hbar^2}{2m}\nabla^2 - \frac{Ze^2}{4\pi\epsilon_0 r}\right]\psi(\mathbf{r}) = E\psi(\mathbf{r})
$$
This describes the quantum mechanical behavior of electrons in atomic orbitals and determines their wavefunctions and energy levels.
:::
Then the **wave function** of the electron of $1s$ orbital is something like $e^{-r/a_0}$ where $a_0$ is the **Bohr radius** and you already get the scale.
So the **size of the atom** is given by the **Bohr radius**.
This you find by solving the **Schrödinger equation** of moving of electron bound in the electromagnetic field of the core.

For the scale $a_0$ is equal to **50 picometers** I think 59, 59,000 femtometers.
This is **60 picometers** and this thing would be of order 50,000.

Wait a second, does not the **charge of the nucleus** affect the radius?
Of course it does.
In fact it just scales.
If you have a $Z$ equal to 8 here, then you are going to find **8 times smaller numbers**.
However, further electrons from the orbital they get **screened** by the internal electrons, they feel less charge and that is why you have **outer shells**, I mean of roughly several hundred picometers.
So I have a clear estimation of 100.

And again, to imagine that I was comparing this to our **solar system** and let me sketch it here.
Here is Earth.
If I compare the radius of the nuclei to the orbital shells and compare to the radius of the sun versus the orbital of the Earth I get that I have to scale the sun by a factor of 150 so it makes them smaller and then it matches the distances in the atom roughly.
This is so that you have scales in mind, scaled some sizes.

The **average radius** for $1s$ is equal to $\frac{3}{2}a_0$.
The average radius for the $2s$ is equal to $6a_0$ and then the average radius for the $2p$.
When this number is roughly taken and divided by **effective charge**, $2s$ is $6a_0$ and then divide by effective charge of roughly probably it is to be started with eight.
We get some screening.
So it is probably four, minus two six.
So we get roughly $a_0$.
That is why $a_0$ is taken is giving us the radius and then roughly where the hundred picometers come from.

## Standard Model Overview

All right, **Standard Model** then questions here.
**Particle physics** has the most accurate and precise theory that describes unfortunately everything that we have observed so far which is the **Standard Model**.
It is so accurate that for **10 years** now we have been trying to find any single deviation by colliding particles at **CERN** and elsewhere from predictions of the Standard Model.
So far we do not find it, it is very nice and accurate.

There are some **problems with the Standard Model** which we will probably touch on at the large scale.
When we think of the evolution of the universe, there are also questions of the **naturalness** of the certain couplings, that is certain parameters have been measured and we know accurately in the Standard Model.
But it is unclear where they come from, why they are like this.

Roughly the Standard Model you can think of is **electroweak sector** times **QCD**.
The fact that Standard Model is such a good theory and it works so well does not mean that we understand it fully.
That particularly refers to the **quantum chromodynamics**.
The interaction that describes **strong interaction**.
Everything that we talk about in hadron physics course is governed by **strong interaction**.

**Quantum chromodynamics** is the theory of the **strong interaction**, theory of the **color charge**.
This is the theory that works very well, for phenomena physics, but it is such a complicated theory that until recently direct predictions from the sort of basic equations of quantum chromodynamics to the real world observables were not possible.

The reason that we will discuss later in the lecture is the fact that **fundamental interaction** describes interactions between its fundamental building blocks, **quarks and gluons**.
After that the theory turns into something different, where there are particles with the **non-trivial structure** and not fundamental particles of the theory starts interacting.
Essentially **hadron physics** is not so much about level of the quark and gluons, but what this fundamental theory implies.

For the form in which the theory manifests itself, the **hadrons** manifest themselves as **color neutral objects**, in the objects where the charge that is carried by the theory is **confined**.
We will in this course, in the scope of this course, we will try to understand the relation of the **fundamental part** to sort of **effective interaction** that appears between hadrons.

Right.
To match to what you prefer already to manage this picture of the standard model being two parts, I think it is worth expanding still.
The **electroweak sector** and the **leptonic sector** contains only three parts: **electromagnetic interaction**, **weak interaction** and **mass energy sector**.

Let us quickly probably have a repetition of that.
Quickly write down the particles.
Write down the particle symbol.

**Standard Model Particle Classification:**

- **Higgs**: Belongs to the Higgs sector
- **$W$ boson**: From the weak sector
- **$Z$ boson**: Belongs to weak sector
- **Photon**: Belongs to electromagnetic sector
- **Top quark**: Strong interaction (QCD)
- **Charm quark**: Strong interaction (QCD)

These are the two **force carriers** of the weak sector.
So they are carriers of the charge in the weak sector.
Which sector would it belong?
Weak interaction plus electromagnetic.
Electroweak.
Then maybe switch finally some particles.

These are called **quarks**.
These are **elementary particles** that make strong interactions so this classification is a little bit vague because we will mostly talk about quarks.
Electroweak talks about **leptons**, electromagnetic has **photons** and weak interaction has $W$, $Z$ bosons and Higgs as a separate field however, as soon as the particle has a **charge** of certain type it can interact with the carriers of the charge in a certain way so things worth describing what charge?

Let us write them all down.
Think that is most important if you forgot the charge of particle.
Should we mention a diagram?
Yes, it is actually and well would have been better to put it first but I think we will get to the discussion of that if you forgot the charge just draw that up down, charm strange, top bottom this diagram and then tells you already a lot so the quarks are organized in **generations** first generation, second generation, third generation and they are organized in the two rows of top quarks and bottom quarks and depending on the location the only thing that matters for the charges is the either top row or bottom row so the top row electric charge of $+2/3$ plus electric charge of $-1/3$ plus $+2/3$ minus $1/3$ and then the weak charge for the upper one will be $+1/2$ weak charge for the lower one will be $-1/2$.

Let us look at the chart **Quark** it has a charge of $+2/3$ and then has the weak charge $+1/2$ as soon as a particle has a charge of certain type it can **couple** to the carrier of the charge it actually has to be other sector that is relevant for this charge has to be considered so the quarks are the most **diverse particles** in the standard model because they couple to all charges they couple to the **electromagnetic charge** they couple to the **weak charge** and then also have **strong charge**.

Let us take **up quark** can it interact with the light that comes out of the window?
Yes it can because it has an **electric charge** can it actually interact with the $Z$ boson and $W$?
Yes it can because it has a **weak charge** and can it interact with the **gluons** carriers of the strong interaction?
Yes, because it has a **strong charge** which in fact we called **color** that is because it is colored.

I do not know if **color charge** and **strong charge** are the same thing.
Like electrons could be positive or negative, the color charge could be positive or negative but also we use letters **red, green and blue** for the color charge.
In the same way **anti-red, anti-green and anti-blue** are the three charges that the antiparticle can have.
You will quickly get used to this language: strong charge as color charge.
In the course of the physics consideration we will be talking about the **strong interaction**, which is also **color interaction**.

::: callout-tip
Remember that **quarks** are unique in coupling to all fundamental forces: electromagnetic, weak, and strong interactions. Their color charge comes in three types (red, green, blue) and determines their strong interactions via gluon exchange.
:::
All right.
And then perhaps worse, squaring the carriers of the...
When we say **interaction**, it is interaction of the object with the **field**.
The fields are represented by these **carriers of the force** which are $W$ and $Z$ for the **weak interaction**, **photons** for **electromagnetic interaction** and **gluons** for the **strong interaction**.

We are reaching...
So we discussed **standard model composition** and we are reaching **unification**.
The standard framework in the field theory to describe the fields and the interaction between particles and carriers is the **field theory**, which starts with the **Lagrangian**, an expression that describes interaction in a very condensed line.

Here I have an example.
You might remember the **Lagrangian mechanics** from your first second semester where the entire motion of the system was condensed down to a single equation.
This was **Lagrange equation**.
There is the **kinetic term**, there is a **potential term**, and once you subtract them you get a certain expression.
This expression represents the **energy of the system**.
So kinetic minus potential in that case, and this is an **equation of motion**.

What happens with the system in the next moment, starting from the initial state, is described by an equation that can be derived from the Lagrangian.
So what you do, you differentiate the Lagrangian by the dot by the velocity.
Then you subtract the term that differentiates Lagrangian by the coordinate.
In that case one that is a system where the point can move here and it creates slides without friction.
Then also we have a pendulum and there is another mass here.
The equation of motion is a **differential equation**.
You find this equation by applying a classical classical equivalent of this equation.



### Indices and Gauge Symmetry in Lagrangian Construction

I will now clarify this equation, because this is the one we will use for the fields.

Let me refresh your memory on this.

I start with **QED (quantum electrodynamics)** — this is how light interacts with anything that has a charge.

It's relevant for us for two main reasons:

1. Our quarks have charge, so they interact with photons.
2. The Lagrangian for QED is much simpler than for QCD (quantum chromodynamics).

Let's use this opportunity to understand all the symbols, and then we'll proceed to QCD later.

The equation looks complicated, but once you understand the general structure, you don't need to look it up to write it down.

The **QED Lagrangian density** is:

$$ \mathcal{L}_{\text{QED}} = -\frac{1}{4}F_{\mu\nu}F^{\mu\nu} + \bar{\psi}(i\gamma^\mu D_\mu - m)\psi $$

What this says is that the Lagrangian is a function of two fundamental fields:

- $\psi$ — the field of an electron, muon, or quark (anything with charge)
- $A$ — the photon field

So, $\psi$ is a **fermion field**, and $A$ is the **photon field**.

The Lagrangian is a **scalar quantity** — not a vector or matrix, but a number once evaluated at any point.

::: callout-note
A scalar quantity is achieved by contracting indices. Every index introduces a dimension, and you only get a scalar when all indices match. We use **Einstein notation**, where repeated indices imply summation.
:::
We have $\mu$ and $\nu$ — these are **Lorentz indices** living in 4 dimensions (3 spatial + 1 time). They must be contracted.

What I'm skipping in the equation is the summation over $\mu$ and $\nu$ — they each appear twice.

Now, $F_{\mu\nu}$ is actually a **matrix**. Since $\mu$ and $\nu$ are 4-dimensional, $F_{\mu\nu}$ is a $4 \times 4$ matrix.

You don't multiply matrices in the usual way here — you multiply them component-wise. Each component of the matrix is multiplied by itself, and then you take the trace or sum all elements.

The components of the **electromagnetic field strength tensor** are defined as:

$$ F_{\mu\nu} = \partial_\mu A_\nu - \partial_\nu A_\mu $$

Here, $\partial_\mu$ is the derivative in time and space — essentially $\partial/\partial x^\mu$.

If it were just $\mu$ contracted with $\mu$, it would be simple. But here, $\gamma^\mu$ is also a matrix — in fact, it's four matrices.

How do we get a scalar quantity? There's another set of indices that I suppressed — the **spinor indices**.

Let me bring them out explicitly: $\tau$ and $\rho$ — these live in **spin space**.

Where does this 4-dimensionality come from? It comes from the fact that particles are not scalars — they have **spin**.

So $\tau$ and $\rho$ are dimensions of spin. That's why the fermion field $\psi$ has four components.

These are **matrix indices**, not Lorentz indices. For matrix indices, we don't distinguish covariant and contravariant — we just sum.

Something still looks fishy in this Lagrangian because I'm adding matrices.

We agree that $\gamma^\mu$ are four matrices, and $D_\mu$ is a vector, so we can contract them to get a matrix here. But then I'm subtracting a scalar — that doesn't work.

What's missing is the **diagonal matrix**.

Let me clarify: $\psi$ is a **four-component spinor**. $\bar{\psi}$ is not exactly a four-component spinor — it's a row vector.

What we do is take the conjugate transpose (dagger), then multiply by the $\gamma$ matrix from the left so it remains a row of numbers. Then you're ready to contract this with whatever matrix is here.

::: callout-important
The covariant derivative in QED is:
$$ D_\mu = \partial_\mu - ieA_\mu $$
This ensures local gauge invariance and describes how fermions couple to photons.
:::
One of the exercises is to see the same structure — what are the objects in terms of dimensions — for the **QCD Lagrangian**, which I'll write next. Once you do it once, it becomes super clear.

Let's do QCD now — it's not too bad.

The exercise says: recover the indices, the range, the number of terms. You introduce the blue one because every index is $N$.

So $F^a_{\mu\nu}$ — no, then $U^a_\nu - D^a_\mu$ — $A$ is contracted, okay, besides gluon.

That's a really good exercise to write down. It's super logical.

It's actually the same equation as here, but with more indices because there are more dimensions.

Let me check if I forgot $G$ in front of the term $g_s$ — exactly, there's another $G$.

Now let's figure out the dimensionality of the objects quickly.

There's this new object $\lambda$ that stands here. These are three-dimensional — that's a good starting point to think about dimensions.

So $IJ$ is here — these are $2 \times 2$ matrices. So $IJ$ must be here, must be here this one.

Then they come — you contract over $A$. So this has a $\mu$ and also $ij$. These are still...

Now we go here — $IJ$ stays $I$, $J$, $I$, $J$. Here is the trace in these $IJ$ dimensions.

When you commute two matrices, you get a matrix — it's multiplication minus subtracted multiplication. Then this is...

Overall, this is a matrix in $\mu$ and $\nu$ ($2 \times 2$), but also in $ij$ where $I$ is an index of 3 and $j$ is an index of 3.

I'll try to make more sense of this equation in a moment. As soon as I think all indices have to be introduced, I really care that you understand what equations are right, at least in terms of mathematical structure.

::: callout-tip
The **QCD Lagrangian density** is:
$$ \mathcal{L}_{\text{QCD}} = -\frac{1}{2}\mathrm{Tr}(G_{\mu\nu}G^{\mu\nu}) + \sum_f \bar{\psi}_f(i\gamma^\mu D_\mu - m_f)\psi_f $$
And the **QCD field strength tensor** is:
$$ G_{\mu\nu}^a = \partial_\mu A_\nu^a - \partial_\nu A_\mu^a + g_s f^{abc}A_\mu^b A_\nu^c $$
The additional term arises from the non-commutative nature of SU(3), leading to gluon self-interactions.
:::
Definitely everyone is capable of tracing this. The $F$ traces the flavors — $F$ numbers: quarks $U$, $D$, $S$, $C$, $T$, $B$. We have six coordinates, so the index $F$ goes over all six possibilities.

What else? Spinors in this case have four dimensions, and now there's an extra three for color. The index $I$ here traces the **color charge**.

The only thing I don't track is the spinor indices. For the QED Lagrangian, we agreed there's something related to the spin projection of the particle — that's another $\tau\rho$ indices. We don't put it here; otherwise it's too complicated.

If you think of this field, it has:

- A flavor (let's fix to $U$ quark)
- A color (let's fix to red)
- Another four which are spinors (spin projections)

The last thing to say about this expression is that once you know the Lagrangian, you can get to the **equations of motion** by applying:

$$ \frac{\partial\mathcal{L}}{\partial(\partial_\mu\phi)} - \frac{\partial\mathcal{L}}{\partial\phi} = 0 $$

How clear is this? Let's see: $\partial\mathcal{L}/\partial(\text{derivative over field})$.

I think it's easier to look at this expression where such a partial derivative would be non-zero. For $\psi$, we can do the same for $A_\mu$ (the gauge field).

$\psi$ only appears in this term. The first derivative for the first term actually equals zero, and the only place where it's non-zero is when you have $D_\mu\psi$.

$D$ has the derivative inside it. If you expand this, you'll have $\bar{\psi}\gamma^\mu D_\mu\psi$. When you differentiate, $\bar{\psi}$ remains, and then $\partial\mathcal{L}/\partial\psi$ would be non-zero from the other term here — this term instead of that — and the mass term as well will produce something for the second term.

That way, you get an equation of motion — differential equations describing how the field evolves in time and space.

If we apply this to QED, do you know what the equation is called that describes the motion of a fermion?

This is — remember — what's the equation? It says it changes, but it doesn't have a $\bar{\psi}$ side; it just has $\psi$.

Note: $g$ plus or minus — minus is the same term as here. I think the $D_\mu$ here instead of the short... Yes.

That would be for the... That's a good point for the next.

So the Rancho Kinemic picture — let me ask questions for this point.

We discussed the Lagrangian and equations of motion. Let's discuss **gauge transformation** and **gauge symmetry** — an extremely important concept in field theory.

We'll only touch on this briefly since we're not doing full field theory, but it's really important — you should know where legs grow from.

Something very familiar from quantum mechanics is the **phase ambiguity** of the wave function. We can update the phase, and the absolute square of the wave function won't change because you multiply $\psi$ to $\psi^\dagger$ and the phase drops out — that's fine.

First, we acknowledge that this should be a symmetry of our theory. This should be allowed — to make this gauge, to make this phase transformation.

It's kind of by definition, so this overall phase you don't even have to think about.

The problem appears when you demand your theory to be invariant under changes of phase at **all possible spacetime points** simultaneously with **different phases**.

What if I want to adjust my wave function at every space point? Why is this a problem?

Because in our equation of motion, in our Lagrangian — let me just write the Dirac part:

There's $\bar{\psi}D_\mu\gamma^\mu\psi$ and the same...

What happens is that here I have a term $\partial_\mu\psi$, and this term is going to become $\partial_\mu\psi'$ which is $\partial_\mu$ of $e^{i\alpha(x)}\psi$.

Let me take the derivative:

$$ \partial_\mu(e^{i\alpha(x)}\psi) = e^{i\alpha(x)}\partial_\mu\psi + i(\partial_\mu\alpha)e^{i\alpha(x)}\psi $$

I simply apply it to the second term $\partial_\mu\psi$. When I apply it to the first term, I get $\partial_\mu$ acting on the exponent. The exponent stays, but then I have to take the derivative of the exponent — so there's an extra derivative term.

What happens? Indeed, the same equation won't hold any longer for $\psi'$. It does not transform to the same equation because the derivative yields another term with $\partial_\mu\alpha$.

In fact, it means that **local gauge transformation** is not a symmetry of the free Lagrangian of the free-moving Dirac particle.

You cannot adjust phase independently at different points for a free particle.

In simple words, this means the theory is **incomplete**. It only becomes complete if you consider radiation, photons, and charged particles together.

The way — once you look at the full Lagrangian — I think I get a minus here. That's an exercise you do in a field theory course.

In the first lecture, you update simultaneously the phase of the field $\psi$ and the electromagnetic field:

$$ \psi(x) \rightarrow \psi'(x) = e^{i\alpha(x)}\psi(x) $$
$$ A_\mu(x) \rightarrow A'_\mu(x) = A_\mu(x) - \frac{1}{e}\partial_\mu\alpha(x) $$

Then you see that the additional term that appears in the covariant derivative — the additional term here — will cancel exactly the one you get from the phase.

Then the Lagrangian stays the same with the new updated field $\psi$ and new updated field $A$.

This fact led us to this consideration — led us to the $D_\mu$ term, which is worse.

Actually, writing $D_\mu$ — plus or minus — was it plus before or minus? That's correct.

Actually, from equations of motion, you can see how different fields are coupled to each other.

In our pendulum example, we would see how the pendulum affects the movement of the upper marble. Similarly, from equations of motion, we can see that motion of fermion fields is affected by motion of photons, and photons are affected by fermions.

The way we introduce gauge symmetry tells us exactly how they affect each other — how they interact.

So **gauge symmetry enforces** a certain way how photons and fermions interact with each other. They have to interact with strength $g$.

The structure is very simple. Again, this is a scalar quantity. You can figure out — convince yourself — that it's a scalar quantity.

I guess it comes from this $g$ matrix. $\gamma$ being $4 \times 4$ and then contracting the stuff. These are contracted. We'll find...

That's important. I think it's worth writing down.

But the gauge symmetry tells us how objects interact with each other — that's very important.

Now we'll take this idea and move from QED to QCD.

Before jumping to QCD, where we have to deal with the wave function in three dimensions, let's consider the wave function in the space of two coordinates.

That's the case for the **weak interaction**.

For weak interaction, you have up components and down components. Remember how the weak charge for quarks was $+1/2$ or $-1/2$ — the same range.

Here you have an up field and down field. Remember, it's still a fermion, so they have hidden four spinor components — we don't talk about that.

But in that case, the transformation that updates the phase is somewhat more general.

What we want is that the update that happens here does not change the observable. Our observable will be $\psi^\dagger\psi$.

$g$ or $g$ the matrix that updates the field — $\psi$ is the $2 \times 2$ matrix, and it's **unitary** because observables should not change.

In this case, we're dealing with transformations that are unitary, described by unitary matrices that span the class of what's called a **group** — specifically $U(2)$.

We'll also fix the determinant of this matrix to be 1, and then this $S$ comes from... So for all matrices that have determinant equal to 1 and are unitary, they can be represented as an exponent.

Who has seen the exponent of a matrix before? So if you saw — what is this? Can you tell me what should I write here and then $V$? Well, this is more complicated.

As soon as I put here one, it gets a little bit... We solved it last year, right? I think it's either 1 or $1 - E$ something. So $e$ to 1, 1, 10 gets more complicated.



### Group Theory and Confinement in QCD

Exactly right.
So the approach is to take the exponent of this expression and then perform matrix multiplication.
Here, this term is certainly not zero, and in fact, I'm not entirely sure about it anyway — but you understand what I'm referring to.

This is the **matrix exponential**, and you can represent any element of the SU(2) group using it:

::: callout-important
Any element of the SU(2) group can be expressed as
$$ U = \exp(i \alpha_a \sigma_a) $$
where $\sigma_a$ are the Pauli matrices, and $\alpha_a$ are real parameters.
:::
Here, we are working with a $2 \times 2$ matrix with zero trace.
The determinant condition for special unitary groups implies:

$$ \det(U) = 1 \Rightarrow \operatorname{tr}(\alpha) = 0 $$

In fact, only three matrices span the entire basis of such traceless Hermitian matrices — the **Pauli matrices**.
These are called the **generators** of the group because they generate any group element.

Once we identify these three generators, we can take any three real numbers $\alpha_1, \alpha_2, \alpha_3$, compute the exponential, and obtain an element that spans the entire SU(2) group.
The generator matrices are fixed; you just input the three numbers into a routine (e.g., in Python).

**Why do we fix the determinant to 1?**
Because we are working with SU(2).
In general, U(2) = U(1) × SU(2), where U(1) corresponds to a scalar phase and SU(2) to a non-trivial matrix part.
The scalar phase behaves similarly to the 2D case, but the matrix part introduces interesting structure.

We fix the determinant because SU(2) is one of the standard groups — well-understood and widely used.
If we considered U(2) instead, we would have more generators and greater complexity.
SU(2) is a primary elementary group: we know its number of generators, matrix representations, and properties — making it a nice object to work with.

This factorization approach generalizes.
For example:

- U(3) = U(1) × SU(3)
- We factor out the phase, and what remains is SU(3), which deals with the global update of the wave function components.

This is exactly what appears in **quantum chromodynamics (QCD)**.
When dealing with color charge, we have three components — red, blue, and green — and transformations are described by $3 \times 3$ matrices with an overall phase.
That’s not too complicated; we've discussed this before.

The non-trivial part involves updating fields via $3 \times 3$ matrices with determinant equal to 1.
Again, we relate this to the matrix exponential, where the exponent must be traceless.

The basis of traceless matrices in three dimensions satisfies certain anti-commutation properties.
If we look at the basis:

- In two dimensions (traceless matrices) → 3 generators
- In three dimensions → 8 generators

::: callout-note
For SU(N) groups, the number of independent generators is
$$ N^2 - 1 $$
This counts the gauge bosons in the corresponding gauge theory.
:::
The number of generators is related to the number of charge carriers in the field.
In fact, we identify each generator matrix with the action of the field, as they appear in the **interaction term**.

Every time we attach the field $\psi$ and the interaction field $A$, they come together with the generator matrix.
To connect this back: recall that this discussion originated from computing derivatives and identifying an extra derivative for the phase.
This led to introducing an extended derivative of the field — an interaction term that appears in Feynman diagrams.

When we move to higher dimensions, the same derivative computation will involve the appropriate matrix.
So, for SU(2), $\alpha$ is $2 \times 2$, and it enters here as another matrix.
The generator matrices — $\sigma$ for SU(2), $\lambda$ for SU(3) — penetrate into the **interaction vertex**.

Thus:

- For SU(2): 3 generators → 3 charge carriers: $Z$, $W^+$, $W^-$
- For SU(3): 8 generators → 8 gluons

Unfortunately, we lack the imagination to name all eight gluons individually.
They are identified by their matrices.

In weak interactions, one matrix is diagonal in the space and corresponds roughly to the $Z$ boson.
Similarly, in the gluon field, some are diagonal, and we assign hypercharge to states; others act like $W^\pm$.

You will see the same matrices in homework exercises.
Think of them as eight different gluons — you can name them, and they act differently on the field.
They appear in interaction vertices depending on the gluon flavor interacting with the quark.
This is driven by Pauli-like matrices, making it a valuable exercise to study this interaction term.

How does this become a skewer?
How to contract color charge is a deep question.

Now, let’s briefly discuss **confinement**, and then we'll move to basic equations.

**Confinement** is a property of the theory where the strong interaction strength **grows** with distance.
For electrons and positrons, the interaction decreases with distance, but for quarks, it's the opposite:
the strong interaction governing color charge **increases** as you pull objects apart.
This confines quarks to small scales.

The only way to experience strong interaction is to zoom in to the smallest objects: **mesons** and **baryons**.

- A **meson** is a quark-antiquark pair.
- A **baryon** consists of three quarks.

**Confined** means that strong interaction exists only inside these hadronic "bubbles."
Outside, there is no strong interaction.
If you try to pull a quark out with huge force, eventually the system divides, and new color-neutral confined objects form.

**Color neutral** means having zero net color charge with respect to strong interaction.
If a particle carries color charge, gluons interact with it, and it is not confined.
Thus, matter forms into small, color-neutral bubbles where strong interactions are active inside and inactive outside.

I’m not deriving this here — it's a postulated fact of the theory, supported by experimental evidence.
Confinement plays a vital role in binding and structuring matter as we know it.

However, looking at the Lagrangian, confinement is not immediately obvious:

::: callout-important
The complete QCD Lagrangian is:
$$ \mathcal{L}_{\text{QCD}} = -\frac{1}{2}\mathrm{Tr}(G_{\mu\nu}G^{\mu\nu}) + \bar{\psi}(i\gamma^\mu D_\mu - m)\psi $$
with the gluon field strength tensor:
$$ G_{\mu\nu}^a = \partial_\mu A_\nu^a - \partial_\nu A_\mu^a + g_s f^{abc} A_\mu^b A_\nu^c $$
:::
Here, $G_{\mu\nu}$ includes terms like $G_\nu G_\nu - G_\nu G_\nu + f^{abc} A_\mu^b A_\nu^c$, leading to **3-gluon** and **4-gluon** interaction vertices.
This **gluon self-interaction** is an indication of confinement — though not a proof.

Various field theories exhibit confinement; others do not.
Confinement remains one of the unsolved problems in theoretical physics — there’s even a prize waiting for someone who can explain it fully.

Now, consider the **running coupling** in QCD.
The strong interaction strength $\alpha_s$ depends on the momentum scale $Q$ at which you probe the hadron.

::: callout-note
The QCD running coupling behaves as:
$$ \alpha_s(Q) \sim \frac{1}{\ln(Q/\Lambda_{\text{QCD}})} $$
:::

- At **very high $Q$**: we enter **asymptotic freedom** — coupling is small.
- At **low $Q$** (around GeV or below): we are in the **confinement regime**.

Hadrons live in the low-$Q$ region, where the interaction is very strong.
When quarks exchange gluons at small momentum transfer (below 1 GeV), the coupling becomes large, and perturbation theory breaks down.

Asymptotic freedom, on the other hand, allows perturbative calculations at high energies.
We will discuss asymptotic freedom in more detail later.



### Request for Lecture Transcript

---
I notice you haven't provided the actual nuclear physics lecture transcript that needs to be polished.

Could you please share the specific raw, unedited speech transcription from the lecture that requires editing?

Once you provide the specific text, I'll apply **minimal corrections** while preserving all:

* **Technical content** and explanations
* **Analogies** and teaching examples
* **Original structure** and flow
* **Meaningful content** in its entirety

The editing will focus on removing only:

* **Hesitations** and false starts
* **Repetitive phrasing**
* Correcting single **misspoken words**
* Completing **partial sentences**

::: callout-note
Common nuclear physics formulas that frequently appear in lectures include:

* **Nuclear Binding Energy**: $B(Z,A) = [Zm_p + (A-Z)m_n - m_{\text{nucleus}}]c^2$ - calculates the energy required to disassemble a nucleus
* **Semi-Empirical Mass Formula**: $B(Z,A) = a_V A - a_S A^{2/3} - a_C \frac{Z(Z-1)}{A^{1/3}} - a_A \frac{(A-2Z)^2}{A} + \delta(A,Z)$ - approximates binding energy accounting for volume, surface, Coulomb, asymmetry, and pairing effects
* **Radioactive Decay Law**: $N(t) = N_0 e^{-\lambda t}$ - describes exponential decay of radioactive nuclei

When you provide the actual lecture transcript, I'll integrate the specific formulas being discussed directly into the relevant content sections.
:::
