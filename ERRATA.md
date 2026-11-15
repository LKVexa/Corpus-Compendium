# Errata: Corpus Compendium on Rails

Corrected edition of 15 November 2026. These changes implement the accuracy and validity audit of the same date.

The corrections were made in the existing PDFs, in place. Each affected line or paragraph was re-typeset in the volume's own fonts and layout (Latin Modern, the same measure and leading), and the original glyphs were removed rather than covered, so search, copy and screen readers see the corrected text. A one-page summary, **Errata and scope notes**, now ends `00_Introduction_and_Apparatus.pdf` (page 35).

Page numbers below are PDF page numbers, not the numbers printed in the running heads.

## 1. Factual corrections in the field files

| Entry | Page | Previously | Now | Basis |
|---|---|---|---|---|
| 01 #10 Cofinality, rail II | 16 | "A space is never the union of fewer than cf(dim *V*) proper subspaces." | "The displayed quantity is always ℵ₀: every infinite-dimensional space is the union of a countable chain of proper subspaces." | The chain *W*ₙ = span(*B* ∖ {*b*ₙ₊₁, *b*ₙ₊₂, …}) exhausts *V*. |
| 29 #25 Cavity Finesse | 38 | "LIGO cavities reach finesse above 10⁴" | "Advanced LIGO's arm cavities have finesse about 450" | Advanced LIGO design, arXiv:1411.4547, Table 1 |
| 31 #37 Open Pipe Resonance | 56 | "End correction 0.6*d* per open end" | "End correction 0.6*d* in total: about 0.3*d* (that is, 0.6*r*) per open end" | Unflanged end correction ≈ 0.61*r* per end |
| 33 #58 Unruh Temperature | 87 | "10²⁰ m/s² gives only 1 K" | "… gives only about 0.4 K" | *T* = ħ*a*/(2π*ck*_B) = 0.405 K |
| 34 #58 Compton–Schwarzschild Crossover, rails I–II | 88 | *m* = *m*_P; "cross at exactly one mass — the Planck mass" | *m* = *m*_P/√2; "cross at exactly one mass, *m*_P/√2 — the Planck scale" | Solving ħ/(*mc*) = 2*Gm*/*c*² |
| 36 #57 Anomalous Magnetic Moment, rails I–II | 86 | "the muon shows a persistent tension with theory"; "The current tension … turns on hadronic contributions computed by lattice methods." | "the muon now matches the 2025 lattice-based prediction"; the tension is described as former, resolved with lattice values | Fermilab final result (June 2025); Muon *g*−2 Theory Initiative (2025) |
| 38 #53 Bremsstrahlung Radiation Loss, rail I | 82 | 1.7 × 10⁻³⁸ *Z*_eff *n*ₑ² √(*T*ₑ[keV]) W/m³ | √(*T*ₑ[eV]) | 1.69 × 10⁻³⁸ is the coefficient for *T*ₑ in eV (NRL Plasma Formulary) |
| 40 #51 Telescope Light Gathering Power | 78 | "The 39 m ELT gathers 250 times more light than an 8 m telescope." | "… about 24 times more light …" | (39/8)² = 23.8 |
| 42 #41 Water Autoionisation | 62 | "it falls to 6.14 at body temperature" | "it falls to about 6.8 at body temperature (and to 6.14 at 100 °C)" | p*K*_w ≈ 13.6 at 37 °C |
| 45 #28 Spherical Harmonic Gravity Field | 42 | "GRACE and GOCE map it to degree 2000" | "GRACE and GOCE resolve it to degree ≈ 300" | Satellite-only models reach degree ~300; degree 2190 needs combined models (EGM2008, EIGEN-6C4) |
| 45 #35 Induction Equation for the Dynamo, rail II | 54 | "Cowling's theorem is a statement that axisymmetric flows cannot produce such an eigenvalue" | "… that no axisymmetric field can be the eigenfunction of such an eigenvalue" | Cowling's theorem concerns axisymmetric fields; axisymmetric flows can be dynamos |
| 47 #36 GWP* for Short-Lived Gases, rail I | 54 | (4.53 Δ*E*_CH4 × 100 − 0.75 *E*_CH4) GWP₁₀₀ | (4.53 *E*_CH4(*t*) − 4.25 *E*_CH4(*t*−20)) GWP₁₀₀ | Smith et al. (2021), *npj Clim. Atmos. Sci.* 4, 19 |
| 51 #38 Kleiber's Law, origin | 59 | "Fractal resource distribution network theory (West, Brown, Enquist)" | "Kleiber's 1932 empirical fit; network theory (West, Brown, Enquist, 1997) is a later explanation" | Kleiber (1932); West, Brown and Enquist (1997) |
| 52 #23 Number of Rooted Trees | 36 | "2 × 10²⁰ trees for 20 taxa" | "8.2 × 10²¹ rooted trees for 20 taxa" | (2*n*−3)!! = 37!! = 8.2 × 10²¹; 2.2 × 10²⁰ is the unrooted count |
| 59 #51 A/B Test Sample Size | 77 | "needs hundreds of thousands per arm" | "needs about 3 million per arm" | *n* ≈ 2.98 × 10⁶ per arm (two-sided α = 0.05, 80% power) |
| 69 #28 Herfindahl–Hirschman Index | 43 | "Above 2500 is highly concentrated in US merger guidelines" | "Above 1800 is highly concentrated in the 2023 US merger guidelines" | 2023 Merger Guidelines, confirmed in force in 2025 |

Found while patching:

| Entry | Page | Previously | Now | Basis |
|---|---|---|---|---|
| 38 #53 Bremsstrahlung, rail II | 83 | *P*_br ∝ *Z*_eff² *n*ₑ² √*T*ₑ | *P*_br ∝ *Z*_eff *n*ₑ² √*T*ₑ | *Z*_eff = Σ *n*ᵢ*Z*ᵢ²/*n*ₑ already carries the square |
| 47 #36 GWP*, rail II | 55 | *E** = 4.53 × (Δ*E*/Δ*t*) × GWP₁₀₀ − 0.75 *E* × GWP₁₀₀ | *E** = (85 Δ*E*/Δ*t* + 0.28 *E*) × GWP₁₀₀, Δ*t* = 20 yr | The rail I metric in rate form (85/20 = 4.25) |
| 37 #30 Wiedemann–Franz Law | 46 | W K⁻² (the Ω printed blank) | W Ω K⁻² | Missing glyph |
| 50 #30 Membrane Capacitance | 46 | 1 F/cm² (the μ printed blank) | 1 μF/cm² | Missing glyph |
| 53 #49 Weber–Fechner Law in Signalling | 75 | NF-B (the κ printed blank) | NF-κB | Missing glyph |

Checked and left unchanged: 65 #44 Tuned Mass Damper Optimum. The formula is Den Hartog's optimum when ζ is measured against the damper's own natural frequency; the entry does not say so.

## 2. Part 0: claims narrowed to what is proved

File `00_Introduction_and_Apparatus.pdf`.

| Page | Passage | Change |
|---|---|---|
| 3 | Preface | "with a proof for every entry" (twice) → "by a six-step construction applied class by class", "in the same way" |
| 3 | Rail III description | "it verifies that switching the transform off returns rail II exactly" → "it returns rail II exactly only for class T4 and for small operators in class T1 (see Errata)" |
| 3 | Rail IV description | "lands back on rail II" → "reaches rail II up to *O*(ℓ²), and only where (P5) does" |
| 3 | The tower | "Theorem J proves T₈S⁽⁰⁾ = id" adds "for operators up to 3 × 3"; identity (0) now ends "= ℒ + *O*(ℓ²)"; "Every rail-IV image returns its own rail-II input" → "Only for such operators does a rail-IV image return its own rail-II input" |
| 4 | Status table | 3,893 / 530 / 178 / 111 / 74 (sum 4,786) → 3,988 / 308 / 266 / 127 / 116 (sum 4,805) |
| 4 | Below the table | "159 entries carry a rejection certificate under Lemma T14" → "all 116 carry a rejection certificate under Lemma T14 on rail III (so do 43 others; see Errata)" |
| 5 | Native fields | "… and are marked *already native* throughout" → "Only 05 marks every entry *already native*; eleven entries in ten other fields carry the same mark." |
| 10 | Composite retraction | adds "for operators up to 3 × 3"; (0) "= ℒ + *O*(ℓ²)"; "returns the rail-II equation it came from, up to *O*(ℓ²) (see Errata)" |
| 12 | Master law | item 7: "an admission rule (unspecified)"; "T₈S⁽⁰⁾ = id (8S Theorem J)" → "(8S Theorem J, for *A* up to 3 × 3)" |
| 13 | Composite retraction | "every calculus image returns its own input equation" → "a calculus image returns its input equation up to *O*(ℓ²)"; (0) "= ℒ + *O*(ℓ²)"; the closing sentence limited to operators up to 3 × 3 |
| 26 | Theorem J | "T₈S⁽⁰⁾[ℒ] = ℒ" → "… = ℒ when *A* is at most 3 × 3"; proof: "*A* itself when dim *A* ≤ 5 and the chosen base realisation of *A* otherwise" → "*A* itself when *A* is at most 3 × 3, and the leading 3 × 3 block of B(*A*) otherwise" (Π(0) keeps three coordinates) |
| 26 | Remark J′ | "Every per-entry proof closes with step (P5) … which verifies that the specific output equation returns the specific input equation at *t* = 0" → returns it "only for class T4 and for T1 operators up to 3 × 3 (see Errata). Elsewhere rail III extends the corpus rather than re-deriving it." |
| 26 | Theorem Θ-J(3) | "= ℒ for every input law ℒ of the corpus" → "= ℒ + *O*(ℓ²) when *A* is at most 3 × 3"; proof (3) adds "for *A* at most 3 × 3" |
| 27 | Lemma T1 | retraction "returning *y* = *Ax* nodewise by Theorem J" adds "when *A* is at most 3 × 3" |
| 27 | Lemma T2 | "degenerates to the ungated spectral statement about *A*" → "degenerates to a trivial spectrum (every eigenvalue is 0); *A* itself is not recovered" |
| 28 | Lemma T3 | "*G*₅ → *I* recovers the input form" → "*G*₅ → *I* gives the Euclidean code distance, not the input form *x*ᵀ*Ax*" |
| 31 | Lemma D11 | "since the objective is concave and the feasible set convex, the KKT conditions are also sufficient" → "if the objective is concave and the feasible set convex (neither is shown here), …" |
| 32 | Lemma T14 | Input clause adds "(116 entries; 43 others filed here are listed in the Errata)" |
| 33 | §5.1 | "carries a proof with exactly six steps" → "carries the same six steps, applied class by class"; (P5) "the input equation is recovered at *t* = 0" → "only for class T4 and for T1 operators up to 3 × 3"; (P6) adds "Score, ℳ₇, ℳ₈, Classify and the thresholds are not specified in this edition, so this step cannot be evaluated"; "… is a complete proof" → "These six steps have the form of a complete proof, but (P5) and (P6) hold only as stated above"; "the two classical results cited by name" (four were listed) → "the four" |
| 33 | §5.2 | the same narrowing for (Q5), (Q6) and the closing paragraph |
| 33 | §6.1 | "It recovers every input equation in the retraction limit (Theorem J)" → "It recovers inputs of size at most 3 × 3 in the retraction limit (Theorem J)" |
| 34 | §6.2 | "Beyond it the free energy has several minima" → "can have several minima" |

## 3. Part 0: other corrections

- **Theorem B** (p. 18): "for any *A*" → "for any *A* ≠ 0"; the strict inequality fails for *A* = 0.
- **Remark C′** (p. 18): adds that the 43 entries filed under Lemma T14 with another rail-II status are an exception to the stable-status claim.
- **Remark D′** (pp. 19–20): the claim that a MinHash sketch makes *d*_J "a genuine ℓ₂ metric on the sketch" is replaced by "a MinHash sketch does not supply [hypothesis (2)]: distances between sketches need not be ℓ₂-embeddable". Four sets with neighbouring sketch distance 0.5 give a matrix −½*JD*²*J* with eigenvalue −0.25.
- **Theorem G** (p. 22): "Full symmetry is necessary for (G2)" → "sufficient". A tensor symmetric only in its last two indices can still give a symmetric positive semidefinite Laplacian (eigenvalues 0, 1, 3).
- **Remark H′** (p. 24): "(C) fails exactly when the gate layer becomes bistable" → "fails whenever". With *N* = 2, *W*₁₂ = 1, *J*₂ = 3 and bias 5 the gate has one fixed point although (C) fails.
- **Remark Θ-H′** (p. 25): "ℱ loses convexity and acquires multiple minima" → "can lose … and acquire".
- **Numbering** (pp. 15–16, 26–27): the definitions of §2.2 (continuum limit, calculus transform, differential signature) were numbered 2.1–2.3, the same as §2.1; they are now 2.5–2.7, and the four references to them are updated.
- **Missing primes**: 31 primed labels (Theorem F′, Remarks A′, C′, D′, F′, G′, H′, I′, J′, D13′, T14′, D14′, Θ-A′, Θ-C′, Θ-G′, Θ-G″, Θ-G‴, Θ-H′ and references to them) printed a blank glyph, because the text font has no prime, and extracted as U+FFFF. They now display and extract correctly.
- **Errata and scope notes** page added at the end (p. 35), with an outline entry.

## 4. Consistency edits across the 80 field files

- **Retraction check marks.** Steps (P5) and (Q5) ended with "✓" in every entry. Only Lemma T4's retraction returns the input statement, so the mark was removed from the 4,359 entries of the other thirteen classes (8,718 marks) and kept in the 446 class-T4 entries.
- **Lemma T12.** Step (P3) of the 203 class-T12 entries cited "Theorem T12"; it now reads "Lemma T12", as (P2) and Part 0 do.
- **Repeated section headings.** Merging the four rails left each section heading repeated up to five times, mostly inside the last entry of the preceding section (before its rails II–IV and after its "Also in" line) and sometimes under a variant name ("Carbon Cycle" and "The Carbon Cycle"). The 1,152 repeated headings were removed, leaving the space they occupied, and each table of contents now lists its sections once, 400 in all, with the page of the heading that opens each section. The audit reported this for five files; it affected all 80.

## 5. Metadata

Every PDF now records the author, title, subject and a rights statement in both its document information and its XMP metadata.

## 6. Known issues not fixed in the PDFs

**Rails III and IV are a construction applied by class.** With entry numbers removed, rail-III proofs reduce to 7–18 distinct texts per class, and the 4,805 entries contain 36 distinct retraction steps. What each class lemma's own retraction returns:

| Class | Entries | The lemma's retraction returns |
|---|---|---|
| T1 linear map | 937 | B(*A*) at each node; the input only if *A* is at most 3 × 3 |
| T2 spectral | 1,001 | ℒ₈S → 0, so every eigenvalue → 0 |
| T3 quadratic form | 329 | the code distance with *G*₅ → *I*, not *x*ᵀ*Ax* |
| T4 projection | 446 | *P*₅ = *P*₄, the input's own projector (consistent) |
| T5 rank | 281 | "dim ker = *N* and no constraint" |
| T6 power law | 311 | *r* = *r*_max, a constant |
| T7 threshold | 144 | the threshold removed |
| T8 kernel | 202 | the bare mask *A*, not the input covariance |
| T9 metric | 328 | the bare code distance, not the input's *d*(*x*, *y*) |
| T10 Markov chain | 98 | *P̂* = *I*, the lazy chain that never moves |
| T11 optimisation | 302 | the unconstrained Score objective, not the input problem |
| T12 convolution | 203 | a scalar (the torus collapses to a point) |
| T13 nonlinear | 64 | both Jacobian blocks vanish |
| T14 obstruction | 159 | every entry admitted |

**Admission is unspecified.** Score, ℳ₇, ℳ₈, Classify, *R*, ε_ind and ε_gain are never defined, and no entry states its operator *A*ᵢ or vector *e*. Steps (P6) and (Q6) and the rejection certificates cannot be evaluated; the per-entry wording of those steps is unchanged.

**Class assignment.** All 302 class-T11 entries give the same reason ("an optimisation over a constrained set"). Roughly 90 are not optimisation statements, for example 01 #1 Cantor's theorem, 24 #2 Navier–Stokes, 28 #24 Faraday's law and 36 #5 the spin–statistics theorem. They have not been reclassified.

**Entries filed under Lemma T14 with another rail-II status (43).** Lemma T14's input is a statement with no faithful linear form; these entries record a different status:

| Entry | Title | Rail-II status |
|---|---|---|
| 01 #13 | Axiom Schema of Replacement | Structural analogue |
| 01 #14 | Axiom of Foundation | Structural analogue |
| 06 #28 | Hilbert Basis Theorem | Structural analogue; trivial in finite dimensions |
| 08 #4 | Closure, Interior, Boundary | Structural analogue |
| 08 #6 | Tychonoff’s Theorem | Structural analogue |
| 08 #18 | Higher Homotopy Groups | Structural analogue rationally; torsion has no linear form |
| 09 #48 | Class Number Formula | Structural analogue |
| 09 #54 | Modularity Theorem | Structural analogue |
| 14 #47 | Glivenko–Cantelli Theorem | Structural analogue |
| 15 #31 | Quasi-Monte Carlo Error (Koksma–Hlawka) | Structural analogue |
| 18 #29 | EOQ Total Cost | Structural analogue |
| 18 #33 | Base Stock Policy | Structural analogue |
| 18 #50 | Weibull Hazard | Structural analogue |
| 20 #22 | Hotelling Location Equilibrium | Structural analogue |
| 20 #40 | First-Price Auction Equilibrium Bid | Structural analogue |
| 23 #18 | Kozeny–Carman Permeability | Structural analogue |
| 26 #1 | Zeroth Law | Structural analogue |
| 26 #7 | Third Law | Structural analogue |
| 27 #58 | Jarzynski Equality | Structural analogue |
| 27 #59 | Crooks Fluctuation Theorem | Structural analogue |
| 38 #55 | Bohm Diffusion Coeﬀicient | Structural analogue |
| 40 #17 | Colour–Temperature Relation | Structural analogue |
| 47 #44 | Marine Ice Sheet Instability | Linearised (the instability criterion); no faithful linear form for the retreat itself |
| 47 #45 | Sea Ice Albedo Transition | Linearised at the threshold; no faithful linear form for the transition |
| 47 #54 | Representative Concentration Pathways | Structural analogue |
| 47 #58 | Tipping Point (Fold Bifurcation) | Linearised at the point; no faithful linear form beyond it |
| 58 #5 | Comparison Sort Lower Bound | Structural analogue |
| 58 #19 | Complexity Class P | Structural analogue |
| 58 #20 | Complexity Class NP | Structural analogue |
| 58 #21 | Polynomial-Time Reduction | Structural analogue |
| 61 #8 | Minimax Value | Structural analogue |
| 61 #19 | First-Order Unification | Structural analogue |
| 61 #20 | Description Logic Subsumption | Structural analogue |
| 62 #27 | Configuration Space | Structural analogue |
| 69 #26 | Bertrand Price Competition | Structural analogue |
| 69 #57 | Adverse Selection (Lemons) | Structural analogue |
| 76 #24 | Quadtree and R-Tree Indexing | Structural analogue |
| 78 #48 | Lempel–Ziv Complexity | Structural analogue |
| 79 #16 | Tsallis Entropy | Structural analogue |
| 79 #27 | Lempel–Ziv Universal Coding | Structural analogue |
| 80 #45 | PACELC Extension | Structural analogue |
| 80 #49 | Paxos and Raft Round Complexity | Structural analogue |
| 80 #54 | Two-Phase Commit Blocking | Structural analogue |

**Titles that occur in two fields (66).** The same equation is often entered twice without a cross-reference. Some pairs share only a name; Liouville's theorem in 03 (complex analysis) and 12 (Hamiltonian dynamics) are different results.

| Title | Entries |
|---|---|
| Z-Transform | 02 #8, 63 #6 |
| Discrete Fourier Transform | 02 #18, 64 #39 |
| Renormalisation Group Flow | 02 #34, 78 #58 |
| Liouville’s Theorem | 03 #53, 12 #45 |
| Product Rule | 04 #2, 10 #1 |
| Polar Decomposition | 05 #47, 22 #3 |
| Graph Laplacian | 05 #60, 77 #45 |
| Geodesic Equation | 07 #34, 33 #30 |
| Reaction–Diffusion System | 11 #40, 78 #38 |
| Routh–Hurwitz Criterion | 12 #8, 63 #12 |
| Master Stability Function | 12 #59, 77 #57 |
| Characteristic Function | 13 #20, 20 #45 |
| Itô’s Lemma | 13 #57, 71 #24 |
| Fisher Information | 14 #9, 79 #17 |
| Bonferroni Correction | 14 #35, 56 #54 |
| Cox Proportional Hazards Model | 14 #60, 56 #23 |
| Finite Element Weak Form | 16 #56, 67 #35 |
| Lagrangian | 17 #14, 21 #45 |
| Bellman Optimality Equation | 18 #37, 61 #35 |
| Expected Utility | 19 #1, 69 #13 |
| Drift Diffusion Model | 19 #52, 73 #50 |
| Replicator Dynamics | 20 #54, 78 #35 |
| Hamilton’s Rule | 20 #56, 54 #60 |
| Price Equation | 20 #57, 54 #59 |
| Parallel Axis Theorem | 21 #24, 67 #17 |
| Escape Velocity | 21 #39, 66 #30 |
| Vis-Viva Equation | 21 #41, 66 #28 |
| Static Equilibrium | 22 #19, 67 #1 |
| Richards Equation | 23 #19, 49 #15 |
| Magnetic Reynolds Number | 23 #40, 38 #27 |
| Debye Length | 23 #49, 38 #2 |
| Rossby Number | 24 #24, 46 #33 |
| Scaling Relations | 27 #37, 78 #57 |
| Percolation Threshold | 27 #45, 77 #53 |
| Landauer’s Principle | 27 #60, 79 #59 |
| Plane Wave Solution | 28 #30, 31 #5 |
| Skin Depth | 28 #50, 64 #56 |
| Plasma Frequency | 28 #54, 38 #1 |
| Magnification | 29 #7, 34 #47 |
| Stevens’ Power Law | 31 #23, 73 #3 |
| Density Matrix | 32 #15, 43 #12 |
| Slater Determinant | 32 #53, 43 #6 |
| Equivalence Principle | 33 #28, 72 #22 |
| Branching Ratio | 36 #54, 78 #25 |
| Gutenberg–Richter Law | 45 #8, 78 #21 |
| Critical Slowing Down | 47 #59, 78 #45 |
| Exponential Growth | 51 #1, 75 #4 |
| Breeder’s Equation | 51 #50, 54 #47 |
| Turing Instability Condition | 51 #56, 78 #39 |
| Direct Standardisation | 55 #14, 75 #8 |
| Survival Function | 56 #16, 72 #1 |
| Cache-Oblivious Complexity | 58 #18, 80 #32 |
| Kolmogorov Complexity | 58 #27, 78 #47 |
| Amdahl’s Law | 58 #52, 80 #3 |
| Average Memory Access Time | 58 #54, 80 #25 |
| Roofline Model | 58 #59, 80 #10 |
| Kullback–Leibler Divergence | 59 #17, 79 #8 |
| Jensen–Shannon Divergence | 59 #18, 79 #9 |
| Spectral Clustering | 59 #38, 77 #48 |
| Normalised Mutual Information | 59 #40, 77 #41 |
| Gini Coeﬀicient | 69 #39, 74 #14 |
| Eigenvector Centrality | 74 #3, 77 #19 |
| Exponential Random Graph Model | 74 #8, 77 #33 |
| Gravity Model of Migration | 74 #29, 75 #41 |
| Voter Model | 74 #52, 78 #36 |
| Bounded Confidence Opinion Dynamics | 74 #53, 78 #37 |

**Other.**
- 01 #10 still carries the status "Exact linear analogue", although the corrected rail II shows that the analogue is degenerate.
- 65 #44 does not say against which frequency ζ is measured (see section 1).
- Entries not named in this file were not checked individually. The audit's sampling suggests roughly 100–150 further errors in rails I–II.
- The six figures are raster images with some labelling glitches, such as duplicated vertex coordinates in Concept 1.
- Removing the repeated headings left vertical gaps where they stood.

## 7. How the PDFs were edited

- Content streams were edited with pikepdf. Replacement lines were typeset with XeLaTeX in the volume's own setup (fontspec, unicode-math, Latin Modern, microtype protrusion, 2.2 cm margins on US letter), which reproduces unchanged lines of the original to within 0.01 pt. Each replacement is drawn as a Form XObject at the original coordinates; the original glyphs were replaced by displacements of the same width, not painted over.
- Each changed page was rendered and inspected. Text extracted from every file was compared page by page with the previous version, and every difference matched an intended edit. All files pass `qpdf --check`, and page counts are unchanged apart from the errata page.
