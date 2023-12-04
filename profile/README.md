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
| [MercuryTechnologies/hlint-plugin](https://github.com/up-do/hlint-plugin) | `1.0.0` | | [⇢](/hlint-plugin.md) |
| [clash-lang/clash-compiler](https://github.com/up-do/clash-compiler) | | [9d89b8](https://github.com/cabalism/updo/commit/9d89b85a54e49fd0c7a29342cf5b98de2529f588) | |
| [commercialhaskell/stack](https://github.com/up-do/stack) | `1.0.0` | | |
| [diku-dk/futhark](https://github.com/up-do/futhark) | | [9d89b8](https://github.com/cabalism/updo/commit/9d89b85a54e49fd0c7a29342cf5b98de2529f588) | |
| [elm/compiler](https://github.com/up-do/elm-compiler) | | [7fa75f](https://github.com/cabalism/updo/commit/7fa75f53441a5a4b858016744ec275a1e7b6a44a) | |
| [google-research/dex-lang](https://github.com/up-do/dex-lang) | `1.0.0` | [7fa75f](https://github.com/cabalism/updo/commit/7fa75f53441a5a4b858016744ec275a1e7b6a44a) | | 
| [haskell/cabal](https://github.com/up-do/cabal) | `1.0.0` | [7fa75f](https://github.com/cabalism/updo/commit/7fa75f53441a5a4b858016744ec275a1e7b6a44a) | | 
| [jgm/pandoc](https://github.com/up-do/pandoc) | | [9d89b8](https://github.com/cabalism/updo/commit/9d89b85a54e49fd0c7a29342cf5b98de2529f588) | |
| [ucsd-progsys/liquid-fixpoint](https://github.com/up-do/liquid-fixpoint) | | [6453f4](https://github.com/cabalism/updo/commit/6453f4b8a74f9ca665ff3d21644b1b9284a87a55) | |
| [ucsd-progsys/liquidhaskell](https://github.com/up-do/liquidhaskell) | | [6453f4](https://github.com/cabalism/updo/commit/6453f4b8a74f9ca665ff3d21644b1b9284a87a55) | |

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
