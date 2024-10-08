---
title: "BitFunnel: Revisiting Signatures for Search"
collection: research
permalink: /research/bitfunnel
excerpt: '<i>Best Paper Award Winner</i>'
date: 2017-08-07
venue: 'Proceedings of the 40th International ACM SIGIR Conference on Research and Development in Information Retrieval'
paperurl: 'https://dl.acm.org/citation.cfm?doid=3077136.3080789'
code: 'https://github.com/BitFunnel/BitFunnel'
citation: 'Bob Goodwin, Michael Hopcroft, Dan Luu, Alex Clemmer, <b>Mihaela Curmei</b>, Sameh Elnikety, and Yuxiong He.'
---
Since the mid-90s there has been a widely-held belief that signature files are inferior to inverted files for text indexing. In recent years the Bing search engine has developed and deployed an index based on bit-sliced signatures. This index, known as BitFunnel, replaced an existing production system based on an inverted index. The driving factor behind the shift away from the inverted index was operational cost savings. This paper describes algorithmic innovations and changes in the cloud computing landscape that led us to reconsider and eventually field a technology that was once considered unusable. The BitFunnel algorithm directly addresses four fundamental limitations in bit-sliced block signatures. At the same time, our mapping of the algorithm onto a cluster offers opportunities to avoid other costs associated with signatures. We show these innovations yield a significant efficiency gain versus classic bit-sliced signatures and then compare BitFunnel with Partitioned Elias-Fano Indexes, MG4J, and Lucene.

![](../../images/bitfunnel.png)

<iframe width="560" height="315" src="https://www.youtube.com/embed/1-Xoy5w5ydM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[`ACM`](https://dl.acm.org/citation.cfm?doid=3077136.3080789)
[`code`](https://github.com/BitFunnel/BitFunnel)
