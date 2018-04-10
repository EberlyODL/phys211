To recap, we can show from Newton's second law <lrn-math inline>(F_{net})_s = ma_s </lrn-math> that  

<lrn-math inline> W = \Delta K </lrn-math>

with the work calculated by integrating the force along the path <lrn-math inline>W=\int (F_{net})_s ds </lrn-math>.

But as the latest question has shown, this does not seem to always be correct. 

Let us look more in detail. In the problem shown below, both block A and block B will speed up (assuming no friction). The system of both blocks will increase their energy but yet the net force on the system is zero since the two forces F cancels.  

[ciscode|rev=1|tool=elmsmedia|item=4355|entity_type=node|render=display_mode|display_mode=image]

The problem is that the system is not just a single particle but has multiple parts and that these parts move independently. 

The system is "deformable" and energy can be put into the deformation. 

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
We will not be analyzing "deformable" system in this course. You should just be aware that such issues can arise. It also makes it easier to understand why we need to go beyond Newton's second law when looking at energy. 
</lrndesign-sidenote>

### Potential energy and Thermal Energy

As we go beyond the single particle model we will start adding terms to our energy equations. 

The form of the equation is always as 

"energy transfers" = change of energy of system

From Newton's second law we get 

<lrn-math inline> W = \Delta K  </lrn-math> 

but for systems with multiple parts, we will need new forms of energy beside kinetic. The new energy equations cannot be easily derived from Newton's second law (but it can be done).  

** Potential energy** is the subject of next week so we will come back to it. In a nutshell, potential energy is the energy related to the relative position of parts of a system that can be stored and retrieved.

If in the image above, there was a spring between block A and block B, the change in position of the two blocks could be stored in the spring and released when the spring snap back. 

Another form of energy is thermal energy which is the sum of all the random kinetic and potential energies of the atoms in a body. 

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
In Phys 211, we will no yet learn the tools on how to compute the exact amount of thermal energy in a given body. We will only be able to compute changes in the thermal energy due to friction. 
</lrndesign-sidenote>

### Kinetic and rolling friction

Kinetic (and rolling) friction are good examples where the naïve use of <lrn-math inline> W = \Delta K </lrn-math> fails. 

It is never correct to say that friction does work since work is a transfer of energy to the system. When you rub your two hands together, both hands get warmer. Friction does not just transfer energy to the system on which it is applied. Both the object and the surface gets warmer. 

More technically, because friction is fundamentally a force applied on a surface with many particles, the derivation of work from Newton's second law does not apply. Kinetic and rolling friction involve multiple deformation, breakage that are hard to fully account for.  

If you define the system to include the object and the surface on which it slides, then the friction is an internal force. It does not do work but it will increase the thermal energy of the system. As shown in your book, it is simple to prove that the amount of the increase is

<lrn-math inline> \Delta E_{th} = f_k\Delta s </lrn-math>

replacing <lrn-math inline>f_k </lrn-math> by </lrn-math> f_r </lrn-math> for rolling friction.

There are many important points to remember here 

* Static friction never does work or increase thermal energy. It does neither. For a force to do the point of contact of the force needs to move and static friction does not do work. A car that propel itself with static friction is using the energy from the gasoline or battery, not from the road. 

* The choice of system is important. If you choose a system with a dissipative force as an external force, you will not be able to (at least easily) apply conservation of energy since it is hard to know how much of the dissipated energy goes in the system versus how much goes out. Just choose a different system! Always put friction (kinetic or rolling) inside the system. 

* The formula for <lrn-math inline> \Delta E_{th} = f_k\Delta s </lrn-math> is very similar looking to what you would get if friction did do work. It make sense its that way but it led to many errors in many textbook and you can often see the phrase "work done by friction". 

