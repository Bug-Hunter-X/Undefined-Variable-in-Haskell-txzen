# Haskell Undefined Variable Bug

This repository demonstrates a common error in Haskell: using an undefined variable. The `bug.hs` file contains the erroneous code.  The `bugSolution.hs` file provides a corrected version.

The bug arises from attempting to use a variable (`x`) before assigning it a value.  Haskell's type system prevents this in many cases, but here, `undefined` explicitly creates a value of any type that will throw an exception when evaluated.