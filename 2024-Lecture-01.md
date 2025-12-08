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



## Lecture Logistics and Upload Plans

Yes. I will upload the lecture as well. If anything reasonable comes out of it, I will be happy to upload it.

Certainly, what will be uploaded is the lecture content with items that I already have. There will also be references to material.


::: callout-note
This initial segment is purely **logistical** and administrative. No specific physics concepts, variables, or mathematical relationships are being discussed here.
:::

But let's go to logistics in the last 15 minutes.



## The Early Universe: From Symmetry Breaking to Hadronization

So we are living in a universe made of hadronic physics, but it was not always the case.

I like thinking of the evolution of the universe on a time scale, with the origin of the universe where everything started. There was a Big Bang first, and then several epochs followed. It started with the Planck epoch, then there was the electroweak epoch, and then the quark epoch.

#### The Electroweak Epoch and Symmetry Breaking

What has been happening during these epochs is the part of the physics that we go through in the courses.

Let me start with the electroweak epoch. This is where the Higgs potential
  $$V(\phi) = \mu^2 |\phi|^2 + \lambda |\phi|^4$$  
—that is the field giving masses to particles and making sure that our proton doesn't decay and our life can exist—gets a condensate.

The electroweak phase is where the transition happens. The entire space is filled now with a condensate, a fixed, non-moving condensate of the Higgs field, through which particles are slowed down; they get inertia and they obtain mass. That's something known as the **Higgs mechanism**.

This process of the potential evolving is called **spontaneous symmetry breaking**, when one of the minima is picked. That's how I like thinking about the electroweak stage.

So what happens then? Particles have masses. The universe starts evolving, and at some point we arrive at the quark epoch.

#### The Quark Epoch and Quark-Gluon Plasma

At this stage, the universe is filled with a **quark-gluon plasma**. Essentially, quarks and gluons are making an unstructured soup of objects. There is nothing about structure formation yet. This is rather quarks disturbing—there is no yet scale that we are going to talk about.

Quarks and gluons are together, and the universe is extremely hot. From that moment it starts cooling down. At some point the temperature is low enough that this medium starts separating, and we arrive at the quantum chromodynamics (QCD) epoch.


::: callout-note
The transition to a quark-gluon plasma occurs when the temperature exceeds the QCD scale:  $T_{\text{QGP}} \sim \Lambda_{\text{QCD}} \approx 150 \text{–} 200 \text{ MeV}$ . In the early universe, the age during this epoch can be estimated as  $t \sim M_{\text{Pl}} / T^2$ , which for  $T \sim 150 \text{ MeV}$  gives  $t \sim 10^{-6} \text{ s}$ .
:::

This hot medium starts forming small volumes where the interactions of quarks and gluons are confined to a small scale. You need two years to learn this in detail. This comes in particle physics, introductory nuclear physics, and a specialized course on QCD at finite temperature, since it's a heated medium and there are different laws applied.

#### The Hadronic Universe and Confinement

**Hadrons** are what we are going to focus on now. But if you think of how quickly this all happened, you're going to be slightly surprised.

The timeline is incredibly brief:

*    $10^{-36}$  seconds for the Planck epoch
*    $10^{-12}$  seconds for the electroweak epoch
*    $10^{-6}$  seconds for the QCD transition
*   Then 1 second.

Just imagine there was nothing, and then the sound reached you on the back. When I clap, if you look at my palms, the time span between when I close them and you hear the sound is roughly 10 milliseconds. By that time we had already passed through all the stages and everything hadronized. That's how quickly the universe evolved.

In that scale, the rest of the interval to the 13 billion years—the age of our universe—has been other interesting physics, but not as intense as this from the perspective of our hadron physics.

We can be talking about hadrons in the sense that we will be talking about the strong interaction. The hadrons are objects where the strong interactions are confined to the small scale of a few fermi:
  $$R_{\text{hadron}} \sim 1 / \Lambda_{\text{QCD}} \approx 1 \text{ fm} = 10^{-15} \text{ m}.$$  

There is essentially nothing around. There is a small chunk of volume where the quarks and gluons live. They interact with each other. There are large fractions of empty space.

One fermi is  $10^{-15}$  meters. It's difficult to imagine this scale, but this number can help you. It is a smaller scale we have, and the smallest scale where we actually can separate things.

The strong interaction is confined in this small scale and it stays there. By colliding hadrons we learned how to study internal structure and how to separate the subject. But there is no natural scale smaller than that.



## The Emptiness of Matter and the Color Charge

So concerning the **empty space** in an atom, I wanted to sketch one of the most common elements on Earth. From the periodic table, what is the most common element? I think it's **oxygen**.

A neutral oxygen atom has eight protons and eight neutrons. Oxygen has many isotopes; one common one is oxygen-16, while oxygen-18 has eight protons and ten neutrons. The atom is neutral, so there must be electrons compensating the charge of the protons. The protons give a charge of  $+8e$ , and there are eight electrons in the configuration  $1s^2 2s^2 2p^4$ .


::: callout-note
This notation,  $1s^2 2s^2 2p^4$ , is the **ground-state electron configuration** for a neutral oxygen atom (atomic number  $Z = 8$ ). It describes how its 8 electrons are distributed: 2 in the  $1s$  orbital, 2 in the  $2s$  orbital, and 4 in the  $2p$  orbitals.
:::

The atom's electrical neutrality is expressed by the condition  $q_{\text{atom}} = Z e + (-e) \sum_{i=1}^{Z} 1 = 0$ . For oxygen ( $Z=8$ ), this is  $+8e - 8e = 0$ .

To understand the scale of emptiness, let's look at the nucleus. There is a center where protons and neutrons are packed closely together. Knowing the scale of a hadron, you can guess the core's scale. The size of the nucleus scales as:

  $$R = R_0 A^{1/3}$$  

Here,  $R_0 \approx 1.2 \, \text{fm}$  (femtometers) is a constant, and  $A$  is the **mass number** (protons + neutrons). This **nuclear radius formula** arises because nuclear volume is proportional to  $A$ , assuming nucleons are closely packed with nearly constant density. For oxygen-16 ( $A = 16$ ), the nuclear radius is roughly  $R \approx 1.2 \times 16^{1/3} \, \text{fm} \approx 3 \, \text{fm}$ .

But electrons are completely different. Their wave function has a size about **3 orders of magnitude bigger**. The atomic radius is roughly **50 picometers** ( $5 \times 10^{-11} \, \text{m}$ ).

Now consider this scale difference:

  $$\frac{R_{\text{atom}}}{R_{\text{nucleus}}} \approx \frac{50 \times 10^{-12} \, \text{m}}{3 \times 10^{-15} \, \text{m}} \sim 10^4$$  

This **atomic vs. nuclear scale ratio**—about **10,000**—shows how empty an atom is. There is a very small core, and around it is a vast space where the electrons exist. In that space, there is **no strong interaction**.

The second item is what we know as the **fundamental hardware**: the **Standard Model**. This is the theory in particle physics that describes most known interactions. Setting aside neutrinos—where there are open questions—it describes everything well.

The part responsible for **strong interactions** is **Quantum Chromodynamics (QCD)**. The participants are **quarks and gluons**. These are the only particles in the Standard Model that carry **color charge**, which is the charge needed to interact via the strong force.

This is similar to electrodynamics: only objects that are not neutral can interact. However, in strong interactions, the relevant charge is a **different type**—it's not electric charge, it's **color charge**. We could have invented a different word, but "color charge" is the term.

Think of this charge as analogous to the electric charge of an electron or muon. But it's a **different quantum number**; they are independent. This is the **charge independence principle** in the Standard Model:

  $$Q_{\text{em}} \neq Q_{\text{color}}$$  

*   A particle with electric charge does not have to have color charge (e.g., an electron).
*   A particle with color charge does not have to have electric charge (e.g., a gluon).

We usually measure electric charge in elementary units: the electron is  $-1$ , the positron is  $+1$ . For color charge, we don't use simple units. Instead, we describe quarks and gluons by introducing their **color wave function**. Once they have a non-trivial color wave function, they are color-charged.



## The Origin of Mass and the Constituent Quark Model

To finish with the Standard Model, I want to mention that these are the only particles that have color charge.

Let me list other particles of the Standard Model: the electron and muon. The electron, muon, and tau lepton are kind of the same, but they have different masses. The electron is the one that is orbiting or living and compensating the charge of protons and neutrons in the nuclei. The muon is the heavier brother of the electron. The tau is a much heavier sister of the electron. All of them can be in both configurations.

But let's complete the list. What else is in the Standard Model? Photons and neutrinos. That's all. I just draw them all here to say that they don't have color charge. They don't have color charge, so they don't interact with the quarks and are not influenced by the strong force. We will see them all the time, but they don't participate in the strong interaction.

As I mentioned, if you don't have a color charge, you don't interact strongly. But if you have a color charge, you must interact strongly, though it doesn't mean you don't interact in other ways. All of these particles have different quantum numbers. Essentially, they are electrically charged. The electric charge of protons and neutrons is not zero for quarks.

There are six quarks in the Standard Model. That's what we see: six quarks exist. They are different, but they have common properties. They are separated into groups by their electric charge.

*   Those in the upper row have a positive charge of  $Q = +\frac{2}{3}e$ .
*   The lower row has an electric charge of  $Q = -\frac{1}{3}e$ .

They also split on the horizontal axis into three groups. These are **generations**: the first generation, second generation, and third generation. The higher the generation you go, the more difficult the particles are to produce, as the objects become heavier. This is why most of the matter we see around us is made of the first generation.

We produce **strangeness** rather easily once we collide particles. Cosmic rays have a lot of strange particle production, and less of the **charm quark**. The 'C' stands for charm. However, it also appears in cosmic rays. There is actually a hot discussion these days on whether the strange quark and the interaction of strange quarks is relevant for the equation of state when stars evolve.

We want to describe the maximal size of a neutron star. This maximal size is driven by the equation of state. Essentially, it depends on how the atoms are packed inside the neutron star. If there are clusters where strange particles appear, it changes the equation of state. This then changes the observable characteristics. Over the last five years, more discussion has evolved on the equation of state and the relevance of the strange quark there.

The charm quark is mostly studied in collisions at high energy, because you need a lot of energy to produce charm and **bottom quarks**. The **top quark** is relevant for Higgs physics. That's the domain where these two are studied. The **up** and **down quarks** are called **light quarks**. The strange quark, charm quark, and bottom quark are studied a lot in colliders to see CP violation and in the search for precision physics.

The top quark measures very well the Standard Model quantities related to Higgs physics and electroweak interactions. We'll be focusing on the five lighter flavors and will not talk much about the top quark because its lifetime is so short that it decays before it can form hadrons. You won't find any hadrons that contain a top quark. But all of these other quarks can form hadrons.

Most of the matter we know and that is abundantly present is of two types. We are going to talk about pions.

Welcome to a lecture dedicated to the **constituent quark model**. Here is a sketch of the simple pictures that classify hadrons. As you see, there are two types: **mesons** and **baryons**. This model describes hadrons as compositions of a quark-antiquark pair or three quarks.

You may ask about gluons. I would like to come back to this picture. There is something very beautiful happening around the chiral symmetry breaking scale. Essentially, another condensation process occurs. When hadronization happens, as quarks and gluons from the soup start to confine themselves, the gluon field condenses as well.

What happens is that the gluon field, similar to the Higgs field, forms a medium in which the quarks are moving. This medium is colored, and the quarks, by interacting with it, acquire energy. Effectively, gluons are now dressing the quarks, making them massive. The quarks we draw in the constituent picture are different from the Standard Model quarks; they are quarks dressed by gluons.


::: callout-note
In the constituent quark model, quarks are dressed by gluons and acquire effective masses much larger than their bare masses. For light quarks:
  $$m_u^{\text{const}} \approx m_d^{\text{const}} \approx \frac{m_p}{3} \approx 313 \text{ MeV}$$  
This is compared to their bare masses from the Higgs mechanism, which are  $m_u^{\text{bare}} \approx m_d^{\text{bare}} \sim 3 \text{ MeV}$ .
:::

There is a nice way of thinking about this. Look at the masses of the light quarks. The mass of the u quark and d quark is on the order of  $3 \text{ MeV}$ . We will be using **natural units** throughout the course, where the speed of light  $c = 1$  and  $\hbar = 1$ .

If you look at the other way of expressing  $\hbar$ , it is a quantity with units:  $\hbar = 6.6 \times 10^{-34} \text{ J} \cdot \text{s}$ , which is also equal to  $6.6 \times 10^{-22} \text{ MeV} \cdot \text{s}$ . In natural units, we set  $\hbar = 1$ . This immediately tells you that to achieve that, you need to be able to translate meters to seconds.

From that, you can take this second and move it to the other side:  $1 \text{ s} = 3 \times 10^8 \text{ m}$ . Meters are the same as seconds. Also from that, you can realize that in these units,  $1 \text{ s}^{-1} = 6.6 \times 10^{-22} \text{ MeV}$ . You can also relate joule and second. It's important to realize these are not just relations between numbers, but also units.

This is the way you translate any meters to seconds and any second to mega electron volts. That's the way to translate electron volts to seconds, and also the way to translate kilograms, because a joule can be expressed in kilograms. In these natural units,  $\text{MeV}$  is the unit of mass, energy, and inverse distance. We will be using eV, MeV, and GeV for everything.

Just to have a scale, in kilograms it's  $10^{-30}$ , which is a huge number. But what is the mass of the proton? The proton, which in the constituent model is made of u and d quarks, has a mass of roughly  $1 \text{ GeV}$ . To be accurate, the proton mass is around  $1.67 \times 10^{-27} \text{ kg}$ . 




![The diagram shows the contribution of different components to the visible mass of matter. Only about one percent comes from the Higgs field, which provides intrinsic fermion masses through Yukawa couplings, while the remaining ninety-nine percent arises from gluon interactions inside nucleons, where the QCD binding energy and quantum fluctuations generate the bulk of the nucleon mass.](2024-Lecture-01-images/fig1.png){#fig-fg1}






Let's do a comparison. The Higgs mechanism involves making the condensate that gives all particles their masses. The mass that quarks get from the Higgs is a few MeV. Then another phenomenon happens. Essentially, energy gets stored in the strong quark interaction.

At the place where the strong interaction is happening, there is a large energy density of the gluon condensate. This large energy accounts for about 99% of the proton mass. If you think of the origin of mass, which was discussed a lot when the Higgs was discovered, the Higgs explains only a small part. It is less than 1% of the proton mass.

I calculated the total mass. I summed the three quark masses and divided by three as well. It's about 1%. If you think like I am around 70 kilos, what are these 70 kilos? Is it me moving through the Higgs field? It is actually gluons and quarks held together by the strong interaction. So, 69 point something kilos of me is due to strong gluon interactions.



## Foundations of Quantum Field Theory

Now let’s move to a bit more of the equations and discuss quantum dynamics.
**Quantum chromodynamics** is the theory of strong interactions. **Quantum electrodynamics** is the theory of electromagnetic interactions. I will put both of them because there is a lot in common between these two.

I think I wrote this already. The framework that we use, starting from classical mechanics, and it turned out to be the most successful, is the **Lagrangian approach**. Similar to a mechanical system, in order to describe the quantum system, we will be using the Lagrangian and Lagrange equations.

Let me start with **QED**. So what is QED? QED essentially is the electromagnetic field. If someone asks you about equations in QED, the first thing that comes to mind is the **Maxwell equations**. This is the equation of motion for the electric field.

The index  $\mu$  here indicates that it’s a **vector field**. It means under boosts and rotations, it transforms as a vector. As the vector that we are used to, like the particle is moving in certain directions, its momentum is also a vector. The same thing is for this field.

Once you see the  $\mu$  index, you know how to boost and rotate this object because it belongs to the vector representation of the Lorentz group. If someone asks you, “I give you the vector,” the zero component is the time component of the four-vector, and then the vector component. It’s the same as the regular four-vectors for momentum: the zero component is the energy and then the spatial components are the momentum. The same for the vector field.

Again, you see the index  $\mu$  and then you know what it is. If I give you a four-vector for the vector field and ask you how it looks if I rotate it by 90 degrees, you know what to do. You remember the rotation matrix: 1, 0, cosine, sine. You just apply this to the vector and that’s it. You know how to boost this field as well, because it’s a vector field. There is a gamma, beta, gamma matrix that you apply and then you have it.

This might sound familiar already. This was in quantum mechanics and many other courses. They will be extremely useful in other field theory courses. But in our course we’ll be mostly operating with a different way. We barely will be using the four-vector. We barely will be using this, essentially four-vectors and tensor contractions.

Another thing to note is that here I am explicitly using **Einstein notation** and explicitly summing over repeated indices.  $\mu$  here,  $\mu$  there. They are repeated. That means if I were accurate, I should have written here a sum, and then have  $A_\mu$  from 0 to 3, and sum all of the components. The  $\nu$  is a repeated index again, sum.

If I look at this, how many terms should I sum? If I put a sum here, how many terms component-wise? If I expand this, how long will it be? It’s a 4 times 4, right? It’s 16 terms. If I also put  $F_{\mu\nu}$  here, and then have these two fields, for both of them there will be an extra four because it’s a two here, two there. If you multiply them, they will be 16 times 4, which is 64 terms.

The equation of motion for this Lagrangian is obtained using the **Lagrange equation**. You might remember this from classical mechanics where we had dots and the first one was the time derivative, the second one was the derivative of the field. We treat our Lagrangian as a function of the fields and their derivatives.

We feel the derivatives and the fields as the different objects and we first differentiate by the derivatives and second we differentiate by the field variables. In that case  $X$  is a  $\mu$ . There should be a sum over  $\mu$ . And then the  $X$  is the  $A_\rho$ . It’s another Lorentz index.

If I take this Lagrangian and I use the Lagrange equation, I get the equation of motion, how the field is moving through space. We know that it’s Maxwell equations. So the equation of motion gives Maxwell and that is important.

Now let me introduce the second part of the topic. This was the **gauge field**. It’s called  $A_\mu$ . This is a little bit less intuitive concept that you might have seen before. But we will need it as well so that there are degrees of freedom that are not fixed for the photons, for the electromagnetic field.

There is an arbitrary gauge that we fix, that we can explore. This gauge is manifested in the fact that we can take  $A_\mu$  and move it to other  $A'_\mu$  which is  $A_\mu - \partial_\mu \chi$ . So  $\chi$  is a scalar field. Essentially I’m taking all of my fields and I shift them by a derivative.

Under this transformation,  $F_{\mu\nu}$  goes to  $F'_{\mu\nu}$ . In order to find what it goes to, we have to put it here. This  $A$  becomes  $A'$  and then you have derivatives. Since this is a function of the space coordinate, you have to differentiate this term as well. You have to do this for the second term.

It turns out, and it’s easy to see, that the minus sign kills the extra term. So  $F'_{\mu\nu} = F_{\mu\nu}$ . Then our Lagrangian is invariant. This is the **symmetry of the Lagrangian under gauge transformation**.

If you do the exercise of the variation of the Lagrangian equations and the Maxwell Lagrangian trying to get the Maxwell equations, you won’t get immediately the known Maxwell equations, you will get them up to a gauge. So we see what this derivative does. It picks one of the terms.

If you differentiate  $F_{\mu\nu}$  by the derivative, you will get  $\partial_\rho A_\nu - \partial_\nu A_\rho$  and then it will be left over. Maxwell equation, as we know, is  $\partial_\mu \partial^\mu A_\nu = 0$ . But you will get an extra term that is easy to kill.

If you know that gauge invariance is present and in order to argue that this extra term vanishes, you can say that I can choose in all of my space such a function  $\chi$  that kills the extra term. By fixing the gauge this way you get the common Maxwell equations that we have in electromagnetics.

Fine, we now introduce the **fermion fields**. As we do in electrodynamics, we have our leptons and the  $\psi$ , where the  $\bar{\psi}$  is  $\psi^\dagger \gamma^0$ . Actually the  $\psi$  is the four-component spinor which is built by steering degrees.

Every Lagrangian is a **scalar quantity**. It means there are no indices. It’s not a vector, not a matrix. Every Lagrangian is sort of a function, a number, and it’s made of objects of different dimensionality. The fermion field, a fermion is a particle that has spin one half.

Since we have to deal with the particle and antiparticle components in the same vector, we have four components in the bispinor here. These are these four components. Don’t mix them up with a four-vector. It’s not legal to say  $\mu$  because  $\mu$  would indicate that this is an object that transforms under boosts and rotations the same way as the four-momentum. But that’s not true.

This field transforms differently. It still has four components, but it’s a different object. It’s called a **bispinor**, it’s not a four-vector.

In order to make a scalar quantity out of this vector, we do this transformation. We take it, we transpose it so it becomes a row. We multiply by the first matrix on the left. This is the gamma matrix. We look at this; it is a matrix as well, because the gamma is a four-by-four matrix. The mass is a scalar. But here there is a four-dimensional identity matrix in order to have the correct dimensions.

Essentially, that way you form the Lagrangian. Then you take the Lagrange equations and you find out that the equation of motion is the **Dirac equation**. We like very much condensed notation. Often this contraction, these gamma matrices, is noted with a slashed symbol, a slash through the matrices.

So this is actually often written as: the equation of motion is  $(i \not{\partial} - m) \psi = 0$ , the Dirac equation.


::: callout-note
**Key formulas from this section:**

*   **Maxwell Lagrangian Density:**  $\mathcal{L}_{\text{EM}} = -\frac{1}{4} F_{\mu\nu} F^{\mu\nu}$ , where  $F_{\mu\nu} = \partial_\mu A_\nu - \partial_\nu A_\mu$ .
*   **Gauge Transformation:**  $A_\mu \rightarrow A'_\mu = A_\mu - \partial_\mu \chi$ , leaving  $F_{\mu\nu}$  invariant.
*   **QED Lagrangian with Fermions:**  $\mathcal{L}_{\text{QED}} = \bar{\psi} (i \gamma^\mu \partial_\mu - m) \psi - e \bar{\psi} \gamma^\mu \psi A_\mu - \frac{1}{4} F_{\mu\nu} F^{\mu\nu}$ .
*   **Dirac Equation:**  $(i \gamma^\mu \partial_\mu - m) \psi = 0$  or, in slash notation,  $(i \not{\partial} - m) \psi = 0$ .
:::



## Gauge Invariance and the Structure of Interactions

And finally we arrive at an important aspect of field theory: **introducing interactions**.
So far, we have dealt with a theory that has **no interactions**. Photons have been moving by themselves without interacting with charge or anything else. The fermions here are also free-moving particles. Essentially, a particle starts moving, doesn't see anything, and just propagates. It is a free particle with no interaction. 




![This figure represents a Feynman diagram illustrating the coupling of a fermionic field \ $\psi(x)\$  to a gauge field \ $A\_\mu\$ . The interaction occurs via the electromagnetic current    $$j^\mu(x) = \bar{\psi}(x)\,\gamma^\mu\,\psi(x),$$    which couples to the gauge field, showing how fermions interact with gauge bosons in the Standard Model.](2024-Lecture-01-images/fig2.png){#fig-fg2}






We now want to introduce interaction. The way to do this is guided by the **gauge principle**.

*   For the gauge invariance of the electromagnetic field, it was the shift of the field  $A_\mu$ .
*   For fermions, gauge invariance implies changing the **phase** of the wave function.

The wave function  $\psi$  for the fermion has an observable absolute value squared, but its phase is not fixed. We should be able to update this phase, which is called a **phase transformation**.

The check for gauge invariance is to perform this phase transformation and see if your Lagrangian remains invariant. It's intuitive that you should be able to update the phase.

What is tricky is that the phase can be updated **differently at every point in spacetime**. We are not doing a global phase rotation for all fields. Instead, we decide for every point what the phase update is.

This local transformation is much different because we must now account for the derivative. When we see how the Lagrangian changes under this transformation, the derivative acts not only on  $\psi$  but also on the spacetime-dependent phase, which generates an extra term.

So, the Lagrangian changes to itself plus an extra term. Let's reason through it:
The derivative acting on the transformed field  $\psi' = e^{i Q \alpha(x)} \psi$  will bring down a factor like  $-iQ \partial_\mu \alpha$ . This extra term breaks the invariance of the free theory.

The solution is to replace the ordinary derivative with the **covariant derivative**:
  $$D_\mu = \partial_\mu - i Q A_\mu$$  

The total Lagrangian for quantum electrodynamics (QED) becomes:
  $$\mathcal{L}_{\text{QED}} = \bar{\psi} (i \gamma^\mu D_\mu - m) \psi - \frac{1}{4} F_{\mu\nu} F^{\mu\nu}$$  

What we find is that for the free Dirac theory, the Lagrangian is **not** gauge invariant because it changes under the phase transformation. However, if we incorporate the gauge field  $A_\mu$  and perform the gauge transformation for **both** fields simultaneously, the extra term gets compensated.

*   The fermion field transforms as:  $\psi \rightarrow \psi' = e^{i Q \alpha(x)} \psi$ 
*   The gauge field transforms as:  $A_\mu \rightarrow A_\mu + \partial_\mu \alpha$ 

The change in the interaction term  $\bar{\psi} i \gamma^\mu Q A_\mu \psi$ , due to the shift in  $A_\mu$ , exactly cancels the unwanted term from the phase transformation of  $\psi$ .


::: callout-important
This is a super important concept: the way fields and fermions interact is **driven by gauge invariance**. We demand the freedom to change the phase locally at every point in spacetime, and this requirement **determines** how the interaction must work. The resulting interaction term in the Lagrangian is  $A_\mu J^\mu$ , where  $J^\mu = \bar{\psi} \gamma^\mu \psi$  is the fermion current.
:::

From this Lagrangian, if you derive the equations of motion, you won't get just the free Dirac equation. You will have a source term, showing it's not a free-moving field—it interacts with photons. This gives us a consistent framework for interactions.

The gauge principle does more than just dictate how particles interact; it determines the **entire structure** of the interactions. Depending on the mathematical nature of the "phase" transformation, we get different fundamental forces.

*   If the phase is a **scalar** (a simple number), you get **electrodynamics (QED)**. There is only one type of gauge boson: the photon.
*   If the phase is a **2x2 matrix** (like the Pauli matrices), you get **Yang-Mills theory**, which describes the **weak interactions** with the W $^+$ , W $^-$ , and Z bosons.
*   If the phase is a **3x3 matrix** (like the Gell-Mann matrices), you get **quantum chromodynamics (QCD)**.

The mathematical object for the phase transformation is connected to a **Lie group** (U(1), SU(2), SU(3)). The dimensionality of this transformation determines the "charge space" in which the fermion field  $\psi$  can live. For example, in electroweak theory, the left-handed quarks (up and down) form a **doublet** under the SU(2) transformation.

The general form of a **non-Abelian gauge transformation** is:
  $$\psi(x) \rightarrow \psi'(x) = e^{i g \alpha^a(x) T^a} \psi(x)$$  
Here,  $T^a$  are the generators of the group (e.g., Pauli matrices  $\sigma^a/2$  for SU(2)), and  $\alpha^a(x)$  are the spacetime-dependent parameters.

The corresponding **covariant derivative** becomes:
  $$D_\mu = \partial_\mu - i g T^a A_\mu^a$$  
This ensures invariance under these more complex local transformations and leads to theories where the gauge bosons themselves carry charge and can interact with each other.



## Exponential Form and Group Closure

Now, the important point when working with two exponents is to ensure we are operating within a **group**. If I were to write the transformations without an exponential form, I could not guarantee that combining them would yield the same type of object.

It is a proven result in group theory that writing a group element in exponential form ensures the result remains within the group. Therefore, if you multiply one such object by another of the same type, the product corresponds to a third object of the same exponential form.

For those familiar with matrix exponentials, what is  $e^{i \theta_a \lambda_a}$ ? To find it, you must perform a Taylor expansion:
  $$\exp(M) = \sum_{n=0}^{\infty} \frac{M^n}{n!}$$  
and then multiply the matrix by itself repeatedly.

This specific matrix follows a simple pattern. I believe once you square it, the result becomes diagonal. Consequently, you can often **truncate the infinite series** after a certain number of terms.

This leads us to an even more intricate object. Here,  $\lambda$  represents a **Gell-Mann matrix**, and there are eight such matrices in the SU(3) formalism.

Let us write  $\lambda_1$ :
  $$\lambda_1 = \begin{pmatrix} 0 & 1 & 0 \\ 1 & 0 & 0 \\ 0 & 0 & 0 \end{pmatrix}$$  

So, what is  $e^{i \theta \lambda_1}$ ? It should be straightforward to compute using the series expansion, noting that  $\lambda_1^2$  is diagonal.


::: callout-tip
The exponential form  $U = \exp(i \theta_a \lambda_a)$  is central to group theory in quantum chromodynamics (QCD). It guarantees **closure under multiplication**—the product of two SU(3) group elements remains an SU(3) element. For matrices like the Gell-Mann matrices, the Taylor series for the exponential often simplifies dramatically.
:::

I am tempted to take a shortcut. You could ask either ChatGPT or Wolfram Alpha for the answer, and it would provide it quickly. However, I am confident it is easy to derive if you think about it for a moment.

You may not have much time now, but I encourage you to familiarize yourself with these matrices. It is both enjoyable and crucial for this course.



## QCD Lagrangian and Confinement

The last concept in this subject is that the Lagrangian for Quantum Chromodynamics (QCD) is constructed to be invariant under the SU(3) gauge transformation.

Its structure is not entirely different from previous gauge theories, but it has a very important distinction: the proliferation of indices. The dimensionality of objects is super important.

Once we have a generator  $T^a$ , where  $T^a = \lambda^a/2$ , it is a  $3 \times 3$  matrix. Contracting it with a field yields another  $3 \times 3$  matrix, which is diagonal in the color dimension. We must keep track of multiple dimensions: color, Lorentz, and the gluon field  $A^a_\mu$ .

An instructive exercise is to recover the familiar terms from Quantum Electrodynamics (QED) from this framework; you will see they are essentially the color-stripped versions.

One crucial aspect of QCD is that it is fundamentally different because it contains a term that allows **gluons to interact with themselves**. Even in a theory without quarks, gluons and their self-interaction terms would remain.

This self-interaction term in the equations of motion means gluons behave profoundly differently from photons. These gluon self-interactions lead to the phenomenon known as **confinement**. The screening of color forces works in the opposite way to the screening of electric forces in QED.

In a proper field theory course, you learn that the strength of interactions depends on the energy scale at which you probe the system, a concept related to **renormalization**. Depending on the energy scale of your experiment, you effectively experience a different charge.


::: callout-important
The QCD Lagrangian contains the strong coupling constant  $g_s$ , which is "bare" in the Lagrangian. However, the coupling you observe in interactions is not this bare constant—it changes with the energy scale. This running is described by the **QCD beta function**:
  $$\beta(\alpha_s) = \frac{d\alpha_s}{d\ln Q} = -\frac{\alpha_s^2}{2\pi} \left( 11 - \frac{2}{3} n_f \right) + \mathcal{O}(\alpha_s^3)$$  
where  $\alpha_s = g_s^2/(4\pi)$  and  $n_f$  is the number of quark flavors. The negative sign is key: it means  $\alpha_s$  decreases at high energies (**asymptotic freedom**) and increases at low energies (**confinement**).
:::

For QED, the coupling constant becomes smaller as you probe shorter distances (higher energy). For the strong interaction, the coupling constant  $g_s$  becomes **stronger** as you reduce the energy scale.

This increasing strength at low energies is the reason **hadrons can form**. Gluons and quarks bind into hadrons at these small energy scales. 




![The diagram shows the dependence of the strong coupling \ $\alpha\_s(Q)\$  on the transferred momentum \ $Q\$ . At high \ $Q\$ , the coupling decreases, illustrating the property of asymptotic freedom. At low \ $Q\$ , the coupling grows, leading to the non-perturbative regime of QCD and the phenomenon of confinement. The transition scale is set by \ $\Lambda\_{\text{QCD}} \sim 300\ \text{MeV}\$ , and for \ $Q \lesssim 1\ \text{GeV}\$  perturbative methods fail, marking the domain of confinement and hadronization.](2024-Lecture-01-images/fig3.png){#fig-fg3}




 The strong interaction is such that it does not allow colored objects (like individual quarks) to escape; it **confines** them. The high-energy regime where the coupling is small is called **asymptotic freedom**.

The root cause of both confinement and asymptotic freedom is the **gluon self-interaction**. There is essentially no "free" theory for QCD; even without quarks, gluons interact. This self-interaction leads to confinement at low energy and asymptotic freedom at high energy. The latter regime is where we perform calculations for processes like Higgs physics, where large momentum transfers occur.

An aspect not discussed in detail today is what Quantum Field Theory (QFT) tells us about performing computations in **perturbation theory**. In QED, or in the asymptotic freedom regime of QCD where the coupling is small, you can expand your equations of motion and iterate using the fact that the coupling is small.

This leads to the **perturbative approach**, with its diagrammatic representation known as **Feynman diagrams**. Using these, you compute **matrix elements**.

In this course, we will often refer to the **matrix element squared**  $|\mathcal{M}|^2$ , which is related to the **cross section**  $\sigma$  of a process. The general formula for a  $2 \to N$  scattering cross section is:
  $$\sigma = \frac{1}{2E_A 2E_B |v_A - v_B|} \int \left( \prod_{f=1}^N \frac{d^3p_f}{(2\pi)^3 2E_f} \right) |\mathcal{M}|^2 (2\pi)^4 \delta^{(4)} \left( p_A + p_B - \sum p_f \right)$$  
Here,  $\Phi$  represents the flux factor, and  $D\Phi$  stands for the integration over the final-state particle phase space.

The matrix element in QFT is the key object that relates theory to observables. It tells you how to compute quantities you can measure in an experiment.

Intuitively, you can understand it this way:

*   The matrix element  $\mathcal{M}$  gives the quantum mechanical amplitude for a transition from an initial state to a specific final state.
*    $|\mathcal{M}|^2$  is proportional to the probability for that specific configuration.
*   To get the total probability, you must **sum over all possible final-state configurations** (integrate over phase space  $D\Phi$ ).

You will see an example next week of how, for a two-body decay, you explicitly count the number of configurations in the final state. The total probability (or decay rate) will be this matrix element squared, summed over all possible configurations.

In these calculations, you must also account for particle spins:

*   **Sum over the spin states of the final particles.**
*   **Average over the spin states of the initial particles.**

This is why for a process like  $A + B \to N$ , we include averaging factors. If you are given a correctly spin-averaged matrix element, along with the  $1/(2E)$  factors for incoming particles, you can immediately calculate the corresponding cross section.

**The cross section  $\sigma$ ** has units of area (e.g., cm $^2$ ). It represents the effective "target area" presented by one particle to another. If the colliding particles pass within this area, the reaction is likely to occur; outside of it, the reaction does not happen.

**The decay width  $\Gamma$ ** is related to the lifetime  $\tau$  of an unstable particle ( $\tau = 1/\Gamma$ ). For a particle of mass  $M$  decaying to  $N$  final particles, the partial width is:
  $$\Gamma = \frac{1}{2M} \int \left( \prod_{f=1}^N \frac{d^3p_f}{(2\pi)^3 2E_f} \right) |\mathcal{M}|^2 (2\pi)^4 \delta^{(4)}\left( p - \sum p_f \right)$$  
We will discuss this formula in more detail next time.



## Course Logistics and Introduction

It's really nice to have you all today. We are three minutes out, but let me quickly go over the logistics for the course.

*   I have prepared notes for **11 lectures** and **11 exercises** (though there will be fewer exercises due to some breaks).
*   A calendar is available on Moodle listing the anticipated dates for lectures and exercises. Closer to those dates, we can discuss shifting exercise sessions, but for now, we will keep the schedule as is.
*   For the **exam**, we will track the points you gain through the exercise sheets during the semester. Achieving **50%** of these points will admit you to the examination.
*   The exam itself is designed to be straightforward: you will receive the problem **one or two weeks in advance** to think about it.
*   During the exam, you will bring your solutions, and we will have a discussion about the material.

I think the most important thing is to work on the **exercise sheets** during the semester. Let me show them to you.

*   There is a barcode to scan on the sheets.
*   There will be **one or two problems per homework** that you must solve.
*   **Process:** You write your solutions down, bring the solved sheets to the lecture, and place them in a designated box. We will check them, and the teaching assistants will return the marked sheets during the Thursday exercise sessions, where they will also discuss the problems.
*   **Schedule:** Lectures are on **Tuesday**, and exercise sessions are on **Thursday**.

We will have a certain excursion during the semester. Although it's fully booked, we may still find one or two places if you haven't signed up.

*   **Office Hours:** I will hold office hours on **Thursdays from 9:00 to 10:00** in my office, **1 3B and B**. You can come to discuss anything related to the course. This will be written down officially.

There are several **summer schools** happening in our field this summer. These are exciting events if you're considering going to a different country.

*   One is in **Zurich, Switzerland**, for **eight weeks**.
*   Another is in **Krakow, Poland**, for **four weeks**.
*   Applications for these are still open for another couple of weeks.
*   We are also organizing one in **Bochum** in **July** for **two weeks**, aimed at people more advanced in the field.

If you are interested, just write me an email, and I can forward you the official announcement.

Regarding the **exercise sheets**, I encourage **collaboration**. You can solve the sheets together and feel free to use any resources—ChatGPT, books, etc. The problems are standard and are meant for learning, not for checking you. How you learn is up to you.

Here are some of the **key textbooks** I will be following:

1.  Halzen and Martin
2.  Martin Schmaltz (dedicated to Higgs physics)
3.  Thomson's *Particle Physics*

The exercise sessions start **this week**. Before leaving, please take the sheets. We printed 15 copies; there are two sheets, each with two pages. Take one for yourself.


::: callout-note
**On Today's Problem:**
The first problem involves a **coupled spring-pendulum system**. The pivot point from which the pendulum hangs can slide. You will start from the Lagrangian, which is the kinetic energy minus the potential energy, and work towards finding relevant equations of motion.

A typical Lagrangian for such a coupled system is:
  $$L = \frac{1}{2} m \dot{x}^2 + \frac{1}{2} m l^2 \dot{\theta}^2 + m l \dot{x} \dot{\theta} \cos\theta - \frac{1}{2} k x^2 - m g l (1 - \cos\theta)$$  
Here,  $\dot{x}$  is the time derivative of the sliding coordinate, and the terms represent kinetic energy from sliding and rotation, a coupling term, and potential energy from the spring and gravity.
:::

This is a fun problem. You can put the derived equations into a differential equation solver. It's not that easy in quantum field theory, but people still do it in their research.

I rushed a bit at the beginning and end, so let me clarify the plan. I will reintroduce the **QED Lagrangian** and the **QCD Lagrangian**. We will calculate something for QED as well, time permitting.


::: callout-note
**Key Lagrangian for QED:**
The Quantum Electrodynamics (QED) Lagrangian describes the interaction between fermions (like electrons) and the electromagnetic field. It is given by:
  $$\mathcal{L}_{\text{QED}} = \bar{\psi}(i\gamma^\mu D_\mu - m)\psi - \frac{1}{4} F_{\mu\nu} F^{\mu\nu}$$  
In this formula,  $D_\mu = \partial_\mu + i e A_\mu$  is the covariant derivative, and  $F_{\mu\nu}$  is the electromagnetic field tensor.
:::

I think starting with a simpler case and explaining how you calculate the terms is a good approach. I've prepared an exercise on gauge transformations for QED. This will provide a useful comparison to understand the added complexity that **QCD** brings. While QED explains most electromagnetic interactions, QCD introduces further complexity.

I think we should proceed. Let's get started.

