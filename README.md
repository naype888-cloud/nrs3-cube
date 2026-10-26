# NRS³ · Cube: the open cube of three path graphs, and everything Physlib merged about it

NRS is the Robertson–Schrödinger inequality for the pair `(T_d, P_d)` on a path graph of `d`
sites. **NRS³** is its extension to the Cartesian product of three path graphs, the open cube
`Nx × Ny × Nz`, with one such pair per axis. The axes commute; each axis carries its own
`C_Nava(N)`, equal to `1` exactly for `N = 2, 3` and above `1` from `N = 4`; the volumetric
quantum `δ(Nx) δ(Ny) δ(Nz)` is the product of the three excesses `δ = C_Nava − 1`.
This repository is the index of that cube: the merged pull requests, the Lean names, the pages
and the figures, in one place. It adds no new theorem.

**[▶ Try it: set Nx, Ny, Nz and read C_Nava, δ, the NRS angle and the volumetric quantum of the cube](https://naype888-cloud.github.io/nrs3-cube/)**

## Merged in Physlib (`PhyslibAlpha/CondensedMatter/TightBindingChain/Cube/`)

| PR | Merged | What | Lean |
|---|---|---|---|
| [#1699](https://github.com/leanprover-community/physlib/pull/1699) | 10-02 | operators on one coordinate of a product commute across coordinates | `FiniteTarget/Product` |
| [#1717](https://github.com/leanprover-community/physlib/pull/1717) | 10-02 | product states: one-coordinate statistics are the factor's | `FiniteTarget/ProductState` |
| [#1725](https://github.com/leanprover-community/physlib/pull/1725) | 10-05 | the open cube; axes commute; `C_Nava` per axis | `nava_robertson_schrodinger_cube` |
| [#1739](https://github.com/leanprover-community/physlib/pull/1739) | 10-07 | Mandelstam–Tamm and Cramér–Rao per axis; ratio `1/C_Nava²` | `Cube/MandelstamTamm` |
| [#1730](https://github.com/leanprover-community/physlib/pull/1730) | 10-06 | Robertson 1934 for several observables | `robertson_det` |
| [#1742](https://github.com/leanprover-community/physlib/pull/1742) | 10-08 | det\|NRS³: six observables, `Ω` block diagonal; strict from `4 × 4 × 4` | `robertson_det_cube`, `robertson_det_maxCurrentCubeState_strict` |
| [#1756](https://github.com/leanprover-community/physlib/pull/1756) | 10-12 | NRS angle `θ = arccos(1/C_Nava)` and the volumetric quantum | `Cube/VolumetricQuantum` |
| [#1774](https://github.com/leanprover-community/physlib/pull/1774) | 10-14 | equality case of Robertson for several observables | |
| [#1745](https://github.com/leanprover-community/physlib/pull/1745), [#1746](https://github.com/leanprover-community/physlib/pull/1746) | 10-08, 10-13 | velocity band of forced uncertainty and its width | `VelocityBand` |

The chain underneath (the open chain: #1689 #1690 #1696 #1708 #1709 #1711 #1716 #1718 #1723
#1724 #1732 #1734 #1735 #1775 #1778 #1781 #1901) and the crystals on top of the cube (#1798
#1802 #1803 #1822 #1823 #1825 #1826 #1896) are merged as well. Closed without merging:
#1773 (forced uncertainty on every axis, in the band) and #1752 (uncertainty cone); both stay
in the base repository. The full list:
[merged pull requests](https://github.com/leanprover-community/physlib/pulls?q=is%3Apr+is%3Amerged+author%3Anaype888-cloud).

## Lean in the base repository

[`nava-robertson-schrodinger`](https://github.com/naype888-cloud/nava-robertson-schrodinger):
`NavaRobertsonIndependent/Mathematics/` `D37` (cube), `D37b` NRS angle, `D37c` cube spectrum,
`D37d` cube Pythagoras, `D37e` volumetric quantum, `D37f` light cone, `D37g` Lieb–Robinson,
`D37h` octahedral symmetry, `D37i` box families, `D39`, `D49`, `D49b`, `D49c`; and
`NavaRobertsonCertificados/` `D43`–`D46`, `D49d`–`D49t`. Details:
[`NRS_OPEN_CUBE.md`](https://github.com/naype888-cloud/nava-robertson-schrodinger/blob/main/NRS_OPEN_CUBE.md).

## Neighbours

[`nrs3-hopf`](https://github.com/naype888-cloud/nrs3-hopf) (the cube in a box, closed axes),
[`nrs3-tritoro`](https://github.com/naype888-cloud/nrs3-tritoro) (the same field on `T³`, and the
open cube's boundary), [`nrs3-uncertainty-cone`](https://github.com/naype888-cloud/nrs3-uncertainty-cone),
[`nrs3-dark`](https://github.com/naype888-cloud/nrs3-dark),
[`nrs3-cristales`](https://github.com/naype888-cloud/nrs3-cristales).

## Figures

`docs/figures/`: the star of `4 × 4 × 4`, the cube Pythagoras, the volumetric quantum, the light
cone and the octahedron, from the base repository.

## License

NRS Noncommercial License, as in the other repositories of the mosaic.
