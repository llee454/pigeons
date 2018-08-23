Pigeons Readme
==============

A proof of the [pigeonhole principle](https://en.wikipedia.org/wiki/Pigeonhole_principle). The Pigeonhole principle
is a fundamental theorem that is used widely in Computer Science and
Combinatorics, it asserts that if you put n things into m containers,
and n > m, then at least one of the containers contains more than
one thing.

Relation to Other Work
----------------------

As far as I can tell, the Coq Standard Library does not contain
a proof of the pigeonhole principle. In addition, when I searched
the Coq Package Index, I only found a single proof of the pigeonhole
principle. This proof is contained in the [CoLoR library](https://github.com/fblanqui/color/blob/bd939824c1b9b3147cc596086627cca586fbbeed/Util/List/ListOccur.v) in a
module defining a predicate named `occur`.

The proof given by the CoLoR library is not a stand-alone proof
and depends on several other functions and predicates provided by
the library. In this library, I present a stand-alone proof that
relies solely on the Coq Standard Library.

Authors
-------

Larry Darryl Lee Jr. <llee454@gmail.com>
