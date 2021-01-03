---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Zhengzhong Liu (People often refer me with my nickname Hector). I am a PhD researcher on Natural Language Processing and Computational Linguistics at [Carnegie Mellon University](https://www.lti.cs.cmu.edu/), working with Professor [Teruko Mitamura](https://www.cs.cmu.edu/~teruko/) and Professor [Eduard Hovy](https://www.cs.cmu.edu/~hovy/). I also work closely with Professor [Eric Xing](http://www.cs.cmu.edu/~epxing/) on the [CASL project](https://casl-project.github.io/). Prior to my PhD, I obtained my master at CMU with Teruko and Ed. And prior to that, I obtained my bachelor degree in [the Department of Computing](https://www.comp.polyu.edu.hk/) from [the Hong Kong Polytechnic University](https://www.polyu.edu.hk/), working with Professor [Qin Lu](https://www4.comp.polyu.edu.hk/~csluqin/). 

I believe that understanding linguistic problems would allow one to apply proper computational methods solve them. During my PhD, I focus on modeling event semantics, which includes event detection ([TAC'17](https://hunterhector.github.io/publication/2015-11-01-tac2015overview), [TAC'15](https://hunterhector.github.io/publication/2015-11-01-tac2015overview)), anaphora resolution ([NAACL'16](https://hunterhector.github.io/publication/2016-06-16-naacl_2016vpe), [NAACL'16](https://hunterhector.github.io/publication/2016-06-12-naacl2016coref), [LREC'14](https://hunterhector.github.io/publication/2014-05-26-lrec2014coref])), script modeling ([COLING'18](https://hunterhector.github.io/publication/2018-01-13-coling2018sequencing)) and salience modeling ([EMNLP'18](https://hunterhector.github.io/publication/2018-09-03-emnlp2018salience)).

I am broadly interested in solving problems by combining machine learning techniques with linguistic insights and human knowledge. In the early days I worked on semantic web problems such as entity disambiguation([WWW'12](https://hunterhector.github.io/publication/2012-04-16-www2012), [entity linking](https://github.com/hunterhector/dbpedia-spotlight)) or [slot filling](https://hunterhector.github.io/publication/2011-11-14-tac2011). Particularly, I love incorporating knowledge into NLP problems, such as in information retrieval ([SIGIR'18](https://hunterhector.github.io/publication/2018-03-03-sigir2018rank_salience),[CIKM'17](https://hunterhector.github.io/publication/2017-11-07-cikm2017joint)), or core NLP tasks ([ACL'16](https://hunterhector.github.io/publication/2016-08-07-acl_2016logic)).

I am also a fan of developing open-source and high quality toolkits about NLP, I have recently worked on the following projects:
  1. [Texar](https://asyml.io/): A modularized approach for Neural Network Based text Generation and more. Texar is nominated for the best demo paper in ACL 2019.
  1. [Forte](https://github.com/asyml/forte): A flexible and highly composable NLP toolkit for a wide range of text applications (including IR, NLU, NLG). Checkout out our [AAAI 2020](https://asyml.github.io/aaai_tutorial/) and [GTC 2020](https://developer.nvidia.com/gtc/2020/video/s21560-vid) Tutorials for the design philosophy.
  1. [Stave](https://github.com/asyml/stave): A general purpose, modern annotation toolkit (under development).

Recently, we have combined these projects together with other [OSS projects](https://github.com/petuum) and launched the [CASL](https://casl-project.github.io/) (Composible, Auotmatic, and Scalable ML) open source effort, led by Professor [Eric Xing](http://www.cs.cmu.edu/~epxing/), to provide a unified umbrella for a Production and Industrial AI Platform. 

I served as Program Committee (reviewer) for ACL  2019 (outstanding reviewer), 2020; ACL SRW 2020; NAACL 2019 (Kudos Reviewer); EMNLP 2018, 2020; NLPCC 2017, 2018, 2019, 2020; CoNLL 2019.

Thesis
---
My [thesis proposal](https://hunterhector.github.io/files/thesis/proposal_draft.pdf) summarizes some of my previous work. We are proposing to deliver two solutions to two problems we observed in event research:
1. Computational Perspective
  - Problem: Dilemma on labelled data for difficult semantic tasks. Such tasks are very difficult to be annotate because of the task complexity for human; but we at the same time require a lot of data to train such tasks because the task complexity for machines as well. 
  - Proposed solution: we are proposing to bring data together, such as jointly using multiple datasets, or looking for incidental supervision signals.
1. Linguistic Perspective
  - Problem: Common approaches on analyzing event relations typically assumes the shared frame elements are identical, this is not always the case.
  - Proposed solution: We adopt the quasi-identity theory on coreference and propose to solve the problem with a slightly different framework.

