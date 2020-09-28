---
title: Questions on Yielding and Plasticity
published: false
---

Hello world, I've recently been studying yielding and plasticity in materials. The topics I've been focusing on are criteria for such deformations to occur and the atomic basis of these deformations. Here are some resulting questions with analysis:

**1. What atomic process enables yielding?**

Yielding is driven by a shearing stress, where one atomic plane slides along another plane at a dislocation. Bonds between planes must be broken to allow for tangential slide associated with yield. In contrast to fracture, yielding allows for the formation of new bonds in new positions. Also, the forces required for cuasing tangential atomic slide from one equilibrium position to another are given by the bond-energy function (repulsive and attractive forces).

**2. Why do we not see yielding in ceramics (ionic solids)?**

In FCC metals (e.g. Au, Cu, etc...), closed-packed planes (those in the {111} Miller index} have large distances between the nearest close-packed planes of adjacent unit cells, giving rise to softer interplanar bonding and wider disloactions (edge or screw). Due to the wide dislocations present in FCC metals, there is a lot less frictional drag corresponding to a smaller Peierls force. That is, there is less resistance to dislocation motion, so the material yields past a certain stress and strain. In BCC metals, dislocation width is smaller, and in ionically or covalently bonded ceramins, the dislocation width is even smaller given the geometry of the lattices. Since the dislocation width in ceramics in much more narrow than in FCC or BCC metals, ceramics experience a much greater Peierls stress. Since the dislocation mobility in ceraemics is much lower than in FCC or BCC metals, ceramics are much more brittle, so they will fracture before reaching the yielding/plasticity region on a stress-strain curve.

**3. How you would calculate or think about the theoretic strength of a material?**

Here we will define the theoretic strength of a material to be the maximum possible stress the material can withstand in its perfect state (no defects). The quoted derivation to follow is from [MIT's 3.11 Mechanics of Materials: The Dislocation Basis of Yield and Creep](http://web.mit.edu/course/3/3.11/www/modules/dn.pdf).

> First we will approximate the bond-energy function describing the tangential slide occuring in the material: 
>> 𝜏 = 𝜏<sub>max</sub> * sin(2π(x/a)) where _a_ is the interatomic spacing and _x_ is the slide distance

> Thus, 𝜏<sub>max</sub> occurs at ¼ distance between 2 atomic equilibrium positions. Now let the shear strain be 𝛾 = x/a. Then we have the following:

>> d𝜏/d𝛾 = (d𝜏/dx)(dx/d𝛾) = a(d𝜏/dx) = a(𝜏_max)(2π/a)cos(2π(x/a))

>Now we define the shear modulus G as the ratio of shear stress to shear strain.

>> If G = d𝜏/d𝛾 as 𝛾 → 0 then G = 𝜏<sub>max</sub> * 2π

> Therefore the shear stress 𝜏<sub>max</sub> at yield = G/(2π) which approximates to G/10 (on an order of 10 GPa). Experimental values of strength of materials are around 10-100 MPa, so the theoretical strength calculated in an arbitrary material is on 2 to 3 orders of magnitude greater than the current materials in practice. 

The theoretical strength of the material seems too large, but the ability to manufacture materials with increasingly less defects is becoming pertinent and advancing rapidly.
