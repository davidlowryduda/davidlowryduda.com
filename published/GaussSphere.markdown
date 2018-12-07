
Update to Second Moments in the Generalized Gauss Circle Problem
================================================================

Last year, my coauthors Tom Hulse, Chan Ieong Kuan, and Alex Walker posted a
[paper][arxivpaper] to the arXiv called "Second Moments in the Generalized Gauss
Circle Problem". I've [briefly described its contents before][bloglink].

This paper has been accepted and will appear in [Forum of Mathematics:
Sigma][sigma].

This is the first time I've submitted to the Forum of Mathematics, and I must
say that this has been a very good journal experience. One interesting aspect
about FoM: Sigma is that they are immediate (gold) open access, and they don't
release in issues. Instead, articles become available (for free) from them once
the submission process is done. I was reviewing a publication-proof of the paper
yesterday, and they appear to be very quick with regards to editing. Perhaps the
paper will appear before the end of the year.

An updated version (the version from before the handling of proofs at the
journal, so there will be a number of mostly aesthetic differences with the
published version) of the paper will appear on the arXiv on
Monday 10 December.[note]due to the way the arXiv handles paper updates over
weekends.[/note]


A new appendix has appeared
---------------------------

There is one major addition to the paper that didn't appear in the original
preprint. At one of the referee's suggestions, Chan and I wrote an appendix. The
major content of this appendix concerns a technical detail about Rankin-Selberg
convolutions.

If $f$ and $g$ are weight $k$ cusp forms on $\mathrm{SL}(2, \mathbb{Z})$ with
expansions
$$
f(z) = \sum_ {n \geq 1} a(n) e(nz), \quad g(z) = \sum_ {n \geq 1} b(n) e(nz),
$$
then one can use a (real analytic) Eisenstein series
$$
E(s, z) = \sum_ {\gamma \in \mathrm{SL}(2, \mathbb{Z})_ \infty \backslash
\mathrm{SL}(2, \mathbb{Q})} \mathrm{Im}(\gamma z)^s
$$
to recognize the Rankin-Selberg $L$-function
\begin{equation}\tag{RS}
L(s, f \otimes g)
:= \zeta(s) \sum_ {n \geq 1} \frac{a(n)b(n)}{n^{s + k - 1}}
= h(s) \langle f g y^k, E(s, z) \rangle,
\end{equation}
where $h(s)$ is an easily-understandable function of $s$ and where $\langle
\cdot, \cdot \rangle$ denotes the Petersson inner product.

When $f$ and $g$ are not cusp forms, or when $f$ and $g$ are modular with
respect to a congruence subgroup of $\mathrm{SL}(2, \mathbb{Z})$, then there are
adjustments that must be made to the typical construction of $L(s, f \otimes
g)$.

When $f$ and $g$ are not cusp forms, then Zagier[note]Zagier, Don. "The
Rankin-Selberg method for automorphic functions which are not of rapid decay."
J. Fac. Sci. Univ. Tokyo Sect. IA Math 28.3 (1981): 415-437.[/note] provided a
way to recognize $L(s, f \otimes g)$ when $f$ and $g$ are modular on the full
modular group $\mathrm{SL}(2, \mathbb{Z})$. And under certain conditions that he
describes, he shows that one can still recognize $L(s, f \otimes g)$ as an inner
product with an Eisenstein series as in \eqref{RS}.

In principle, his method of proof would apply for non-cuspidal forms defined on
congruence subgroups, but in practice this becomes too annoying and bogged down
with details to work with. Fortunately, in 2000, Gupta[note]Gupta, Shamita
Dutta. "The Rankin-Selberg method on congruence subgroups." Illinois Journal of
Mathematics 44.1 (2000): 95-103.[/note] gave a different construction of $L(s, f
\otimes g)$ that generalizes more readily to non-cuspidal forms on congruence
subgroups. His construction is very convenient, and it shows that $L(s, f
\otimes g)$ has all of the properties expected of it.

However Gupta does not show that there are certain conditions under which one
can recognize $L(s, f \otimes g)$ as an inner product against an Eisenstein
series.[note]or something analogous to that, as the story is slightly more
complicated on congruence subgroups.[/note] For this paper, we need to deal very
explicitly and concretely with $L(s, \theta^2 \otimes \overline{\theta^2})$,
which is formed from the modular form $\theta^2$, non-cuspidal on a congruence
subgroup.

The Appendix to the paper can be thought of as an extension of Gupta's paper: it
uses Gupta's ideas and techniques to prove a result analogous to \eqref{RS}. We
then use this to get the explicit understanding necessary to tackle the Gauss
Sphere problem.

There is more to this story. I'll return to it in a later note.



Other submission details for FoM: Sigma
---------------------------------------

I should say that there are many other revisions between the original preprint
and the final one. These are mainly due to the extraordinary efforts of two
Referees. One Referee was kind enough to give us approximately 10 pages of
itemized suggestions and comments.

When I first opened these comments, I was a bit afraid. Having *so many
comments* was daunting. But this Referee really took his or her time to point us
in the right direction, and the resulting paper is vastly improved (and in many
cases shortened, although the appendix has hidden the simplified arguments cut
in length).

More broadly, the Referee acted as a sort of mentor with respect to my technical
writing. I have a lot of opinions on technical writing,[note]and on writing in
general... and actually on LaTeX source as well. I'm an opinionated person, I
guess.[/note] but this process changed and helped sharpen my ideas concerning
good technical math writing.

I sometimes hear lots of negative aspects about peer review, but this particular
pair of Referees turned the publication process into an opportunity to learn
about good mathematical exposition --- I didn't expect this.


I was also surprised by the infrastructure that existed at the University of
Warwick for handling a gold open access submission. As part of their open access
funding, Forum of Math: Sigma has an author-pays model. Or rather, the author's
institution pays. It took essentially no time at all for Warwick to arrange the
payment (about 500 pounds).

This is a not-inconsequential amount of money, but it is much less than the 1500
dollars that PLoS One uses. The comparison with PLoS One is perhaps apt. PLoS is
older, and perhaps paved the way for modern gold open access journals like FoM.
PLoS was started by group of established biologists and chemists, including a
Nobel prize winner; FoM was started by a group of established mathematicians,
including multiple Fields medalists.[note]One might learn from this that it's
necessary to have a little "oh" in your acronym in order to be a successful
high-ranking gold open access journal.[/note]

I will certainly consider Forum of Mathematics in the future.



[arxivpaper]: https://arxiv.org/abs/1703.10347
[bloglink]: http://davidlowryduda.com/second-moments-in-the-generalized-gauss-circle-problem/
[sigma]: https://www.cambridge.org/core/journals/forum-of-mathematics-sigma
