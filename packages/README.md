# Package management

There are a few ways to ~~manage~~ install packages for Haskell.

## cabal

Tried and true cabal-install, otherwise know as [cabal]
(https://www.haskell.org/cabal/) is the defacto community tool for installing
packages with Haskell. [Hackage](http://hackage.haskell.org/), the Haskell
Package Database, is where cabal pulls all of its packages from.

More information about cabal can be found [here]
(https://www.haskell.org/cabal/).

## stack

Stack is the new package installation tool on the block and it builds upon cabal
leveraging the [stackage package database](http://www.stackage.org/). Stackage
itself is a snapshot of Hackage and curated so that all the packages build
against each other.

More information about stack can be found [here]
(https://github.com/commercialhaskell/stack).
