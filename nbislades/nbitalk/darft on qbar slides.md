planar $\mathcal{N}=4$ SYM, known as the harmonic oscillator of QFT in the following senses:

It is a integrable 4-dimensional QFT and have the connection to Quantum Gravity in AdS, It contains new mathematical structures  such as positive Grassmannian and the amplituhedron, and it also provides a fruitful playground for Feynman loop integrals. 

The N=4 SYM theory has 2 gauge boson, 8 fermion and 6 scalars. All these particles are related by supersymmetry and can be packaged into one single supermultiplet. Instead of considering the scattering of gauge boson, fermion of scalars, we will consider the scattering of supermultiplet which encode the SUSY ward identities and easier and more symmetric than component amplitudes. It is well know that N=4 Super Yang-mills theory has the conformal symmetries at both classical and quantum level which ensure amplitudes are UV finite. 

However, hidden symmetries are recovered when we consider the planar amplitudes in N=4 SYM theory, this symmetries  are manifest after introducing a dual superspace  for which we will use x and $\theta$ to parameterize this space. （This kind of symmetries are first noticed in multi-loop integrand, then at strong coupling, and lead to a remarkable connection between amplitudes and  Wilson loop). then the planar amplitudes just become a light-like polygonal Wilson loop in the dual superspace, the dual superconformal symmetries are just the superconformal symmetries of Wilson loop.



Remarkably, superconformal symmetries, together with the dual superconformal symmetries, generate an infinite-dimensional Yangian symmetries, It is the emergence of such infinite dimensional symmetries to make the planar N=4 SYM solvable. From the perspective of symmetries, what is the general Yangian invariants and what kind of role do they play in the amplitudes/Wilson loop.



To address these questions, it is convenient to linearly realize these symmetries by introducing so-called twistor and moment twistor, Then the superconformal transformation turn out to be SL(4|4) transformation on momentum twistors. In the following, we mainly use momentum twistors. In terms of momentum twistor,  it is easy to build two prototypes of dual conformal invariants, one is the SL(4) invariant, the Plucker coordinate, and the other is the well known R-invariant, which also is the first non-trivial Yangian invariant.





To generate general Yangian invariants, one needs to consider the full Yangian symmetries. Inspired by Witten's twistor string, it's convenient to express such invariants as integrals over an auxiliary space. Here the auxiliary space turn out be Grassmannian, and such Grassmannian integral are uniquely fixed by considering the action of  Yangian  generator.



On the other hand, these Grassmannian integral can be represented by the so-called on-shell diagram, in which each vertex is associated a MHV/$\overline{\text{MHV}}$ 3-point amplitudes, while each propagator is associated with an integral over on-shell degree of freedom. Form this point of view, Yangian invariants are leading singularities of loop-integrand. Based on the generalized unitarity method, we have the following expansion for $n$ point N$^{k}$MHV L-loop  amplitudes in planar N=4 SYM.



When we move to loop amplitudes, since we are considering the scattering of massless particles, the dual conformal invariance is broken by the infrared divergence of loop amplitudes. However, the  infrared structures of amplitude are understood up to all multiplicity and all loop, that is, BDS ansatz, after subtract this part, the dual conformal invariance is restored, we called the MHV BDS-subtracted amplitude reminder function, while the helicity structure are encoded in the ratio of non-MHV amplitudes and MHV amplitudes, that is so-called ratio function. The reminder part are finite functions of dual conformal invariants. Since we can not build a dual conformal invariant just by 5 particles. Such nontrivial part first show up at six points. Here we are interested in the 2-loop NMHV BDS-subtracted amplitude. 



Since the infrared divergence have been substracted，the BDS-subtracted amplitudes, R_{n,k} can be expressed as a sum over Yangian invariant times transcendental function F. As we said before, Yangian invariant are totally determined by the Yangian Symmetries only and independent of loop-integral. while transcendental function $F$ arise form loop-integral and carry the cut structure of amplitudes. Moreover, For MHV and NMHV amplitudes, these $F$ are believe to be just Multiple polylogarithm of weight 2L.



So let me briefly introduce such transcendental function. An polylog of weight 2L are  2L-fold iterated integrals, where $s_{i}$ are rational functions of integration variables.  Such functions can be characterized by its symbol, then $s_{i}$ are called symbol letter. and the collection of all letters is called alphabet. Here are two examples for polylog of weight 2 and their symbols. The most important information of a symbol are carried by the first entries and last entries, the first entries encode the discontinuity of function F, while the last entries are related to the derivative of functions, since the derivatives only acts on the last entry of the symbol according to the definition. 

In recent years, there are numerous progress in computing multi-loop contribution to reminder functions and ratio functions. most notably by the hexagon and heptagon bootstrap program. The great achievement on hexagon and heptagon bootstrap programs are mainly based on the assumption that the corresponding alphabets consist of 9 and 42 variables, which are cluster variables for G(4,6) and G(4,7), thus the solution space for hexagon and heptagon are finite dimensional. By impose physical constrains on cut structure and boundary conditions on amplitudes further, the MHV hexagon reminder function can be determined even up to 7 loops.

However, starting with octagon, such a program is difficult to perform since the alphabets are not well understood. There are two reason for this, 

1. The symbol alphabet get out of control from cluster algebras which turn out to be infinite type for $n$>7. 

2. More Importantly, square roots appear in symbol letters even at one-loop N$^{2}$MHV 8-point. We will see such square roots indeed  appear in 2-loop NMHV octagon amplitudes and we refer such letters to algebraic letters. 



Another way to compute amplitudes is using (Quantum) Yangian Symmetries. in particular $\bar{Q}$-equation and its parity conjugate. This method is based on the dual super conformal anomaly of amplitudes, here the operator qbar is a chiral half of dual superconformal generator. BDS-subtracted amplitudes has anomalies under the action of $\bar{Q}$ . And  OPE analysis tell us that the result is given by an integral over the collinear limit of a higher-point amplitude. Perturbatively, this relate a L-loop amplitudes to a (L-1)-loop amplitude with both n and k adding one. In the following, we will use C and C' to denote these two factors.  

The most important operation in $\bar{Q}$ equation is the integral measure, which consist of bosonic part and fermionic part. When we performing this integral, we first do the Grassmann integral, then take the colinear parameterization and take residue at $\epsilon=0$. At last perform the integral  for $\tau$  from 0 to infinity. 





Due to dual conformal invariance, F are functions of cross-ratios, further more, F are expected to be polylog  for MHV and NMHV amplitude. then their derivatives are just polylog of weight (2L-1) times dlog $s_{\beta}$ Since the only difference between the differential operator d and Qbar is just replace dZ by $\chi$, then the action of $\bar{Q}$ on $R_{n,k}$ is trivial. Just replace the dlog in the derivative of F with Qlog. This form are what we expected from the right hand side of Qbar-equation. After this form is obtained, we can inverse the replacement, and obtain the differential of amplitudes, the argument of Qlog hence become the last entries of $R_{n,k}$, 



Now we need to figure out the kernel of $\bar{Q}$ operator. If the kernel of $\bar{Q}$ contains a non-trivial dual conformal function F. Then for any solution of $\bar{Q}$ equation,  this solution plus F are also a solution of $\bar{Q}$ equation.  The kernel of $\bar{Q}$ depend on k, and start with NNMHV amplitudes, the kernel will contain DCI functions. So we can use $\bar{Q}$ equation fix MHV and NMHV amplitudes uniquely.



Now let us see how to obtain the differential of amplitudes from the Right hand sides of Qbar equations. Since the operation in right hand side is integral over the particle n+1, and the second term depend on this particle  by a tree amplitude. this part is a little trivial. So let us focus on the first term. Since we know the structure of $R_{n,k}$, we can again decompose it into two parts, the Yangian invariants and transcendental function F. For the first step, we don't need to any true integral, We just do the Grassmann integral and take the residue at $\epsilon$=0  for Yangian invariant, this procedure will yield Yangian invariants with n and k decreased  by 1, times $\bar{Q}\log$ of something and dlog f(\tau) that will becomes measure of tau-integral,  and for the transcendental functions F, we just take the collinear limit, and they will becomes functions of tau. In the second step, we just put everything related to tau together and do the tau-integral. In usual cases, they are rational function of \tau, this integral can be easily performed, however there are some exception discussed latter. Despite of these exception, this integral will yield a polylog of weight 2L-1, together with the last entries given by $\bar{Q}\log$, we obtain a symbol of weight 2L. A crucial fact about $\bar{Q}$ equation is this operation, as we have seen, only act on Yangian invariants, and hence independent of loop order, that means the Last entries of MHV and NMHV amplitudes are totally determined by NMHV and N$^{2}$MHV Yangian invariants, respectively.  



The NMHV Yangian invariant are R-invariants. 

The N$^{2}$MHV Yangian invariants have been classified and can be found in the book by Arkani-Hamed et.al. 

Here I and J can generally be intersections of momentum twistors. but these intersections are not arbitrary, they share the same particles with the associated R-invariant. 



Now let me show how to use this equation to compute two-loop NMHV amplitudes. To compute the 2-loop NMHV n-point amplitudes, we need  the one-loop N^{2}MHV amplitudes as the input. which can be obtained from the chiral box expansion. 

Here $f_{a,b,c,d}$ are linear combinations of N$^{2}$MHV Yangian invariants and can be obtained from the computation of leading singularity. $f^{\text{MHV}}$ are MHV leading singularities, 



In the  box expansion, the most generic terms are four mass box. For such box we introduce u v, and the square root delta, and we find its box coefficient are this Yangian invariant, and the box integral is a polylog of weight 2. here \alpha and \delta are two solutions of Schubert problem, and the solutions will contain delta. However, for any degenerated box, that means one or more mass corner becomes massless, the square root will disappear, since one of u and v will vanish. 



All difficulty in the $\bar{Q}$-calculations comes form the tau integral for four-mass box, because the square root $\Delta$ will not become a rational function of $\tau$ under the collinear limit. However, $\Delta(\tau )$ can be rationalized by a variable substitution, since $\Delta^{2}$ is only a quadratic polynomial of $\tau$. Then this is nothing but the classical problem to find a rational parameterization of a quadratic curve. It is not hard to find such variable substitution. Once such substitution has been found, then integral can be easily performed. 



At the end, we find that $\tau$-integrals for four-mass box will introduce a cyclic seed of new algebraic letters of the form, with 6 choices of $x_{\ast}$, note that when $x_{\ast}$ take zero, these algebraic letters will reduce to the algebraic letter appearing one-loop, all these new algebraic letters always enter the symbol in the following combinations



The algebraic letter given in this way are not multiplicative independent, For the octagon, the $\bar{Q}$ calculation will gives the 44 algebraic letters, but only 18 of them are independent.  

Besides 18 algebraic letters, the alphabet for 2-loop NMHV octagon also have 180 rational letters which are contained in the prediction of Landau analysis. 

Here I briefly comment on these algebraic letters which can not be obtained from the Landau analysis. these letters can be rewritten as such standard form, Unlike rational ones, such letter indicates two kind of cuts: One arise from the discriminant, and the other arise from b goes to zero which is the same as the cut of log b. Landau equation tell us b must belong to 180 rational ones, and we have checked it indeed is this case. but  landau equation can not tell us what a is.



Finally let me comment on a cross check with Feynman integral computation. The simplest component of our result, the coefficient of $\chi_{1}\chi_{3}\chi_{5}\chi_{7}$. In our basis, the symbol  of this component has the minimal size and completely free of algebraic letters. This component correspond to the difference of two Feynman integrals.  each integral  depend on many algebraic letters, but the difference is free of algebraic letter. And their result are agree with our result.