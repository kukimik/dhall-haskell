1.0.12

* [Fix white flashes on page load in dark mode](https://github.com/dhall-lang/dhall-haskell/pull/2574)
* [Render standalone text files as preformatted text](https://github.com/dhall-lang/dhall-haskell/pull/2565)
* [Render Markdown files as HTML](https://github.com/dhall-lang/dhall-haskell/pull/2579)
* [Default to browser settings for dark mode](https://github.com/dhall-lang/dhall-haskell/pull/2582)
* [Fix typo and formatting in a warning message](https://github.com/dhall-lang/dhall-haskell/pull/2572)

1.0.11

* Build against `dhall-1.42`
* [Build against `turtle-1.6`](https://github.com/dhall-lang/dhall-haskell/pull/2465)
* [Build against `transformers-0.6` and `mtl-2.3`](https://github.com/dhall-lang/dhall-haskell/pull/2471)

1.0.10

* [Index non-`.dhall` files](https://github.com/dhall-lang/dhall-haskell/pull/2407)

1.0.9

* Build against `dhall-1.41`
* [Relax upper bound on `path-io`](https://github.com/dhall-lang/dhall-haskell/pull/2385)
* [Build against `optparse-applicative-0.17`](https://github.com/dhall-lang/dhall-haskell/pull/2376)
* [Build against `text-2.0`](https://github.com/dhall-lang/dhall-haskell/pull/2356)

1.0.8

* [Support GHC 9.2](https://github.com/dhall-lang/dhall-haskell/pull/2328)
* [Build against `tasty-silver-3.3`](https://github.com/dhall-lang/dhall-haskell/pull/2307)
* [Build against `megaparsec-9.2`](https://github.com/dhall-lang/dhall-haskell/pull/2311)
* [Build against `lucid-2.11`](https://github.com/dhall-lang/dhall-haskell/pull/2327)
* [Build against `doctest-0.19`](https://github.com/dhall-lang/dhall-haskell/pull/2331)

1.0.7

* [Add `--base-import-url` flag](https://github.com/dhall-lang/dhall-haskell/pull/2215)
    * This flag adds a URL prefix to all paths copied to the clipboard for ease
      of pasting the import in Dhall code

1.0.6

* Build against `dhall-1.39.0`

1.0.5

* [BUG FIX: Fix index generation](https://github.com/dhall-lang/dhall-haskell/pull/2150)
    * Indices are now created for intermediate directories without `.dhall` files
    * `dhall-docs` no longer hangs when the top-level directory has no `.dhall` files
* [Fix lower bound on `dhall`](https://github.com/dhall-lang/dhall-haskell/pull/2147/)
* [Allow doctest-0.18](https://github.com/dhall-lang/dhall-haskell/pull/2148)
* [Allow bytestring-0.11](https://github.com/dhall-lang/dhall-haskell/pull/2144)
* [Add `README` to tarball](https://github.com/dhall-lang/dhall-haskell/pull/2145)
* [Remove test dependency on HaXml](https://github.com/dhall-lang/dhall-haskell/pull/2156)

1.0.4

* Build against `dhall-1.38.0`, `tasty-1.4`, `tasty-silver-3.2`, and
  `cryptonite-0.28`

1.0.3

* Build against `dhall-1.37.0`

1.0.2

* [Fix command-line completions for files](https://github.com/dhall-lang/dhall-haskell/pull/2034)

1.0.1

* Improved jump to definition support
    * [Jump to definition on `let` bindings](https://github.com/dhall-lang/dhall-haskell/pull/1966)
    * [Jump to definition on `λ` bindings](https://github.com/dhall-lang/dhall-haskell/pull/1982)
    * [Jump to definition on record fields](https://github.com/dhall-lang/dhall-haskell/pull/1991)
* [BUG FIX: Support for long path names](https://github.com/dhall-lang/dhall-haskell/pull/1976)
* [BUG FIX: Support for large directory trees](https://github.com/dhall-lang/dhall-haskell/pull/2006)
* [Add `dhall-docs` `man` page](https://github.com/dhall-lang/dhall-haskell/pull/2010)

1.0.0

* [Generate documentation from header comment](https://github.com/dhall-lang/dhall-haskell/pull/1929)
    * `dhall-docs` will now render a module header from a comment at
      the beginning of a Dhall file
    * The comment syntax is essentially markdown with the same whitespace
      and indentation rules as multi-line strings in Dhall
    * Both block comments and multiple single-line comments are supported
* [Jump to imports](https://github.com/dhall-lang/dhall-haskell/pull/1959)
    * The documentation will now generate links for relative and remote imports found within the
      rendered source code
* [Add support for non-`let` type annotations](https://github.com/dhall-lang/dhall-haskell/pull/1928)
    * `dhall-docs` can now also extract the type of a module from a type
      annotation on a bare expression (i.e. an expression that is not a
      `let` expression)

0.0.1

* Initial beta release
