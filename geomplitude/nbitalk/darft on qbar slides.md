### Last Entries

Slide 1:

To obtain the NMHV last entry condition, we need calculate the $\mathrm{d}^{2\vert 3} \mathcal{Z}_{n+1}$ integration for all possible N$^{2}$MHV Yangian invariants. The N$^{2}$MHV Yangian invariants have been classified and there are 14 classes of them. which you can be found in the book. Just note that the first 13 classes are rational. The d$^{2|3}\mathcal{Z}_{n+1}$ integration can be performed as in the NMHV case which did in the original $\bar{Q}$ paper. While the last class need a special attention. This kind of Yangian invariants contains square roots and hence is algebraic. How to deal with these Yangian invariants will be the main theme of this talk. For now, let me just spell out the last entries obtained from N$^{2}$MHV Yangian invariants. 

Slide 2:

Taking the cyclicity into account. There are 3 different classes of NMHV last entries: the first is just  MHV last entries multiplied by an arbitrary R-invariants. While in the second and third classes, the arguments of  $\bar{Q}\log$ involves the intersections of momentum twistors. These intersection are not arbitrary, they respect planarity in some sense. Furthermore, in these two classes, the associated R invariants are fixed, they must share the same particles with the intersections. 

### Algebraic letters and words in two-loop NMHV amplitudes.

Slide 3:

 To compute the 2-loop NMHV n-point amplitudes, we need  the one-loop N$^{2}$MHV amplitudes as the input. which can be obtained from the chiral or the scalar box expansion. We need to regulate some integrals in this expansion to deal with the infrared divergence, here we use the DCI regularization scheme. Then, the scalar box expansion for the BDS-normalized amplitude can be written in the following form, where $f_{a,b,c,d}$ are the box coefficients for N^{2}MHV amplitudes and hence  are linear combinations of N$^{2}$MHV Yangian invariants mentioned above, $f^{\text{MHV}}$ are MHV leading singularities, which are either 0 or 1. the infrared divergence in box integrals are canceled , hence only finite parts remain, and they are some weight-2 polylog

Slide 4:

In the box expansion, the most generic terms are four mass box, where each corner involves more than 1 particles and hence are massive. To describe this boxes, we introduce $u$,$v$, and in particular this square root $\Delta$. For this box, the box coefficient is exactly the last Yangian invariant we mentioned above, here  we give the explicit formula, and the box integral is a simple weight-2 polylog which depends on $z$ and $\bar{z}$  here $\alpha$ and $\delta$ are solutions of this Schubert problem, and again the solutions will contain this square root $\Delta$. 

However, for any degenerated box, that means one or more mass corner becomes massless, the square root will disappear, since one of $u$ and $v$ will vanish. For these boxes, the $\mathrm{d}^{2\vert 3}\mathcal{Z}_{n+1}$ integration can be performed without any obstacle. 

So from now on, we will focus on these four-mass box: Recall that the $\mathrm{d}^{2\vert 3}\mathcal{Z}_{n+1}$ integration contains a fermionic integral over $\chi_{n+1}$, that means one of eight legs (a-1,a),...,(d-1,d) must be $n{+}1$, otherwise this fermionic integration gives 0, the   $\mathrm{d}^{2\vert 3}\mathcal{Z}_{n+1}$ integration also contains a contour integral around $\epsilon=0$, that means the box must become singular under the colinear limit, otherwise this contour integral gives 0. 

Slide 5:

All in all, only two kinds of 4-mass boxes have contributions. one is $f_{a,b,c,n+1}$ and the other is $f_{1,b,c,n}$, however, only the first kinds is is an obstacle. since under the collinear limit, the square root $\Delta_{1,b,c,n}$ becomes 1-u which is not a square root any more. While the second kinds of square root $\Delta_{a,b,c,n+1}$ will becomes a square root of a quadratic polynomial in $\tau$. Mathematicians have already known how to handle with such square roots for centuries,  This is a very classical problem to find a rational parameterization of a quadratic curve, the upshot is to find a rational point of this curve, once the rational point is found, you can easily work out the rationalize parameterization.(The algorithm can be found in Wikipedia)

For our cases, once you write down the explicit expression for A,B, and C, you can easily find the rational points and hence the rationalize parameterization $t(\tau)$. Using this variable substitution, the $\tau$-integrand becomes a rational function of $t$, while the integration region now involve algebraic quantity $\Delta$. Even so, the result after this variable substitution and the 1-D integrations is too lengthy to be written down in fewer slides. But we do find that both the algebraic letters and algebraic words follow a simple pattern. Let me spell the algebraic letters first:

Slide 6:

There are two kinds of new algebraic letters, which are denoted by $\mathcal{X}$ and $\tilde{\mathcal{X}}$ and labeled by 1 superscript and 4 sub subscripts. The subscripts are in a cyclic ordering and indicate the associated square root $\Delta_{a,b,c,d}$. Once the subscripts has been fixed, we have six different choices for superscript, which rely on the first three subscript and represent different $x$'s. Note that the square root $\Delta_{abcd}$ is invariant under the cyclic rotation of its subscripts,  so $\mathcal{X}_{abcd}$, $\mathcal{X}_{bcda}$, etc., will involve the same square root. You may wonder that why we write the algebraic letters in such a way, for example, why we introduce these $x$,  I will show you later the reason. For now, Let us just count how many algebraic letters we obtain. 

Slide 7:

You may have noticed that there is potential degeneracy if we take $a$ to be $d+2$ or take $c$ to be $d-2$, so let us start with the most generic case (that is each mass corner involve 3 particles at least). For this case, we have 50 algebraic letters which involve the same square root, 48 of them would be $\mathcal{X}$ and $\tilde{X}$ since we have 4 different but cyclic equivalent orderings and 6 choices of superscripts, 2 of them would be $z/\bar{z}$ and $(1-z)/(1-\bar{z})$ which already appear in the symbol of one-loop amplitudes. As mentioned above, some degeneracy happens when some mass corners only involve 2 particles, this is because that some $x$ introduced above becomes 0 or $\infty$, there are two examples.  Therefore, for a square root $\Delta_{a,b,c,d}$,  if there are $m$ corners that contain only two particles in the corresponding 4-mass box, then there would be 50-2m algebraic letters associated with this square root. These $\mathcal{X}$ and $\tilde{\mathcal{X}}$ are directly obtained form the $\bar{Q}$ calculation, together with $z/\bar{z}$ and $(1-z)/(1-\bar{z})$, they give a cyclic and reflection invariant set of algebraic letters. However there are not multiplicatively independent.  They satisfy some multiplicative relations.

Slide 8:

Amazingly, no matter what $a,b,c,d$ are, there are 33 multiplicative relations. In their most generic form, these relations reads:

You may worry about the degeneracy we mentioned above, while, if such a degeneracy indeed happens, then we can simply replaced that degenerate $\mathcal{X}$ or $\tilde{\mathcal{X}}$ with $z/\bar{z}$ or $(1-z)/(1-\bar{z})$, the same multiplicative relations still hold. It is remarkable that we have the same 33 multiplicative relations for any degenerate case, and it would be interesting to understand them better, especially if we can relate them to the cluster algebra Gr(4,n).

(So for 8 point, since there are only 2 different four mass box, and every corner of these boxes only contains 2 particles, there are would be 18 multiplicatively independent algebraic letters, for 9 points, by the same way, you will find 99 multiplicatively independent algebraic letters.  )

Slide 9:

Here I briefly comment on these algebraic letters (which can not be obtained from the Landau analysis). these algebraic letters can be rewritten as such standard form, Unlike rational ones, such a letter indicates two kind of cuts: One arise from the discriminant, and the other arise from b goes to zero which is the same as the cut of log b. Landau equation tell us b must belong to rational letters. Since we already have all possible algebraic letters, then we can have some prediction for  the alphabet of rational letters by computing these $b$, Just recall that all algebraic letters are written in terms of $(a+\Delta)/(a-\Delta)$, then we can obtain these $b$ by $(a+\Delta)(a-\Delta)$, this product is represented by $|a+z|^{2}$. Here are some examples: 

where we introduced four lines. For the 2-loop 9 point  NMHV amplitudes, we found 58 cyclic-inequivalent rational letters, and these rational letters indeed contain all ration letters on R.H.S. 

In particular, we predict a new class of rational letters which first appear in 9-point. 

Slide 10:

Once the algebraic letters are expressed in terms of $(a+\Delta)/(a-\Delta)$, we can separate the words involving algebraic letters from the symbol without ambiguity, and we call such words algebraic words. More importantly, as noted in our pervious work, these algebraic words, although not integrable, follow a very simple pattern:

First the first two entries form the weight-2 symbol of the four-mass box integral $I_{a,b,c,d}$, 

Second, the third entry is an arbitrary algebraic letter. 

Here we have a stronger result that the last entries final entries and the accompanied R invariants are also fixed. In particular, if the third entry is a non-degenerate $\mathcal{X}$ or $\tilde{\mathcal{X}}$, the algebraic words have a very simple expression as follows:

Here you see the reason why we introduce these $x$, they are exactly the last entries of these algebraic words. It is very non-trivial that this pattern of algebraic words extends to all multiplicities; it would be nice to understand the origin. 

While if the third entry is $z/{\bar{z}}$ or $(1-z)/(1-\bar{z})$, the result is slight lengthy, but it still can be written with in one-piece of paper. Here we just remark one property shared by these two kinds of algebraic words: the accompanied $R$-invariants always contains two pairs of adjacent particles. This property gives a  very significant corollary.

 Slide 11:

The $\chi_{i}\chi_{j}\chi_{k}\chi_{l}$ components with non-adjacent $i,j,k,l$ of the two-loop NMHV amplitudes are free of all these algebraic words, since the R invariants accompanying algebraic words have no contributions to this component. Further more, this kind of components are the simplest components in two-loop NMHV amplitudes, their symbol has the minimal size, and for 8-point, we find the alphabet for this component only has 68 rational letters. More interestingly, this component correspond to the difference of the so-called double pentagon integrals. The result or symbol of these integrals currently are unknown, however, by evaluating it at a specific kinematic point, Bourjaily etc., found these integrals individually contains algebraic quantities like $\Delta$. And their numeric result are  agree with our result.

