---
event_type: ReleaseEvent
avatar: "https://avatars.githubusercontent.com/u/5080549?"
user: chrischoy
date: 2021-02-06
repo_name: NVIDIA/MinkowskiEngine
html_url: https://github.com/NVIDIA/MinkowskiEngine/releases/tag/v0.5.1
repo_url: https://github.com/NVIDIA/MinkowskiEngine
---

<a href='https://github.com/chrischoy' target='_blank'>chrischoy</a> released <a href='https://github.com/NVIDIA/MinkowskiEngine/releases/tag/v0.5.1' target='_blank'>v0.5.1</a>.

<small>- v0.5 documentation updates
- Nonlinear functionals and modules
- Warning when using cuda without ME cuda support
- diagnostics test
- TensorField slice
    - Cache the unique map and inverse map pair in the coordinate manager
    - generate inverse_mapping on the fly
- CoordinateManager
    - `field_to_sparse_insert_and_map`
    - `exists_field_to_sparse`
    - `get_field_to_sparse_map`
    - fix `kernel_map` with empty coordinate maps
- CoordiateFieldMap
    - `quantize_coordinates`
- TensorField binary ops fix
- MinkowskiSyncBatchNorm
    - Support tfield
    - conver sync batchnorm updates
- TensorField to sparse with coordinate map key
- Sparse matrix multiplication
    - force contiguous matrix
- Fix AveragePooling cudaErrorMisalignedAddress error for CUDA 10 (#246)

</small><a href='https://github.com/NVIDIA/MinkowskiEngine/releases/tag/v0.5.1' target='_blank'>View Comment</a>