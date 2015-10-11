## Building blocks for Erlang/OTP systems using distributed algorithms. ##

copyright 2007-2008 Basho Technologies

authors:
  * Justin Sheehy
  * Andy Gross


---


Code added so far:

| Vector Clocks | [module](http://distributerl.googlecode.com/svn/trunk/vclock.erl) | [documentation](http://distributerl.googlecode.com/svn/trunk/vclock.html) |
|:--------------|:------------------------------------------------------------------|:--------------------------------------------------------------------------|

references:
  * Leslie Lamport (1978). "Time, clocks, and the ordering of events in a distributed system". Communications of the ACM 21 (7): 558-565.
  * Friedemann Mattern (1988). "Virtual Time and Global States of Distributed Systems". Workshop on Parallel and Distributed Algorithms: pp. 215-226

| Consistent Hashing | [module](http://distributerl.googlecode.com/svn/trunk/chash.erl) | [documentation](http://distributerl.googlecode.com/svn/trunk/chash.html) |
|:-------------------|:-----------------------------------------------------------------|:-------------------------------------------------------------------------|

reference:
  * Karger, D.; Lehman, E.; Leighton, T.; Panigrahy, R.; Levine, M.; Lewin, D. (1997). "Consistent hashing and random trees". Proceedings of the twenty-ninth annual ACM symposium on Theory of computing: 654~663. ACM Press New York, NY, USA

| Merkle Trees | [module](http://distributerl.googlecode.com/svn/trunk/merkerl.erl) | [documentation](http://distributerl.googlecode.com/svn/trunk/merkerl.html) |
|:-------------|:-------------------------------------------------------------------|:---------------------------------------------------------------------------|

reference:
  * Ralph C. Merkle, A Digital Signature Based on a Conventional Encryption Function, A Conference on the Theory and Applications of Cryptographic Techniques on Advances in Cryptology, p.369-378, August 16-20, 1987

---

Coming soon: generic versioned objects for convenient use with Merkle trees

---

Coming a bit later: Generic Gossip Protocol
