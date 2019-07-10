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


# Call for Position Papers and Participation in the Challenge

We are soliciting two kinds of contributions from the community:

#### Participation in the replicability challenge and related "docker paper"

  We solicit participants who would be willing to contribute Docker images that encapsulate strong baselines as well as state-of-the-art techniques: examples include runs based on query expansion, entity annotations, and neural networks. In particular, we are actively soliciting involvement from researchers working on neural IR.
  
  Tentatively, our initial focus will be on newswire collections (since they are smaller and more manageable).

 These Docker images have to be accompanied by a paper describing the experience of a team in participating to the challenge.
  
#### Position papers

  We solicit perspective authors to submit position papers around the issues of replicability in the IR field, with a special focus on infrastructures to enable them.
  
  The goal of these papers is to further stimulate the discussion at the workshop and help shaping the path forward for the community.

All the papers will be reviewed by at least three members of the program committee.

All the accepted papers, both position and docker images papers, will be included in the OSIRRC 2019 proceedings in the [CEUR Workshop Proceedings](http://ceur-ws.org/) series, indexed by DBLP, Google Scholar, Scopus and others.

All the accepted papers will be given a presentation slot during the workshop.


# Paper Submission Guidelines

We invite submissions of:

* docker papers (up to 8 pages): describing the participation in the OSIRRC challenge; these papers can be submitted only by teams which have also submitted docker images

* position papers (up to 4 pages): discussing replicability and reproducibility challenges in IR,  with a special focus on infrastructures enabling them;

Submissions must be in English, in PDF format, and must use standard ACM SIGIR templates, available at [http://www.acm.org/publications/proceedings-template](http://www.acm.org/publications/proceedings-template) for both LaTeX and Word. 

Papers must report work that is not previously published, not accepted for publication elsewhere, and not currently under review elsewhere.

Papers should be submitted electronically conference submission system at: [https://easychair.org/conferences/?conf=osirrc2019](https://easychair.org/conferences/?conf=osirrc2019)

## Important Dates for Position Papers

Deadline time is 11:59 p.m. (anywhere in the world)

- Position papers: June 14, 2019
- Position papers notifications to authors: June 28, 2019
- Camera ready (position papers) due: July 5, 2019
- OSIRRC 2019, co-located with [SIGIR 2019](http://sigir.org/sigir2019/), Paris, France: July 25, 2019

## Important Dates for Docker Images and Docker Papers

Deadline time is 11:59 p.m. (anywhere in the world)

- Docker images submission deadline:  June 24, 2019
- Docker papers submission deadline:  June 28, 2019
- Docker papers notifications to authors: July 7, 2019
- Camera ready (docker papers) due: July 12, 2019
- OSIRRC 2019, co-located with [SIGIR 2019](http://sigir.org/sigir2019/), Paris, France: July 25, 2019


# Program

### 08:55-09:00 Welcome and Opening

### 09:00-09:30 OSIRRC Overview

- *Overview of the 2019 Open-Source IR Replicability Challenge (OSIRRC 2019)*  
  Ryan Clancy, Nicola Ferro, Claudia Hauff, Jimmy Lin, Tetsuya Sakai, Ze Zhong Wu.


### 09:30-10:30 Lightning Talks [4 minutes each]

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




