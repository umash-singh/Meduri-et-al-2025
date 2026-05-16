# Deep Analysis of FANTOM CAGE Data Reveals Hierarchical Patterns of TSS
# Co-deployment Hubs and Their Disruption in Cancers

> Meduri Ruthwick, Aditi Lakshmi Satish, Umashankar Singh*
>
> HoMeCell Lab, Department of Biological Sciences and Engineering,
> Indian Institute of Technology Gandhinagar, Gujarat 382055, India.
>
> \* Correspondence: [usingh@iitgn.ac.in](mailto:usingh@iitgn.ac.in)

---

## Abstract

Selective deployment of multiple transcription start sites (TSSs) is a major
regulatory feature of human transcriptomes. FANTOM CAGE data exhibit a
near-universal TSS deployment parsimony that is disrupted in cancers. We have
previously shown that TSS deployment is sensitive to gene function, futile
upstream transcription, and cellular biosynthetic states.

Here, we propose and test the possibility that certain TSSs act as epromoter-like
co-varying hubs of transcriptional activity for multiple other promoters. Using
deep analysis of CAGE data implemented through neural networks, we demonstrate
that non-cancers implement transcriptional co-deployments through cores of
epromoter-like TSSs that are generally proximal to their start codons and exhibit
enhancer-like TFBS profiles. Comparison with cancer CAGE data reveals that this
concentrated epromoter core is disrupted in cancers, with multiple distal TSSs
replacing the proximal TSS cores. We further show that core TSSs are enriched for
YY1 and CTCF binding sites and are associated with transcription factor-coding
genes. Together, our findings establish that TSS co-deployment covariance is
sensitive to transcriptional resource cost, and that parsimonic co-deployment
depends on proximal TSSs in non-cancers — a mechanism grossly disrupted in cancers.

---

## Data Availability

| Resource | Availability |
|---|---|
| FANTOM CAGE data | Publicly available via [FANTOM5](https://fantom.gsc.riken.jp/5/) |
| CAGE scaled scores & derivatives | Satish et al., 2025 (unpublished; DOI: [10.64898/2025.12.22.696121](https://doi.org/10.64898/2025.12.22.696121)) |
| Autoencoder weights | Available upon request to the corresponding author |
| Latent vectors | Available upon request to the corresponding author |
| Exclusive TSS pair sets (N•N, N•C, C•C, C•N) | Supplementary Tables S5–S8 |

> **Note:** CURATED_CAGE_PEAKS, NORMAL_CAGE_DERIVATIVES, and
> CANCER_CAGE_DERIVATIVES are not distributed in this repository.
> Pre-trained model weights and latent vectors will be shared upon
> reasonable request.

---

## Keywords

`CAGE` `Transcription Start Site` `Transcriptional Covariance` `CTCF` `YY1` `Cancer`
`Denoising Autoencoder` `FANTOM5` `ePromoters` `CoPTrS`

---

## License

Code in this repository is released under the [MIT License](LICENSE).
Data and notebooks are released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

---

## Contact

**Dr. Umashankar Singh** — [usingh@iitgn.ac.in](mailto:usingh@iitgn.ac.in)
HoMeCell Lab, IIT Gandhinagar
