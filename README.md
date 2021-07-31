# Techlab - Bleeding Edge Prelude For Problem Solvers

Techlab is a prelude for aimed at maximising expressivity and compositionality
in Haskell, for a natural-feel, machine-assisted problem solving toolkit.

This is in early development but well supported and in use at
[homotopic.tech](https://homotopic.tech), intended for serious Haskell power
users who don't mind the ground moving under them.

Techlab values expressivity above all other concerns. We want to make strides
towards a collection of language elements that can model any domain problem,
and type-level tools to break it into to manageable pieces that can be solved
independently.

We don't know exactly what the final form of this toolkit might look like, and
we make no guarantees that anything you might want in a prelude won't be
sacrificed in pursuit of shinier language elements and ergonomics.

Techlab currently contains re-exports of

* chassis
* polysemy (and many polysemy libraries)
* dhall
* vinyl/composite
* formatting
* dimensional https://hackage.haskell.org/package/dimensional
* optics
* ixset-typed
* path
* first-class-families

Hobbyists who like polysemy will probably feel right at home here, and
contributions and discussions are welcome.

Things we plan to add:

* a parsing library (likely megaparsec)
* frp/signal processing
* better attention given towards generics
* tutorials, for intermediate haskellers who might want to experiment with
  this, and advanced use cases
