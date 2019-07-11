# Vision

The importance of repeatability, replicability, and reproducibility is broadly recognized in the computational sciences, both in supporting desirable scientific methodology as well as sustaining empirical progress. Recent [ACM guidelines](https://www.acm.org/publications/policies/artifact-review-badging) precisely define the relevant terms as follows:

- Repeatability (same team, same experimental setup): a researcher can reliably repeat her own computation.

- Replicability (different team, same experimental setup): an independent group can obtain the same result using the author’s own artifacts.

- Reproducibility (different team, different experimental setup): an independent group can obtain the same result using artifacts which they develop completely independently.

These guidelines are also being adopted by the SIGIR community, which has recently established [a task force to determine how to implement them for IR](http://sigir.org/wp-content/uploads/2018/07/p004.pdf).

OSIRRC 2019 aims to address the replicability challenge for ad hoc document retrieval. That is, how can we make it easy for others to replicate our results? Trivially, replicability ensures repeatability, and is a stepping stone toward reproducibility.

Our vision is to build Docker-based infrastructure for replicating results on standard ad hoc test collections (newswire, web, etc.). A future paper, for example, might be paired with a Docker image whose execution yields the results presented in the paper. However, to maximize the impact of these Docker images, the following would be desirable:

1. These Docker images should follow some common specification, with "hooks" for indexing, training, retrieval, etc. The development of this specification should involve a community process.

2. There needs to be evaluation infrastructure that calls the "hooks" above for multiple images to perform aggregation and analyses, for example, to populate a leaderboard or to evaluate the images on a blind held-out test set.

Participants in OSIRRC 2019 will help build consensus on the Docker specifications and contribute Docker images that conform to the agreed-upon specifications. The organizers, potentially with help from the community, will build the evaluation infrastructure.

Interested individuals and teams are requested to email osirrc2019-organizers@googlegroups.com for more details or directly join the Google groups osirrc2019@googlegroups.com.


# Contributions

We are solicited two kinds of contributions from the community:

#### Participation in the replicability challenge and related "docker paper"

  Docker images that encapsulate strong baselines as well as state-of-the-art techniques: examples include runs based on query expansion, entity annotations, and neural networks. 
  
 These Docker images have to be accompanied by a paper describing the experience of a team in participating to the challenge.
  
#### Position papers

  Position papers around the issues of replicability in the IR field, with a special focus on infrastructures to enable them.
  
  The goal of these papers is to further stimulate the discussion at the workshop and help shaping the path forward for the community.


Here, you can find full details about [Submission Instructions and Important Dates](https://osirrc.github.io/osirrc2019/cfp.html).


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


### 09:30-10:30 Lightning Talks [4 minutes each]


##### Position Papers

- *STELLA: Towards a Framework for the Reproducibility of Online Search Experiments*  
  Timo Breuer, Philipp Schaer, Narges Tavalkolpoursaleh, Benjamin Wolff, Bernd M&uuml;ller
- *Let's measure run time! Extending the IR replicability infrastructure to include performance aspects*  
  Sebastian Hofst&auml;tter, Allan Hanbury
- *Reproducible IR needs an (IR) (Graph) Query Language*  
  Chris Kamphuis, Arjen P. de Vries

##### Docker Papers

- *Entity Retrieval Docker Image for OSIRRC at SIGIR 2019*  
  Negar Arabzadeh
- *Dockerising Terrier for The Open-Source IR Replicability Challenge (OSIRRC 2019)*  
  Arthur Barbosa C&acirc;mara, Craig Macdonald
- *Dockerizing Automatic Routing Runs for The Open-Source IR Replicability Challenge (OSIRRC 2019)*  
  Timo Breuer, Philipp Schaer
- *University of Waterloo Docker Images for OSIRRC at SIGIR 2019*  
  Ryan Clancy, Zeynep Akkalyoncu Yilmaz, Ze Zhong Wu, Jimmy Lin
- *A Docker-Based Replicability Study of a Neural Information Retrieval Model*  
  Nicola Ferro, Stefano Marchesin, Alberto Purpura,  Gianmaria Silvello
- *Dockerizing Indri for OSIRRC 2019*  
  Claudia Hauff
- *The OldDog Docker Image for OSIRRC at SIGIR 2019*  
  Chris Kamphuis, Arjen de Vries
- *PISA: Performant Indexes and Search for Academia*  
  Antonio Mallia, Micha&lstrok; Siedlaczek, Joel Mackenzie, Torsten Suel
- *ielab at the Open-Source IR Replicability Challenge 2019*  
  Harrisen Scells, Guido Zuccon
- *BM25 Pseudo Relevance Feedback Using Anserini at Waseda University*  
  Zhaohao Zeng, Tetsuya Sakai
  

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




