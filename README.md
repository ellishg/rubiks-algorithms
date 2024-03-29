# Rubik's Cube Algorithms

* [Algorithms](#Algorithms)
  * [2 Look OLL](#2-Look-OLL)
  * [2 Look PLL](#2-Look-PLL)
  * [Blindfold](#Blindfold)
  * [Pocket Cube](#Pocket-Cube-2x2)
  * [Rubik's Cube Revenge](#Rubiks-Cube-Revenge-4x4)
* [Notation](#Notation)

## Algorithms

### 2 Look OLL
Orient Last Layer

#### Edge Orientation
| Name | Image |  Algorithm |
|:----:|:-----:|:----------:|
| Opposite | ![](img/oll/opposite.png) | __F (R U R' U') F'__ |
| Adjacent | ![](img/oll/adjacent.png) | __f (R U R' U') f'__ |
| None | ![](img/oll/none.png) | __F (R U R' U') F' f (R U R' U') f'__ |

#### Corner Orientation
| Name | Image |  Algorithm |
|:----:|:-----:|:----------:|
| Sune | ![](img/oll/sune.png) | __R U R' U R U2 R'__ |
| Anti-Sune | ![](img/oll/anti_sune.png) | __R' U' R U' R' U2 R__ |
| Car :car: | ![](img/oll/car.png) | __F (R U R' U')*3 F'__ |
| Blinker :rotating_light: | ![](img/oll/blinker.png) | __R U2 R2 U' R2 U' R2 U2 R__ |
| Headlights | ![](img/oll/headlights.png) | __R2 D R' U2 R D' R' U2 R'__ |
| Chameleon :frog: | ![](img/oll/chameleon.png) | __r U R' U' r' F R F'__ |
| Bowtie :bowtie: | ![](img/oll/bowtie.png) | __F' r U R' U' r' F R__ |

### 2 Look PLL
Permute Last Layer

#### Corner Permutation
| Name | Image | Algorithm |
|:----:|:-----:|:---------:|
| CW Corner 3-Cycle | ![](img/pll/corner_3cycle.png) | __x R' U R' D2 R U' R' D2 R2__ |
| E-Perm            | ![](img/pll/eperm.png) | __x' R U' R' D R U R' u2 R' U R D R' U' R__ |

#### Edge Permutation
| Name | Image | Algorithm |
|:----:|:-----:|:---------:|
| CW Edge 3-Cycle | ![](img/pll/edge_cw_3cycle.png) | __R2 U R U R' U' R' U' R' U R'__ |
| CCW Edge 3-Cycle | ![](img/pll/edge_ccw_3cycle.png) | __R U' R U R U R U' R' U' R2__ |
| H-Perm |![](img/pll/hperm.png) | __M2 U M2 U2 M2 U M2__ |
| Z-Perm | ![](img/pll/zperm.png) | __M2 U M2 U M' U2 M2 U2 M' U2__ |

### Blindfold
http://cubefreak.net/bld/3op_guide.php

| Name | Image | Algorithm | Inverse |
|:----:|:-----:|:---------:|:-------:|
| Edge Orientation | ![](img/blind/edge.png) | [__M' U M' U M' U2 M U M U M U2__](https://alg.cubing.net/?type=alg&alg=M-UM-UM-U2MUMUMU2&view=playback) |
| Corner Orientation Pair | ![](img/blind/corner1.png) ![](img/blind/corner2.png) | __R' D' R D R' D' R__ | __R' D R D' R' D R__ |
| Corner Orientation Triple | ![](img/blind/corner3.png) | __(R' D' R D)*2__ | __(R' D R D')*2__ |
| Corner 3-Cycle | ![](img/pll/corner_3cycle.png) | __x R' U R' D2 R U' R' D2 R2__ |
| CCW Corner 3-Cycle | ![](img/pll/corner_ccw_3cycle.png) | __R B' R F2 R' B R F2 R2__ |
| Edge 3-Cycle | ![](img/pll/edge_cw_3cycle.png) | __R2 U R U R' U' R' U' R' U R'__ | __R U' R U R U R U' R' U' R2__ |

### Pocket Cube (2x2)
http://www.cubewhiz.com/ortegapbl.php

| Name | Image | Algorithm | Inverse |
|:----:|:-----:|:---------:|:-------:|
| Corner T-Perm | ![](img/pocket/t_perm.png) | [__(R U R' U') (R' F) (R2 U') (R' U' R U) (R' F')__](https://alg.cubing.net/?puzzle=2x2x2&alg=(R_U_R-_U-)_(R-_F)_(R2_U-)_(R-_U-_R_U)_(R-_F-)&setup=F_R_U-_R-_U_R_U_R2_F-_R_U_R_U-_R-&view=playback) |


### Rubik's Cube Revenge (4x4)
http://www.rubiksplace.com/cubes/4x4/

| Name | Image | Algorithm |
|:----:|:-----:|:---------:|
| Edge Merge | ![](img/revenge/edge_merge.png) | [__d R U R' d'__](https://alg.cubing.net/?type=alg&puzzle=4x4x4&alg=dRUR-d-&setup=y&view=playback) |
| Anti-Edge Merge | ![](img/revenge/anti_edge_merge.png) | [__d' L' U' L d__](https://alg.cubing.net/?type=alg&puzzle=4x4x4&alg=d-L-U-Ld&setup=y&view=playback) |
| Double Edge Merge | ![](img/revenge/double_edge_merge.png) | [__d R F' U R' F d'__](https://alg.cubing.net/?type=alg&puzzle=4x4x4&alg=dRF-UR-Fd-&setup=y&view=playback) |
| OLL Parity | ![](img/revenge/oll.png) | [__r U2 x r U2 r U2 r' U2 l U2 r' U2 r U2 r' U2 r'__](https://alg.cubing.net/?puzzle=4x4x4&alg=r_U2_x_r_U2_r_U2_r-_U2_l_U2_r-_U2_r_U2_r-_U2_r-&type=alg&setup=xx&view=playback) |
| PLL Parity | ![](img/revenge/pll.png) | [__2R2 U2 2R2 u2 2R2 2U2__](https://alg.cubing.net/?puzzle=4x4x4&alg=2R2_U2_2R2_u2_2R2_2U2&type=alg&setup=xx&view=playback) |

## Notation
http://www.rubiksplace.com/move-notations/

### Faces
* __F__ :point_right: Front
* __R__ :point_right: Right
* __B__ :point_right: Back
* __L__ :point_right: Left
* __U__ :point_right: Top (Up)
* __D__ :point_right: Bottom (Down)

### Middle Layers
* __M__ :point_right: Slice between __L__ & __R__ (Middle)
* __E__ :point_right: Slice between __U__ & __D__ (Equator)
* __S__ :point_right: Slice between __F__ & __B__ (Side)

### Cube Rotations
* __x__ :point_right: Rotate about __R__ face
* __y__ :point_right: Rotate about __U__ face
* __z__ :point_right: Rotate about __F__ face

A single letter implies a __clockwise__ turn of 90 degrees when viewed directly at the face. If it's followed by a prime, then it implies a __counter-clockwise__ turn. It it's followed by a __2__, then it implies a __half__ turn of 180 degrees.

A lowercase letter means you need to turn two layers of the corresponding face.

With the Rubik's Cube Revenge, a __2__ in front of a letter means you only turn the inner layer of that face.

### Examples
* __F2__ :point_right: Turn front face twice
* __D' R__ :point_right: Turn bottom face counter-clockwise, then the right face clockwise
* __x M R2__ :point_right: Turn cube so top face is towards you, then rotate the middle slice clockwise and the right face twice
