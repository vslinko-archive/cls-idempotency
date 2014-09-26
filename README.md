# cls-idempotency

`cls-idempotency` is class inheritance solution based on [cls](https://github.com/benjamn/cls).

`cls-idempotency` have 3 core differences from standard `cls`:

1. Constructor might have only one argument.
2. Constructor might be called without `new` keyword like an usual function.
3. Constructor might be called with own instance as argument without problems.

Reasons for these changes you can find in article
[Six reasons to define constructors with only one argument](http://gcanti.github.io/2014/09/25/six-reasons-to-define-constructors-with-only-one-argument.html).
