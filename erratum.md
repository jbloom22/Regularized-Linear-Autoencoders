# Clarification and Erratum

- In Section 1, we write "While the paper made no mention of it,
we realized by looking at the code that training was done with the
common practice of L2-regularization". While we did realize this by
looking at the code, in fact Plaut does mention in [Section IV](https://arxiv.org/abs/1804.10253) that
he found "weight decay regularization" to be beneficial. Our work
proves that it is necessary.

- In Section 6 and Appendix B, we explain how the connectedness
of R^m implies that all minima are connected through paths of gradient trajectories
through index-1 saddles. In the (regularized) LAE case, our work
derives the heights of all critical points in terms of the spectrum of X.
This spectrum is extremely well-studied for random matrices,
including [those](https://arxiv.org/abs/cond-mat/9709283)
which commonly arise in applications. A related concentration of
measure phenomenon is applied to general deep neural networks
in [The Loss Landscapes of Multilayer Networds](https://arxiv.org/abs/1412.0233),
explaining the empirical observation in
[Fast Geometric Ensembling](https://arxiv.org/pdf/1802.10026.pdf),
of paths between minima that remain *close in height* to the that of the minima.

- In Appendix B, the final sentence should read: "And since R^m is
contractible, their method may in principle extend to finding
critical points of higher index that form a *contractible chain
complex*, flowing along gradient trajectories from one minimum
to all minima through index-1 saddles, from those index-1 saddles
to other index-1 saddles through index-2 saddles, and so on until
contractibility is satisfied. Note there may exist additional
critical points forming *null-homotopic chain complexes*."

### Typos

- In Footnote 1, we write "The principal directions of X are
the eigenvectors of the covariance of X." To clarify, we mean
the m x m covariance matrix between the rows of X.

- In Section 2.3, the first paragraph should conclude: "In fact,
L_2-regularization reduces the symmetry group from GL_k(R) to
O_k(R), making the [right] singular vectors of the encoder and
[left] singular vectors of the decoder well-defined."

- In Section 2.3, "(2)" refers to the second item in the list,
not equation (2).

- Theorem 2.1 is preceded by an errant ")".

- Theorem 2.1 should say "While critical points of L [and L_pi] satisfy W_1 = W_2^+".

- In Theorem 4.2, there is an errant comma after  L_σ.

- In Section 6, items 1, 3, and 4 in the list are with respect to critical points of the loss function.

- In Lemma A.5, the equation should end with a period.

- In Appendix B, citing the 3-dimensional Poincare conjecture is overkill.
If a homology 3-sphere admits a perfect Morse function, then it consists of
a 3-cell attached to a 0-cell, and is therefore the 3-sphere.

- In Appendix B, the columns of the Morse index table should be labeled
by the principal directions u_1, u_2, u_3, and u_4.

- In Appendix B, "topologically inevitable" is not a technical term.
But it should be.
