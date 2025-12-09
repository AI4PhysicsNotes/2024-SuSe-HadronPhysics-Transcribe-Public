---
title: (2025) Lecture 9
author: ''
presenter: Mikhail Mikhasenko
note_taker: Anna Zimmer
date: '2025'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



## Analyticity and Unitarity in Scattering Amplitudes

### Lecture 9: Recap and Introduction to Analyticity

We start with a recap of the previous lecture.

Let's discuss the problems. Who is finished with the first? Who is finished with the second? Good.

Then, what's the name of the area of the decay that we have here? The usual representation of the decay in the coordinates of the invariants is called a **Dalitz plot**, but you can use the same type of coordinates for the crossed process, for the scattering process.

I don't want you to know the equation by heart, but rather I want to stress that the same equation would be relevant not just for the Dalitz plot and the decay region, but exactly the same equation would determine the border of the scattering process.

So, can anyone tell me what equation that is? It's the **Kibble function**. The Kibble function of  $s, t, u$  is equal to zero. The Kibble function is also known as the Chew function. The Chew function depends on the mass of the decaying particle, the pair mass of the two particles, and then the other one.


::: callout-important
The **Kibble (or Chew) function** defines the boundary of the physical region in scattering or decay processes (e.g., a Dalitz plot) in terms of Mandelstam variables  $s, t, u$ . It ensures energy-momentum conservation and relates to the condition that the scattering angle cosine is  $\pm 1$ :
  $$\Phi(s, t, u) = 0$$  
where  $\Phi$  is often expressed as:
  $$\Phi(s, t, u) = s t u - (m_1^2 s^2 + m_2^2 t^2 + m_3^2 u^2) + \text{(mass-dependent terms)} = 0$$  
This describes the kinematic limits for processes like  $\pi^+ \pi^0 \to \pi^- \pi^0$  or crossed channels.
:::

If you want to plot the area, you just look for the solutions in the plane. It's easy to derive this from scattering or for the decay. The fact that it describes both appears as the fact that you change one particle to the other side does not change the kinematics. 




![This figure represents the **Mandelstam plane**, a plot with axes labeled by the Mandelstam variables  $s$  and  $t$ , which describe the kinematics of scattering processes. The "physical region" indicated in the diagram corresponds to the subset of allowed values of  $s$  and  $t$  where the scattering or decay process can physically occur, determined by kinematic constraints (such as the Kibble or Chew function discussed in the lecture). Outside this region, the amplitude can still be defined by analytic continuation, but does not correspond to direct physical processes—these are the unshaded or shaded regions outside the "physical region" boundary. The diagram illustrates how analytic properties of scattering amplitudes extend beyond the physical region into the complex Mandelstam plane, a concept central to the analytic approach to scattering theory described in the lecture.](2025-Lecture-09-images/fig11.png){#fig-fg11}






This condition comes from considering the scattering angle and requiring that the scattering angle is either plus one or minus one; this determines the border. The meaning of this scattering angle changes a little bit once you go from the scattering domain to the decay domain.

You see it in the rest frame of two particles. Let's say it's the  $s$  channel: here's particle 1, here's particle 2, 1, 2, 3. And then this is the  $\cos \theta$ . The condition for the border is determined by the equations that  $\cos \theta$  is equal to plus one or minus one. It's the same for the decay and for the scattering.

It's just the direction of this arrow would change. For the decay, two particles collide and the system that you consider is the center of mass for the whole system. For the scattering, that's for the scattering. For the decay, it's just a subsystem of the final state.

The way how you derive it: you write the cosine in terms of the invariants and then you set  $\cos \theta = 1$  and you arrive at this same equation.

I'm surprised you need scattering. I suppose most of the variables are defined to be for momentum and then you use energy conservation, and I guess you can somehow introduce cusp functions. The channel function is just a breakup momentum.

I would consider this once you derive it, once you can consider this as common knowledge. It's easy to remember. You have derived this one or you look it up in the Bickerstaff-Cajandji book.

The recipe is you start with the scattering kinematics, and that's unique because you know that the ranges of the physical region correspond to the cosine going to being plus one or minus one.

But let's not get distracted because there's a lot of material here. The one thing to realize is that once you put this into Mathematica and ask what are the regions in the two-dimensional plane where this equation is satisfied, you don't get only this region; you also get the other regions that correspond to the cross process.

Here I'm asking: what are the other physical processes that are connected by crossing and draw the regions? The answer here is that the regions will lie somewhere here, and these lines where also the Kibble function is zero are the borders of the other process.

You understand them by looking at your original kinematics. So if this is zero going to 1, 2, 3, that process. Then here we define  $s$  so that process would correspond to—so the variable  $s$  that you have here for any place inside of the Dalitz plot is a positive quantity and you want to keep it positive.

For this area it's bigger but it's also positive, while the other one becomes negative. For this area these two particles are still in the physical space, so they are in either initial state or final state, while the other one you get crossed to the other side.

So it's a  $0, \bar{3}$  scattering into the 1, 2. The process that we talk about when we discuss this domain is  $\pi^+ \pi^0$ , so  $\pi^+ \pi^0$  scattered with the other particle that was a  $\pi^-$ . Then we put it to there by  $+ \omega \pi^0$  and we talk about this domain, but in terms of  $\pi^- \pi^0$  and  $\omega$ , what is 1, 2 and 3?

One has to be always consistent, so this zero depends on the axis. So the  $\omega \pi$ . I call this one, this is two, this is three. So the process here would be zero. But why? For the first process we moved  $\pi^-$  to the other side, not  $\pi^0$ .

Because one axis is  $\omega \pi^0$  and another one is  $\pi^- \pi^0$ , right?  $\pi^-$ . No, it's diagonal. No, it's  $\pi^- \pi^0$ . So that one. So then if there are two  $\pi^0$ s, shouldn't we move  $\pi^0$  to the other side? So I argue that way.

I have here  $\omega$  and I have here  $\pi^0$ . That's what my channel represents. That's a threshold for their channel. That's up to the threshold for that channel. And that will be production threshold for the initial state. I always have this  $s$  increasing along this axis.

Are these asymptotes of the locus, like a hyperbola? I'm asking because like in the original Mandelstam paper, they're not. They try to go over it. I never understood. No, going over is fine. But the question is, do they approach them at the infinite energy region and that's where you can neglect the masses? I think so.

Asymptotes means not here and they can cross. But when the energy gets high, do you approach this line? I think so. Well, is it that line or is it another line? The close one is that it's slightly offset by the threshold.

Let me draw it here, what scattering process we are dealing with. So the zero scatters with the particle. So 1, 2, 1 3, 2 3. So the energy gets positive. And here is the zero with one bar. So the process here is the  $\pi^+ \pi^0 \omega$  goes to  $\pi^- \pi^0$ .

Then you see that for the particle that you cross to the other side becomes an antiparticle. But for  $\omega$  and for  $\pi^0$ , particle and antiparticle is the same. Things get a bit more tricky once you take into account that particles have spin.

So in fact I should have written here lambda because  $\omega$  has spin and then helicities; they also have peculiar relations with respect to the crossing. We don't talk about that. So for the kinematical considerations it's enough. You can think of particles as scalars.

To really relate the amplitudes with helicity indices requires more work. Draw regions, indicate process. I think we did draw roughly the regions together. More accurately you have to open a computational notebook, otherwise it's intuitive.

### Unitarity and the Optical Theorem

So, questions here quickly. The second unitarity equations. So we consider an elastic scattering process. Shall we break this down. What does it mean? What is  $s$  and  $t$ ? Maybe you guys follow what is  $A$ ? What  $s$  for the same?  $A$  is scattering amplitude,  $s$  is Mandelstam  $s$ .

What does it refer to? Like how do you compute this variable? It's like  $p_0, p_1$ . And  $t$  is a Mandelstam variable related to the difference of these two momenta and then scattering amplitude. I'm saying process, but in fact it's a scattering amplitude.

What does elastic mean here? I don't think we discussed elastic, but maybe you heard of this. Energy is conserved. Energy is always conserved. That we're doing the same check. Exactly. So the initial state and the final state are the same. That's what I mean.

Actually here it's somewhat slang and the elastic is used in a different context. But when we talk about elastic process we usually say initial state is the same as the final state. Elastic scattering.

Formulate  $A$  using explicit dependence. Formulate partial wave in unitarity and optical theorem. Can you tell me in the unitarity equation for  $A$ , maybe can you help me? Is he like what should I relate.

I mean, what is it about? I don't know how you've so far introduced amplitudes. I always see that this normalized with regards to that energy which introduces a phase space factor. So I would say it's like  $1 + i \rho A$ . So I want to write the unitarity equation for  $A$ .

So how unitarity constrains my  $A$  and in fact what you... When you do this consideration, as you say follow, you get constrained to the imaginary part of  $A$  and then the imaginary part of  $A$  is related to other amplitudes.

So maybe I draw it diagrammatically first and then you help me to get the equations. But this is the optical theorem, right? No, that's the unitarity equation for  $A$ . What is different between  $t, t'$  and  $t''$ ? Very good.

We are discussing the elastic process. And so  $s$  and  $t$  are defined. Here you have. Imaginary part of amplitude is related to the amplitude squared in the elastic region. This is the unitarity equation one has to integrate over all intermediate states when you contract one amplitude to another.

But since it's elastic, it's the same state that is present here. So the same particles, the only difference. Well, the integration actually takes into account that the configuration of the particles in the intermediate states could be different.

If I consider this process of initial state scattering to the final state, let's say it, the intermediate state that appears in unitarity equations. Well, essentially what the unitarity equation says, is that you have to sum over all intermediate states that appear for the elastic region.

It's just different configurations. There is only one type of particle states that are present. And therefore integration over phase space includes only different orientations of the particles. They are the same particles.

Once you go to high energy, there will be many more intermediate states that come into the unitarity equations. But to clarify, maybe this drawing can clarify the configuration. What we have to integrate over.

We fix the initial state, we fix the final state and then the  $t$  is the scattering angle between the initial and final state. We say they form a plane. This sits in the x-z plane. So here is the x axis, here is the z axis here in the plane.

The only variable that we have,  $t$  is connected to the scattering angle between initial and final state. So this angle  $\theta$  describes is connected to the  $t$ . What appears in the intermediate state is the arbitrary configuration in the space of the vector of the intermediate state here.

I call here the  $p_1, p_2$ . Here is the  $q_3 q_4$  and here is the  $p_3 p_4$ . So here there are two scattering processes. First from  $p$  to  $q$  and then from  $q$  to  $p$  again. So we have to integrate, so the plane is fixed, the  $q$  points somewhere in the space and we have to integrate over all possible configurations.

That's why the  $t'$  and  $t''$  come in. And then this is the unitarity equation for the full amplitude. Great simplification. Can you write phase space explicitly? Because  $t'$  and  $t''$  are, what they should be in the phase space.

It's a regular two-body phase space. We have to integrate over all possible configurations of one vector and a second vector. But there is a constraint making them back to back to each other. Writing this in terms of the  $t'$  and  $t''$  is really a highly non-trivial task.

The way to proceed actually to get our regular unitarity that we know and like—where amplitude is related to itself—requires partial wave expansion. So the next step would be to take each amplitude  $A$  here,  $A$  here and  $A$  there and expand them into partial waves.

The partial waves would involve connection between scattering angle in the  $t$  or  $t''$ . And then we use properties of the angular momentum of the angular functions to get rid of this integral essentially.

And then once we do, this equation becomes very simple. Instead of the integral of the phase space, we have simply a phase space factor. It's not an integral, it's just an energy-dependent factor. So this  $\rho$  is  $\frac{1}{16 \pi^2} \times \frac{p}{2\sqrt{s}}$ .

The  $p$  is the breakup momentum in the system. It's a function of the energy. And then here  $A$  appears. That's the unitarity equation for the partial wave. Partial wave amplitude has only one dependence on  $s$  and things drastically simplify. There is no  $t$  any longer.


::: callout-important
The **unitarity equation** for the elastic scattering amplitude  $A(s, t)$  ensures probability conservation. It relates the imaginary part of the amplitude to an integral over intermediate states:
  $$2 \, \text{Im} \, A(s, t) = \int d\Phi_2 \, A^*(s, t') \, A(s, t'')$$  
where  $d\Phi_2$  is the two-body phase space, and  $t', t''$  are momentum transfers for intermediate configurations. This is a manifestation of the optical theorem.
:::


::: callout-note
Expanding the amplitude in partial waves  $a_\ell(s)$  simplifies the unitarity condition, as different angular momenta decouple:
  $$\text{Im} \, a_\ell(s) = \rho(s) \, |a_\ell(s)|^2$$  
where  $\rho(s) = \frac{1}{16\pi^2} \frac{q}{2\sqrt{s}}$  is the phase space factor, and  $q$  is the breakup momentum. This implies  $a_\ell(s)$  can be written as  $a_\ell(s) = \frac{1}{\rho(s)} \sin \delta_\ell(s) e^{i\delta_\ell(s)}$ , with  $\delta_\ell(s)$  the phase shift.
:::

Another thing I wanted to point out coming back here is that you see that there is a  $t'$  and  $t''$ . The reason they are different is because  $t'$  is measured for the vector  $q$  with respect to the  $p_1$ , right? So it's an amplitude computed between  $q_3$  and  $p_1$ .

So this vector and that vector and then  $q_3$ . So  $t''$  is computed between  $q_3$  and  $p_3$ . So it's an intermediate and final state. So either you take these vectors or you take these vectors or these vectors and that's what makes the variables different.

There is one limit when these variables are becoming the same. When you have not just elastic scattering, but forward scattering. When you have kinematics, you collide the particles and then they just pass through. It's forward scattering.

In that case  $A$  is equal to... Sorry,  $t$  is equal to 0. And in that case, if  $p_1$  is equal to  $p_4$ ,  $t$  and  $t'$  becomes the same,  $t'$  and  $t''$  become the same. There are two values for  $t$ ,  $t$  equal to 0 and  $t$  equal to its maximum.

Another negative value. So for this type of scattering, forward and backwards. For the backward, the  $t$  equals to its maximum value, it's negative. Exactly. But for the forward scattering. You're right, but it's a different limit.

So now I want to discuss the forward limit. In the forward limit, the point is that this amplitude becomes the same as this amplitude. And we can write squared amplitude already right here.

My question was, isn't it the same for backward as well? No, I don't think it's. No, it's not. The reason is like forward we have to consider this is a  $p_1$  and then this is the  $q$  and this is the  $p_3$  and this is the  $q$ , right? That's a form  $q_3$ , that's forward scattering.

And that's why what makes them, what makes this angle to be the same as this angle? If you consider backward scattering, so  $p_3$  will be in that direction,  $q_3$  will be this and the angle is this. So it's different.

You can identify  $t'$  and  $t''$  to be the same in a backward scattering? So finishing this I wanted to give the final expression for the optical theorem that comes from this is the following. It's, but this, nothing else but the full cross section.

And here you have an optical theorem. Amplitude for the forward scattering is equal to the flux times the full cross section. It's important to acknowledge the fact here that it's valid in the elastic region.

Forward scattering is really important because that's when you identify that's how you get rid of one of the variables. The cross section is a function of  $s$  only. The total cross section doesn't know anything about angular dependence.

So you integrate this and this happens once you identify two amplitudes to be the same and take into account the phase space. It's from unitarity. So this is the first condition wrote down and what comes down.

So the dependence on the cross section and the flux is the optical theorem for you. So what is what here? I can understand you correctly. The first is unitarity. The second is optical theorem. The second is optical theorem.

I'm not sure we discussed this last time, but optical theorem comes in quantum mechanics. That's mentioned. And here is this analog of this related to the transition matrix element amplitude we have in the scattering process.


::: callout-important
The **Optical Theorem** is a special case of unitarity for forward scattering ( $t = 0$ ), relating the imaginary part of the forward amplitude to the total cross section  $\sigma_{\text{tot}}(s)$ :
  $$\text{Im} \, A(s, t=0) = 2 \sqrt{s} \, q \, \sigma_{\text{tot}}(s)$$  
or equivalently,
  $$\sigma_{\text{tot}}(s) = \frac{1}{2q\sqrt{s}} \, \text{Im} \, A(s, t=0)$$  
This connects the amplitude's analytic properties to measurable cross sections.
:::

Recap. Well, since it's recap, let's recap once again the recap. The unitarity for  $A$  is this. And then explicitly all variables are mentioned. The cosine is the function that defines the  $t$ .

So you can either write the  $t$  as a function of the  $s$  and cosine or cosine as a function of  $s$  and  $t$ . So two of them are independent. So here is the equation for the unitarity.

Partial wave unitarity comes when you get rid of the angle dependence. And then  $L$  here is the summation index. It's partial waves. And then what is interesting here worth noticing is that partial waves don't talk to each other.

Only  $L$  that is on the left appears on the right. So these properties of the polynomials help you to identify the terms. And  $a_L$  is a function of  $s$  only, there is no  $t$  any longer.

Finally, optical theorem. Optical theorem is the relation of the amplitude for the forward scattering to the total cross section. Good. And then when we discussed optical theorem last time. So that's good that we discussed today. It's important to relate the concepts to each other.

### Introduction to Analyticity and Complex Functions

Today in the lecture we will go through analytic functions and see how scattering matrix principles are constrained by their properties. How scattering amplitudes are constrained by the properties of the scattering matrix, such as its analyticity and particularly crossing symmetry.

To consider this first part, I want to make the first part a little bit more mathematical, discussing analytic functions and real analytic functions. I will say a few words about analytic continuation at the end.

In hadron physics we deal with interactions that are not driven by simple Lagrangian or Hamiltonian dynamics. We cannot proceed unless we restrict ourselves to specific near-threshold interactions. We cannot derive the scattering amplitudes from first principles. 




![This figure represents a schematic energy spectrum of hadronic states, specifically showing the quantum mechanical levels of a two-particle system (for instance, a pion–pion or pion–strange meson system) as a function of a variable labeled "lqq," which likely refers to quantum numbers or a kinematic variable relevant in the study of hadron physics. The vertical axis is energy ( $E$ ), while the horizontal axis shows "lqq".  The diagram features boxes corresponding to different energy levels and angular momentum (orbital) quantum numbers:   - "1S" and "2S" indicate the first and second S-wave (zero orbital angular momentum) states, while   - "1P" indicates the first P-wave (one unit of orbital angular momentum) state.  In the context of the lecture, which discusses scattering theory, analytic properties, and resonance spectroscopy, this diagram illustrates how physical resonances (hadronic states) appear as discrete levels in energy for two-particle systems, categorized by their angular momentum. The variables within the boxes—such as  $a_0, a_2, b_4$ —represent scattering parameters or possibly resonance parameters like scattering lengths (for different partial waves). This reflects how amplitude analysis and the study of analytic functions in the S-matrix formalism enable the extraction and classification of resonance parameters from the energy dependence of scattering amplitudes. The structure of the levels ties into discussions of analytic properties, poles (resonances), and real analyticity as these physical states correspond to singularities (poles) in the complex energy plane.](2025-Lecture-09-images/fig13.png){#fig-fg13}






Instead, a different approach is used. We study the general principles of scattering theory. And it appears to be constraining enough to derive the general form of the amplitude, having parametric freedom in certain places that can be fixed from the data.

Therefore, the approach that is utilized in hadron physics to describe the scattering of hadrons, especially from experimental data, is to use general parameterizations of the amplitudes that satisfy unitarity and analyticity.

Rarely crossing symmetry, very rarely can be included. And then we fix the parametric freedom and get the scattering amplitude as a mathematical expression and study its properties.

While studying the properties of the scattering amplitude, we get properties of the objects that we describe, the resonances. So that's the program of hadron spectroscopy: amplitude building and using scattering theory tools to have access to the properties of the objects.

We study resonances and analyticity is one of the constraints; unitarity is another one, especially telling that the function is constrained in different regions of the variables.

If a function depends on  $s$  and  $t$ , this function must extend, since its validity goes beyond the physical region, and extra constraints come in. And then we consider the amplitude as a complex function of its variables. The scattering amplitude.

While observables are all real values. The cross section is a real number. The amplitude itself is a complex number and it has a value; it has an absolute value and it has a phase. And this in turn gives important information about the scattering process.

Let me start with the fact that as we saw in the problem we discussed there, the amplitude was a function of the two variables  $s$  and  $t$ . 




![This figure illustrates the analytic structure and kinematic channels of the pion-pion ( $\pi\pi$ ) scattering amplitude as a function of the Mandelstam variable  $s$ :  - **Left Side (Complex  $s$ -Plane):**     The horizontal axis represents the real part of the complex Mandelstam variable  $s$ , and the vertical axis is the imaginary part. The amplitude  $A_{\pi\pi \rightarrow \pi\pi,\rho}(s)$  is analytic except along cuts, which are indicated on the real axis. The solid blue line starting at the threshold  $4m_\pi^2$  (where  $m_\pi$  is the pion mass) represents the **s-channel unitarity cut**, i.e., the physical region where two-pion production becomes kinematically allowed. This is the beginning of the non-analytic region associated with the opening of the  $\pi\pi$  channel. The blue region labeled "u-channel" on the negative real axis represents the unitarity cut for the crossed channel, corresponding to different intermediate states due to crossing symmetry. The label "cardinal sheet" refers to the principal (physical) Riemann sheet of the analytic amplitude. The threshold marks the onset of physical two-pion states, relating to where the imaginary part of the amplitude (discontinuity) develops, as discussed under analytic and real analytic functions and their branch cuts.  - **Right Side (Feynman Diagram):**     This shows a generic  $2 \to 2$  pion scattering process: two incoming pions ( $\pi_1, \pi_2$ ) scatter via an interaction blob into two outgoing pions ( $\pi_3, \pi_4$ ). The Mandelstam variable  $s$  labels the center-of-mass energy squared of the incoming channel, and  $t$  labels the momentum transfer. This diagram is used to define the physical process that the complex  $s$ -plane structure corresponds to, connecting the analytic properties of the amplitude to physical scattering.  **Physical meaning in context:**   This figure visually connects the analytic properties (cuts, thresholds, Riemann sheets) of the scattering amplitude in the complex  $s$ -plane with their physical origins in pion-pion scattering. Concepts like the unitarity cut, threshold, and crossing symmetry (s-channel and u-channel) are depicted, illustrating how non-analyticities (branch cuts) in the amplitude arise from opening physical channels—key points in the study of analyticity and scattering theory as discussed in the lecture.](2025-Lecture-09-images/fig10.png){#fig-fg10}




 So it's a multivariable function. 




![This figure illustrates the physical manifestations of different singularities of the scattering amplitude  $a$  in the complex energy plane, as discussed in the context of analyticity and amplitude analysis. The horizontal axis represents  $\sqrt{s}$ , where  $s$  is a Mandelstam variable related to the squared center-of-mass energy, while the vertical axis shows  $|a|^2$ , the squared modulus of the scattering amplitude, which is related to observable probabilities or cross sections.  - The **top panel** depicts a **resonance**, characterized by a pronounced peak in  $|a|^2$  above the threshold. The resonance is associated with a pole in the complex  $s$ -plane near the real axis. The curve rises sharply, reaches a maximum (the resonance energy or mass), then falls off. The threshold marks the lowest energy where the reaction can occur. The nearby **branch point** is also indicated, signifying the opening of the physical channel (threshold), and the analytic continuation shows how singularities influence the physical amplitude.  - The **middle panel** shows a **bound state**, which appears as a divergence in  $|a|^2$  below the threshold, indicated by a pole on the real axis below threshold. This manifests as a sharp feature (essentially a "delta function"-like effect in the cross-section) signaling a stable particle or state that cannot decay into the considered channel.  - The **bottom panel** demonstrates a **virtual state**, which manifests as a cusp or an enhancement right at the threshold, but there is no true resonance peak or bound state pole on the physical sheet. The cusp reflects the analytic structure of the amplitude due to a pole on the unphysical sheet, which doesn't correspond to a particle but still impacts the observable cross-section near threshold.  These cases illustrate how underlying singularities in the analytic structure of the scattering amplitude (poles and branch points in the complex  $s$ -plane) physically manifest as observable features—resonances, bound state divergences, or threshold cusps—in experimental scattering data. The analytic continuation concept is critical for understanding how such "hidden" (complex-plane) singularities influence real, measurable quantities due to the analyticity and real analytic properties of the amplitude.](2025-Lecture-09-images/fig14.png){#fig-fg14}




 It's a complex multivariable function.

It appears that we will get some benefits and new insights into the amplitude if we consider not just the amplitude to be a complex function, but also for it to be a function of complex variables.

So what we are going to do as the sort of imaginary and theoretical part of the theoretical exploration is we will make our  $s$  variable—a physical thing, something that used to be physical—we will make it complex.

We'll see what the properties of the amplitude are when we make the energy of the scattering complex, or when we make the angle of the scattering a complex number, not 30 degrees, but 30 degrees plus i or something. And we'll see it gives us new insight.

So what is important for us is not just that the amplitude is a complex function, but also that it's an analytic function of its arguments everywhere in the complex plane, except a few minor segments.

Before going into the details, I would like to discuss analytic functions. So here is the mathematical part of the lecture. I would like to remind you what analytic functions are, or the other way we call them is holomorphic.

Holomorphic just simply means analytic. Holomorphic or analytic functions are functions that match their Taylor series in the vicinity of every point of the complex plane or of the domain.

If you look in mathematics books, it says an analytic function is one that is complex differentiable everywhere in the complex plane. But we will consider a domain of analyticity. The function doesn't have to be analytic everywhere in the complex plane, but in certain domains.

And then in that domain, complex differentiability simply means that it's equal to its Taylor series. So there is a polynomial series that approximates the function exactly at every point of the plane or in the vicinity of every point.

I could remind you what the Taylor series means, but you probably remember that expression with the derivatives—essentially a polynomial. That's the point. And the series can go to infinity, but the function must match it.

Let's discuss examples. Clearly, if required, the function matches the polynomial series. Any polynomial function is analytic in  $\mathbb{C}$ . Polynomials are excellent functions analytic everywhere, but also the boring functions like the square root of  $z$ , log  $z$ , are functions that are analytic everywhere except on a line segment.

This line segment is the cut. For every cut we have two branch points. Sometimes one of the branch points is at infinity, another in the finite range. And then the line that connects the branch points is called the branch cut. 




![This figure illustrates the analytic structure of a function in the complex  $z$ -plane, focusing on the concept of branch points and branch cuts. The point at the origin is labeled as a **branch point**, from which a **branch cut** extends along the negative real axis. This reflects the analytic properties of functions like  $\sqrt{z}$ , which are analytic everywhere except along the branch cut that starts at the branch point (here,  $z=0$ ).  Physically, in the context of the lecture, this is used to describe how complex functions (such as scattering amplitudes) behave: they are analytic in most of the complex plane, but exhibit non-analytic behavior (discontinuity) when crossing the branch cut. At points just above or below the cut (e.g.,  $f(-1 + i\epsilon)$  vs.  $f(-1 - i\epsilon)$ ), the function takes different values, highlighting the multivalued nature due to the branch point. This property is crucial for understanding the analytic structure of scattering amplitudes, where cuts and branch points correspond to physical thresholds and the opening of new channels, and dictate how analytic continuation—and hence the exploration of resonances, unitarity, and causality—are treated in quantum field theory.](2025-Lecture-09-images/fig1.png){#fig-fg1}






Let me draw a few examples convenient to discuss. The  $z$  plane, where along the x axis we have the real part of  $z$  and the y axis is the imaginary part of  $z$ . And then for every point I can plot, it is the real part plus i times the imaginary part.

So what I can do using this plot is to indicate where a function is analytic and where it is not. There are regions of non-analyticity. For example, for the function square root of  $z$ , there is a branch point at zero and a branch cut going to the left, indicating that if I compute the function on one side and on the other side I get different values.

If I compute the square root of  $z$  at minus 1 plus a little bit, I get plus i. 




![This figure illustrates the analytic structure of the function  $f(z) = \sqrt{z - 1}$  in the complex  $z$ -plane. The horizontal axis represents the real part of  $z$  ( $\mathrm{Re}(z)$ ), and the vertical axis represents the imaginary part ( $\mathrm{Im}(z)$ ).   The blue wavy line begins at the point  $z = 1$  on the real axis and extends to  $-\infty$  along the real axis. This line marks the **branch cut** of the function, which connects the **branch point** at  $z = 1$  to  $-\infty$ .   Physically, this illustrates the concept that functions like  $\sqrt{z-1}$ , which appear in the description of scattering amplitudes, are analytic everywhere in the complex plane except along their branch cut. The presence of the branch point and associated cut means that the value of the function is discontinuous across the cut, reflecting the multi-sheeted nature of such complex functions. This analytic structure is fundamental in understanding how scattering amplitudes behave as functions of complex variables, especially when we discuss analytic continuation and the physical meaning of singularities and discontinuities in scattering theory.](2025-Lecture-09-images/fig2.png){#fig-fg2}




 And if I compute it from that side, I get minus i. 




![This figure represents the analytic structure of the complex function  $f(z) = \sqrt{z-1} - \sqrt{z}$  in the complex  $z$ -plane. The real axis is labeled as "Re" and the imaginary axis as "Im." The blue wavy line running from  $z = 0$  to  $z = 1$  along the real axis indicates a **branch cut**—a region where the function is non-analytic due to the multivalued nature of the square root functions.   Physically, this branch cut corresponds to a discontinuity in the value of the function as you cross from just above to just below the real axis, reflecting a non-trivial analytic structure. In the context of scattering amplitudes discussed in the lecture, such branch cuts represent kinematic thresholds—boundaries in the complex energy plane (or similar Mandelstam variables) where new physical processes (such as particle production) can occur and the amplitude develops an imaginary part.   This analytic feature is essential for understanding the behavior of scattering amplitudes, as the existence and location of branch cuts (and their associated **branch points** at  $z = 0$  and  $z = 1$ ) dictate where the amplitude ceases to be real and begins to have a discontinuity—properties crucial for unitarity and the correct physical description of processes.](2025-Lecture-09-images/fig4.png){#fig-fg4}




 It doesn't happen on that side. If I compute the function at 1 plus i epsilon, I get one. And if I compute it from that direction, like 1 minus i epsilon, I also get one. 




![This figure represents the analytic structure of the function  $f(z) = \sqrt{-z}$  in the complex  $z$ -plane. The plot shows a branch cut along the positive real axis, indicating the line segment where the function is non-analytic. This cut starts at the branch point at the origin ( $z=0$ ) and extends to  $+\infty$  along the real axis.  Physically, in the context of scattering amplitudes, such branch cuts correspond to the thresholds for physical processes, such as the onset of particle production or scattering channels, and the branch point represents where a new channel opens. The function is analytic everywhere else except along this branch cut. The existence of the branch cut is a manifestation of the multi-valuedness of the function (here, due to the square root), and the discontinuity across the cut reflects the appearance of an imaginary part in the amplitude, related to inelastic processes and the unitarity cut in scattering theory. This structure illustrates how analytic functions in physics, such as scattering amplitudes, are characterized by their branch points and cuts in the complex plane, which encode essential physical information about reaction thresholds and continuations to different Riemann sheets.](2025-Lecture-09-images/fig3.png){#fig-fg3}




 But on that side there is a discontinuity of the function.

Just to demonstrate that the branch cut doesn't have to be at 0. For the function square root of  $z - 1$ , the branch cut starts at 1 and goes backwards. For the function square root of  $-z$ , the branch cut starts at 0 and goes upwards. 




![This figure illustrates the analytic structure of the function  $f(z) = \sqrt{z^2 - 1}$  in the complex  $z$ -plane, specifically highlighting the locations of branch cuts and branch points. The real and imaginary axes are labeled as "Re" and "Im," and the function is annotated in the upper right.  Physically, in the context of the lecture, this type of function models the analytic structure one encounters in scattering amplitudes, where the square root reflects the opening of new channels or thresholds. The blue wavy lines represent branch cuts: one running from  $-\infty$  to  $-1$  along the real axis, and another from  $1$  to  $+\infty$ , indicating non-analytic (discontinuous) behavior of  $f(z)$  across these intervals. The endpoints  $z = -1$  and  $z = 1$  are branch points, signaling the start of the branch cuts and corresponding to physical thresholds (like the onset of new particle production in scattering).   This structure encodes how the amplitude (or any analytic function with such a branch cut structure) changes its value when moving around these points in the complex plane, which is crucial for understanding phenomena like the development of an imaginary part (related to physical processes becoming possible) and the analytic continuation to different Riemann sheets—core ideas in the analytic S-matrix approach discussed in the lecture.](2025-Lecture-09-images/fig5.png){#fig-fg5}






For the function square root of  $(z - 1) z$ , the branch cut starts at zero and goes to 1. For the function square root of  $z^2 - 1$ , the branch cut is more complicated. It starts at 1, goes to 0, then to plus infinity, comes back from minus infinity to minus 1.

The last example is the log of  $z$ . And in that case the branch cut starts at zero and goes backwards. Another class of functions and another type of singularities that is present is the poles. Poles are the functions that have poles.

They are isolated singularities where a function approaches infinity, complex infinity. So let's say  $\frac{1}{z - 1 + i}$ . So when  $z$  is equal to  $1 - i$ , we approach the pole of the function, the function is undefined, it's complex infinity. 




![This figure illustrates the concept of a **pole** in the complex plane, which is a type of isolated singularity important in the analytic structure of scattering amplitudes. The function shown,  $f(z) = \frac{1}{z - 1 + i}$ , has a pole at  $z = 1 - i$ , indicated by the black dot on the diagram at that coordinate in the complex  $z$ -plane (with the real and imaginary axes labeled).   Physically, such poles in the scattering amplitude correspond to resonances or bound states in hadron physics; the amplitude becomes very large near the pole, signaling a strong "signal" or enhancement in the cross section. In the analogy provided in the lecture, the pole is like an "internet router"—the amplitude is strongest (largest) when you are closest to the pole in the complex plane, reflecting elevated probability or cross section values in experiments.   Thus, this figure emphasizes how the analytic properties—specifically the location and nature of poles—encode key physical information about the behavior of scattering processes and resonances.](2025-Lecture-09-images/fig6.png){#fig-fg6}

 




![This figure illustrates the **analytic continuation** of the scattering amplitude  $A_{\pi\pi \to \pi\pi, \rho}^{II}(s)$  onto the **second Riemann sheet** in the complex  $s$ -plane. In the context of this lecture, the figure shows that:  - The **real axis** (horizontal line) represents physical values of the Mandelstam variable  $s$ , with the thick segment (branch cut) indicating the area where the imaginary part of the amplitude appears due to the opening of physical thresholds (e.g., two-pion production). - The **branch cut** is associated with the onset of physical intermediate states (unitarity cut), and analytic continuation through this cut leads to a different "sheet" of the function—a key concept in complex analysis of scattering amplitudes. - The **second Riemann sheet** (notated with  $II$ ) is accessed by analytically continuing the amplitude through the branch cut—this is where **resonance poles** appear. These poles correspond to unstable particles (resonances), which manifest as enhancements ("bumps") in the cross section in physical processes. - The figure also marks a **virtual state** (star on the imaginary axis left of threshold), representing a singularity not associated with a physical particle, but with a non-observable state. - Thus, the physical meaning is that the analytic structure of the scattering amplitude in the complex  $s$ -plane, especially the nature and position of its singularities (poles and cuts), encodes information about observable resonances and virtual states in hadron spectroscopy. This is a direct consequence of considering the amplitude as a **real analytic function** and performing analytic continuation.  In the context of the lecture, the figure emphasizes how complex analysis and the concept of Riemann sheets are essential for understanding the nature of resonances in scattering theory.](2025-Lecture-09-images/fig12.png){#fig-fg12}






Once we go away from this point, the amplitude value is really high. So what I want to say is that that pole value would feel this pole value even being away from it. But we will see that all of the features that we see in the scattering, like bumps or cusps, they are related to the singularities in the complex plane.

The branch points are just doors to other domains of analyticity. The poles are something that makes the strength of the amplitude. I was thinking of this nice example of the complex multi-floor house that has many Internet routers and you have a router.

So the poles are your routers. And if you want to have a strong Internet, you better sit next to the router and that provides you a signal. And if you are as close as you are to this Internet router, the better Internet you have, it's better. It's a higher value of the absolute value of the amplitude you have.

If you measure the process and you see that this cross section is large, something must be driving this large cross section. And it's probably a pole somewhere in the complex plane.

Interesting things about the cuts. One thing to consider is that the cuts are the doors to other domains, every cut. You probably have heard the saying that branch points are fixed, but the way you draw the cuts is arbitrary, up to you.

That—I don't like this way of putting it—but this is another way of saying that the way we draw the cut, you can draw the cut differently by extending the domain of the function. The way I'd like to think of this is that for every cut, you can come up with a different function.

What I mean is the following. You deal with a function that has a branch point at zero and the cuts towards the left. And the claim is, you can come up with a different function, call it  $F_2$ , that's defined in the complex plane such that it's analytically continuous.

The function above the cut analytically continues into the domain of analyticity. So I can come up with a different function. In that case, it's  $\sqrt{z}$ . But I can tell you the recipe to come up with this  $F_2$  such that if you join the function, you take this domain and that domain, so there are no cuts any longer.

The branch point is still there, but the function is analytic in this domain. If I take this and that, one can see this as the way to go beneath the cut. So I can analytically continue the function down. And that's the perspective that I offer.

That's, I think, the easiest way to wrap your head around it. There is a function defined everywhere in  $\mathbb{C}$  except a finite number of points, except a finite number of segments. And you can compute. If I ask you to compute a value, you can compute the value everywhere.

The cut locations are fixed; we don't touch them. We just come up with a different function  $F_2$  that's, again, for starters, it has nothing to do with  $F$ . It's again another function that I define everywhere except a finite number of segments.

But what makes us consider them together? The one analytically continues the other. Maybe it's a bit late, but if you come back to this function, square root of  $z - 1$ , minus  $s$ . Shouldn't there be two branches? Two branch cuts. One from 1 to infinity, from 0 to infinity.

If it's a minus, you're right. But if it's multiply, then that's. And well, we can go back here. For all of the functions with the cuts, we can discuss what is  $F_2$ , what function makes analytic continuation.

For that function we can discuss that. For any of them, you can ask me a question. What happens? What function would analytically continue the domain of analysis in that direction? And I know the answer. Just a minus sign here or here or there.

For any way you approach the cut, there should be analytic continuation. The other notion, the other way people talk about that is the Riemann sheets. Instead of saying that there is one function, second function, third function, people say there is just one function that is multivalued and it has a value on different Riemann sheets.

But that's the same as saying that there is  $F_1, F_2, F_3$ . So  $F_1$  is the value of the function on the first Riemann sheet.  $F_2$  is the value of the function on the second Riemann sheet. And so on.

So then, can you come up with the analytic continuation? That guy, that guy and that guy. But you tell me what  $F_2$  would look like here if I want to analytically continue. And then here, so quickly, what is  $F_2$ ? What is  $F_3$  here? No, minus, simply so, when you have a square root, the other sheet or the other branch is simply minus, and you convince yourself by computing  $+\epsilon$ .

So  $F_1$  at  $+\epsilon$  and  $F_3$  at  $+\epsilon$  should be equal to each other if the continuation is correct. And then here, what is  $F_2$ ? No, it can't be the same, because I can demonstrate that with log.

So here,  $F_1$  is the log of minus 1 plus i epsilon is equal to  $\pi i$ . And on that side, log of minus 1 minus epsilon is equal to minus  $\pi i$ . 




![This figure illustrates the concept of real analyticity for complex functions in the context of scattering amplitudes. The shaded segment along the real axis represents the domain where the function  $f(z)$  is real. When moving away from this segment into the complex plane (either above or below the real axis), the function develops an imaginary part: moving upward in the imaginary direction leads to a positive imaginary component, while moving downward results in a negative imaginary part. This behavior reflects the Schwarz reflection principle, which states that the value of the function at a point and its complex conjugate are related such that  $f(z^*) = f^*(z)$ . Physically, this underpins the analytic properties of scattering amplitudes and ensures that discontinuities across cuts in the complex plane are purely imaginary, as discussed in the lecture.](2025-Lecture-09-images/fig7.png){#fig-fg7}




 No, it's a plus. 




![This figure illustrates the analytic structure of a scattering amplitude as a function of the Mandelstam variable  $s$  in the complex  $s$ -plane. The real axis represents physically allowed values of  $s$ , while the imaginary axis corresponds to complex (unphysical) values.  The branch points at  $(m_1 - m_2)^2$  and  $(m_1 + m_2)^2$  indicate the kinematic thresholds for particle production in the scattering process, i.e., the minimal and maximal invariant mass squared for producing particles of masses  $m_1$  and  $m_2$ . Between and beyond these points, the amplitude develops branch cuts (shown as wavy lines), which represent the discontinuities or non-analytic regions associated with the opening of physical channels.  The blue annotation that "the branch cuts cancel out → function is continuous" emphasizes that, across certain regions (possibly when combining different contributions or sheets), the discontinuity due to the branch cuts can be made to vanish, resulting in a function that is continuous in the complex plane except at the branch points themselves. This reflects the property of **real analyticity** discussed in the lecture: the amplitude is analytic everywhere except along the physical cuts, and across the real axis (below threshold) it is continuous and real. The Schwarz reflection principle guarantees that the amplitude behaves smoothly except precisely along and across these branch cuts.  Physically, this diagram encodes how the analytic properties of the scattering amplitude connect to physical thresholds, and how analyticity and unitarity restrict the possible singularities (cuts and poles) in the complex  $s$ -plane. The function is analytic except for these branch cuts associated with the creation of intermediate states or particles.](2025-Lecture-09-images/fig9.png){#fig-fg9}




 So, and the way to see that is we computed this already and it's minus  $\pi i$ . 




![This figure illustrates the analytic structure of the scattering amplitude  $A(s)$  in the complex  $s$ -plane, demonstrating the physical meaning of different singularities and cuts as discussed in the lecture. The real axis  $\mathrm{Re}(s)$  corresponds to physical kinematic values, with a branch cut (in magenta) starting at the threshold  $s > s_{\text{th}}$ , representing the onset of physical scattering (the unitarity or right-hand cut). The blue and green lines indicate different analytic domains or "sheets" of the amplitude.  The orange point above the real axis on the imaginary axis denotes a "bound state" pole, corresponding to a stable particle below threshold on the physical sheet. The orange point below the real axis, labeled "virtual state," represents a pole associated with an unstable or non-physical state (on the unphysical sheet). The orange crosses on the lower half-plane, labeled "resonances," represent poles associated with resonant states—unstable particles that manifest themselves as peaks in the cross section—on the second Riemann sheet ( $A^{II}(s)$ ).   The diagram also demonstrates how the amplitude  $A(s)$  behaves in various regions, showing the importance of analytic continuation and Riemann sheets: the physical amplitude is found on the first (physical) sheet, while resonances and virtual states manifest as poles on other sheets, accessible via analytic continuation across the cut. This structure encodes the complex analytic (and real analytic) nature of the scattering amplitude, the linkage of poles to observable physical phenomena, and the impact of branch cuts associated with multi-particle thresholds.](2025-Lecture-09-images/fig15.png){#fig-fg15}






If we add  $2 \pi i$ , we will have the value on that side, so  $F_2$  equals to plus  $\pi i$ , so it will analytically continue. Why is it Sheet 3 right away? Oh, it's not Sheet 3, it's just labeling. You can call it 2 or. Well, it's up to me.

I can call the function going in that direction. So the other function,  $F_3$ , that is analytically continued would be the one that analytically continues from below, and the one from above is  $F_2$ . It's just my notation.

An interesting aspect that is closely related to the scattering amplitude is the concept of real analyticity. One can take the words "real analytic" literally: a real analytic function that is analytic and real.

I would like to extend this definition and call the functions real analytic if it has a segment along the real axis, then it's real. Like this is again my z-plane and then this is my x-axis where the  $z$  is real.

I compute the  $F$  of the real value and I get a real value for the function. It turns out that once you have this function, it has very peculiar properties. It satisfies the reflection principle. The function is real on this segment.

Analyticity is sort of a special type of continuity of the function. This implies that once you start going away from the real axis, the imaginary part must appear. So the function cannot stay real once you go away from the real axis and it will start appearing in the opposite direction.

If an imaginary part develops in the positive direction once you go up from the real axis, it must go to the opposite negative direction if you go down from the real axis. That's essentially what the Schwarz reflection principle tells you.

The imaginary part of that point is going to be opposite to the imaginary part of the symmetric point. You simply, oh, here you see that I put a star. Star means complex conjugation, which means flip the imaginary part.

We started by discussing the function that just has a similar single segment of real values. And then if you follow that consideration and do analytic continuation, you realize that the only way for this function to stop being real on the real axis is to get a branch point.

The function along the real axis is real on a segment and only becomes non‑real once you introduce the branch point. The only way for the function to get an imaginary part is to get the branch point and the cut, for exactly the same reason you have a segment where the function is real here and the imaginary part develops to the. 




![This figure illustrates the analytic structure of the scattering amplitude  $A(s, t)$  as a function of the complex Mandelstam variable  $s$ , for fixed  $t$ . The horizontal axis represents the real part of  $s$  ( $\text{Re}(s)$ ), while the vertical axis is the imaginary part ( $\text{Im}(s)$ ). The depicted thick lines along the real axis correspond to the **branch cuts** associated with physical thresholds for two different scattering channels:  - The **threshold for the s-channel** is marked on the positive real- $s$  axis. This is where physical s-channel particle production can occur and corresponds to the opening of the unitarity cut. - The **fixed threshold for the u-channel** is indicated on the negative real- $s$  axis. This relates to the production threshold for the crossed (u-channel) process.  The region between the cuts, on the real  $s$ -axis below threshold, is labeled "real analytic," indicating that the amplitude is real and analytic in that segment — in accordance with the property of real analytic functions discussed in the lecture. The cuts themselves signify the locations where the amplitude develops an imaginary part (discontinuity), corresponding to physical particle production (unitarity cuts).  This diagram physically encodes how the analytic (and specifically, real analytic) properties of the scattering amplitude in the complex  $s$ -plane reflect causality and unitarity, with thresholds demarcating the transition points where new physical channels become accessible. These analytic properties are crucial for defining the amplitude's behavior and for connecting it to physical observables.](2025-Lecture-09-images/fig8.png){#fig-fg8}






So imaginary part on that side is positive, imaginary part on that side is negative. That’s why the discontinuity around the cut is going to be twice the imaginary part, because they are developing in opposite directions.

So now that’s the second lowest threshold opening. Any segment along the real axis would be like closed or open. I’m thinking about. I mean, analytic functions always have an open domain. They have to. As soon as you have an open domain, you can always come.

So from A to B you can always come with the closed domain. So A minus i epsilon is included. My point is that as soon as you include one of those edges, you cannot put some kind of small circle around it and then say it’s still smooth.


::: callout-important
Scattering amplitudes are **real analytic functions** of  $s$  (for fixed  $t$ ), meaning they satisfy the **Schwarz reflection principle**. This is tied to causality and implies specific symmetry in the complex  $s$ -plane:
  $$A(s^*, t) = A^*(s, t)$$  
This property ensures that the amplitude is real along the real axis below thresholds and that discontinuities across cuts are purely imaginary, e.g.,  $\text{Disc} \, A(s, t) = 2i \, \text{Im} \, A(s, t)$  along the unitarity cut.
:::



