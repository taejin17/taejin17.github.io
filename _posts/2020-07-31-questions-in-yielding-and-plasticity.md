---
title: Questions in Yielding and Plasticity
published: true
---

Hello world, I've recently been studying yielding and plasticity in materials. The topics I've been focusing on are criteria for such deformations to occur and the atomic basis of these deformations. Here are some resulting questions with analysis:

**1. What atomic process enables yielding?**

Yielding is driven by a shearing stress, where one atomic plane slides along another plane at a dislocation. Bonds between planes must be broken to allow for tangential slide associated with yield. In contrast to fracture, yielding allows for the formation of new bonds in new positions. Also, the forces required for causing tangential atomic slide from one equilibrium position to another are given by the bond-energy function (repulsive and attractive forces).

**2. Why do we not see yielding in ceramics (ionic solids)?**

In FCC metals (e.g. Au, Cu, etc...), closed-packed planes (those in the {111} Miller index} have large distances between the nearest close-packed planes of adjacent unit cells, giving rise to softer interplanar bonding and wider dislocations (edge or screw). Due to the wide dislocations present in FCC metals, there is a lot less frictional drag corresponding to a smaller Peierls force. That is, there is less resistance to dislocation motion, so the material yields past a certain stress and strain. In BCC metals, dislocation width is smaller, and in ionically or covalently bonded ceramics, the dislocation width is even smaller given the geometry of the lattices. Since the dislocation width in ceramics is much more narrow than in FCC or BCC metals, ceramics experience a much greater Peierls stress. Since the dislocation mobility in ceramics is much lower than in FCC or BCC metals, ceramics are much more brittle, so they will fracture before reaching the yielding/plasticity region on a stress-strain curve.

**3. How would you calculate or think about the theoretical strength of a material?**

Here we will define the theoretical strength of a material to be the maximum possible stress the material can withstand in its perfect state (no defects). The quoted derivation to follow is from [MIT's 3.11 Mechanics of Materials: The Dislocation Basis of Yield and Creep](http://web.mit.edu/course/3/3.11/www/modules/dn.pdf).

> First we will approximate the bond-energy function describing the tangential slide occuring in the material: 
>> ???? = ????<sub>max</sub> * sin(2??(x/a)) where _a_ is the interatomic spacing and _x_ is the slide distance

> Thus, ????<sub>max</sub> occurs at ?? distance between 2 atomic equilibrium positions. Now let the shear strain be ???? = x/a. Then we have the following:

>> d????/d???? = (d????/dx)(dx/d????) = a(d????/dx) = a(????_max)(2??/a)cos(2??(x/a))

>Now we define the shear modulus G as the ratio of shear stress to shear strain.

>> If G = d????/d???? as ???? ??? 0 then G = ????<sub>max</sub> * 2??

> Therefore the shear stress ????<sub>max</sub> at yield = G/(2??) which approximates to G/10 (on an order of 10 GPa). Experimental values of strength of materials are around 10-100 MPa, so the theoretical strength calculated in an arbitrary material is on 2 to 3 orders of magnitude greater than the current materials in practice. 

The theoretical strength of the material seems too large, but the ability to manufacture materials with increasingly less defects is becoming pertinent and advancing rapidly.
