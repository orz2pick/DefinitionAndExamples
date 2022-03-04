# DefinitionAndExamples

Uniform hyperbolity

M: manifolds $\to$(compact) $TM$: tangent bundle

$f:M \to M$ diffeomorphism,$C^1$ and $f^{-1}\in C^1$, is  <span style='color:blue'>hyperbolic</span> if the tangent bundle <u>split</u> into 2 invariant sub bundles.

$$T_xM=E_x^s \oplus E_x^u $$   $$\forall x \in \Lambda$$

$Df(x)E^s_x=E_{f(x)}^s$

$Df(x)E^u_x=E^u_{f(x)}$

$\exist$ metric for which

$$|Df(x)\nu^s|<1<|Df(x)\nu^u|$$

$\nu^u,\nu^s$ are unit vectors

<span style='color:yellow'>Example,A is <u>uniformly hyperbolic</u></span> 

<u>Equivalent definition:</u>

$TM=E^s\oplus E^u$, $Df$-invarient

$\exist c>0,\exist\lambda\in (0,1),s.t.$

$ \forall\nu^s\in E^s,$we have $||Df^n(x)\nu^s||\le C \lambda^n ||\nu^s||,\forall n>0$

$ \forall\nu^u\in E^u,$we have $||Df^{-n}(x)\nu^u||\le C \lambda^n ||\nu^u||,\forall n>0$

==Remark==: previous definition is less trivial

metric in defn.1 <u>Adapred metric</u>



$\Lambda:$ compact set $f(\Lambda)=\Lambda$, $f:M\to M$ is diffeomorphism, $\Lambda$ <u>hyperbolic set</u> if



<u>Theorem</u>: ==Stable manifold theorem==

$f:M\to M$ is hyperbolic $C^1$ diffeomorphism 

then $\omega^s(x)=\{ y\in M: d(f^n(x),f^n(y))\to0 ,h\to\infty \}$

$\omega^s_\epsilon(x)=\{y\in M:d(f^n(x),f^n(y))\le \epsilon \forall, n\ge0\}$

then $\exist \epsilon>0, s.t. \forall x$

$\omega^s_\epsilon(x)$ is an s-dimensional disc

$x\to \omega^s_\epsilon(x)$ vaies continuously

$T_y\omega^s_\epsilon(x)=E^s_y,\forall y\in \omega^s_\epsilon(x).$
$$
f\left(w^{s}(x)\right) \subset w^{s}(f(x))
\\
w^{s}(x)=\bigcup_{n \geq 0} f^{-n}\left(w_{\varepsilon}^{s}\left(f^{n}(x)\right)\right.
$$


$w^{s}(x)$ homosmophic to $\mathbb{R}^{3}$
$$
s=\operatorname{dim} E^{s}
$$
immersed manifold

### 9.25

$f:M\to M$ is $C^1$ and diffeomorphism 

$\mu$ is <u>invariant</u> if $\forall A $ measurable $\mu(f^{-1}(A))=\mu(A)$

$\mu$ invariant probability measure

$\mu$ is <u>ergodic</u> if $f^{-1}(A)=A\quad mod\ 0$, then $\mu(A)=0$ or 1

Example: rational rotations on $S$ <u>NOT</u> ergodic, whereas irational rotations are <u>ergodic</u>.

Theorem: the A is ergodic

###### <u>Stable Ergodicity</u>

$f:M\to M$ is $C^1$ and diffeomorphism s.t. $f$ <u>preserves</u> Lebesgue measure.

$Diff_m^{r}(M)=\{f:M\to M: C^r \text{diffeomorphisms s.t. m is f-invariant }  \}$

$f$ is stably ergodic if $\exist U\subset Diff_m^1(M)$ open set containing $f$

s.t. $g \in M\cap Diff^2_m(M) \Rightarrow g$ isergodic

remark: with this defn. f could be stably ergodic but not ergodic





$\pitchfork$

# DefinitionAndExamples
