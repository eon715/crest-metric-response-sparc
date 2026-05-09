# CREST Coherence-Weighted Metric Response: SPARC Benchmark

This repository contains the paper, scripts, and validation archive for a galaxy-held-out SPARC benchmark of the CREST metric-response projector.

## Main paper

The main paper is:

`paper/crest_coherence_weighted_metric_response.pdf`

## Main claim

A framework-constrained CREST response projector improves galaxy-held-out SPARC prediction over:

- a fitted RAR/MOND-like backbone,
- radius-plus-baryonic-acceleration nuisance controls,
- and no-retuning NFW/Burkert halo-prior predictors.

The improvement collapses under matched null actions that destroy invariant-sector alignment while preserving nuisance structure.

## Claim boundary

This is a no-retuning prediction-efficiency result.

It does **not** claim that CREST disproves dark matter, closes lensing/cosmology, or beats fully tuned per-galaxy halo fits. Flexible per-galaxy halo fits remain stronger raw curve-fitting ceilings.

## Repository contents

- `paper/` — compiled CREST paper PDF.
- `archive/` — source/results archive exported from the benchmark run.
- `README.md` — repository overview.

## Core theoretical ingredients

CREST is treated here as a scalar-tensor metric-response framework. The response sector is defined by the residual curvature tensor:

```math
E^\chi_{\mu\nu} = G_{\mu\nu} - 8\pi G T^{\rm bar}_{\mu\nu}
and becomes predictive only through a constrained response law:
Math
E^\chi_{\mu\nu}
=
A_{\mu\nu}[\chi,\nabla\chi,\nabla\nabla\chi,\eta,I,F,\Phi_{\rm irr},R_\chi,S_\chi,g_{\mu\nu}].
The coherence-weighted irreversibility law separates integrated irreversible load F from instantaneous irreversible flux Phi_irr:
Math
\Theta_\chi =
\frac{\Phi_{\rm irr}}{\chi \eta^2 I + \epsilon}.
Validation layers
The paper reports:
v5b framework-shrinkage projector,
v7 no-retuning halo-prior comparison,
v9 post-fit null-collapse test,
v10 lightweight full-refit null confirmation.
Data
The benchmark is based on public SPARC rotation-curve mass models and galaxy metadata.
SPARC source page:
https://astroweb.cwru.edu/SPARC/⁠�
Citation
Citation information and DOI will be added after the first Zenodo release.
