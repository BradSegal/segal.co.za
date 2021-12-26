---
title: Evaluating the Clinical Realism of Synthetic Chest X-Rays Generated Using
  Progressively Growing GANs
publication_types:
  - "2"
authors: []
doi: https://doi.org/10.1007/s42979-021-00720-7
publication: SpringerNature Computer Science
publication_short: SN Computer Science
abstract: >-
  Chest X-rays are a vital diagnostic tool in the workup of many patients.
  Similar to most medical imaging modalities, they are profoundly multi-modal
  and are capable of visualising a variety of combinations of conditions. There
  is an ever pressing need for greater quantities of labelled images to drive
  forward the development of diagnostic tools; however, this is in direct

  opposition to concerns regarding patient confdentiality which constrains access through permission requests and ethics approvals. Previous work has sought to address these concerns by creating class-specifc generative adversarial networks (GANs) that synthesise images to augment training data. These approaches cannot be scaled as they introduce computational trade ofs between model size and class number which places fixed limits on the quality that such generates can achieve. We

  address this concern by introducing latent class optimisation which enables efcient, multi-modal sampling from a GAN and with which we synthesise a large archive of labelled generates. We apply a Progressive Growing GAN (PGGAN) to the task of unsupervised X-ray synthesis and have radiologists evaluate the clinical realism of the resultant samples. We provide an in depth review of the properties of varying pathologies seen on generates as well as an overview of the extent of disease diversity captured by the model. We validate the application of the Fréchet Inception Distance (FID) to measure the quality of X-ray generates and fnd that they are similar to other high-resolution tasks. We quantify X-ray clinical realism

  by asking radiologists to distinguish between real and fake scans and fnd that generates are more likely to be classed as real than by chance, but there is still progress required to achieve true realism. We confrm these fndings by evaluating synthetic classifcation model performance on real scans. We conclude by discussing the limitations of PGGAN generates and how to achieve controllable, realistic generates going forward. We release our source code, model weights, and an archive of labelled generates.
draft: false
featured: false
categories: []
image:
  filename: segal2021_article_evaluatingtheclinicalrealismof.jpg
  focal_point: Smart
  preview_only: false
date: 2021-12-26T21:31:07.161Z
---
