# Ackermann.dhall

An implementation of the Ackermann function in the terminating configuration language Dhall

## Why?

For fun, it's a good example that terminating doesn't always mean polynomial/elementary/primitive recursive.
It's also cool because the manner of recursion needed to use terminating folds is interesting: we have to compute
a function as we go, if we were just computing a natural number result we'd be stuck with primitive recursion which is much weaker.

You can also import this to make your configuration not finish, if that's what you're into.
