* `axis_buffer` can now be a tuple, allowing separate axis buffers for each dimension. Additionally, if one of the dimensions has zero variance, then the axis buffer will still be able to increase the size of that dimension. `curvature_scalar` can now be a matrix, so that each edge can have its own curvature. ([#96])