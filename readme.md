# A Reading List for Distributed Large-Scale Systems

This repository contains a list of papers that focus on the design and implementation of distributed systems. To better exhibit the design trend in this research area, this reading list is intended to only contain high-quality papers published in top-tier conferences/journals.
- - -

## Contents
- [Surveys](#surveys)
- [In-Memory Tree Indexing](#in-memory-tree-indexing)
- [In-Memory Hash Indexing](#in-memory-hash-indexing)

- - -

## Surveys
* D. Lomet, [The Evolution of Effective B-tree: Page Organization and Techniques: A Personal Account](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/p64-lomet.pdf), in ACM SIGMOD Record, 2001.
* G. Graefe, [A Survey of B-Tree Locking Techniques](https://dl.acm.org/citation.cfm?id=1806907.1806908), in TODS 2010.
* G. Graefe, [Modern B-tree techniques](https://www.nowpublishers.com/article/Details/DBS-028), in Foundations and Trends in Databases 2011.

## In-Memory Tree Indexing
* T. Lehman, et al., [A Study of Index Structures for Main Memory Database Management Systems](http://www.vldb.org/conf/1986/P294.PDF), in VLDB 1986.
* M. Bender, et al., [Cache-Oblivious Streaming B-Trees](https://dl.acm.org/citation.cfm?id=1248393), in SPAA 2007.
* C. Kim, et al., [FAST: Fast Architecture Sensitive Tree Search on Modern CPUs and GPUs](https://dl.acm.org/citation.cfm?id=1807206), in SIGMOD 2010.
* Y. Mao, et al., [Cache Craftiness for Fast Multicore Key-Value Storage](https://dl.acm.org/citation.cfm?id=2168855), in EuroSys 2012.
* V. Leis, et al., [The Adaptive Radix Tree: ARTful Indexing for Main-Memory Databases](https://db.in.tum.de/~leis/papers/ART.pdf), in ICDE 2013.
* V. Leis, et al., [The ART of Practical Synchronization](https://dl.acm.org/citation.cfm?id=2933352), in DaMoN 2016.
* H. Zhang, et al., [Reducing the Storage Overhead of Main-Memory OLTP Databases with Hybrid Indexes](https://dl.acm.org/citation.cfm?id=2915222), in SIGMOD 2016.
* R. Binna, et al., [HOT: A Height Optimized Trie Index for Main-Memory Database Systems](https://dl.acm.org/citation.cfm?id=3183713.3196896), in SIGMOD 2018.

## In-Memory Hash Indexing
* X. Li, et al., [Algorithmic Improvements for Fast Concurrent Cuckoo Hashing](https://dl.acm.org/citation.cfm?id=2592820),  EuroSys 2014
## External Key Value Storage
* Lim et. al., [MICA: A Holistic Approach to Fast In-Memory Key-Value Storage](https://www.usenix.org/system/files/conference/nsdi14/nsdi14-paper-lim.pdf) - NSDI 2014
* Lim et. al., [SILT: A Memory-Efficient, High-Performance Key-Value Store](https://www.cs.cmu.edu/~dga/papers/silt-sosp2011.pdf) - SOSP 2011
* Chandramouli et. al., [Faster: A Concurrent Key-Value Store with In-Place Updates](https://www.microsoft.com/en-us/research/uploads/prod/2018/03/faster-sigmod18.pdf) - SIGMOD 2018
## Others
* J. Rao, et al., [CSB+Tree Making B+-Trees Cache Conscious in Main Memory](https://dl.acm.org/citation.cfm?id=335449), in SIGMOD 2000
* J. Levandoski, et al., [The Bw-Tree: A B-tree for New Hardware Platforms](https://www.microsoft.com/en-us/research/publication/the-bw-tree-a-b-tree-for-new-hardware/), ICDE 2013.
* J. Waldo, et.al., [A Note on Distributed Computing](https://www.cc.gatech.edu/classes/AY2010/cs4210_fall/papers/smli_tr-94-29.pdf), SLMI 1994
* E. Brewer, [CAP Twelve Years Later: How the "Rules" Have Changed](https://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed)
* S. Yegge, [Steve Yegge's Google Platforms Rant](https://gist.github.com/chitchcock/1281611)
* P. Helland, [Building on Quicksand](https://arxiv.org/abs/0909.1788), arxiv 2009
