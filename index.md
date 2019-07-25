# Vision

The importance of repeatability, replicability, and reproducibility is broadly recognized in the computational sciences, both in supporting desirable scientific methodology as well as sustaining empirical progress.  The **Open-Source IR Replicability Challenge (OSIRRC2019)**, organized as a workshop at [SIGIR 2019](http://sigir.org/sigir2019/), aims to improve the replicability of ad hoc retrieval experiments in information retrieval by building community consensus around a common technical specification, with reference implementations.



In order to precisely articulate the goals of this workshop, it is first necessary to establish common terminology. We use the below terms in the same manner as recent [ACM guidelines](https://www.acm.org/publications/policies/artifact-review-badging) pertaining to artifact review and badging:

- Repeatability (same team, same experimental setup): a researcher can reliably repeat her own computation.

- Replicability (different team, same experimental setup): an independent group can obtain the same result using the author’s own artifacts.

- Reproducibility (different team, different experimental setup): an independent group can obtain the same result using artifacts which they develop completely independently.

These guidelines are also being adopted by the SIGIR community, which has recently established [a task force to determine how to implement them for IR](http://sigir.org/wp-content/uploads/2018/07/p004.pdf).

This workshop tackles the replicability challenge for _ad hoc_ document retrieval, with three explicit goals:

1. Develop a common Docker specification to support images that capture systems performing _ad hoc_ retrieval experiments on standard test collections.
The solution that we have developed is known as `the jig`.

2. Build a curated library of Docker images that work with the jig to capture a diversity of systems and retrieval models.

3. Explore the possibility of broadening our efforts to include additional tasks, diverse evaluation methodologies, and other benchmarking initiatives.


Participants in OSIRRC 2019 help in building consensus on the Docker specifications and contribute Docker images that conform to the agreed-upon specifications. 

Interested individuals and teams are requested to email osirrc2019-organizers@googlegroups.com for more details or directly join the Google groups osirrc2019@googlegroups.com.


# Contributions

We solicited two kinds of contributions from the community:

#### Participation in the replicability challenge and related "docker paper"

  Docker images that encapsulate strong baselines as well as state-of-the-art techniques: examples include runs based on query expansion, entity annotations, and neural networks. 
  
 These Docker images have to be accompanied by a paper describing the experience of a team in participating to the challenge.
  
#### Position papers

  Position papers around the issues of replicability in the IR field, with a special focus on infrastructures to enable them.
  
  The goal of these papers is to further stimulate the discussion at the workshop and help shaping the path forward for the community.


Here, you can find full details about [Submission Instructions and Important Dates](https://osirrc.github.io/osirrc2019/cfp.html).


# OSIRRC 2019 Proceedings at CEUR-WS

The [OSIRRC 2019 Proceedings](http://ceur-ws.org/Vol-2409/) are available online at CEUR-WS.

You can cite them as:

Clancy, R., Ferro, N., Hauff, C., Sakai, T., and Wu, Z. Z., editors (2019). *Proc. of the Open-Source IR Replicability Challenge (OSIRRC 2019)*. CEUR Workshop Proceedings (CEUR-WS.org), ISSN 1613-0073, http: //ceur-ws.org/Vol-2409/.


# OSIRRC 2019 Image Library

The [OSIRRC 2019 Image Library](https://github.com/osirrc/osirrc2019-library/) repository catalogs the images that have been submitted to the OSIRRC 2019.
The actual raw runs are held in a [separate repository](https://github.com/osirrc/osirrc2019-runs).


+ [Anserini](https://github.com/osirrc/osirrc2019-library/#Anserini)
+ [Anserini-bm25prf](https://github.com/osirrc/osirrc2019-library/#Anserini-bm25prf)
+ [ATIRE](https://github.com/osirrc/osirrc2019-library/#ATIRE)
+ [Birch](https://github.com/osirrc/osirrc2019-library/#Birch)
+ [Elastirini](https://github.com/osirrc/osirrc2019-library/#Elastirini)
+ [EntityRetrieval](https://github.com/osirrc/osirrc2019-library/#EntityRetrieval)
+ [Galago](https://github.com/osirrc/osirrc2019-library/#Galago)
+ [ielab](https://github.com/osirrc/osirrc2019-library/#ielab)
+ [Indri](https://github.com/osirrc/osirrc2019-library/#Indri)
+ [IRC-CENTRE2019](https://github.com/osirrc/osirrc2019-library/#IRC-CENTRE2019)
+ [JASS](https://github.com/osirrc/osirrc2019-library/#JASS)
+ [JASSv2](https://github.com/osirrc/osirrc2019-library/#JASSv2)
+ [NVSM](https://github.com/osirrc/osirrc2019-library/#NVSM)
+ [OldDog](https://github.com/osirrc/osirrc2019-library/#OldDog)
+ [PISA](https://github.com/osirrc/osirrc2019-library/#PISA)
+ [Solrini](https://github.com/osirrc/osirrc2019-library/#Solrini)
+ [Terrier](https://github.com/osirrc/osirrc2019-library/#Terrier)


# Program

### 08:55-09:00 Welcome and Opening

### 09:00-09:30 OSIRRC Overview

- *Overview of the 2019 Open-Source IR Replicability Challenge (OSIRRC 2019)*  
  Ryan Clancy, Nicola Ferro, Claudia Hauff, Jimmy Lin, Tetsuya Sakai, Ze Zhong Wu  
  [[Paper]](http://ceur-ws.org/Vol-2409/invited01.pdf) [[Slides]](https://osirrc.github.io/osirrc2019/slides/invited01-slides.pdf)


### 09:30-10:30 Lightning Talks [4 minutes each]


##### Position Papers

- *STELLA: Towards a Framework for the Reproducibility of Online Search Experiments*  
  Timo Breuer, Philipp Schaer, Narges Tavalkolpoursaleh, Benjamin Wolff, Bernd M&uuml;ller  
  [[Paper]](http://ceur-ws.org/Vol-2409/position01.pdf) [[Slides]](https://osirrc.github.io/osirrc2019/slides/position01-slides.pdf)
- *Let's measure run time! Extending the IR replicability infrastructure to include performance aspects*  
  Sebastian Hofst&auml;tter, Allan Hanbury  
  [[Paper]](http://ceur-ws.org/Vol-2409/position02.pdf) [[Slides]](https://osirrc.github.io/osirrc2019/slides/position02-slides.pdf)
- *Reproducible IR needs an (IR) (Graph) Query Language*  
  Chris Kamphuis, Arjen P. de Vries  
  [[Paper]](http://ceur-ws.org/Vol-2409/position03.pdf) [[Slides]](https://osirrc.github.io/osirrc2019/slides/position03-slides.pdf)
- *Repeatable Runs for Test Collection Documentation*  
  Ian Soboroff 
  [[Slides]](https://osirrc.github.io/osirrc2019/slides/position04-slides.pdf)

##### Docker Papers

- *Entity Retrieval Docker Image for OSIRRC at SIGIR 2019*  
  Negar Arabzadeh  
  [[Paper]](http://ceur-ws.org/Vol-2409/docker01.pdf)
- *Dockerising Terrier for The Open-Source IR Replicability Challenge (OSIRRC 2019)*  
  Arthur Barbosa C&acirc;mara, Craig Macdonald  
  [[Paper]](http://ceur-ws.org/Vol-2409/docker02.pdf) [[Slides]](https://osirrc.github.io/osirrc2019/slides/docker02-slides.pdf)
- *Dockerizing Automatic Routing Runs for The Open-Source IR Replicability Challenge (OSIRRC 2019)*  
  Timo Breuer, Philipp Schaer  
  [[Paper]](http://ceur-ws.org/Vol-2409/docker03.pdf) [[Slides]](https://osirrc.github.io/osirrc2019/slides/docker03-slides.pdf)
- *University of Waterloo Docker Images for OSIRRC at SIGIR 2019*  
  Ryan Clancy, Zeynep Akkalyoncu Yilmaz, Ze Zhong Wu, Jimmy Lin  
  [[Paper]](http://ceur-ws.org/Vol-2409/docker04.pdf) [[Slides]](https://osirrc.github.io/osirrc2019/slides/docker04-slides.pdf)
- *A Docker-Based Replicability Study of a Neural Information Retrieval Model*  
  Nicola Ferro, Stefano Marchesin, Alberto Purpura,  Gianmaria Silvello  
  [[Paper]](http://ceur-ws.org/Vol-2409/docker05.pdf) [[Slides]](https://osirrc.github.io/osirrc2019/slides/docker05-slides.pdf)
- *Dockerizing Indri for OSIRRC 2019*  
  Claudia Hauff  
  [[Paper]](http://ceur-ws.org/Vol-2409/docker06.pdf) [[Slides]](https://osirrc.github.io/osirrc2019/slides/docker06-slides.pdf)
- *The OldDog Docker Image for OSIRRC at SIGIR 2019*  
  Chris Kamphuis, Arjen de Vries  
  [[Paper]](http://ceur-ws.org/Vol-2409/docker07.pdf) [[Slides]](https://osirrc.github.io/osirrc2019/slides/docker07-slides.pdf)
- *PISA: Performant Indexes and Search for Academia*  
  Antonio Mallia, Micha&lstrok; Siedlaczek, Joel Mackenzie, Torsten Suel  
  [[Paper]](http://ceur-ws.org/Vol-2409/docker08.pdf) [[Slides]](https://osirrc.github.io/osirrc2019/slides/docker08-slides.pdf)
- *ielab at the Open-Source IR Replicability Challenge 2019*  
  Harrisen Scells, Guido Zuccon  
  [[Paper]](http://ceur-ws.org/Vol-2409/docker09.pdf) [[Slides]](https://osirrc.github.io/osirrc2019/slides/docker09-slides.pdf)
- *BM25 Pseudo Relevance Feedback Using Anserini at Waseda University*  
  Zhaohao Zeng, Tetsuya Sakai  
  [[Paper]](http://ceur-ws.org/Vol-2409/docker10.pdf) [[Slides]](https://osirrc.github.io/osirrc2019/slides/docker10-slides.pdf)
  

### 10:30-11:00 Coffee Break

### 11:00-11:45 Breakout Group Discussion

### 11:45-12:30 General Discussion and Closing

### 12:30-13:30 Lunch




# Organization

## Program Committee

- Shane Culpepper, RMIT University, Australia
- Yixing Fan, Chinese Academy of Sciences (CAS), China
- Norbert Fuhr, University of Duisburg-Essen, Germany
- Faegheh Hasibi, Radboud University, The Netherlands
- Makoto P. Kato, University of Tsukuba, Japan
- Diane Kelly, University of Tennensee, USA
- Maria Maistro, University of Copenaghen, Denmark
- Raffaele Perego, ISTI, CNR, Italy
- Martin Potthast, Leipzig University, Germany
- Ian Soboroff, National Institute of Standards and Technology (NIST), USA
- Andrew Trotman, University of Otago, New Zealand
- Arjen P. de Vries, Radboud University, The Netherlands
- Justin Zobel, University of Melbourne, Australia



## OSIRRC 2019 Chairs

- Ryan Clancy, University of Waterloo, Canada
- Nicola Ferro, University of Padua, Italy
- Claudia Hauff, Delft University of Technology, The Netherlands
- Jimmy Lin, University of Waterloo, Canada
- Tetsuya Sakai, Waseda University, Japan
- Ze Zhong Wu, University of Waterloo, Canada

Contact: osirrc2019-organizers@googlegroups.com 




