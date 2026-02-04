# CHANGELOG

> Package changelog.

<section class="release" id="v0.2.3">

## 0.2.3 (2026-02-04)

<section class="reverts">

### Reverts

-   [`1dd3fdc`](https://github.com/stdlib-js/stdlib/commit/1dd3fdcf42490e1d3c93fa3a21a65aca69454932) - chore: update to modern benchmark Makefile

</section>

<!-- /.reverts -->

<section class="commits">

### Commits

<details>

-   [`faa8717`](https://github.com/stdlib-js/stdlib/commit/faa87173668a1219c8753d932209fe220af97fa6) - **chore:** add structured package data for `math/base/special/ceil` [(#7978)](https://github.com/stdlib-js/stdlib/pull/7978) _(by Nakul Krishnakumar, Athan Reines)_
-   [`7add020`](https://github.com/stdlib-js/stdlib/commit/7add0201c13e56a0381926ccfd4073c84eaf2ed4) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`dd5765d`](https://github.com/stdlib-js/stdlib/commit/dd5765d771186bddbbc716d577bb94eafc0ac36b) - **docs:** replace manual `for` loop in examples [(#6607)](https://github.com/stdlib-js/stdlib/pull/6607) _(by Harsh Yadav)_
-   [`57efa3d`](https://github.com/stdlib-js/stdlib/commit/57efa3d9de9c4c2f0a94387079e356dad7649a40) - **chore:** rename C files to follow current project conventions [(#6410)](https://github.com/stdlib-js/stdlib/pull/6410) _(by Karan Anand, stdlib-bot)_
-   [`73d8eb8`](https://github.com/stdlib-js/stdlib/commit/73d8eb85e52e10d7928ec64809752baa2b23e4cc) - **bench:** refactor random generation in `math/base/special/ceil*` [(#5834)](https://github.com/stdlib-js/stdlib/pull/5834) _(by Saurabh Singh)_
-   [`b0e68c5`](https://github.com/stdlib-js/stdlib/commit/b0e68c5bc8ee985794eb2ea1791c9337cd15fbd0) - **chore:** update to modern benchmark Makefile _(by Philipp Burckhardt)_
-   [`1dd3fdc`](https://github.com/stdlib-js/stdlib/commit/1dd3fdcf42490e1d3c93fa3a21a65aca69454932) - **revert:** chore: update to modern benchmark Makefile _(by Philipp Burckhardt)_
-   [`cdaf16f`](https://github.com/stdlib-js/stdlib/commit/cdaf16f9f3c05f153fcffbb00dab12412196cce6) - **chore:** update to modern benchmark Makefile _(by Philipp Burckhardt)_
-   [`272ae7a`](https://github.com/stdlib-js/stdlib/commit/272ae7ac5c576c68cfab1b6e304c86407faa20cd) - **docs:** remove comment _(by Athan Reines)_
-   [`55ec8ed`](https://github.com/stdlib-js/stdlib/commit/55ec8edfeb7000bca7478af116e794f20560e922) - **docs:** remove comment _(by Athan Reines)_
-   [`2777e4b`](https://github.com/stdlib-js/stdlib/commit/2777e4be161869d09406e3b17947d24c64b47af2) - **bench:** resolve lint errors in benchmarks _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 6 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Harsh Yadav
-   Karan Anand
-   Nakul Krishnakumar
-   Philipp Burckhardt
-   Saurabh Singh

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.2.2">

## 0.2.2 (2024-07-28)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.2.1">

## 0.2.1 (2024-02-24)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.2.0">

## 0.2.0 (2024-02-14)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.1.1">

## 0.1.1 (2023-10-10)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.1.0">

## 0.1.0 (2023-09-23)

<section class="features">

### Features

-   [`33b55e6`](https://github.com/stdlib-js/stdlib/commit/33b55e66e1ce8720ed5fcb9e8885fa56de010774) - remove out argument support in croundn and add C implementations [(#1009)](https://github.com/stdlib-js/stdlib/pull/1009)
-   [`58832ee`](https://github.com/stdlib-js/stdlib/commit/58832eef6d93e6519622148242600eae93dca4d9) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`33b55e6`](https://github.com/stdlib-js/stdlib/commit/33b55e66e1ce8720ed5fcb9e8885fa56de010774): remove support for `out` argument

    -   To migrate, users should provide a complex number object and handle a complex number object return value.

-   [`58832ee`](https://github.com/stdlib-js/stdlib/commit/58832eef6d93e6519622148242600eae93dca4d9): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`33b55e6`](https://github.com/stdlib-js/stdlib/commit/33b55e66e1ce8720ed5fcb9e8885fa56de010774) - **feat:** remove out argument support in croundn and add C implementations [(#1009)](https://github.com/stdlib-js/stdlib/pull/1009) _(by Stephannie Jiménez Gacha, Athan Reines)_
-   [`58832ee`](https://github.com/stdlib-js/stdlib/commit/58832eef6d93e6519622148242600eae93dca4d9) - **feat:** update minimum TypeScript version _(by Philipp Burckhardt)_
-   [`5363054`](https://github.com/stdlib-js/stdlib/commit/536305400d60ff7450198139f2f9aef9eb06581a) - **docs:** resolve C lint errors _(by Athan Reines)_
-   [`b9e414a`](https://github.com/stdlib-js/stdlib/commit/b9e414a8958f7e59ebf824db6923eb6aba0010a0) - **docs:** resolve C lint errors _(by Athan Reines)_
-   [`28e1c84`](https://github.com/stdlib-js/stdlib/commit/28e1c84390d88044883c9ef940a12f38d66ea3ef) - **docs:** resolve C lint errors _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 3 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Philipp Burckhardt
-   Stephannie Jiménez Gacha

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.0.8">

## 0.0.8 (2022-02-16)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.7">

## 0.0.7 (2021-08-22)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.6">

## 0.0.6 (2021-07-07)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.5">

## 0.0.5 (2021-06-27)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.4">

## 0.0.4 (2021-06-16)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.3">

## 0.0.3 (2021-06-15)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.2">

## 0.0.2 (2021-06-15)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.1">

## 0.0.1 (2021-06-14)

No changes reported for this release.

</section>

<!-- /.release -->

