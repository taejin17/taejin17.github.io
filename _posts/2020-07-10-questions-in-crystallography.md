---
title: "Questions in Crystallography"
published: false
---

Hello world, I've recently been studying crystallography. The topics I've been specifically focusing on are crystalline solid structures, alongside learning all of the notation for defining crystal planes and directions. Here are some resulting questions with analysis:

**1. What does the (111) plane of an FCC lattice look like?**

First, we should visualize the atoms to be space filling. The FCC crystal contains an atom at each of the 8 vertices and center of each of the 6 faces (assuming we don't bound it to the unit cell (e.g. split the atoms)). We then slice the FCC crystal along the [111] direction. The result would be a triangular plane with spherical cross sections at each vertex, and spherical cross sections at each midpoint between the vertices of the triangular plane.

**2. What are all potential body diagonals (what constitutes <111>)?**

A simplified definition of the crystallographic notation is as follows: the first integer, second integer, and third integer represent the coordinates x, y, and z respectively. [xyz] refers to direction from a defined origin point. <xyz> refers to the family of all [xyz]-like directions. Similarly, (hkl) refers to a plane such that x/a + y/b + z/c = 1 where h = 1/a, k = 1/b, and l = 1/c. {hkl} refers to the family of all (hkl)-like planes. Bar above a number signifies the negative direction with respect to the xyz axes. In a cubic structure, there are 4 distinct body diagonals, so it follows that there are 8 different directions. The directions that constitutes <111> are the following: [111], [11¯1], [¯1¯1¯1], [1¯11], [¯11¯1], [1¯1¯1], [¯1¯11], [¯111]. _Note_: ¯1 denotes 1 with a macron on top.

**3. What kind of rotational symmetries are allowed in solid crystals?**

For the sake of simplicity, we'll just analyze the FCC, BCC, and SC crystal lattices. For cubics like the aforementioned structures, the following rotations are possible: point rotations, axis rotations about both diagonal and horizontal vertical cross sectional planes, 2-fold (180°), 3-fold (120°), 4-fold (90°), and n-fold where n divides the 360° rotational possibility into an integer ending in 0.

**4. Is 5-fold axis rotation possible?**

No, it is not possible. 5-fold is indivicative of a pentagon in a 2-D cyrstal structure simplification. A 2-D pentagon as a unit cell for a plane results in a non space-filling pattern. That is, if one were to optimally layout pentagons adjacent to each other on a plane, there would inevitably be gaps. Thus, the 2-D pentagon does not scale up to a 3-D crystal structure as a unit cell, so it is not possible to rotate 5-fold.
