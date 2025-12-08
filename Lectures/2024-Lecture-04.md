---
title: (2024) Lecture 4
author: ''
presenter: Mikhail Mikhasenko
note_taker: Ilya Segal
date: '2024'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



## Computing the Omega Baryon Magnetic Moment

Today's lecture is dedicated to the experiments in spectroscopy and the computations of the kinematics for the experiments. But before going there, I would like to have a short recap of the last lecture and to pose two questions.

1.  **Compute the magnetic moment in the current model of the Omega baryon.**
2.  **Compute the lowest 1s multiplet excitation multiplet of the Sigma particle parameter.** This is essentially asking about isospin fermions.

Let's address the first question quickly because it's rather straightforward.

### **Calculating the Magnetic Moment of the Omega Baryon**

**What is the quark content of the Omega baryon (Ω⁻)?** It consists of three strange quarks (*sss*).

The total wave function lives in the tensor product space of color, flavor (isospin), and spin coordinates. For this magnetic moment calculation, we focus on the **spin** part, as the flavor part is trivial for three identical strange quarks.

The Omega baryon has spin  $J = 3/2$  and positive parity. To calculate its magnetic moment, we use the maximal spin projection state,  $|s↑ s↑ s↑ \rangle$ , where all three quark spins are aligned up.


::: callout-tip
You don't need to use complicated spin configurations. For calculating the magnetic moment, you can simply take the state with the highest value of spin projection ( $m_s = +3/2$ ). Acting on this state with the magnetic moment operator yields an eigenvalue directly.
:::

The total magnetic moment operator for the baryon is the sum of the magnetic moment operators for its constituent quarks:
  $$\hat{\mu}_z = \sum_{i=1}^{3} \hat{\mu}_{i,z} = \sum_{i=1}^{3} \frac{e q_i}{2 m_i} \sigma_z^{(i)}$$  
where for a strange quark, the charge  $q_s = -\frac{1}{3}e$  and its mass  $m_s \approx 500 \text{ MeV}$ .

Since all three quarks are identical, the magnetic moment of the Omega baryon is simply three times the magnetic moment of a single strange quark in this fully aligned state:
  $$\mu_{\Omega^-} = 3 \cdot \mu_s = 3 \cdot \left( \frac{e q_s}{2 m_s} \right)$$  
Substituting  $q_s$  gives:
  $$\mu_{\Omega^-} = \frac{e}{2 m_s} \cdot (3 \cdot (-\frac{1}{3})) = -\frac{e}{2 m_s}$$  
In absolute terms,  $|\mu_{\Omega^-}| = \frac{e}{2 m_s}$ .

### **Interpretation and Scale**

Our intuition is correct: the magnetic moment is negative because the Omega baryon has a net negative charge. However, the mass in the denominator is the **constituent quark mass** (roughly 500 MeV), not the mass of the Omega baryon itself (about 1672 MeV).

**How does this compare to an electron?** The electron's magnetic moment is  $\mu_e = \frac{e}{2 m_e}$ , with  $m_e \approx 0.5 \text{ MeV}$ . The ratio is:
  $$\frac{|\mu_{\Omega^-}|}{\mu_e} = \frac{m_e}{m_s} \approx \frac{0.5}{500} = 10^{-3}$$  
This shows the Omega baryon's magnetic moment is about **one thousand times smaller** than the electron's, due to the much larger mass scale of the strange quark.

**Key Lesson:** With a simple, symmetric wave function, the evaluation is straightforward. You take the maximal projection state, apply the magnetic moment operator, and collect the contributions.



## Excitation Pattern of the Σ_b Baryon

Now, question number two is the excitation pattern of the  $\Sigma_b$  baryon.

I gave you a hint that the ground state of the  $\Sigma_b$  baryon has the light diquark in the configuration with isospin  $I=1$  and spin  $1/2^+$ .

A bonus question is the isospin pattern: the partners of this baryon that one gets simply from isospin. You see that isospin equals 1. It immediately tells you the multiplicity of the isospin multiplet.

How many charge partners am I going to get for this baryon? Since isospin is one, there are three different projections, three different quantizations:  $I_3 = +1$ ,  $0$ , and  $-1$ .

What are the charges? I'm going to get  $\Sigma_b^+$  (uub),  $\Sigma_b^0$  (udb), and  $\Sigma_b^-$  (ddb). Two up quarks and one bottom quark is like a proton, it has a charge of  $+1$ . Once I act with a spin lowering operator, I reduce the charge by one unit. So this number tells you immediately how many particles and what their charges are. It is super simple.


::: callout-note
The charges for the  $\Sigma_b$  isospin triplet ( $I=1$ ) can be determined from the quark content or the Gell-Mann–Nishijima formula,  $Q = I_3 + Y/2$ , where the hypercharge  $Y=1$ . This gives:

*    $I_3 = +1$  →  $Q = +1$  ( $\Sigma_b^+$ , uub)
*    $I_3 = 0$  →  $Q = 0$  ( $\Sigma_b^0$ , udb)
*    $I_3 = -1$  →  $Q = -1$  ( $\Sigma_b^-$ , ddb)
:::

In order to find the excitation pattern you need to work with spin, not with isospin. All three families are related by isospin, therefore their properties are going to be almost the same. Isospin is broken by different quark masses, but this breaking is tiny. I can talk about any of these three, and for all of them, the ladder of excitations is going to be the same.

Let's now pick one of them, put it as the lowest state as usual. For the diagram of the excitation pattern, we draw on the x-axis different quantum numbers, often the orbital angular momentum  $L$ . On the y-axis we put the energy or the rest mass of the state, which is the same as the mass of the hadron.

To obtain that, I start by combining the spins of the light quarks and the heavy quark. 




![This figure schematically illustrates the **excitation pattern of the  $\Sigma_b$  baryon** in terms of its quantum numbers and mass splittings, as discussed in the lecture. On the vertical axis is the **energy or mass of the hadron** (labeled "mass of hadron"), while the horizontal axis represents the **orbital angular momentum  $L$ ** of the system.  - The lowest block at  $L=0$  (S-wave) corresponds to the **ground state multiplet** of the  $\Sigma_b$ , specifically the  $J^P=1/2^+$  and  $J^P=3/2^+$  states, arising from combining the light diquark spin ( $s_\ell = 1$ ) with the heavy quark spin ( $s_Q = 1/2$ ).  - The "radial excitation" arrow, labeled as approximately  $\Lambda_{\text{QCD}}$ , represents the energy gap between different principal quantum numbers (radial excitations), reflecting the typical QCD scale for hadronic structure. - The higher-lying blocks at  $L=1$  (P-wave) display the **P-wave excitation multiplet**, with five total states corresponding to the possible combinations of spins and orbital motions: specifically,  $J^P=1/2^-, 3/2^-$  (from  $S=1/2$ ) and  $J^P=1/2^-, 3/2^-, 5/2^-$  (from  $S=3/2$ ). - The vertical separations correspond to mass splittings between S-wave and P-wave states (dominated by orbital excitation energy, of order  $\Lambda_{\text{QCD}}$ ), while the smaller splittings within each block are due to **hyperfine interactions** (suppressed by  $1/m_Q$  for the heavy quark). - This diagram captures the overall **structure of the baryon spectrum**, encoding both the quantum number assignments and the physical energy scales discussed in the lectures on spectroscopy and multiplet structure.](2024-Lecture-04-images/fig1.png){#fig-fg1}




 For most hadrons, except the light meson sector, the radial excitation from 1s to 2s orbitals is much higher than the hyperfine splitting. Once you deal with heavy quarks, this is always true.

The energy difference from combining the spin of the heavy quark and the spin of the light quark comes with a suppression factor,  $1/m_Q$ . When you combine the light diquark, which has spin  $s_\ell=1$ , and the heavy quark of spin  $s_Q=1/2$ , for the S-wave you get two total spin combinations:  $J=1/2$  and  $J=3/2$ .

**Ground State (S-wave) Multiplicity:**

*   Coupling  $s_\ell = 1$  and  $s_Q = 1/2$  gives:  $J = \frac{1}{2}, \frac{3}{2}$ .
*   Parity is positive for S-wave states.
*   This yields the ground-state doublet:  $\Sigma_b (J^P = 1/2^+)$  and  $\Sigma_b^* (J^P = 3/2^+)$ .

If I want to calculate the multiplicity of states after adding one unit of orbital angular momentum, I have to consider both possibilities separately and do the spin algebra. For the P-wave ( $L=1$ ), combining with  $S=1/2$  gives  $J^P = 1/2^-, 3/2^-$ . Combining with  $S=3/2$  gives  $J^P = 1/2^-, 3/2^-, 5/2^-$ .

**P-wave ( $L=1$ ) Multiplicity:**

*   For  $S = 1/2$ :  $J^P = \frac{1}{2}^-, \frac{3}{2}^-$ 
*   For  $S = 3/2$ :  $J^P = \frac{1}{2}^-, \frac{3}{2}^-, \frac{5}{2}^-$ 
*   **Total:** Five distinct P-wave states (negative parity).

The multiplicity for the P-wave block is five. The multiplicity for the S-wave orbital is two. The lowest state is  $1/2^+$  and  $3/2^+$ . Then there are five states in the P-wave. That is what we call the excitation pattern.

All of these lines are different particles you find in the PDG. I don't think the 2004 PDG had even the next one, because it was discovered recently. The  $\Sigma_b^*$  entered there roughly 10 years ago. This was a discovery of the colliders.

Now one word about energy splitting. The energy splitting between the S-wave and P-wave states is caused by the orbital excitation, with a scale given by quark dynamics of order  $\Lambda_{\text{QCD}}$ , roughly a few hundred MeV. That gives the elevation of the different blocks.

Within a block, the splitting between levels comes from the dynamics of the heavy quark spin. This splitting is suppressed inversely proportional to its mass,  $\Delta E_{\text{hyperfine}} \sim \kappa/m_Q$ . In the Lagrangian of effective theories, the spin-orbit interaction enters as a term like  $(C/m_Q) \vec{S}_Q \cdot \vec{S}_\ell$ .

The mass of the  $b$  quark is about 4 GeV.  $\Lambda_{\text{QCD}}$  is a few hundred MeV. The ratio between them is roughly 1:10. That is the difference between the orbital excitation energies and the hyperfine splittings within a multiplet.

I think that if I remember correctly, the energy difference between  $\Sigma_b$  with spin  $3/2$  and  $\Sigma_b$  with spin  $1/2$  is on the order of 10 MeV.



## The Puzzle of Exotic Hadrons

Today's lecture is dedicated to **kinematics and experimental techniques**.

I would like to start by overviewing what we do in physics on the experimental side. The direction of **hadron spectroscopy** has been extremely vibrant and fruitful in the last 10 years. It started around 2004, where it became a prominent and trending topic with the first observations of **exotic particles**.

Since then, every few months, there would be new observations of hadrons that do not fit the simple quark model of mesons and baryons. Many experiments have since dedicated part of their programs to study these exotic hadrons.

Across the world, several large labs study particle collisions. One of the central, puzzling questions is to understand the very fabric of matter: how hadrons form, which combinations are possible, and what rules determine their excitation patterns and properties.

We have a quantum theory of strong interactions—**Quantum Chromodynamics (QCD)**—which seems to describe these interactions well. However, there has been no success in **classifying and predicting large multiplets of exotic hadrons from first principles**. We observe something and would like to predict its properties, but we cannot. This is due to:

*   Limitations in our computational methods (e.g., Lattice QCD works well for ground states but not yet for excited states).
*   The intrinsic complexity of the theory itself.

There are many emerging phenomena. You can look at the QCD Lagrangian and see quarks and gluons, but these are not the direct degrees of freedom for describing hadrons. We seem to be facing a transition in the description of matter: from configurations where **quark degrees of freedom** are important, to configurations where **hadrons themselves** become the important degrees of freedom, binding together to form hadronic atoms or molecules.

In hadron spectroscopy, you face this borderline. You have a mixture of:

*   **Compact hadrons** made of elementary quarks.
*   **Larger, sparse objects** where hadrons bind into bigger entities (e.g.,  $\text{Hadron}_1 + \text{Hadron}_2 \rightarrow \text{Molecule}$ ).

Some hadrons are complicated exactly for this reason—they are in a **mixed state** of different configurations. Some properties require it to be a compact hadron, while others require it to be a sparse hadronic molecule. This is the area where, at the current stage, lattice QCD cannot help very much.

Experiments around the world provide new data and insight. The way we understand this is by measuring the properties of hadrons and their decays. We want to:

1.  Observe hadrons in new decay configurations.
2.  Measure the same hadron from different production mechanisms.

Many labs explore these different mechanisms:

*   **Experiments like Belle (Japan) and BESIII (China)** collide **leptons** (electrons and positrons). They annihilate to produce an intermediate state that decays. A typical reaction is:
  $$e^+ + e^- \rightarrow \psi \rightarrow \text{hadrons}, \quad \sqrt{s} \sim 2 - 4 \, \text{GeV}$$  
The study happens by analyzing these decay products.

*   **Colliders at CERN, like the LHC**, explore different mechanisms by colliding **protons** (large energetic conglomerates of quarks and gluons). This produces many particles, including long-lived particles with heavy quarks like  $B$  and  $D$  mesons.

These heavy mesons live long enough to travel a measurable distance, providing a clean environment to study hadrons. A  $B$  or  $D$  meson is produced, flies a few millimeters, and we track this with our detectors. We can then distinguish the **primary vertex** from the **secondary decay vertex**.


::: callout-note
**Key Experimental Formulas**
The analysis in these experiments relies on fundamental kinematic formulas:

*   **Relativistic Energy-Momentum:**  $E^2 = p^2 c^2 + m^2 c^4$ 
*   **Invariant Mass:** Used to reconstruct particle masses from decay products.
      $$M_{\text{inv}}^2 = \left( \sum_i E_i \right)^2 - \left( \sum_i \vec{p}_i \right)^2 c^2$$  

*   **Decay Width & Lifetime:**  $\Gamma = \hbar / \tau$ 
*   **Resonance Cross-Section:** Described by a Breit-Wigner form,  $\sigma(E) \propto 1/[(E - M)^2 + \Gamma^2/4]$ , crucial for identifying short-lived exotic states.
:::



## Hadron Production and Spectroscopy Experiments

Another class of experiments uses **hadronic production**. Essentially, shooting a hadron at a hadron without aiming to describe the kinematics exclusively. Those are mostly fixed-target experiments.

I will be talking about the **GlueX experiment** at Jefferson Lab that has a photon beam, and the **COMPASS experiment** at CERN that has a pion beam. They both use a hydrogen target. The proton in the target and whatever particle comes in gets excited or scatters off the target. 




![This figure schematically represents a **generic hadronic collision** in which two incoming particles interact and produce a multiparticle final state. The arrows entering the central blob on the left signify two **incoming particles** (such as protons, pions, photons, or leptons) participating in the collision. The arrows exiting on the right denote the **production of several outgoing hadrons** ("h" stands for a generic hadron), which may include resonances or decay products.  In the context of this lecture, this diagram illustrates the general ** $2 \to n$  process** central to experiments in hadron spectroscopy. Such processes underpin both **inclusive** and **exclusive production mechanisms** discussed above—for example, proton-proton collisions at the LHC, photon-proton collisions at GlueX, or  $e^+e^-$  annihilation at Belle and BES experiments. The central region represents the **strong interaction dynamics**, where the initial particles interact via Quantum Chromodynamics (QCD) to create various possible hadronic final states.  Physically, this encapsulates the need to analyze multi-particle final states using **Lorentz invariant phase space**, **mass-shell constraints**, and **energy-momentum conservation**, as described in the kinematics section of the lecture. The schematic is a universal representation of the kind of events for which one computes invariant masses, studies resonance production, and counts independent kinematic variables.](2024-Lecture-04-images/fig9.png){#fig-fg9}




 That's another way to study hadrons, by using different production mechanisms.

I would say the third major way to study hadrons is to compute their properties from **lattice QCD**. That's where a large piece of information comes from.

Let's overview the production mechanism and experiments. We start with **BES**.

*   The **BES experiment** (Beijing Spectrometer) is located at the **BEPC** (Beijing Electron Positron Collider) accelerator complex.
*   It collides electrons and positrons and is dedicated to studying hadrons in the Charmonium and Tau energy regions.
*   It is a **symmetric collider**; the electron has the same energy as the positron. 




![This diagram represents the process of electron-positron ( $e^+e^-$ ) annihilation and the subsequent production of hadrons in a collider experiment such as BESIII or Belle II. In this physical context, an electron ( $e^-$ ) and a positron ( $e^+$ ) collide head-on, annihilate at the interaction point, and produce a virtual intermediate state—typically a photon or a vector meson with quantum numbers  $J^{PC} = 1^{--}$ . This intermediate state then decays into multiple hadrons, shown here as several arrows radiating from the interaction point.  The image encodes the experimental environment where all produced hadrons fly out from the collision vertex and are detected. This is central to studies in hadron spectroscopy, where the kinematics and invariant mass distributions of the outgoing hadrons are analyzed to identify hadron resonances, determine their properties, and scan for new or exotic states. This mechanism serves as the basis for resonance production, allowing experiments to reconstruct resonance peaks and study the strong interaction via the analysis of the final-state hadrons.](2024-Lecture-04-images/fig2.png){#fig-fg2}






When the two particles collide, one interaction possibility is **annihilation**. The electron and positron produce a virtual photon that then couples to a hadron.


::: callout-important
**Quantum Number Selection Rule**
In relativistic  $e^+ e^-$  collisions, the initial state quantum numbers restrict the produced virtual photon.
:::




![This diagram depicts the fundamental process of hadron production in an electron-positron ( $e^+ e^-$ ) collider experiment as described in the lecture. An electron ( $e^-$ ) and a positron ( $e^+$ ) annihilate, producing a virtual photon ( $\gamma$ ). This virtual photon then couples to a hadronic resonance, specifically the  $J/\psi$  meson, which has quantum numbers  $J^{PC} = 1^{--}$ , consistent with the selection rules discussed. The  $J/\psi$  resonance subsequently decays into three pions: a positive pion ( $\pi^+$ ), a negative pion ( $\pi^-$ ), and a neutral pion ( $\pi^0$ ).   In the context of the lecture, this process illustrates how  $e^+ e^-$  annihilation at experiments like BES or Belle/Belle II can be used to study hadron spectroscopy, especially by observing exclusive decay final states of vector mesons (like  $J/\psi$ ) into lighter mesons. The depicted reaction is a clear example of both the initial state quantum number selection (only  $1^{--}$  states can be directly produced) and the analysis of exclusive decays in spectroscopy experiments. The decay products ( $\pi^+$ ,  $\pi^-$ , and  $\pi^0$ ) can be reconstructed to study the properties and dynamics of the  $J/\psi$  resonance via invariant mass techniques and Dalitz plot analysis as highlighted in the lecture.](2024-Lecture-04-images/fig3.png){#fig-fg3}




 Combining the spins and parities of the electron ( $1/2^-$ ) and positron ( $1/2^+$ ) in an S-wave results in quantum numbers  $J^{PC} = 1^{--}$ . This means **only hadronic resonances with  $J^{PC} = 1^{--}$ ** (like the  $J/\psi$  or  $\psi(2S)$ ) can be directly produced in  $e^+ e^-$  annihilation. 




![This figure schematically represents the total cross section  $\sigma_{e^+e^- \to X}$  measured as a function of the center-of-mass energy  $\sqrt{s}$  in electron-positron annihilation experiments, such as those conducted at BES or Belle II. The vertical axis shows the cross section for producing hadronic final states  $X$  in  $e^+e^-$  collisions, while the horizontal axis is the center-of-mass energy, marked at characteristic values (e.g., 2 GeV, 4 GeV). The sharp peaks and structures correspond to the production of intermediate resonances, such as the  $J/\psi$  and its excitations ( $\psi(2S)$ , etc.), which have  $J^{PC}=1^{--}$  and couple directly to the virtual photon in  $e^+e^-$  annihilation. The decomposition  $\sigma_\text{full} = \sigma_{3\pi} + \sigma_{2D} + \dots$  at the top indicates that the total cross section is the sum over exclusive cross sections for different final states. This plot physically illustrates how the hadronic production rate varies with  $\sqrt{s}$ , highlighting resonance peaks where particle production is enhanced due to the formation of specific quark-antiquark bound states (quarkonia), a central method in hadron spectroscopy.](2024-Lecture-04-images/fig4.png){#fig-fg4}






Therefore, the BES experiment explores hadrons with the quantum numbers  $1^{--}$ .

The experiment operates in two main modes:

1.  **Resonance Peak Data Taking:** They set the beam energy to sit directly on a resonance peak (e.g., the  $J/\psi$ ) and collect enormous amounts of data on its production and decays.
2.  **Energy Scan:** They vary the beam energy point-by-point to measure the cross section  $\sigma_{\text{total}}$  as a function of center-of-mass energy  $\sqrt{s}$ .

  $$\sigma(e^+ e^- \to R \to \text{hadrons}) \propto \frac{\Gamma_{e^+ e^-} \Gamma_{\text{total}}}{(s - M_R^2)^2 + M_R^2 \Gamma_{\text{total}}^2}$$  

The cross section is not homogeneous; it shows **peaking structures (resonances)** where the probability of interaction is higher. Researchers then analyze specific final states (like  $\pi^+\pi^-$  or  $3\pi$ ) from these data sets to extract hadron properties.

The **Belle II experiment** in Japan also uses an electron-positron collider (the SuperKEKB accelerator). Its primary goal was to study **B mesons and CP violation**, but its data is extremely valuable for hadron spectroscopy.

In contrast to symmetric colliders like BES, **Belle II is an asymmetric collider**. The electron and positron beams have different energies. 




![This figure illustrates the production mechanism at the Belle II experiment, an **asymmetric electron-positron collider**. An electron beam with an energy of approximately 7 GeV collides with a positron beam of about 4.6 GeV. The collision center-of-mass energy is tuned to  $\sqrt{s} \approx 10.58\,\text{GeV}$ , which matches the mass of the  $\Upsilon(4S)$  resonance (a bottomonium state with quantum numbers  $J^{PC} = 1^{--}$ ). The  $\Upsilon(4S)$  then decays predominantly into a pair of  $B$  mesons ( $B\bar{B}$ ). The **asymmetric beam energies** provide a net boost to the produced  $B$  mesons, causing them to travel a measurable distance before decaying—this is essential for identifying secondary decay vertices. This process is a central feature of experimental techniques in hadron spectroscopy described in the lecture, specifically highlighting how asymmetric colliders like Belle II facilitate the study of  $B$  mesons through precise vertex separation and kinematic reconstruction.](2024-Lecture-04-images/fig5.png){#fig-fg5}






*   For symmetric colliders:  $\sqrt{s} = 2E$ 
*   For asymmetric colliders:  $\sqrt{s} = 2\sqrt{E_- E_+}$ 

Belle II operates at a center-of-mass energy tuned to the  $\Upsilon(4S)$  resonance mass ( $\sqrt{s} = 10.58 \text{ GeV}$ ), which primarily decays to a  $B\bar{B}$  pair.


::: callout-note
**Purpose of the Asymmetric Design**
The energy asymmetry ( $E_- \neq E_+$ ) creates a **boost** of the entire center-of-mass frame along the beam axis.
  $$\beta_{\text{CM}} = \frac{|E_- - E_+|}{E_- + E_+}, \quad \gamma_{\text{CM}} = \frac{E_- + E_+}{\sqrt{s}}$$  
This boost gives the produced B mesons significant longitudinal momentum. As a result, they travel a longer, measurable distance ( $L_{\text{lab}} = \gamma_{\text{CM}} \beta_{\text{CM}} c \tau$ ) from the primary interaction vertex before decaying. This **secondary vertex separation** is crucial for identifying and studying the short-lived B mesons.
:::

Let's return to the spectrum. The  $J/\psi$  is the first charmonium state discovered and appears as a clear peak in the  $e^+ e^-$  cross section. It is a  $1^{--}$  state.

The charmonium spectrum is organized into multiplets based on radial ( $n$ ) and orbital ( $L$ ) excitations:

*   The lowest  $1^{--}$  state is the  $J/\psi(1S)$ .
*   Its radial excitation is the  $\psi(2S)$ .
*   The lowest state in the 1S multiplet is the  $\eta_c(1S)$  ( $0^{-+}$ ).
*   The P-wave multiplet ( $L=1$ ) consists of the  $\chi_{cJ}$  states:  $\chi_{c0}$  ( $0^{++}$ ),  $\chi_{c1}$  ( $1^{++}$ ), and  $\chi_{c2}$  ( $2^{++}$ ).

The mass splittings within these multiplets arise from the detailed interactions in the quark model, including spin-spin and spin-orbit terms.



## From Charmonium to Bottomonium and LHC Multiplicities

To reconstruct the schematics before we move away from Belle II, let me relate to what we just said before.

Essentially it's the same process:  $e^+e^-$  annihilation. So it's a total cross section  $\sigma(e^+e^- \to \text{everything})$ .

### **Quarkonium Spectroscopy: Charmonium to Bottomonium**

The Belle experiment operated at energies covering the  $J/\psi$  and the  $\tau$  production threshold. Belle II operates in the region of **bottomonium**—the family of hadrons made of  $b\bar{b}$  quarks, analogous to **charmonium** ( $c\bar{c}$ ).

*   The energy scale moves from ~3 GeV (KEK) to the ~10 GeV region.
*   The bottomonium system is very similar to charmonium, but the  $b$  quark is heavier.
*   This leads to a **smaller hyperfine splitting** between states. The mass difference is given by:
  $$\Delta M_{\text{hfs}} = M(1^{--}) - M(0^{-+})$$  

*   While the scale between major energy levels is still roughly a few hundred MeV, the states within each level are **much more condensed in energy**.

The new symbol here is **upsilon** ( $\Upsilon$ ). This is the vector particle (spin 1, quantum numbers  $1^{--}$ ), making it the **cousin of the  $J/\psi$ **.

*   The  $J/\psi$  is the easiest charmonium particle to produce in  $e^+e^-$  annihilation due to its  $1^{--}$  quantum numbers.
*   Its counterpart in the bottomonium spectrum is the  $\Upsilon$ .
*   When scanning the energy, the states appear sequentially:  $\Upsilon(1S)$ ,  $\Upsilon(2S)$ ,  $\Upsilon(3S)$ ,  $\Upsilon(4S)$ .
*   The  $\Upsilon(4S)$  is notable because all these states are above the production threshold for  $b$  quarks (~9.46 GeV for the  $\Upsilon(1S)$ ).
### **Contrast with Hadron Colliders: The LHC Environment** 




![This figure illustrates the physical process occurring during a high-energy proton-proton collision at a hadron collider like the LHC. Each proton (denoted by "P") enters the collision point with an energy of 7 TeV. Upon collision, the energy released results in the production of a very large number of secondary particles—on the order of  $10^3$  (about a thousand) per event. This reflects the high multiplicity environment typical of LHC collisions, as described in the lecture. The resulting particles are distributed in various directions with a broad range of momenta, most commonly with energies of a few hundred MeV. This environment is crucial for hadron spectroscopy studies, as it enables the observation and identification of rare and exotic hadronic states among the many produced particles. The diagram underscores the difference between the complex, high-multiplicity environment of hadron colliders and the cleaner environment of  $e^+ e^-$  colliders.](2024-Lecture-04-images/fig6.png){#fig-fg6}






Proton-proton colliders like the LHC present a **far more complex environment** compared to clean  $e^+e^-$  annihilation.

*   **Energy & Process:** At the LHC, protons collide at energies like 7.7 TeV per beam. This is not a simple annihilation process; the **beam remnants**—primarily quarks and gluons—carry TeV-scale energies.
*   **Event Multiplicity:** The collisions produce a very high number of particles. The average multiplicity  $\langle N \rangle$  scales with the collision energy  $\sqrt{s}$ :
  $$\langle N \rangle \propto \ln(\sqrt{s})$$  
At the LHC, a **typical event has a multiplicity of roughly a thousand particles**.

*   **Particle Spectrum:** The transverse momentum ( $p_T$ ) distribution of these particles follows an approximate exponential fall-off:
  $$\frac{dN}{dp_T} \propto e^{-p_T / \langle p_T \rangle}$$  
This means there are **many low-energy particles** and a **long tail extending to high energies**.


::: callout-note
**Key Scale:** The typical energy scale for most particles produced in an LHC collision is on the order of **hundreds of MeV**. Even with thousands of particles sharing the total collision energy, the bulk of them have low momentum, establishing this few-hundred-MeV scale as characteristic of the hadronic environment.
:::



## Hadron Production and Spectroscopy at LHCb

LHCb has been the most productive experiment in discovering new hadrons because of the high cross section. The cross section for two protons interacting,  $\sigma_{pp \to \text{hadrons}}$ , is much larger than the cross section for annihilating two electrons,  $\sigma_{e^+e^- \to \text{hadrons}}$ . This enables the detailed study of hadron production.

The two main production mechanisms explored in proton-proton collisions are:

*   **Prompt production:** The particle of interest originates directly from the primary collision vertex.
*   **Displaced production:** The particle originates from the decay of a longer-lived particle, creating a secondary vertex.
### Studying Hadrons via Prompt Production 




![This figure illustrates two main types of hadron production observed in high-energy collider experiments, as discussed in the lecture: **prompt production** and **production from  $b$ -hadron ( $B/\Lambda_b$ ) decays**.  - **Prompt production:**     The top part shows the direct (prompt) creation of hadrons at the primary interaction point. It depicts the decay of an excited charmed baryon,  $\Omega_c^0$ , which promptly decays into a cascade baryon  $\Xi_c$  and a  $K^-$  meson. The  $\Xi_c$  is then reconstructed from its decay products (e.g., proton,  $K^-$ , and  $\pi^+$ ), and a characteristic **secondary vertex** is indicated (displaced by several millimeters from the primary vertex), signifying the weak decay of the  $\Xi_c$ .  - **Production from  $b$ -decays:**     The bottom part shows the production of hadrons via the decay of a long-lived  $b$ -hadron ( $B$  or  $\Lambda_b$ ). The  $B/\Lambda_b$  baryon travels a measurable distance (on the order of  $\sim 2$  cm) from the primary collision before decaying. Its decay produces particles such as  $J/\psi$ , a proton ( $p$ ), and a kaon ( $K$ ). The diagram notes ** $P_c$  resonances** (pentaquark candidates observed in the  $J/\psi p$  invariant mass spectrum) and ** $\Lambda^*$  resonances** (seen in the  $pK$  spectrum), illustrating how secondary vertices allow the identification of new excited hadronic states.  The physical meaning centers on the use of **vertex displacement** to distinguish production mechanisms, the reconstruction of invariant mass spectra to identify resonances, and the importance of tracking kinematics in hadron spectroscopy studies as explained in the lecture.](2024-Lecture-04-images/fig7.png){#fig-fg7}






A prime example from charm production is the observation of the  $\Omega_c$  baryons and the  $\Xi_c^*$  and  $\Omega_c^*$  baryons in prompt production. This is done by reconstructing  $\Xi_c K$  combinations.

The  $\Xi_c$  is the ground state of the cascade multiplet. For all such multiplets containing a charm or bottom quark, the ground state decays weakly because the heavy quark is stable under the strong interaction. The decay proceeds via the weak interaction, with a proper lifetime  $\tau$  on the order of  $10^{-10}$  seconds.

For a boosted particle with a momentum around 100 GeV, this lifetime results in a measurable flight distance. The decay length in the lab frame is given by:

  $$L = \gamma \beta c \tau$$  

where  $\gamma$  is the Lorentz factor and  $\beta = v/c$ . This is sufficient to resolve its decay vertex from the primary vertex. The ground states of charm baryons fly millimeters; we resolve their decays from the primary vertex. In this case, the  $\Xi_c$  produces a separate secondary vertex, displaced by roughly 5 or 6 millimeters.

You reconstruct this  $\Xi_c$  secondary vertex by looking at combinations of charged particles, such as a proton, kaon, and pion. From the thousands of other particles, you then loop over all kaons and combine each with an identified  $\Xi_c$ .

By examining these combinations, you find resonances that are produced promptly at the primary vertex and then decay into this pair. In the spectrum of the  $\Xi_c K$  invariant mass, defined as:

  $$M_{\Xi_c K}^2 = (E_{\Xi_c} + E_K)^2 - (\vec{p}_{\Xi_c} + \vec{p}_K)^2$$  

you see distinct peaks. These peaks, five of them, correspond to the highest probability for producing a system, meaning the system resonates at a frequency corresponding to excited states in the  $\Omega_c$  spectrum.


::: callout-note
**Identifying the State via Strangeness:**
The  $\Xi_c$  has quark content  $csu$  and contains one strange quark (s), giving it strangeness  $S = -1$ . The  $K^-$  has quark content  $s\bar{u}$  and strangeness  $S = -1$ . Therefore,  $\Xi_c K$  combinations have a total strangeness of  $S = -2$ . The resonances appearing in this spectrum have quark content  $css$ , which is precisely the  $\Omega_c$  baryon.
:::

### Studying Hadrons via Displaced Production

Another method is to look at separate secondary vertices from  $B$  hadrons. The ground-state hadrons containing a  $b$  quark are the  $B$  mesons and the  $\Lambda_b$  baryon. These are easiest to produce from the fragmentation of the initial  $b$  quark.

Since they are ground states, they also decay weakly. Their proper lifetime is longer, on the order of  $10^{-9}$  seconds. When boosted, they produce a secondary vertex a few centimeters away from the primary interaction point, for example, two centimeters.

This flight distance cleanly separates the decay we want to study from the primary interaction vertex, making the kinematics very clean. You reconstruct the final-state particles, determine the decay length and the momentum of the  $B$  hadron, and study its isolated decay. (see @fig-fg7)

Resonances in this case appear **within** the decay products of the  $B$  or  $\Lambda_b$ . A prominent recent example, which led to the discovery of pentaquark states, is the decay:

  $$\Lambda_b \to J/\psi \, p \, K^-$$  

This is a three-body decay. You start with the  $\Lambda_b$  and look at the exclusive combination of the final-state particles:  $J/\psi$ , proton, and kaon. These particles can resonate at different masses.

*   If you look at the invariant mass spectrum of the proton and kaon,  $M_{pK}^2 = (p_p + p_K)^2$ , you see bumps corresponding to known  $\Lambda$  resonances.
*   If you look at the invariant mass spectrum of the proton and  $J/\psi$ ,  $M_{J/\psi p}^2 = (p_{J/\psi} + p_p)^2$ , you do not expect any known resonances. However, resonant peaks are still observed.

These peaks in the  $J/\psi\, p$  spectrum correspond to **pentaquark resonances**, meaning they are combinations of five quarks:  $u, u, d, c, \bar{c}$ .



## Fixed-Target Experiments and Light Hadron Spectroscopy

Now let's quickly overview **fixed-target experiments** and the techniques used there.

I will have three examples.

*   **The GlueX experiment at Jefferson Lab** operates with a **9 GeV photon beam** hitting a liquid hydrogen target, which is essentially a liquid way of preparing protons as a target.
*   **The COMPASS experiment at CERN** explores hadron structure with a **beam of pions**, also using a liquid hydrogen target.
*   **The CB-ELSA/TAPS experiment at Bonn** uses a **2 GeV photon beam**.

With these energies, we are not talking about bottom or charm quark production. Most of these experiments are focused on **light hadron spectroscopy**.

*   COMPASS studies light hadrons like protons, kaons, and light mesons.
*   GlueX does similar physics but with a different setup, beam, and energy.
*   CB-ELSA/TAPS also studies light mesons in a fixed-target configuration.


::: callout-note
The **center-of-mass energy** available in these fixed-target collisions is a key kinematic quantity, given by:
  $$\sqrt{s} = \sqrt{m_{\text{beam}}^2 + m_{\text{target}}^2 + 2 E_{\text{beam}} m_{\text{target}}}$$  
For photoproduction experiments like GlueX and CB-ELSA/TAPS, the **threshold photon energy** to produce a particle of mass  $m_X$  from a proton target is:
  $$E_{\gamma}^{\text{th}} = \frac{m_X^2 - m_p^2}{2 m_p}$$  
:::

The event rate in these experiments depends on the **luminosity**. For a fixed-target setup, the luminosity is  $\mathcal{L} = \Phi \, n \, L$ , where  $\Phi$  is the beam flux,  $n$  is the target number density, and  $L$  is the target length.



## Two Mechanisms in Fixed-Target Experiments

It is important to realize that there are two different mechanisms involved when you deal with fixed-target experiments at intermediate energy. These are not the same.

The first process is **diffraction** and the second one is **s-channel scattering**. Which process happens when you collide two particles is determined by the energy.
### Diffraction vs. s-Channel Scattering 




![This figure illustrates the two primary physical processes occurring in fixed-target hadron experiments at intermediate energies: **diffraction** and **s-channel scattering**.  - On the left, the diagram represents **diffraction**, where an incoming photon ( $\gamma$ ) interacts with a stationary proton ( $p$ ) via the exchange of a color-neutral **gluonic field**, phenomenologically described as a **Pomeron**. This process is characteristic at higher energies (around 20 GeV), where the proton acts as a source of strong interaction fields. The photon is excited through interaction with the gluonic field, producing a final hadronic state, with the proton typically remaining intact.  - On the right, the diagram depicts **s-channel scattering**, which occurs predominantly at lower energies (2–3 GeV). Here, an incoming pion ( $\pi$ ) collides with a proton ( $p$ ), and both particles can resonate together via an intermediate state (the "X" in the middle), forming a true resonance. The final state contains specific outgoing hadrons resulting from this short-lived intermediate state.  These processes are distinguished by their production mechanisms: **diffraction** involves exchange of a Pomeron (gluonic field) and typically dominates at higher energies, while **s-channel scattering** proceeds through the formation of a resonant intermediate state and is more prevalent at lower energies. This distinction is crucial for understanding hadron production and excitation patterns in experiments like GlueX and COMPASS, as described in the lecture.](2024-Lecture-04-images/fig8.png){#fig-fg8}






*   **Diffraction:** This process uses the proton as the source of the strong interaction field. The proton sits and emits gluons. A pion or a photon comes and interacts with these gluonic fields and gets excited. The excited state  $X$  then flies for a bit and decays.
*   When we say "for a bit," it's not a physical flight in the detector. We are talking about strong interactions and hadronic resonances. Light hadronic resonances live for about  $10^{-25}$  seconds, which is not sufficient time at these energies to move away from the primary vertex. However, on diagrams we sketch them as separate particles.

*   **s-Channel Scattering:** This process is more plausible at lower energies, typically around 2–3 GeV. Here, the proton and the incoming beam (pion or photon) can resonate at a specific frequency.

For fixed-target kinematics, experiments like COMPASS separate the regime of diffraction from the regime of s-channel production to study baryonic excitations.


::: callout-note
The exchanged object in diffraction is not a single gluon (the proton must remain color neutral). It is a color-neutral gluonic field, described phenomenologically by the **Pomeron**. The Pomeron is not a fundamental particle found in the Particle Data Group (PDG) listings but is a useful way to model this interaction.
:::

### Exclusive vs. Inclusive Processes & Kinematic Counting

We now move to discussing **exclusive reactions**, where all final-state particles are measured ( $2 \to n$ ). This is in contrast to **inclusive** processes, where a system is produced alongside many other particles that are not measured.

To analyze an exclusive process, we need to count its independent **kinematic variables**. The method is:

1.  Count the independent components of all particle momenta.
2.  Subtract constraints from energy-momentum conservation.
3.  Optionally subtract degrees of freedom fixed by choosing a specific reference frame.

**Example: A  $2 \to 3$  Process**

*   Each of the 5 particles has a four-momentum  $p_i^\mu = (E_i, \mathbf{p}_i)$ .
*   The **mass-shell condition**  $p_i^2 = E_i^2 - \mathbf{p}_i^2 = m_i^2$  reduces each four-vector to 3 independent components.
*   **Energy-momentum conservation**,  $\delta^4(P_{\text{initial}} - \sum p_i)$ , imposes 4 constraints.

The count before fixing a frame is:
  $$N_{\text{vars}} = (5 \text{ particles}) \times (3 \text{ components}) - 4 \text{ constraints} = 11$$  

By choosing a specific frame (fixing 3 rotations and 3 boosts), we lose 6 more degrees of freedom, leaving **5 independent variables** to describe the kinematics.

### Phase Space and its Element

For cross-section calculations, we need the **Lorentz Invariant Phase Space (LIPS) element**, which counts the number of accessible kinematic configurations. For an  $n$ -particle final state, it is:

  $$d\Phi_n = \left[ \prod_{i=1}^n \frac{d^3 \mathbf{p}_i}{(2\pi)^3 \, 2E_i} \right] (2\pi)^4 \delta^4\!\left(P_{\text{initial}} - \sum_{i=1}^n p_i\right)$$  

**Key points about this formula:**

*   The factor  $\frac{d^3 \mathbf{p}_i}{(2\pi)^3 2E_i}$  for each particle comes from integrating over its four-momentum and enforcing the mass-shell condition.
*   The  $(2\pi)^4 \delta^4(...)$  enforces total energy and momentum conservation.
*   This element is Lorentz invariant, meaning it has the same form in any inertial reference frame.

Phase space for complex processes (e.g., a  $1 \to 4$  decay) can often be evaluated recursively by factorizing it into successive two-body phase spaces, which is a kinematic simplification, not a dynamical one.



## Recursive Phase Space Parameterization

When you calculate the phase space, you see that three integrals come for every particle. That's why I have a factor of three here for every particle in the phase space.

Here we have a final state and an initial state. For the phase space to count, you only count the final state. So you see the initial state doesn't enter.

Then the four energy-momentum conservation conditions come here explicitly. That's the number of the integrals that remain. That gives you three times four: twelve, minus four remains eight.

This is the five kinematic variables. So five plus three overall rotations, which is five variables. The three rotations are the Euler angles. But which five I pick to parameterize my kinematics is up to me.

One has to choose these five in the most convenient way to calculate dynamics, because it's not going to tell you what interactions you have in these vertices. It doesn't even tell you that your reactions happen in this cascade way. It's just purely kinematical parameterization. It's your choice of the kinematic variables.

One particular choice is to say I'm going to introduce  $M_X$  here and  $M_Y$  there and write my phase space as the integral  $\frac{dM_X^2}{2\pi} \frac{dM_Y^2}{2\pi} \, d\Phi_2(P \to p_X, p_Y) \, d\Phi_3(p_Y \to p_1, p_2, p_3)$ . That's what is referred to as the **recursive expression**.

It's not only valid for two, but you can also do this for three. The important thing is that they introduce a variable that is the sort of intermediate mass of the combination and you integrate over this variable, and every integral comes with a  $2\pi$  in the denominator.

Just another example: if I just introduce  $d\Phi_2(P \to p_Y, p_4)$  and then  $d\Phi_3(p_Y \to p_1, p_2, p_3)$ , that's also legal. That's fine.


::: callout-note
The general formula for an  $n$ -body final state is:
  $$d\Phi_n(P; p_1, \dots, p_n) = (2\pi)^4 \delta^{(4)}\left(P - \sum_{i=1}^n p_i\right) \prod_{i=1}^n \frac{d^3p_i}{(2\pi)^3 2E_i}$$  
The number of independent kinematic variables is  $3n - 4$ .
:::




![This diagram represents a typical **cascade decay chain** in a multi-particle final state process, often encountered in hadron spectroscopy experiments. Here, an initial state produces an intermediate resonance  $X$  (after vertex 1), which subsequently decays into another intermediate state (at point 2), followed by further decays resulting in final state particles labeled 3 and 4. The particle denoted "i" appears to decay into a multi-particle final state, as indicated by the several lines emerging from it.  Physically, this diagram illustrates how a **complex decay topology** is analyzed via **exclusive processes** (where all final state particles are measured), as discussed in the lecture. Each vertex represents a step in the decay where **energy-momentum conservation** applies, and the overall structure enables the use of **recursive phase space factorization**. For example, the total  $n$ -body phase space  $d\Phi_n$  can be decomposed into products of two- and three-body phase spaces at each vertex, integrating over intermediate invariant masses (e.g.,  $M_X$ ). This is foundational for reconstructing resonance signals, calculating invariant mass distributions (such as those used in Dalitz plots), and determining the kinematic variables required to describe multi-body decays in hadron spectroscopy experiments.](2024-Lecture-04-images/fig10.png){#fig-fg10}




 For a 4-body decay ( $n=4$ ), this gives  $3 \times 4 - 4 = 8$  variables, as mentioned.

Once you learn this trick, this calculation of the phase space is super straightforward because every two-to-two phase space is  $\frac{2p}{\sqrt{s}} \frac{d\Omega}{4\pi} \times \frac{1}{2\pi}$ . So this does not have any simplification.



## Two-Body Phase Space and Introduction to the Dalitz Plot

---

We have now completed a **more general treatment** for the **two-body phase space**.

With this expression and the general formula, you are equipped to calculate **any n-body phase space**. As a next step, there is an exercise for you to try at home: play with the **three-body phase space**.

The **three-body phase space** will have:

* Three particles × three coordinates = **9** initial degrees of freedom.
* Minus **4** constraints from energy-momentum conservation.
* Minus **3** from overall rotations.

This leaves only **two independent variables**. The resulting distribution is often represented using these two variables.

A common choice for these two variables is to use **invariant masses** of particle pairs. When plotted, this representation is called the **Dalitz plot**.


::: callout-tip
In a three-body decay, the **Dalitz plot** is a two-dimensional distribution where each point corresponds to a specific pair of invariant masses squared. It visually encodes the entire dynamics of the decay, making it a powerful tool for analyzing resonances and interaction mechanisms.
:::

