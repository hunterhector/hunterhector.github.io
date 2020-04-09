---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Zhengzhong Liu (People often refer me with my nickname Hector). I am a PhD researcher on Natural Language Processing and Computational Linguistics at [Carnegie Mellon University](https://www.lti.cs.cmu.edu/), working with Professor [Teruko Mitamura](https://www.cs.cmu.edu/~teruko/) and Professor [Eduard Hovy](https://www.cs.cmu.edu/~hovy/). Prior to my PhD, I obtained my master at CMU with Teruko and Ed. And prior to that, I obtained my bachelor degree in [the Department of Computing](https://www.comp.polyu.edu.hk/) from [the Hong Kong Polytechnic University](https://www.polyu.edu.hk/), working with Professor [Qin Lu](https://www4.comp.polyu.edu.hk/~csluqin/). 

I believe that understanding linguistic problems would allow one to apply proper computational methods solve them. During my PhD, I focus on modeling event semantics, which includes event detection ([TAC'17](https://hunterhector.github.io/publication/2015-11-01-tac2015overview), [TAC'15](https://hunterhector.github.io/publication/2015-11-01-tac2015overview)), anaphora resolution ([NAACL'16](https://hunterhector.github.io/publication/2016-06-16-naacl_2016vpe), [NAACL'16](https://hunterhector.github.io/publication/2016-06-12-naacl2016coref), [LREC'14](https://hunterhector.github.io/publication/2014-05-26-lrec2014coref])), script modeling ([COLING'18](https://hunterhector.github.io/publication/2018-01-13-coling2018sequencing)) and salience modeling ([EMNLP'18](https://hunterhector.github.io/publication/2018-09-03-emnlp2018salience)).

I am broadly interested in solving NLP problems by combining machine learning techniques and linguistic insights, such as entity modeling (disambiguation([WWW'12](https://hunterhector.github.io/publication/2012-04-16-www2012)), 【linking】(https://github.com/hunterhector/dbpedia-spotlight)), information extraction, information retrieval ([SIGIR'18](https://hunterhector.github.io/publication/2018-03-03-sigir2018rank_salience),[CIKM'17](https://hunterhector.github.io/publication/2017-11-07-cikm2017joint)), knowledge enhanced NLP ([ACL'16](https://hunterhector.github.io/publication/2016-08-07-acl_2016logic)).

I am also a fan of development open-source and high quality toolkits about NLP, I have recently worked on the following projects:
  1. [Texar](https://asyml.io/): A modularized approach for Neural Network Based text Generation and more. Texar is nominated for the best demo paper in ACL 2019.
  1. [Forte](https://github.com/asyml/forte): A flexible and highly composable for board range text applications.
  1. [Stave](https://github.com/asyml/stave): A general purpose, modern annotation toolkit (under development).

Thesis
---
My [thesis proposal](https://hunterhector.github.io/files/thesis/proposal_draft.pdf) summarizes some of my previous work. We are proposing to deliver two solutions to two problems we observed in event research:
1. Computational Perspective
  - Problem: Dilemma on labelled data for difficult semantic tasks. Such tasks are very difficult to be annotate because of the task complexity for human; but we at the same time require a lot of data to train such tasks because the task complexity for machines as well. 
  - Proposed solution: we are proposing to bring data together, such as jointly using multiple datasets, or looking for incidental supervision signals.
1. Linguistic Perspective
  - Problem: Common approaches on analyzing event relations typically assumes the shared frame elements are identical, this is not always the case.
  - Proposed solution: We adopt the quasi-identity theory on coreference and propose to solve the problem with a slightly different framework.

