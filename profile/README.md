# Updo Examples

_From Dhall configuration, generate Stack and Cabal projects with Dhall text templating_

Please see the [readme](https://github.com/cabalism/updo#readme) or
[announcement](https://blockscope.com/posts/2023-11-15-updo.html) for more
details on Updo itself. Here you'll find examples of projects converted to use
Updo to configure, generate and sometimes upgrade projects.

## Conversions

These Haskell projects have been upgraded to a published version of Updo, e.g.
`updo-1.0.0`, or have been upgraded to development version of Updo, identified
with a commit hash.

| Source | Updo Version | Updo Hash | Notes |
| :- | -:| :-: | :-: |
| [MercuryTechnologies/hlint-plugin](https://github.com/up-do/hlint-plugin) | `1.0.0` | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | [⇢](/hlint-plugin.md) |
| [clash-lang/clash-compiler](https://github.com/up-do/clash-compiler) | | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | |
| [commercialhaskell/stack](https://github.com/up-do/stack) | `1.0.0` | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | | 
| [diku-dk/futhark](https://github.com/up-do/futhark) | | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | |
| [elm/compiler](https://github.com/up-do/elm-compiler) | | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | |
| [google-research/dex-lang](https://github.com/up-do/dex-lang) | `1.0.0` | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | | 
| [haskell/cabal](https://github.com/up-do/cabal) | `1.0.0` | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | | 
| [jgm/pandoc](https://github.com/up-do/pandoc) | | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | |
| [ucsd-progsys/liquid-fixpoint](https://github.com/up-do/liquid-fixpoint) | | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | |
| [ucsd-progsys/liquidhaskell](https://github.com/up-do/liquidhaskell) | | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | |

## Proposed

These projects are up for conversion. Add a pull request if you want to suggest
another project.

* [agda/agda](https://github.com/agda/agda)
* [digitallyinduced/ihp](https://github.com/digitallyinduced/ihp)
* [haskell-servant/servant](https://github.com/haskell-servant/servant)
* [idris-lang/Idris-dev](https://github.com/idris-lang/Idris-dev)
* [input-output-hk/plutus](https://github.com/input-output-hk/plutus)
* [lamdu/lamdu](https://github.com/lamdu/lamdu)
* [simonmichael/hledger](https://github.com/simonmichael/hledger)
* [unisonweb/unison](https://github.com/unisonweb/unison/)
* [yesodweb/persistent](https://github.com/yesodweb/persistent)
* [yesodweb/yesod](https://github.com/yesodweb/yesod)
* [yi-editor/yi](https://github.com/yi-editor/yi)

## Considered but Rejected

* [ghc/ghc](https://github.com/ghc/ghc)[^1]
* [github/semantic](https://github.com/github/semantic)[^2]

[^1]: When GHC builds with Cabal.
[^2]: It looks like the [github/semantic]() project is parked (["in
      flux"](https://github.com/github/semantic/issues/698#issuecomment-1503955816))
      with development shifted to
      [github/stack-graphs](https://github.com/github/stack-graphs), a rust
      project.
