---
title: "Hybrid Conjugate Gradient (HCG) Method in Polymer SCFT"
date: 2026-02-27
permalink: /posts/2026/02/hybrid-conjugate-gradient-method-polymer-scft/
categories:
  - polymer-field-theory
tags:
  - scft
  - numerical-methods
  - optimization
  - conjugate-gradient
---

{% assign pdf_path = '/files/Research_Block_Posts/Polymer_Field_Theory/Hybrid_Conjugate_Gradient__HCG__Method_in_polymer_SCFT.pdf' | relative_url %}

## Summary

This note documents the Hybrid Conjugate Gradient (HCG) strategy for solving polymer SCFT equations.

The method combines robust gradient-based updates with conjugate-direction acceleration to improve convergence behavior in nonlinear self-consistent iterations.

It is useful for reducing iteration cost and stabilizing difficult SCFT solves in high-dimensional parameter settings.

## Full Derivation (PDF)

The full method note is provided below.

- [Download the full derivation (PDF)]({{ pdf_path }})

<iframe src="{{ pdf_path }}" width="100%" height="900" style="border: 1px solid #ddd; border-radius: 6px;" title="Hybrid Conjugate Gradient Method in Polymer SCFT PDF"></iframe>

If the embedded viewer does not load in your browser, use the download link above.
