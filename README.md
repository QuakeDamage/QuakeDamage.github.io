# Venezuela Earthquake 2026 — AI Post-Earthquake Building-Damage Assessment

An interactive web dashboard presenting AI-generated, per-building damage predictions for the
2026 Venezuela earthquake, with an optional community-validation layer where anyone can review
and correct predictions against before/after satellite imagery.

**Live map:** per-building damage segmentation (Intact / Damaged / Destroyed) over ~352 km²
and 478,467 buildings · before/after imagery inspection · crowd validation.

> **Disclaimer** — Results are AI-generated from satellite imagery and provided for informational
> purposes only. They may contain errors and must not be treated as official damage assessments,
> safety evaluations, or emergency guidance. Independently verify all results before use.

## Authors

**Deepank Singh** · **Vedhus Hoskere**
Structures and Artificial Intelligence Lab ([SAIL](https://sail.cive.uh.edu)),
Department of Civil & Environmental Engineering, University of Houston.

Contact: [dksingh@uh.edu](mailto:dksingh@uh.edu) · [vhoskere@uh.edu](mailto:vhoskere@uh.edu)

## Related work

- **Multiclass Post-Earthquake Building Assessment Integrating High-Resolution Optical and SAR
  Satellite Imagery, Ground Motion, and Soil Data with Transformers.** Singh, Hoskere, Milillo.
  *Earthquake Spectra* (2025).
  [Journal](https://journals.sagepub.com/doi/10.1177/87552930251377778) ·
  [arXiv:2412.04664](https://arxiv.org/abs/2412.04664)
- **Post-Disaster Damage Assessment Using Ultra-High-Resolution Aerial Imagery with
  Semi-Supervised Transformers.** Singh, Hoskere. *Sensors* 23(19):8235 (2023).
  [MDPI](https://www.mdpi.com/1424-8220/23/19/8235)

## Data & attribution

Basemaps and imagery © their respective providers: OpenStreetMap contributors, CARTO, Esri /
Maxar / Earthstar Geographics, Maxar/Vantor open data, and building footprints from
[Overture Maps](https://overturemaps.org). Community-validation backend: Supabase.

## License

Code released under the [MIT License](LICENSE). Model outputs, imagery, and third-party data
remain subject to their respective licenses and the disclaimer above.
