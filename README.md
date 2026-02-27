PolyTrim is an open-source scripted module implemented within the 3D Slicer platform (v5.x) for the systematic batch decimation of polygonal surface meshes. The module enables controlled reduction of mesh complexity to a predefined target polygon count while preserving surface topology. It is specifically designed to facilitate methodological standardisation in large-scale morphological datasets where polygon density may introduce analytical bias.

In quantitative surface analyses, variations in mesh resolution can influence curvature-based metrics, surface complexity indices, and geometric morphometric outputs. PolyTrim addresses this issue by allowing reproducible mesh normalisation across entire datasets, supporting workflows in:

Dental (and non-dental) topographic analysis

Functional morphology

Paleoanthropological comparative studies

Computational anatomy

Surface-based machine learning frameworks

The module operates on PLY and OBJ mesh formats and performs directory-level batch processing, automatically generating reduced meshes within a structured output subdirectory. By integrating directly into 3D Slicer’s ecosystem, PolyTrim ensures compatibility with established segmentation, transformation, and surface analysis pipelines.

PolyTrim contributes to reproducible computational morphology by formalising mesh standardisation as a transparent and automatable preprocessing step.
