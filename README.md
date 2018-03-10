Vertcoin Cash Core integration/staging tree
===========================================

https://vertcoincash.org

What is Vertcoin Cash?
----------------------

Vertcoin Cash is a fork of Bitcoin that is designed to embrace the all types of mining power.
 - 2.5 minute block targets
 - subsidy halves in 840k blocks (~4 years)
 - ~84 million total coins
 - 50 coins per block (25 after block 840,000)
 - Difficulty retargeting every block to recover from large hashrate swings
 - ASIC support and multi-algorithm
 

For more information, as well as an immediately useable, binary version of
the Vertcoin Cash client sofware, see http://www.vertcoincash.org.

License
-------

Vertcoin Cash Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

Developers work on their own forks and submit pull requests in order to merge
changes with `master`. Due to the relatively small size of the development team,
developers also commit directly to the repo often. Anyone is allowed to contribute
though and useful pull requests will almost always be accepted given various
obvious stipulations regarding stability etc. 

Testing
-------

Vertcoin Cash currently relies on Bitcoin Core for its testcases, and few of them are
known to work, though the software is based on fully test conforming upstream 
Bitcoin Core versions. We would be grateful to those who can help port the existing
Bitcoin Core test cases to Vertcoin Cash such that they can be used to assure correctness.

Translations
------------

Changes to translations as well as new translations can be submitted to as pull
requests to this repo or to upstream Bitcoin Core.
