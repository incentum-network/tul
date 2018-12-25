# Token Use License

The open source landscape is changing rapidly, with more companies adopting a more restricted form of open source licensing. This is due to the fact that large cloud computing companies sell cloud based versions of popular open source software without giving anything to the community, or worse, competing directly with paid versions of open source offered by the community. For example, the [Commons Clause](https://commonsclause.com) has been adopted by several open source companies to restrict commercial use of open source software. 

Projects that require a utility token to access a service present a new and unique model for software developers. However, there are still competing licensing requirements:

1. The license should encourage an open community that is using, enhancing, promoting, and distributing the licensed work.
1. The license must protect and promote the use of the utility token(s).
2. The license must be simple enough to understand and implement.

The Token Use License is designed to satisfy all of these criteria. It is similar to the Apache 2.0 License, but with additional restrictions on redistribution. Essentialy, two restrictions are added: Derivative Works require *primary and significant functionality* and must abide by a *Token Use Clause* attached to the license.

The *Token Use Clause* describes the definition and requirements for using the utility token(s) included in the licensed work. Usually, using the same token(s) in the same manner as the licensed work will be sufficient for most *Token Use Clauses*, but it is split out into a separate file for cases that might be more complex. We recommend using the name *TUC.md* or *TUC.txt* for the *Token Use Clause*.

Note that this license is not intended to prohibit the use of other utility tokens as a part of a Derivative Work. A good use case for this license is for core components that Derivative Works are built upon. For example a Smart Contract component that could be used in multiple blockchain platforms is a good target. Gas denoted with a utility token is used to pay for the execution of the Smart Contracts in the original licensed work. The *Token Use Clause* for this Smart Contracts component would stipulate that the same utility token be used to pay gas in the Derivative Work.

