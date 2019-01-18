## Examples

| File name                                                                                                                                        | $M^{-1}_1$ | $M^{-1}_2$  | inexact CS  | comments                                           |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | ----------- | ----------- | -------------------------------------------------- |
| [diffusion-3d-minimal-direct.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/diffusion-3d-minimal-direct.edp)       |          |             |             | direct solver <br> MUMPS                           |
| [diffusion-3d-minimal-ddm.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/diffusion-3d-minimal-ddm.edp)             | RAS        | GenEO       |             |                                                    |
| [diffusion-3d-simple.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/diffusion-3d-simple.edp)                       | RAS        | GenEO       |             | comparison with <br> direct solver                 |
| [diffusion-2d-thirdlevelgeneo.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/diffusion-2d-thirdlevelgeneo.edp)     | RAS        | GenEO       | RAS + GenEO |                                                    |
| [elasticity-3d-simple.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/elasticity-3d-simple.edp)                     | RAS        | GenEO       |             |                                                    |
| [elasticity-3d-thirdlevelgeneo.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/elasticity-3d-thirdlevelgeneo.edp)   | RAS        | GenEO       | RAS + GenEO |                                                    |
| [Helmholtz-2d-simple.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/Helmholtz-2d-simple.edp)                       | ORAS       | Coarse Mesh |             |                                                    |
| [Helmholtz-2d-marmousi.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/Helmholtz-2d-marmousi.edp)                   | ORAS       | Coarse Mesh |             |                                                    |
| [Helmholtz-3d-simple.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/Helmholtz-3d-simple.edp)                       | ORAS       | Coarse Mesh |             |                                                    |
| [Helmholtz-3d-overthrust.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/Helmholtz-3d-overthrust.edp)               | ORAS       |             |             |                                                    |
| [Helmholtz-2d-HPDDM-BGMRES.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/Helmholtz-2d-HPDDM-BGMRES.edp)           | ORAS       |             |             | multi-rhs <br> Block GMRES <br> with HPDDM         |
| [Navier-2d-marmousi2.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/Navier-2d-marmousi2.edp)                       | ORAS       | Coarse Mesh |             |                                                    |
| [Maxwell-3d-simple.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/Maxwell-3d-simple.edp)                           | ORAS       | Coarse Mesh |             |                                                    |
| [Maxwell_Cobracavity.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/Maxwell_Cobracavity.edp)                       | ORAS       | Coarse Mesh | ORAS        |                                                    |
| [natural_convection.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/natural_convection.edp)                         | ORAS       | Coarse Mesh |             | nonlinear                                          |
| [natural_convection_3D_obstacle.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/natural_convection_3D_obstacle.edp) | ORAS       | Coarse Mesh |             | nonlinear                                          |
| [Richards-2d.edp](https://github.com/FreeFem/FreeFem-sources/tree/v4/examples%2B%2B-ffddm/Richards-2d.edp)                                       | RAS        |             |             | nonlinear <br> time dependent <br> mesh adaptation |