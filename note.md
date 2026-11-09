# The two-point strain–direction pairing on unmodified Navier–Stokes ends at \( C_{\mathrm{CZ}} M(t)\,|\delta\xi|^2 + \text{remainders} \). Replacing the coefficient by an \( M \)-independent \( -\gamma \) is equivalent to the regularity problem.

**Benjamin Stanley Frohman**  
Independent Researcher  
8 November 2026

## Explicit non-claim

This note does not prove global regularity for the 3D incompressible Navier–Stokes equations on \(\mathbb{R}^3\) or \(\mathbb{T}^3\). It does not prove the Constantin–Fefferman hypothesis (uniform Lipschitz control of the vorticity direction \(\xi\) on regions of large vorticity). Replacing the leading coefficient \( C_{\mathrm{CZ}} M(t) \) by an \( M \)-independent negative constant \( -\gamma \) is equivalent to the open regularity problem. The calculation stops at the Calderón–Zygmund coefficient.

## Geometric kernel expansion

Let \( u \) be a classical solution of the unmodified 3D incompressible Navier–Stokes equations. Let \( \omega = \nabla \times u \), \( \xi = \omega / |\omega| \) (where defined), \( M(t) = \|\omega(\cdot,t)\|_{L^\infty} \), and \( S \) the strain tensor. The two-point pairing admits the expansion

\[
\delta\xi \cdot \bigl( S(x)\xi(x) - S(y)\xi(y) \bigr) = C_{\mathrm{CZ}} M(t)\,|\delta\xi|^2 + R_A + R_B + R_C,
\]

where the named remainders satisfy closed bounds of strictly lower order on intermediate-axis alignment (see below). The constant \( C_{\mathrm{CZ}} \) is the standard Calderón–Zygmund constant arising from the Biot–Savart representation of the strain.

## Intermediate-axis 1-jet

On intermediate-axis alignment the leading term is positive of size order \( M(t) \). An explicit 1-jet computation with slow tilt toward the principal stretching axis yields a positive contribution \( \lambda_1 \beta^2 + O(\beta^4) \) with \( \lambda_1 \sim M > 0 \). Max-axis alignment gives the opposite (good) sign and is withdrawn as a counterexample. The intermediate-axis case demonstrates that the coefficient cannot be replaced by an \( M \)-independent negative constant without additional directional control.

## Named remainders (A)–(C)

The near/far/high–low splitting of the singular integral produces three remainders:

- (A) Near-field remainder controlled by local Lipschitz of \(\xi\) and lower-order strain.
- (B) Far-field remainder controlled by enstrophy and decay of the kernel.
- (C) High–low frequency remainder controlled by the same scale separation.

None of (A)–(C) cancels the leading \( C_{\mathrm{CZ}} M(t)\,|\delta\xi|^2 \) term on intermediate-axis alignment. Their bounds are closed and of lower order.

## Conclusion

The expansion ends at \( C_{\mathrm{CZ}} M(t)\,|\delta\xi|^2 + \text{remainders} \). The replacement of this coefficient by an \( M \)-independent \( -\gamma \) remains open and is equivalent to the regularity question.
