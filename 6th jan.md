# The Golden Age of Software Architecture: A Comprehensive Survey (2006) #

*	The paper is a survey of the current state (2006) of research in Software Architecture.

*	The paper examines the path that Software Architecture has taken to reach "The Golden Age", this is explanied using six typical phases taking 15-20 years
	as explained by Samuel Redwine and William Riddle in Software technology maturation.

*	The different phases of the development of Software Architecture are recognized using the rate of paper citations.

*	In the Basic research phase several foundational ideas were already in place as these had already travelled their own 15-20 year period. In this period the concepts of information-hiding, data types, and deliberately-designed specialized software structures to solve particular problems in specific fields, were created and contributed to the idea of software elements as black boxes.

*	In the Concept formulation phase the architecture description language was developed in parallel with programming languages sometimes even as an integrated part of that development.
	The understanding of the relationship between architectural decisions and quality validated this as a useful way of risk reduction.
	This period also proved architectual views as a working concept and workshops and seminars were created for the community.

*	In the development and extension phase the groundwork for the acme language began with the goal of creating a framework to move information between architecture description languages.
	This phase also began the refinment of the taxonomies and languages, and actual roadmaps and conferences were created.

*	In the internal enhancement and exploration phase, a few formal analysis of system designs had been done in one of these systems inconsistencies were found before implementation, saving extensive redesign of the system. Analysis and evaluation emerged and gave way for ATAM. Books that turned research into pratice were also released in this period thereby signaling a new kind of maturation of Sfotware Architecture.

*	In the external enhancement and exploration phase serveral areas had matured to a level were they could be used outside thier developer group. UML was developed and became the industry standard ADL. This period also includes the rise of object-oriented programming languages that conforms with the black box thinking.

*	In the popularization phase Software Architecture products were commercialized, fully integrated development systems were created (like DotNet), and standards for component families and interfaces had been in use for several years. The teaching of subjects in software architecture are done on a wider scale and were moved from graduate to under-graduate courses. In this phase it is common to find the job title "software architech" at nearly any software company.

*	The paper then explains the current status of Software architecture, which includes off-the-shelf cerification programs, standard architectures, end-to-end lifecycle models, robust tools, commercial quality infrastructure and application layers, career tracks for software architects.

*	The paper recommend points on which to improve software architecture in the future, which includes topics such as; Finding the right language to repesent architectures, finding ways to assure conformance betwwen architecture and code, rethinking software testing, and developing architectural support for dynamic systems.

### Questions ###

*	The paper uses citation data to analyse the growth; are there any other ways that this could have been done?

*	As also mentioned in the paper, maturation of technology does not follow the steps defined by Redwine and Riddle completely; Why is it then important to use those steps for analysing the current status, and why are they formatted as closed off steps?

# Exploring the duality between product and organizational architectures: A test of the "mirroring" hypothesis (2012) #

*	The paper explores the "mirroring" hypothesis, which is the idea that a product will reflect the organization by which it is build.

*	The mirroring hypothesis is tested by comparing the source code of open-source projects to that of a program with nearly the same features build by a single organization.

*	The papers hypothesis is that a program build by the open-source community is much more modular than one build by a large cooperation.

*	The paper compares five different programs (of similar size) of which one is created by a cooperation and one is created by the open-source community, the paper finds that in four out of five open-soruce projects, the propagation cost of open-soruce programs are much lower than with programs build by a single organization. In one of the five cases (Gnumeric) the propagation cost is as high as the one build by an organization, it is argued however that the Gnumeric program is actually only build by a few people with a much higher rate of communication than in other open-soruce projects.

*	The paper finds that the "mirroring" hypothesis holds for software development, but also argue that it does not necessarily apply to other lines of work.

### Questions ###

*	Are there any perfomance implications to the modular work-flow of open source projects?

*	More and more cooperations are creating open-source projects, that they also use for their own commercial products (Apple (Swift), Google (Android), Netflix (Streaming technologies), Facebook, and so on.). What are the positive and negative sides of doing this? Does this also necessarily change the internal structure of the companies developing these projects?