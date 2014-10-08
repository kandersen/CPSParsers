CPSParsers - Continuation Based Parser Combinators for Elm
==========

This library is an implementation of the 6th order parser combinators devised in the functional pearl by Chris Okasaki[^1].

They started life as a stand-in for the JSON marshalling facilities in Elm, which were, at the time… lacking.

The code compiled then, but likely won't now as they type-checker was rewritten to not accept recursive types, even though they wont "go wrong" per se. Some careful guarding of recursive calls are necessary in a rewrite that I will probably never get around to, unless Elm introduces type classes, at which point it would be too much fun not to : )

[^1]:  CHRIS OKASAKI (1998). Even higher-order functions for parsing or Why would anyone ever want to use a sixth-order function?. Journal of Functional Programming, 8, pp 195-199. (Function"http://www.westpoint.edu/eecs/SiteAssets/SitePages/Faculty%20Publication%20Documents/Okasaki/jfp98sixth.pdf)
