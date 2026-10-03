# PV panel segmentation demo

Interactive inspection of precomputed RGB and thermal module-segmentation results.
Seven examples include a smaller-tile stress run. Open the GitHub Pages site to
zoom, select panels, compare clean outlines with raw/reference masks, and download results.

The research/ comparison adds shared-shape, table-grid and image-refined geometry,
strict development metrics and an unlabeled external orthomosaic. It preserves
failed variants and fallback status. These experimental results do not establish
production reliability or exhaustive module detection.

Sample imagery, annotations and model provenance:
[CVUT PVsegmentation](https://imr.ciirc.cvut.cz/Datasets/PVsegmentation).
Third-party materials retain their own rights; this repository does not grant a new license.
External orthomosaic: lakshmi, *solar-panels-*, 23 February 2021, OpenAerialMap,
CC BY 4.0. A cropped JPEG preview and experimental outlines are derived from the
original; source and license links are included in the comparison.

These are development examples with unknown training overlap, not independent
accuracy validation. No live inference, image uploads or thermal diagnosis is provided.
