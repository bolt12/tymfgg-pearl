# Type Your Matrices For Great Good (Functional Pearl) - A Haskell library of typed matrices and applications

This Functional Pearl was accepted at the Haskell Symposium 2020.

## Abstract

We study a simple inductive data type for representing correct-by-construction matrices.
Despite its simplicity, it can be used to implement matrix-manipulation algorithms efficiently and safely,
performing in some cases faster than existing alternatives even though the algorithms are written in a direct
and purely functional style.
A rich collection of laws makes it possible to derive and optimise these algorithms using equational reasoning,
avoiding the notorious off-by-one indexing errors when fiddling with matrix dimensions.
We demonstrate the usefulness of the data type on several examples,
and highlight connections to related topics in category theory.

## Implementation

See https://github.com/bolt12/laop for the source code.
