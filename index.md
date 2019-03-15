# Call for Participation

Organizers: Nicola Ferro, Claudia Hauff, Jimmy Lin, and Tetsuya Sakai

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

Tentatively, our initial focus will be on newswire collections (since they are smaller and more manageable). We solicit participants who would be willing to contribute Docker images that encapsulate strong baselines as well as state-of-the-art techniques: examples include runs based on query expansion, entity annotations, and neural networks. In particular, we are actively soliciting involvement from researchers working on neural IR.

Interested individuals and teams are requested to email osirrc2019-organizers@googlegroups.com for more details or directly join the Google groups osirrc2019@googlegroups.com. We are currently in the process of gathering potential participants and initial expressions of interest, after which discussion will commence on the mailing list to converge towards the specifications of the Docker images as described above.

The tentative timeline is as follows:

- Immediately: expressions of interest by joining mailing list
- Shortly thereafter: mailing list discussions on Docker specifications
- mid-April: final Docker specifications available
- June: Docker images due from participants
- June-July: organizers execute and analyze Docker images from participants
- July 25: workshop at SIGIR

The workshop itself at SIGIR will be devoted to discussing the results of this exercise and the path forward for the community. Although this replicability challenge is the "main event" of the workshop, we are considering the solicitation of position papers to round out the agenda, in which case the deadline will align with other SIGIR workshops in early May. We are also considering the publication of lightweight proceedings (containing, for example, replication reports) via CEUR-WS.
