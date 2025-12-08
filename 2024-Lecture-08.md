---
title: (2024) Lecture 8
author: ''
presenter: Mikhail Mikhasenko
note_taker: Ilya Segal
date: '2024'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



## Analytic and Holomorphic Functions

In today's lecture, I would like to discuss unitarity and complex numbers and move towards discussing complex functions. We had a little too little time in the previous lecture to cover these aspects, but this is important to understand and I think it also links to what you already know from mathematics.

I would like to introduce you to two mathematical concepts: **analytic functions** and **holomorphic functions**, which are two words for the same idea.

*   A function is called **analytic at a point  $x_0$ ** if it can be represented by a Taylor series that equals the function in the vicinity of that point. This means there exist coefficients such that:
  $$f(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(x_0)}{n!} (x - x_0)^n$$  

*   A function is called **holomorphic** if its complex derivative exists, meaning you can approach the point from any direction in the complex plane and the derivative is the same. This is the same property as being analytic. Don't be afraid of the word "holomorphic"—it's just mathematicians inventing a cool word to say a function is analytic.


::: callout-note
**Key Definitions:**

*   **Analytic/Holomorphic Function:** A function that can be locally represented by a convergent power series (Taylor series) and has a well-defined complex derivative.
*   **Taylor Series Representation:**  $f(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(x_0)}{n!} (x - x_0)^n$  expresses that the function's value near  $x_0$  is determined by its derivatives at  $x_0$ .
:::

### Examples and Properties of Analytic Functions

As examples, consider functions that are analytic:

*   All **polynomials** are analytic everywhere.
*   A **rational function** (a polynomial divided by another polynomial) is analytic except at a finite number of points—the zeros of the denominator.
*   When we say a function is analytic on a domain, it means **every point** in that domain is a point of analyticity.

The function  $\sqrt{x}$  is analytic everywhere except at  $x = 0$ . Zero is called a **branch point**, a point where there is no derivative and no valid Taylor series.

**Real analytic functions** are another interesting class—functions that are real-valued and analytic. An example is the real function  $\sqrt{x}$  for  $x \geq 0$ .

A key property of a real analytic function extended to the complex plane is the **Schwarz reflection principle**. It states that for such a function  $f$ , the value at the complex conjugate of a point is the complex conjugate of the function's value:
  $$\overline{f(z)} = f(\overline{z})$$  

### Visualizing and Applying the Concepts

When discussing analytic functions of a single complex argument, it's convenient to draw the domain—the complex plane. On the x-axis is the real part of the argument ( $\Re(z)$ ), and on the y-axis is the imaginary part ( $\Im(z)$ ). We can indicate regions of analyticity on this diagram.

The Schwarz reflection principle implies a symmetry: the function's values in the lower half-plane are related to those in the upper half-plane. You can compute a value in the lower half-plane by computing it at the conjugate point in the upper half-plane and then taking the complex conjugate.

Let's test this with an example using  $f(z) = \sqrt{z}$ , which is real analytic for real  $z$ . We'll compute  $\sqrt{1 + i}$  and  $\sqrt{1 - i}$ .

First, express the numbers in polar form  $z = r e^{i\theta}$ , where  $r = |z|$  and  $\theta = \arg(z)$ :

*   For  $1 + i$ :  $r = \sqrt{2}$  and  $\theta = \pi/4$ . So,  $1 + i = \sqrt{2} e^{i\pi/4}$ .
*   For  $1 - i$ :  $r = \sqrt{2}$  and  $\theta = -\pi/4$ . So,  $1 - i = \sqrt{2} e^{-i\pi/4}$ .

Now, apply the square root using the rule  $\sqrt{z} = \sqrt{r} e^{i\theta/2}$ :

*    $\sqrt{1 + i} = \sqrt{\sqrt{2} e^{i\pi/4}} = 2^{1/4} e^{i\pi/8}$ 
*    $\sqrt{1 - i} = \sqrt{\sqrt{2} e^{-i\pi/4}} = 2^{1/4} e^{-i\pi/8}$ 

Notice that  $\sqrt{1 - i}$  is indeed the complex conjugate of  $\sqrt{1 + i}$ , which confirms the Schwarz reflection principle:  $\overline{\sqrt{1 + i}} = \sqrt{\overline{1 + i}} = \sqrt{1 - i}$ .



## Cauchy's Theorem and Discontinuous Integrals

Cauchy's theorem states that the integral over a closed contour of a function in the complex plane is equal to all non-analytic contributions inside this contour. If the singularity is a pole, it's given by residues. If it's a branch point, one must contour around it, and so on. The theorem systematically accounts for all non-analytic behavior.

What is notable is that this provides a numerically well-defined procedure to integrate a function that is discontinuous. For example, we can compute the integral of the function  $\sqrt{z}$  on the circle of radius 1, and the integral converges despite the function being discontinuous at the branch point.

### **Contour Integral of  $\sqrt{z}$  on the Unit Circle**

On the circle  $|z|=1$ , the function is parameterized as  $z = e^{i \phi}$ . However,  $\sqrt{z}$  jumps across the branch cut: above the cut it is  $+1$ , and below it is  $-1$ . The contour integral is:

  $$\oint_{|z|=1} \sqrt{z} \, dz = \int_{0}^{2\pi} \sqrt{e^{i \phi}} \cdot i e^{i \phi} \, d\phi$$  

Taking the principal branch where  $\sqrt{e^{i \phi}} = e^{i \phi/2}$ , this simplifies to:

  $$\oint_{|z|=1} \sqrt{z} \, dz = i \int_{0}^{2\pi} e^{i (3/2) \phi} \, d\phi$$  

Care must be taken because the function is discontinuous on the interval  $[0, 2\pi]$ ; one cannot simply evaluate at the endpoints. To handle this properly, one can shift the integration range to  $[-\pi, \pi]$ , where the function is continuous on that segment:

  $$i \int_{-\pi}^{\pi} e^{i (3/2) \phi} \, d\phi$$  

This yields a finite, well-defined result.

### **Deforming the Contour and the Branch Cut Discontinuity**

The key point is that this contour integral equals the integral of the discontinuity across the branch cut. By shrinking the contour around the branch cut (typically placed along the negative real axis), the integral transforms.

For  $\sqrt{z}$  with a branch cut along the negative real axis, the values on either side of the cut are:

*   **Above the cut:**  $\sqrt{z}_{\text{above}} = i\sqrt{|x|}$ 
*   **Below the cut:**  $\sqrt{z}_{\text{below}} = -i\sqrt{|x|}$ , for  $z = x < 0$ 

The discontinuity across the cut is therefore:

  $$\sqrt{z}_{\text{above}} - \sqrt{z}_{\text{below}} = 2i\sqrt{|x|}$$  

Thus, deforming the original circular contour gives an equivalent representation:

  $$\oint \sqrt{z} \, dz = \int_{\text{branch cut}} \left[ \sqrt{z}_{\text{above}} - \sqrt{z}_{\text{below}} \right] dz = \int_{-\infty}^{0} 2i\sqrt{|x|} \, dx$$  

This illustrates a core property of analytic functions and Cauchy's theorem: **the contour of integration can be deformed freely as long as no non-analytic regions are crossed**. For this example, it is instructive to verify that the circular integral and the branch-cut discontinuity integral give the same result.


::: callout-important
The residue theorem,  $\oint_{\mathcal{C}} f(z) \, dz = 2\pi i \sum_{k} \text{Res}(f, z_k)$ , is the foundation. For integrals with branch points, we extend the logic by deforming the contour around branch cuts, which reduces the problem to integrating the function's **discontinuity** across that cut. This technique is powerful for evaluating real integrals and appears in physics contexts like dispersion relations and spectral representations.
:::

The remaining step is the final evaluation, which involves the imaginary part of  $\sqrt{x}$  times  $i$ , leading to a simple integration on the real axis. The two methods—direct parameterization and branch-cut deformation—provide a consistent answer, demonstrating the robustness of the complex analysis approach.



## Analyticity and Branch Points in the Scattering Amplitude

The scattering amplitude is the real magic function. 




![This figure illustrates the derivation of the **optical theorem** using the principle of **unitarity** in scattering theory. On the left, the sum over all possible intermediate states ( $\sum_n$ ) is shown, representing the process where the initial state can scatter into any set of possible intermediate particles (labeled by  $n$ ). The diagram in the center shows the forward scattering amplitude, while the terms on the right represent the subtraction of the amplitude from its complex conjugate. This corresponds to taking the difference between the amplitude and its Hermitian conjugate, which isolates the imaginary part of the forward scattering amplitude. This imaginary part is related (via unitarity) to the total cross section for the process, connecting the squared modulus of the amplitude summed over all intermediate states to the discontinuity (imaginary part) of the amplitude itself. This graphical equation expresses the optical theorem in terms of **analyticity** and **unitarity** of the scattering amplitude as described in the lecture.](2024-Lecture-08-images/fig1.png){#fig-fg1}






Let's return to our two sketches of the amplitude, for which we derived the optical theorem and discussed the analytic structure. The claim is that the amplitude is a real magic function, so part of it.

Let's clarify the assumptions and the physical principle. The amplitude is not accessed directly in experiment; we cannot validate its properties exactly. What we measure is the amplitude squared. Access to the amplitude itself is only available via our observables.

However, scattering theory and probability conservation imply that certain properties of the amplitude, particularly constraints on its imaginary part, tell us where the imaginary part is present. The fact that it's analytic is a postulate. This is something we have to assume.

It's stronger than an assumption. We don't assume its analytic properties; this is the building principle of our series. All series we have seen so far have unitarity built in. Therefore, not only unitarity, but also causality, which is related to analyticity.

The amplitude being an analytic function is a principle that is postulated in our theory. It is related to the causality of the theory—that the past does not influence the future. Events separated outside the causality cone don't influence each other. We are not deriving this, but you can find the causality connection to analyticity in several books; we take it as a postulate.

The amplitude is analytic, and then unitarity tells you more. Moreover, the amplitude is **real analytic** below the threshold, because the imaginary part is connected to the particle's appearance in intermediate states. This is only present once you are above threshold, because the interaction tells you that the amplitude has an imaginary part above the threshold. Below threshold it doesn't have any imaginary part; it's real.

So here I have a diagram on the x-axis. Again, it's the complex plane of the energy. The variable  $s$  is  $E^2$ , where  $E$  is the center-of-mass energy, and the amplitude  $\mathcal{A}(s)$  as a function of this  $s$  is an analytic function.

What we get to deal with is only the values of this amplitude above the threshold. However, the postulates of our theory tell you that using analyticity we can extend the domain of definition into the full complex plane. I hope you wrap your mind around the idea that now we can extend this analytic domain and think of our amplitude as a complex function.

Instead of the energy of the interactions being like 5 GeV, you can put a complex number there and then you probe the function away from the real axis. This function has a certain range of singularities. The fact that the imaginary part is not present below threshold and then suddenly appears above threshold tells you that a certain singular disk pops up. These singularities are the **branch points**.

Every threshold has nice derivations of the threshold singularities for different numbers of particles. However, something to see easily is the two-body threshold. I want to show you that it introduces **square root singularities**. It simply follows from the fact that the imaginary part has a square root.

Let me show you that the imaginary part of the amplitude from unitarity that we derived last time is related to the amplitude squared itself. There is a prefactor here. This prefactor is the phase space, simply the two-body phase space. The one half comes from  $\mathcal{A} - \mathcal{A}^*$ .

I place the imaginary part on here, here I replace it and  $\frac{1}{2}$  over here. The two-body phase space has the factor  $\frac{2p_{\text{cm}}}{\sqrt{s}}$ . This  $2p_{\text{cm}}$  is the breakup momentum. This is something that actually makes a singularity, something that vanishes at the threshold.

The breakup momentum is the momentum particles have. Clearly if you are at the threshold, you have the minimal energy of the system. It's simply two masses of the particles. They don't have free energy, they don't have momentum. That's something that vanishes.

Mathematically you see that if you compute this two-body breakup momentum, you find that it's equal to the Källén function. 




![This figure represents the analytic structure of the scattering amplitude  $\mathcal{A}(s)$  as a function of the Mandelstam variable  $s = E^2$ , where  $E$  is the center-of-mass energy. The horizontal axis is the real axis of  $s$ , while the vertical axis would represent the imaginary part if drawn fully. The portion of the real axis labeled "real analytic" depicts the region below the two-particle threshold at  $s = (m_1 + m_2)^2$ . In this region, the amplitude is real analytic, meaning it is a real-valued, analytic (holomorphic) function—there is no imaginary part, and the function can be represented by a convergent Taylor series.  At the point  $s = (m_1 + m_2)^2$ , the threshold for producing two particles of masses  $m_1$  and  $m_2$ , a branch point occurs. This marks the beginning of a branch cut along the real axis for  $s > (m_1 + m_2)^2$ , which is where the imaginary part of the amplitude appears due to physical particle production. The branch cut is related to the square root behavior of the two-body phase space, as discussed in the lecture. Thus, the figure illustrates how the analytic properties of the amplitude change at the physical threshold, emphasizing the importance of branch points and cuts in the analytic structure of scattering amplitudes.](2024-Lecture-08-images/fig2.png){#fig-fg2}




 Remember  $\lambda(x, y, z) = x^2 + y^2 + z^2 - 2xy - 2yz - 2zx$ . You can arrange this as the product, and to be precise, the product of the two terms where you have  $x - y + z$ . This is the masses of two particles and the difference between them and under the square root.

The first term gives you a singularity at the threshold and the second one gives you a singularity at the pseudothreshold. The integral relation as we wrote it, as we derived, is valid only above the threshold. The imaginary part is non-zero and present only once you go above the threshold.

This imaginary part appears to have a square root behavior. That indicates, that tells you that the function itself has a **square root branch point**. Essentially above that point the function has this branch cut.

We would like to connect this to the **Schwarz reflection principle**. Since our function was real and analytic on a segment of the real axis, the Schwarz reflection principle works above. It connects the amplitude in the upper half-plane with the amplitude in the lower half-plane.

If your function is  $\mathcal{A}(s + i\epsilon)$ , it simply tells you that the imaginary part flips if you go from above the real axis to below the real axis. That's a relation where  $\epsilon$  is small enough.

This is now in the pop, in the rock. People like the word. Maybe next time I bring you something. I was impressed recently. Listen to the song "Infinitesimal," and that's a word I like. It just means very, very small, infinitesimal.

I'm going to use this  $i\epsilon$ , and you've seen it before. This is just the little number that indicates that you are like a very, very small amount above the real axis or below the real axis. Cool.

It happens due to the phase space. We realized that if the function, if there were no phase space configuration summations on the right, you could relate the imaginary part to the amplitude itself and there would not be branch points. But it's unavoidable. You have to sum over phase configurations.

That gives you the square root branch point. It also tells you that the amplitude has a branch point starting at the threshold and going in the positive direction.

I wanted to quickly give an example of such a function, an example of a real analytic function, a function with a cut to the right. An example of a real analytic function like our scattering amplitude, but something very simple with a square root function that has a cut to the right.

The square root of  $x$  doesn't work. Test. Cut on the left? On the left. Let's cut to the left. How do I see where it has the cut? Simply because amplitude of  $1 + \epsilon$  is equal to amplitude of  $1 - \epsilon$ , there is no cut.

Then  $\sqrt{-1 + i\epsilon}$  is equal to  $i$ , and  $\sqrt{-1 - i\epsilon}$  is equal to  $-i$ . On this side the function evaluated from above and the function evaluated from below have different values. That tells me in which direction I put my cut.

This is a branch point and this is a non-analytic point. For every branch point there is a cut attached and then it splits my manifold and analyticity into the functions, into the sort of surfaces, different sheets. All of the functions elsewhere except this point are analytic.

But you have to work to see this analyticity. Essentially you have to analytically continue functions. If you see the pattern, you want to make this function analytic. It's always possible, but you have to work a little bit by extending the analyticity domain.


::: callout-important
**Key Formulas for This Section**

*   **Two-Body Unitarity:**  $\operatorname{Im} \mathcal{A}(s) = \frac{1}{2} \int d\Phi_2 \, |\mathcal{A}(s)|^2$ 
*   **Breakup Momentum & Phase Space:**  $\rho(s) = \frac{2p_{\text{cm}}}{\sqrt{s}}$ , where  $p_{\text{cm}} = \frac{\sqrt{\lambda(s, m_1^2, m_2^2)}}{2\sqrt{s}}$ 
*   **Källén Function:**  $\lambda(x, y, z) = x^2 + y^2 + z^2 - 2xy - 2yz - 2zx$ . For two-body kinematics, this becomes  $\lambda(s, m_1^2, m_2^2) = [s - (m_1 + m_2)^2][s - (m_1 - m_2)^2]$ , showing the square-root branch points at the threshold  $(m_1+m_2)^2$  and pseudothreshold  $(m_1-m_2)^2$ .
*   **Schwarz Reflection Principle:**  $\mathcal{A}(s + i\epsilon)^* = \mathcal{A}(s - i\epsilon)$  for real  $s$  below the first threshold.
:::



## Analytic Structure and Branch Cuts of a Square Root Function

Coming back to the example, you'll understand it better once I finish it.

So, if I put the minus *x* and evaluate the function somewhere in the complex plane, I find it's now fully analytic here, and it has a cut to the right.

Now, let's evaluate this function at **s = -1**. What is it equal to? I want my function here, and it gives me one minus, minus. This is an example of a real analytic function.

Or, let's put the amplitude—the simplest amplitude. A valid amplitude would be:
  $$\sqrt{-s + m_1^2 m_2^2}$$  
which has similar properties. 




![This figure illustrates the analytic structure of the function  $\sqrt{x}$  in the complex plane. The image shows a complex plane with a vertical (imaginary axis) and horizontal (real axis) line, with a thickened or darkened segment along the negative real axis. This dark segment represents the **branch cut** of the function  $\sqrt{x}$ , which is a line (chosen conventionally along the negative real axis) where the function is discontinuous. The point at the origin ( $x=0$ ) is the **branch point** where the non-analytic behavior begins. Physically, this means that as you move around the origin in the complex plane, the value of  $\sqrt{x}$  can jump discontinuously when crossing the cut, which is essential for defining the function's analytic properties. In the context of scattering amplitudes and complex analysis, identifying such branch points and cuts is crucial for understanding where the amplitude is analytic (holomorphic) and where it develops discontinuities due to physical thresholds.](2024-Lecture-08-images/fig3.png){#fig-fg3}







::: callout-note
This function  $f(s) = \sqrt{-s + m_1^2 m_2^2}$  is analytic in the complex  $s$ -plane except along a **branch cut**. This cut is typically placed where the expression under the square root,  $-s + m_1^2 m_2^2$ , is real and negative, leading to a discontinuity.
:::

Quickly, while I'm cleaning the board: what is the analyticity structure of this? We are in the *x*-plane.

Let's finish here. I put **-9** in the first one to make it more interesting. Anyway, this first function has the cut on the right, and the second one has a cut. They are very similar, but shifted by one.

So essentially, the structure is: **one cut**, then a **second cut**. When you have this situation, there is no jump here. You can jump twice and the cuts overlap, so there is no discontinuity of the function. It's analytic right here.

The right answer is just the cuts connecting two points. This one is tricky. The first time I saw it in a mathematical context, I was really shocked because the locations of the **branch points** are the same. There are two points, *x* and *x*, where the function is non-analytic.

But the locations of the **cut** are driven by the places where the imaginary expression under the square root has an argument of  $\pi$  or  $-\pi$ . For a regular square root function, the cut appears where the argument is either  $\pi$  or  $-\pi$ .

To understand where your Mathematica, C, or Python library would draw a cut, you need to understand where the expression under the square root has an argument touching  $\pi$  or  $-\pi$ . And then, apparently, this is indeed between the points, but also along this line.

*   This is the first cut going to infinity.
*   This is the second cut going to infinity.

It's crazy, and this is actually different from the previous case.

If you just split the product into two square roots:
  $$\sqrt{(-s + a)(-s + b)} = \sqrt{-s + a} \cdot \sqrt{-s + b}$$  
then you remove these two connections. I don't want to confuse you, but to warn you: one has to be careful **how you write the expression**, exactly how you split the square root, because that makes the function different on the real axis.

I think they will be the same on the real axis, but on the complex plane the functions are different. They might even be different elsewhere...

To prove that  $\sqrt{(-s + a)(-s + b)}$  is **not** equal to  $\sqrt{-s + a} \cdot \sqrt{-s + b}$ , we can simply evaluate the function at **s = -1**. That's an easy exercise.

The way I see that they are different is because I know the analytic structure of the first expression is **one cut connecting two branch points**. In order to arrive from this structure to the other, I can take this cut, rotate it over here, take this one, rotate it over there, and cancel two cuts. Making these two cuts cancel each other tells me that the function in the original configuration has a different value at **s = -1**.

If I evaluate, I should see this immediately:

*   Evaluating the top one:  $\sqrt{(-(-1) + 2)(-(-1) + 2)} = \sqrt{(1+2)(1+2)} = \sqrt{9} = 3$ 
*   Evaluating the product of square roots: from the first factor  $\sqrt{1+2} = \sqrt{3}$  and from the second  $\sqrt{1+2} = \sqrt{3}$ . Their product is  $(\sqrt{3})^2 = 3$ .

However, with careful sign consideration from the branch choices (as hinted in my notes), the values can differ. For instance,  $\sqrt{2i} \cdot \sqrt{2i}$  could be evaluated as  $2i$ , while  $\sqrt{(2i)^2} = \sqrt{-4}$  could be  $2i$  with an appropriate branch, illustrating the subtlety. The key point is their **analytic structures**—their branch cuts—are fundamentally different.



## Complex Plane Analogy for Scattering Amplitudes and Resonances

Its resonances are **poles of the scattering amplitude**. You will hear that many times in the future.

Think of the intensity flow. The function in the complex plane is like the complex structure of a house. In this house there are just a few routers. You desperately want your Internet; the farther you are from the router, the weaker signal you get. If you sit at a point and you have a really good Internet, you are probably sitting not far from the router. Similar to that, this is our couch in the house where people usually sit and they experience different strengths of the Internet. The routers are the resonances.

Here I have combined two modes on the Y axis. I have a complex  $s$  plane, with real  $s$  on the axis. This indicates minus imaginary  $s$ . This is the same as I would have for the complex plane. I draw a square. The square is the strength of your Internet when you sit on this couch. In the middle you have the closest distance to the router, to the resonance pole, and therefore your strength is the highest. If you go far away, your Internet weakens.

Now let's make the house a little bit more complicated. We have several floors. In that case the cuts... Here is my map of the room. As usual, I am the couch where people sit on the real axis. But in that case I have the house a little bit complex. There is a room with different electronics, a different floor, so I can go to another room. I experience all the routers that are in another room. Essentially, if in another room I have a router sitting here, I want to see the influence of it from my couch. Let me put it here. This is floor one and the next is two. I am going to draw the sheet too. Sheet one is our floor one and then sheet two is floor two. Here is the gate. You can think of this now as the sort of stairs from one to another, and this continues. If I have my router here, I am going to see I have a really good strength here and then here as well. But if I go around the corner, I start losing the signal. Here the distance becomes high. The way to get Internet is around the wall. This is the gate to another floor and I can only enter on that side.

Is it clear? I feel like this picture of the floors and the routers is really helpful, but might be still overwhelming. The routers are the resonances. I see the routers on each floor. If they are above the threshold, it is too complicated. Essentially, when you hear about the complex plane and the poles, just think of the intensity floor somewhere in the complex domain. There are gates to other floors. Do not think about them as changing the level, but it is simply the way to connect one to another. Somewhere on this surface that has different levels, you place the routers. These routers influence your intensity, which you see on the real axis.

What is the difference between a bigger room and multiple floors? No difference. The rooms are infinitely big either way. But since at every point I can be at different sorts of floors that are connected smoothly to each other, I have to draw several maps, several sheets. In the shopping malls you also have multiple floors with shops indicated because it is really hard to show it on a single one.

For simplicity, unitarity tells us the cut should be to the right. But I would never do it practically like that. I know unitarity tells me that. Nothing happens if I just place the cut to the left. I will demonstrate what I want to do with the square root function,  $\sqrt{x}$ . It has a branch cut and I am carrying my function value right here. There is nothing going to happen if I just draw the cut in different directions. I would like to say that this function is the same function. But now in that case I have a branch cut. Is it the same? Let us evaluate this function. At  $x = -1$  you have an  $i$ . At  $-1 + \epsilon$  you have an  $i$ . This function at  $-1$  gives you an  $i$  again. This function and that function are exactly the same in this region. The difference between them is that I took my branch cut and rotated it to the right such that I opened the space underneath. I just made the renovation and changed the rooms how they are located in the house. It changes nothing in the strength of the amplitude essentially because the walls, I mean there are no walls. Essentially everything is continuous. The cut, the way how I draw the cut, is just a way to separate different branches. There is no wall that prevents the signal strength. That is why for this I would never do this practically like that. This is what unitarity tells us about imaginary part and real analyticity. For practical reasons it is always convenient to open up the closest branch to us to see. Therefore it is more natural to place the cut in a convenient location. The cut goes to the right, I turn it to the left and now actually my function is not real, but I now expose a bigger range of the complex plane to analyze.

Essentially, if I sit here, this point on the real axis is influenced by all singularities in the complex plane that are nearby. If I have a pole right here, I do not have to care about the branches any longer. I just immediately see the effect in the strength of my amplitude if my pole is nearby. That is the most convenient, in my opinion, way to think of the complex plane and the scattering amplitude. 




![This figure illustrates the physical meaning of **resonances as poles in the scattering amplitude** and the analytic structure of complex functions in the context of scattering theory.  - **Branch cuts and analyticity:** The sketches at the top show the analytic structure of functions like  $\sqrt{x(x-1)}$  versus  $\sqrt{x}\sqrt{x-1}$ , emphasizing that while individual square roots have branch cuts on the real axis, their product (if not written with care) might not match the full analytic structure, demonstrating the importance of how a function is defined with respect to branch points and cuts. The analytic continuation and placement of branch cuts affect the behavior and discontinuities of the function.  - **Poles and "intensity flow":** The middle section introduces the concept that physical resonances correspond to poles of the scattering amplitude in the complex  $s$ -plane (where  $s$  is the Mandelstam variable, often  $s=E^2$ ), and how these influence observable data. The schematic "complex  $s$  plane" with a marked resonance pole shows that the observable intensity  $|A|^2$  (the square of the amplitude) on the real axis is enhanced in the vicinity of such a pole—this is the resonance "peak" seen in experiment. The sketch shows this as "strength of signal" near the pole.  - **Sheets and analytic continuation:** The two panels labeled "Sheet I" and "Sheet II" display different Riemann sheets in the complex  $s$ -plane associated with the function's branch points and cuts. This reflects the fact that multivalued functions like those with square roots naturally extend to multiple sheets, and poles associated with resonances may appear on different sheets depending on the analytic continuation—a key concept in understanding physical resonances and thresholds.  - **Cuts can be rotated:** The panel illustrating how branch cuts can be "rotated" or placed differently without changing the analytic nature of the function emphasizes that the mathematical convenience of cut placement aids analysis, but the physical consequences (like the influence of poles) are unchanged.  - **Amplitude pole formula and physical interpretation:** The expression  $\mathcal{A} = 1/(m_R^2 - s)$  and the boxed formula  $m_R^2 = (M_R - i \Gamma_R/2)^2$  indicate that the complex pole position encodes both the mass  $M_R$  and width  $\Gamma_R$  of the resonance, and the concept of "Full Width at Half Maximum" (FWHM) shown on the intensity plot at bottom right links these mathematical quantities directly to physical observables.  - **Influence of singularities:** It is noted that "data points are influenced by singularities"—meaning that the experimental measurements on the real axis “feel” the presence of nearby analytic structures (branch cuts and poles) in the complex plane.  **Physically**, this figure captures: - How the analytic structure (branch points, cuts, and poles) of the scattering amplitude function in the complex plane directly governs the observable phenomena in scattering experiments (resonance peaks, thresholds, and cusps). - That resonances (unstable particles) are defined as poles of the amplitude in the complex  $s$ -plane, while branch cuts stem from multi-particle thresholds. - The importance of Riemann sheets and analytic continuation for understanding the full behavior of these complex amplitudes. - The freedom to draw branch cuts where convenient, reflecting the purely mathematical aspect of cuts in representing multi-valuedness, rather than physical discontinuities. - Ultimately, **the physical resonances in scattering data are manifestations of the analytic structure of complex functions associated with the amplitude**—particularly the positions and nature of poles and branch points in the complex plane.](2024-Lecture-08-images/fig4.png){#fig-fg4}







::: callout-note
**Key Analytic Structure**
The scattering amplitude  $\mathcal{A}(s)$  has a pole at a complex value  $s = s_p$  where the denominator vanishes:
  $$\mathcal{A}(s) \propto \frac{1}{s - s_p}$$  
This pole defines the resonance. Its location is complex:  $s_p = (M_p - i\Gamma_p/2)^2$ , where  $M_p$  is the pole mass and  $\Gamma_p$  is the pole width.
:::

I measure my amplitude above threshold. Here is  $(M_1 + M_2)^2$ . That is where I measure my amplitude. What I measure is influenced by structures near threshold. If there is a resonance that I see in the data, it means down below there is a pole that makes this resonance. A resonance is always a pole. That is actually how we define the particles. Particles are always poles in the amplitude.

We have conventions for how to define the width and mass of the resonance. They come from the location of the pole. A single pole amplitude has this form:  $\mathcal{A}(s) \propto \frac{1}{s - s_p}$ . When I say pole I literally mean a zero of the denominator. The location of this pole where the denominator vanishes is  $s_p$  or  $\bar{m}^2$ . This is a complex number. The real and imaginary part of this number are called mass parameters of the pole. This is literally the definition.

We call the mass of the pole the real part of the square of the pole location and the width of the pole twice the square root of the pole, twice imaginary part minus twice imaginary part of the pole location. More precisely,  $s_p = (M_p - i\Gamma_p/2)^2$ . They are related to the observed mass and width, because this is something you can define experimentally. If you see the signal, it has a peak location and a full width at half maximum. For narrow resonances,  $\Gamma_p$  is approximately equal to the full width at half maximum and  $M_p$  is approximately equal to the peak location. That is not the case for broad resonances, but for narrow ones this is the case.

What is the analytic structure of this function? The analytic structure is simply a pole. There are no branch points, there is nothing else. It is simply one pole.

A little bit more complex example that we have on an exercise sheet is the relativistic case. Wigner had everything built in. It had a pole in the K-matrix and it had a square root branch point from the phase space. The K-matrix that we discussed last time is the way to incorporate poles and correct analytic structure together. It works for multiple loops. The scattering amplitude is  $\mathcal{A} = K (1 - i \rho K)^{-1}$ .


::: callout-important
**Parameterizing Resonances**
In practice, we often use specific parameterizations to fit data:

*   The **Breit-Wigner amplitude** is a common limit:
      $$\mathcal{A}_{\text{BW}}(s) = \frac{g}{s - M^2 + i M \Gamma(s)}$$  

*   The more general **K-matrix formalism** ensures unitarity and can handle multiple channels:
      $$\mathcal{A} = K (1 - i \rho K)^{-1}$$  
    Here,  $K$  is a real symmetric matrix, and  $\rho$  is the phase-space factor.
:::

The last comment on this subject is what we do when we analyze the data. The ultimate goal is to characterize resonances by their mass and width, or the pole location. We come up with the parameterization using a K-matrix or P-vector. Often you can use a simple Breit-Wigner,  $\mathcal{A}_{\text{BW}}(s) = \frac{g}{s - M^2 + i M \Gamma(s)}$ , which is the limit case of the K-matrix, unless you constrain your amplitude. The amplitude then has an expression that is rather complicated, has many terms, but it is an analytic function.

You have three parameters that you are just looking at in the data. By fitting this, you fix these parameters by analyzing data and then you explore the analytic expression. You know that it probably has a branch point. You decide either you draw it to the right or to the left. It is up to you. What is important is that everything that you see, all spikes, all peaks, everything that you see in your functions has some origin, and the origin is in the complex plane. If it has a peak, likely there is a pole there.



## Thresholds, Branch Points, and Poles

Another important phenomenon you see in the data is the **cusp**. This is the amplitude squared,  $|A|^2$ , plotted against the Mandelstam variable  $s$ . You see a cusp, and that type of singularity is also known as a **branch point**.

So, do we have our branch points? The first threshold introduces a branch point; every threshold introduces a singularity. For two particles, it's a branch point. We have already discussed this branch point. If there are more than two particles, combinations like  $\pi\pi$ ,  $KK$ , or  $\bar{K}K$  would give a branch point at 1 GeV. Then the amplitude might have a spike. This is an indication that in the complex plane all is fine, but there is a branch point.

For every branch point, we have to attach a sheet. This is the location of the cut; it's up to us how to draw it, but it introduces more surfaces. So this is a direction.

The last thing to realize is about the triangle. We know that at threshold the function has a square root singularity, but thresholds are only opening new surfaces for you. The thresholds are only determining the map of your complex plane. The real singularities, or the strong singularities that make intensity peak, are **poles**.

A situation where  $|A|^2$  has this threshold behavior, but then rises very quickly and goes down, indicates that there are some poles nearby. If the poles were underneath, that kind of function would of course peak at that place. In that case, what likely happens is that there is a **bound state**; there is a pole here. If there is a pole on the real axis, it would not show up as a nice resonance-like peaking structure.

If you think again about the map of routers and the internet: if you have a router here and you sit on the couch, the signal strength will be highest here and then lower farther away. That's simply how to understand **threshold enhancements**.

*   **Threshold enhancements** are often indications of poles *below* threshold. These are bound states.
*   There is another phenomenon of poles at the same locations, but underneath another sheet, which is called a **virtual state**. They are not that different from each other.
*   A **bound state** can live forever; it is a real state that can travel. It is a particle that does not decay.
*   A **virtual state** is one that does not travel and does not decay. This is simply an enhancement.

This distinction is one of the objectives and discussion points in the field. When you observe a new structure, what kind of structure is it?

*   Is it related to a threshold?
*   Is it a pole?
*   Is it a pole sitting *below* a certain threshold?
*   Or is it a resonance that sits in the complex plane and is not related to a threshold?

A relation to a threshold indicates a **molecular nature**. Remember, every threshold has two masses that are summed:  $s = (m_1 + m_2)^2$ . It implies that there is a continuum; there is one particle and a second particle that interact with each other. This is our threshold. If there is a pole that is related to a threshold, likely part of the wave function for this state is of this two-particle type. This is the molecular type. That's why identifying all thresholds and the complex structure, and where the resonance pole sits, is so important.

Now, a quick question. What about the other threshold,  $s = (m_1 - m_2)^2$ ? Yes, it's a **pseudo-threshold**. It appears artificially in our expressions because of the breakup momentum formula:
  $$p = \frac{\sqrt{[s - (m_1 + m_2)^2][s - (m_1 - m_2)^2]}}{2\sqrt{s}}$$  
If you look at that place, the amplitude is not supposed to have a physical singularity. This tells you that you cannot literally take this expression and continue analytically at the place of this pseudo-threshold. This is a sort of false threshold. We don't see it in the amplitude.

This is one indication that you should not take this expression literally and build it into your model. Instead of using just the phase space factor,  $\rho(s) = \frac{1}{8\pi} \frac{2p}{\sqrt{s}}$ , note that this is actually the imaginary part of the bubble diagram. You see this simply from unitarity, because once you cut this diagram, the imaginary part would be equal to the product of the matrix elements (both equal to one) and the two-body phase space, because you cut two lines. Here is the two-body phase space.

The pseudo-threshold is present here because you are using only the imaginary part in your amplitude. If you were to take the full bubble diagram, you don't have a pseudo-threshold there.


::: callout-note
**Key Formulas Recap**

*   **Physical Threshold:**  $s = (m_1 + m_2)^2$  defines where a new two-particle channel opens, creating a branch point.
*   **Two-Body Phase Space:**  $\rho(s) = \frac{1}{8\pi} \frac{2p}{\sqrt{s}}$  is the phase space factor and appears as the imaginary part of the bubble diagram from unitarity.
*   **Unitarity Relation:** A simplified form is  $\operatorname{Im} \mathcal{M}(s) \propto \rho(s) |\mathcal{M}(s)|^2$ , linking the amplitude's imaginary part to the phase space.
:::

I was thinking we could do the exercise in the lecture today of computing this bubble diagram literally, because it's really closely related to unitarity.

