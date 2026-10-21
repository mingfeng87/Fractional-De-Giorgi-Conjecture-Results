# Fractional De Giorgi Conjecture

This repository hosts AI-assisted research manuscripts on one-dimensional
symmetry for the fractional Allen–Cahn equation. Together the drafts cover
dimension four across $0 < s < 1$ and dimension eight in the two regimes
near the endpoints $s = 1/2$ and $s = 1$. Furthermore, under the assumption of the optimal BV estimate, we have the one-dimensional symmetry for all $N\leq8$ and $1/2<s<1$.

**Draft status:** All manuscripts present candidate proofs. The team is
continuing to verify every argument. The summaries below describe the
statements and proofs as currently drafted.

---

## Manuscripts

### 1. Stable nonlocal cones and the fractional De Giorgi conjecture in dimension four below one half

📄 **[Read the PDF](https://github.com/mingfeng87/Fractional-De-Giorgi-Conjecture/blob/main/fractional_degiorgi_N4_less-half.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | 4 |
| **Range** | $0 < s < 1/2$ |
| **Length** | 57 pages |

The manuscript proves one-dimensional symmetry for bounded entire classical
solutions in $\mathbb{R}^4$ that are strictly increasing in one coordinate,
with no prescribed directional limits (Theorem 1.2). Its geometric statement
classifies nontrivial stationary stable nonlocal perimeter cones in
$\mathbb{R}^3$ as halfspaces for every perimeter order $0 < p < 1$, where
$p = 2s$. The hypotheses require a locally one-sided smooth boundary away
from the origin, a compact smooth spherical link, and stability under compact
variations away from the origin; connectedness of the link is not assumed
(Theorem 1.3). The proof develops angular-kernel estimates and normal-flux
pinching, then connects the cone classification to the fractional Allen–Cahn
equation.

---

### 2. The fractional De Giorgi conjecture in dimension four for \(1/2 < s < 1\)

📄 **[Read the PDF](https://github.com/mingfeng87/Fractional-De-Giorgi-Conjecture/blob/main/fractional_degiorgi_N4_bigger-half.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | 4 |
| **Range** | $1/2 < s < 1$ |
| **Length** | 124 pages |

The manuscript proves one-dimensional symmetry for bounded entire classical
solutions in $\mathbb{R}^4$ that are strictly increasing in one coordinate,
with no prescribed directional limits (Theorem 1.1). The argument first
establishes the classification of bounded stable entire classical solutions
in $\mathbb{R}^3$ as constant wells or planar layers (Theorem 1.2). Its main
ingredients include transition-sheet separation, profile and curvature
estimates, a tangential trace operator, surface stability, and a capacity
argument. The four-dimensional conclusion then employs directional limits,
global minimality, and minimizer rigidity.

---

### 3. Fractional De Giorgi rigidity in dimension eight near one

📄 **[Read the PDF](https://github.com/mingfeng87/Fractional-De-Giorgi-Conjecture/blob/main/fractional_degiorgi_N8_near_one.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | 8 |
| **Range** | $s$ sufficiently close to $1$ |
| **Length** | 105 pages |

The manuscript gives an argument for one-dimensional symmetry of bounded
entire solutions of $(-\Delta)^s u = u - u^3$ in $\mathbb{R}^8$ that are
strictly monotone in one direction, for $s$ sufficiently close to $1$
(Theorem 1.1). The proof uses the classical stable Allen–Cahn classification
in $\mathbb{R}^7$ (Theorem 1.2) and the stable Bernstein theorem for
complete two-sided stable minimal immersions $M^6 \to \mathbb{R}^7$
(Theorem 1.3). Its analytic core consists of intrinsic sheet separation,
two-component interaction estimates, quantitative profile preparation, signed
row capacities, and curvature retention on a complete intrinsic limit. A
residual calculation and a global physical test show that this limit is
minimal and stable, giving stable classification in $\mathbb{R}^7$ near the
local endpoint. The directional limits of a monotone solution then yield
global minimality in $\mathbb{R}^8$; a monotone perimeter blow-down and
asymptotic flatness give the claimed symmetry. No energy-growth bound,
prescribed end states, or restriction on the number of transition components
is imposed.

---

### 4. The fractional De Giorgi conjecture in dimension eight near the half-Laplacian

📄 **[Read the PDF](https://github.com/mingfeng87/Fractional-De-Giorgi-Conjecture/blob/main/fractional_degiorgi_N8_less_near_half.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | 8 |
| **Range** | $s_0 < s < 1/2$ for some $s_0 \in (0, 1/2)$ |
| **Length** | 84 pages |

The manuscript gives an argument for one-dimensional symmetry of bounded
entire solutions of $(-\Delta)^s u = u - u^3$ in $\mathbb{R}^8$ with
$\partial_{x_8} u > 0$, whenever $s_0 < s < 1/2$, for some
$s_0 \in (0, 1/2)$. No limits in the monotone direction are prescribed
(Theorem 1.1). The geometric argument first establishes separation of
neighboring stable interfaces at scale $\sqrt{1-2s}$. Averaged stability
then passes to classical minimal laminations, and the stable Bernstein
theorem in $\mathbb{R}^7$ gives uniform curvature bounds. Compactness of
cone links and a homogeneous gap inequality yield regular stable-cone
rigidity in ambient dimensions four through seven. This classifies the stable
end profiles of the eight-dimensional solution and makes it a global
minimizer. Its directed minimizing blow-downs are half-spaces, producing the
oriented phase trapping required by improvement of flatness. The threshold is
obtained by compactness and is not quantified; the argument does not address
all exponents below $1/2$.

---

### 5. A sharp-growth extension of the fractional De Giorgi method through dimension eight

📄 **[Read the PDF](https://github.com/mingfeng87/Fractional-De-Giorgi-Conjecture-Results/blob/main/fractional_de_giorgi_N8_BV.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | 8 |
| **Range** | $1/2 < s < 1$ |
| **Length** | 178 pages |

The manuscript establishes one-dimensional symmetry for bounded entire
solutions of $$(-\Delta)^s u = u - u^3$$ in $\mathbb{R}^8$ that are
monotonicity and BV condition — e.g. strictly increasing in one coordinate,
and of bounded variation, for $1/2 < s < 1$ (Theorem 1.1). The proof works in a
bounded-variation framework and combines compactness of BV
minimizers, interface separation at scale,
and propagation of stability / dimensional reduction.

---

## Citing a manuscript

Use the full manuscript title and the date printed in the PDF. Include the
[repository URL](https://github.com/mingfeng87/Fractional-De-Giorgi-Conjecture)
and the commit hash or a commit-specific PDF link for the version consulted,
so that the cited draft can be identified after revisions.

---

## Repository structure

| File | Description |
|---|---|
| [`fractional_degiorgi_N4_less-half.pdf`](https://github.com/mingfeng87/Fractional-De-Giorgi-Conjecture/blob/main/fractional_degiorgi_N4_less-half.pdf) | Dimension 4, $0 < s < 1/2$ |
| [`fractional_degiorgi_N4_bigger-half.pdf`](https://github.com/mingfeng87/Fractional-De-Giorgi-Conjecture/blob/main/fractional_degiorgi_N4_bigger-half.pdf) | Dimension 4, $1/2 < s < 1$ |
| [`fractional_degiorgi_N8_near_one.pdf`](https://github.com/mingfeng87/Fractional-De-Giorgi-Conjecture/blob/main/fractional_degiorgi_N8_near_one.pdf) | Dimension 8, $s$ near 1 |
| [`fractional_degiorgi_N8_less_near_half.pdf`](https://github.com/mingfeng87/Fractional-De-Giorgi-Conjecture/blob/main/fractional_degiorgi_N8_less_near_half.pdf) | Dimension 8, $s$ slightly below $1/2$ |
| [`fractional_de_giorgi_N8_BV.pdf`](https://github.com/mingfeng87/Fractional-De-Giorgi-Conjecture-Results/blob/main/fractional_de_giorgi_N8_BV.pdf) | Dimension 8 |
| [`docs/`](https://github.com/mingfeng87/Fractional-De-Giorgi-Conjecture/tree/main/docs) | Documentation site files |
| [`SECURITY.md`](https://github.com/mingfeng87/Fractional-De-Giorgi-Conjecture/blob/main/SECURITY.md) | Security policy |

---

## Keywords

Fractional De Giorgi conjecture; fractional Allen–Cahn equation;
one-dimensional symmetry; monotone solutions; stable solutions; nonlocal
minimal cones; spherical links; curvature estimates; layer separation; stable
Bernstein theorem; improvement of flatness.
