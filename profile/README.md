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
| [Copilot-Language/copilot](https://github.com/up-do/copilot) | | [a86c16](https://github.com/cabalism/updo/commit/a86c165687b2b5e8251265418a9c4181c6a651a0) | |
| [MercuryTechnologies/hlint-plugin](https://github.com/up-do/hlint-plugin) | `1.0.0` | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | [⇢](/hlint-plugin.md) |
| [clash-lang/clash-compiler](https://github.com/up-do/clash-compiler) | | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | |
| [commercialhaskell/stack](https://github.com/up-do/stack) | `1.0.0` | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | | 
| [diku-dk/futhark](https://github.com/up-do/futhark) | | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | |
| [elm/compiler](https://github.com/up-do/elm-compiler) | | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | |
| [gelisam/klister](https://github.com/gelisam/klister) | | [a86c16](https://github.com/up-do/klister/commit/118996d6ed534ba52fbf799333d48a490cdb46aa) | |
| [google-research/dex-lang](https://github.com/up-do/dex-lang) | `1.0.0` | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | | 
| [haskell/cabal](https://github.com/up-do/cabal) | `1.0.0` | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | | 
| [jgm/pandoc](https://github.com/up-do/pandoc) | | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | |
| [ucsd-progsys/liquid-fixpoint](https://github.com/up-do/liquid-fixpoint) | | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | |
| [ucsd-progsys/liquidhaskell](https://github.com/up-do/liquidhaskell) | | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | |
| [unisonweb/unison](https://github.com/up-do/unison/) | | [cdb06e](https://github.com/cabalism/updo/commit/cdb06ebebaf6b8739e900780bc317cec3cac2d24) | |
| [yesodweb/persistent](https://github.com/up-do/persistent) | | [60545b](https://github.com/cabalism/updo/commit/60545b108b7a6a2f802ec7a161aa4b9eb7441baf) | |
| [yesodweb/yesod](https://github.com/up-do/yesod) | | [d5de60](https://github.com/cabalism/updo/commit/d5de6070bed90c3c1a92d3a976998fcf847d77af) | |

## Proposed

These projects are up for conversion. Add a pull request if you want to suggest
another project.

* [agda/agda](https://github.com/agda/agda)
* [digitallyinduced/ihp](https://github.com/digitallyinduced/ihp)
* [haskell-servant/servant](https://github.com/haskell-servant/servant)
* [input-output-hk/plutus](https://github.com/input-output-hk/plutus)
* [lamdu/lamdu](https://github.com/lamdu/lamdu)
* [simonmichael/hledger](https://github.com/simonmichael/hledger)
* [yi-editor/yi](https://github.com/yi-editor/yi)

## Considered but Rejected

* [ghc/ghc](https://github.com/ghc/ghc)[^1]
* [github/semantic](https://github.com/github/semantic)[^2]
* [idris-lang/Idris-dev](https://github.com/idris-lang/Idris-dev)[^3]

[^1]: When GHC builds with Cabal.
[^2]: It looks like the [github/semantic]() project is parked (["in
      flux"](https://github.com/github/semantic/issues/698#issuecomment-1503955816))
      with development shifted to
      [github/stack-graphs](https://github.com/github/stack-graphs), a rust
      project.
[^3]: Idris has [moved on from Haskell](https://github.com/idris-lang/Idris-dev/tree/master#status).
      > This is Idris 1, implemented in Haskell. Idris 1 is not actively
      > worked on anymore.
      > [Idris 2](https://github.com/idris-lang/Idris2) is the next generation
      > of Idris, and where primary development happens.
