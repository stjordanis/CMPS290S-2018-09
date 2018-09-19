# Readings

_This page is a draft and subject to change._

This page is neither sound (i.e., if it's listed here, that doesn't mean we'll read it) nor complete (i.e., if it's *not* listed here, that doesn't mean we *won't* read it).  So, don't read too much into what's listed here or how it's categorized.  I'm making it all up as I go along, y'all.

| Date             | Topic                                        | Presenter            | Reading
|------------------|----------------------------------------------|----------------------|-----------------------------------------------------
| Friday, 9/28     | Overview and introduction                    | Lindsey              | (none)
| Monday, 10/1     | The CAP theorem                              |                      | Seth Gilbert and Nancy Lynch, [Brewer's Conjecture and the Feasibility of Consistent, Available, Partition-Tolerant Web Services (2002)](http://www.comp.nus.edu.sg/~gilbert/pubs/BrewersConjecture-SigAct.pdf)
| Wednesday, 10/3  | CAP redux                                    |                      | Eric Brewer, [CAP Twelve Years Later: How the "Rules" Have Changed (IEEE Computer, 2012)](https://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed)
| Friday, 10/5     | Consistency models                           |                      | Maurice P. Herlihy and Jeannette M. Wing, [Linearizability: A Correctness Condition for Concurrent Objects (TOPLAS 1990)](http://cs.brown.edu/~mph/HerlihyW90/p463-herlihy.pdf)
| Monday, 10/8     | Consistency models                           |                      | Mustaque Ahamad et al., [Causal memory: definitions, implementation, and programming (Distributed Computing, 1995)](https://link.springer.com/article/10.1007/BF01784241)
| Wednesday, 10/10 | Consistency models                           |                      | Leslie Lamport, [Time, Clocks, and the Ordering of Events in a Distributed System (1978)](https://lamport.azurewebsites.net/pubs/time-clocks.pdf)
| Friday, 10/12    | Consistency models                           |                      | Douglas B. Terry et al., [Session Guarantees for Weakly Consistent Distributed Data (PDIS '94)](https://dl.acm.org/citation.cfm?id=645792.668302)
| Monday, 10/15    | Consistency models                           |                      | Wyatt Lloyd et al., [Don't Settle for Eventual: Scalable Causal Consistency for Wide-Area Storage with COPS (SOSP '11)](https://www.cs.cmu.edu/~dga/papers/cops-sosp2011.pdf)
| Wednesday, 10/17 | Consistency models                           |                      | Paolo Viotti and Marko Vukolić, [Consistency in Non-Transactional Distributed Storage Systems (ACM Computing Surveys, 2016)](https://dl.acm.org/citation.cfm?id=2926965) (see also: [author's version](http://www.vukolic.com/consistency-survey.pdf); [version on arXiv](https://arxiv.org/abs/1512.00168); cf. [the Jepsen overview of consistency models](https://jepsen.io/consistency))
| Friday, 10/19    | Replicated data types                        |                      | Marc Shapiro et al., [Conflict-free Replicated Data Types (2011)](https://hal.inria.fr/inria-00609399/document)
| Monday, 10/22    | Replicated data types                        |                      | Marc Shapiro et al., [A comprehensive study of Convergent and Commutative Replicated Data Types (2011)](https://hal.inria.fr/inria-00555588/document)
| Wednesday, 10/24 | Replicated data types                        |                      | Sebastian Burckhardt et al., [Cloud Types for Eventual Consistency (ECOOP '12)](https://dl.acm.org/citation.cfm?id=2367183) (see also: Burckhardt's book, [_Principles of Eventual Consistency_](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/final-printversion-10-5-14.pdf))
| Friday, 10/26    | Replicated data types                        |                      | Sebastian Burckhardt et al., [Replicated Data Types: Specification, Verification, Optimality (POPL '14)](https://www.microsoft.com/en-us/research/publication/replicated-data-types-specification-verification-optimality/)
| Monday, 10/29    | \*pause for breath\* **(aim to be done with a draft of your first blog post and soliciting editor/instructor feedback by today)** | | (none)
| Wednesday, 10/31 | Combining consistencies                      |                      | Alexey Gotsman et al., ['Cause I'm Strong Enough: Reasoning About Consistency Choices in Distributed Systems (POPL '16)](http://software.imdea.org/~gotsman/papers/logic-popl16.pdf)
| Friday, 11/2     | Combining consistencies                      |                      | Brandon Holt et al., [Disciplined Inconsistency with Consistency Types (SoCC '16)](http://bholt.org/gen/ipa.pdf)
| Monday, 11/5     | Combining consistencies                      |                      | Matthew Milano and Andrew C. Myers, [MixT: a Language for Mixing Consistency in Geodistributed Transactions (PLDI '18)](http://www.cs.cornell.edu/andru/papers/mixt/mixt.pdf)
| Wednesday, 11/7  | Verifying consistency                        |                      | Mohsen Lesani, Christian J. Bell, and Adam Chlipala, [Chapar: Certified Causally Consistent Distributed Key-Value Stores (POPL '16)](http://www.cs.ucr.edu/~lesani/companion/popl16/POPL16.pdf)
| Friday, 11/9     | Verifying consistency                        |                      | Gowtham Kaki et al., [Safe Replication through Bounded Concurrency Verification (OOPSLA '18)](https://2018.splashcon.org/event/splash-2018-oopsla-safe-replication-through-bounded-concurrency-verification) (TODO: update with correct paper link)
| Monday, 11/12    | No class (Veterans Day) **(hard deadline to have your first of two blog posts published)**
| Wednesday, 11/14 | Languages and frameworks for distribution    |                      | Peter Alvaro et al., [Consistency Analysis in Bloom: a CALM and Collected Approach (CIDR '11)](http://db.cs.berkeley.edu/papers/cidr11-bloom.pdf)
| Friday, 11/16    | Languages and frameworks for distribution    |                      | Neil Conway et al., [Logic and Lattices for Distributed Programming (SOCC '15)](https://dl.acm.org/citation.cfm?id=2391230)
| Monday, 11/19    | Languages and frameworks for distribution    |                      | Yanhong A. Liu et al., [From Clarity to Efficiency for Distributed Algorithms (OOPSLA '12)](http://www3.cs.stonybrook.edu/~liu/papers/DistPL-OOPSLA12.pdf)  (see also: [the extended TOPLAS version](https://arxiv.org/pdf/1412.8461.pdf); [the DistAlgo website](https://sites.google.com/site/distalgo/))
| Wednesday, 11/21 | Languages and frameworks for distribution    |                      | Cezara Drăgoi, Thomas Henzinger, and Damien Zufferey, [PSync: A partially synchronous language for fault-tolerant distributed algorithms (POPL '16)](https://hal.inria.fr/hal-01251199/document)
| Friday, 11/23    | No class (Thanksgiving)
| Monday, 11/26    | Languages and frameworks for distribution    |                      | Sergey Bykov et al., [Orleans: Cloud Computing for Everyone (SOCC '11)](https://www.microsoft.com/en-us/research/wp-content/uploads/2011/10/socc125-print.pdf)
| Wednesday, 11/28 | Languages and frameworks for distribution **(aim to be done with a draft of your second blog post and soliciting editor/instructor feedback by today)**  |                      | Sebastian Burckhardt and Tim Coppieters, [Reactive Caching for Composed Services: Polling at the Speed of Push (OOPSLA '18)](https://2018.splashcon.org/event/splash-2018-oopsla-reactive-caching-for-composed-services) (TODO: update with correct paper link)
| Friday, 11/30    | Languages and frameworks for distribution    |                      | Ankush Desai et al., [P: Safe Asynchronous Event-Driven Programming (PLDI '13)](https://dl.acm.org/citation.cfm?id=2462184) (see also: [P on GitHub](https://github.com/p-org/P))
| Monday, 12/3     | Abstractions for configuration management    |                      | Sameer Ajmani, Barbara Liskov, and Liuba Shrira, [Modular Software Upgrades for Distributed Systems (ECOOP '06)](http://pmg.csail.mit.edu/pubs/ajmani06modular-abstract.html)
| Wednesday, 12/5  | Abstractions for configuration management    |                      | Mark Reitblatt et al., [Abstractions for Network Update (SIGCOMM '12)](http://reitblatt.com/papers/consistent-updates-sigcomm12.pdf)
| Friday, 12/7     | Abstractions for configuration management    |                      | Rian Shambaugh, Aaron Weiss, and Arjun Guha, [Rehearsal: A Configuration Verification Tool for Puppet (PLDI '16)](https://people.cs.umass.edu/~arjun/papers/2016-rehearsal.html)
| Wednesday, 12/12 | ~~final exam~~ end-of-quarter celebration **(hard deadline to have your second of two blog posts published)**

## Further reading

There's a vast amount of reading material that would be in scope for a course on "languages and abstractions for distributed programming", but that this particular course won't have time to cover, including but not limited to:

  - ...yet more foundational or survey papers on consistency models, such as:
    - Leslie Lamport, [How to Make a Multiprocessor Computer That Correctly Executes Multiprocess Programs (1979)](https://www.microsoft.com/en-us/research/publication/make-multiprocessor-computer-correctly-executes-multiprocess-programs/)
    - Theo Haerder and Andreas Reuter, [Principles of Transaction-Oriented Database Recovery (ACM Computing Surveys, 1983)](https://dl.acm.org/citation.cfm?id=291)
    - Prince Mahajan, Lorenzo Alvisi, and Mike Dahlin, [Consistency, Availability, and Convergence (2011)](http://www.cs.cornell.edu/lorenzo/papers/cac-tr.pdf)
  - ...yet more material on verif{ying, ied} distributed systems, such as:
    - James R. Wilcox et al., [Verdi: A Framework for Implementing and Formally Verifying Distributed Systems (PLDI '15)](http://verdi.uwplse.org/verdi.pdf) (see also: [the Verdi website](http://verdi.uwplse.org/))
    - Ilya Sergey, James R. Wilcox, and Zachary Tatlock, [Programming and Proving with Distributed Protocols (POPL '18)](http://ilyasergey.net/papers/disel-popl18.pdf)
  - ...material on process calculi, such as:
    - the pi-calculus (see [Jeannette Wing's FAQ](https://www.cs.columbia.edu/~wing/publications/Wing02a.pdf)
    - Cédric Fournet et al., [A Calculus of Mobile Agents (CONCUR '96)](https://dl.acm.org/citation.cfm?id=703841)
    - Luca Cardelli and Andrew D. Gordon, [Mobile Ambients (FoSSaCS '98)](http://lucacardelli.name/Papers/MobileAmbientsETAPS98.A4.pdf)
  - ...material on early or pioneering distributed languages, such as:
    - Andrew Black et al., [Distribution and Abstract Types in Emerald (IEEE TSE 1987)](http://web.cecs.pdx.edu/~black/publications/Emerald%20IEEE%20TSE.pdf)
    - Barbara Liskov, [Distributed Programming in Argus (CACM 1988)](https://dl.acm.org/citation.cfm?id=42399)
    - Luca Cardelli, [A Language with Distributed Scope (POPL '95)](http://lucacardelli.name/Papers/Obliq.pdf)
    - Joe Armstrong, [Erlang (CACM 2010)](https://cacm.acm.org/magazines/2010/9/98014-erlang/fulltext)
    - Andreas Rossberg et al., [Alice Through the Looking Glass (TFP '04)](https://people.mpi-sws.org/~rossberg/papers/Rossberg,%20Le%20Botlan,%20Tack,%20Brunklaus,%20Smolka%20-%20Alice%20Through%20the%20Looking%20Glass.pdf) (see also: [the Alice ML website](https://www.ps.uni-saarland.de/alice/))
  - ...material on extending languages for distribution, such as:
    - Jeff Epstein, Andrew P. Black, and Simon Peyton Jones, [Towards Haskell in the Cloud (Haskell '11)](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/07/remote.pdf) (see also: [the Cloud Haskell website](http://haskell-distributed.github.io/))
  - ...material on Dryad, Naiad, and all that, such as:
    - Yuan Yu et al., [DryadLINQ: A System for General-Purpose Distributed Data-Parallel Computing Using a High-Level Language (OSDI '08)](https://www.usenix.org/legacy/events/osdi08/tech/full_papers/yu_y/yu_y.pdf)
    - Derek G. Murray et al., [Naiad: A Timely Dataflow System (SOSP '13)](http://sigops.org/sosp/sosp13/papers/p439-murray.pdf)
  - ...more "systems-y" perspectives on mixing consistency levels, such as:
    - Douglas B. Terry et al., [Consistency-based service level agreements for cloud storage (SOSP '13)](https://www.microsoft.com/en-us/research/publication/consistency-based-service-level-agreements-for-cloud-storage/)
  - ...material on distributed programming models that facilitate testing, such as:
    - Ankush Desai et al., [Compositional Programming and Testing of Dynamic Distributed Systems (OOPSLA '18)](https://2018.splashcon.org/event/splash-2018-oopsla-compositional-programming-and-testing-of-dynamic-distributed-systems) (TODO: update with correct paper link)
  - ...material on multitier programming, such as:
    - Ezra Cooper et al., [Links: web programming without tiers (FMCO '06)](http://links-lang.org/papers/links-fmco06.pdf)
    - Pascal Weisenburger, Mirko Köhler, and Guido Salvaneschi, [Distributed System Development with ScalaLoci (OOPSLA '18)](https://2018.splashcon.org/event/splash-2018-oopsla-distributed-system-development-with-scalaloci) (TODO: update with correct paper link) (see also: [ScalaLoci website](https://scala-loci.github.io/) and [GitHub organization](https://github.com/scala-loci))
  - ...material on computation orchestration, such as:
    - Jayadev Misra and William R. Cook, [Computation Orchestration: A Basis for Wide-Area Computing (JSSM 2007)](http://orc.csres.utexas.edu/papers/OrcJSSM.pdf)
    - David Kitchin et al., [The Orc Programming Language (FORTE '09)](http://orc.csres.utexas.edu/papers/forte09.pdf)
  - ...material on modal logic as a basis for distributed computing, such as:
    - Joseph Y. Halpern, [Using Reasoning About Knowledge to Analyze Distributed Systems (1987)](https://www.cs.cornell.edu/home/halpern/papers/UsingRAK.pdf)
    - Limin Jia and David Walker, [Modal Proofs as Distributed Programs (ESOP '04)](http://sip.cs.princeton.edu/pub/modal-esop04.pdf)
    - Tom Murphy VII, Karl Crary, and Robert Harper, [Type-Safe Distributed Programming with ML5 (TGC '07)](http://www.cs.cmu.edu/~tom7/papers/ml5_tgc2007_preproceedings.pdf) (see also: Murphy's dissertation, [_Modal Types for Mobile Code_](http://www.cs.cmu.edu/~tom7/papers/modal-types-for-mobile-code.pdf))
  - Etc., etc., etc.