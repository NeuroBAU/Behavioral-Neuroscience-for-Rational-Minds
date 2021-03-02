# Behavioral-Neuroscience-for-Rational-Minds #

![alt text](../img/dualism.jpg)

## Course description ##

The main goal of the course [Spring semester 2020 @ University of Lausanne, Switzerland] is to support students in the development of the mindset necessary to both (i) design unbiased experiments and (ii) obtain reproducible results in behavioral neuroscience. To this end, the course will take advantage of a modern framework derived from the field of artificial intelligence to rationalize and operationalize complex concepts in behavioral neuroscience. During the course students will learn a system that eases the transition from traditional behavioral assays to computational behavioral studies that take advantage of modern in-vivo imaging/recording techniques in freely-moving animals. The course provides a basic introduction to open-source / free softwares for running estimation statistics, power/sample size calculations, data extraction from graphs, and video/frame analysis. An introduction to basic concepts of Machine learning will get students started in the frame-by-frame behavior classification. An introduction to the analysis of neural signals time-locked to behavioral measures will be provided.

The main goal of the course is to support students in the development of a mindset necessary to: (i) design unbiased experiments and (ii) obtain reproducible results in behavioral/systems neuroscience. In addition, the course is intended to be a first exposure to basic concepts in machine learning/artificial intelligence and how these approaches support the analysis of behavioral data.

> **The course experienced an abrupt disruption in March 2020 due to  the COVID-2019 pandemic. As a consequence of this disruption, the course has been redesigned to fit the "online/remote" learning model.**

Let's keep in mind that "every cloud has a silver lining"! In future years this course will be composed of an introductory in person / face-to-face lesson followed by a series of online courses tutorials. The course will end with a final 3-hour face-to-face workshop aimed at  assessing/refining what students have learned from the online sessions.



**Part-1.** In the first part (interactive lecture) we provide an introduction to behavioral neuroscience in the context of cognitive science. David Marr’s 3-level analysis together with the conceptualization of artificial agents will be introduced. These concepts will provide a robust framework to address questions at the neural level using a behavioral approach.

**Part-2.** In the second (hands-on) part a behavioral experiment will be developed from scratch. Students will learn (i) strategies to access relevant information in Pubmed, (ii) how to calculate the expected effect size, desired power and sample size and (iii) experimental design and data analysis specifically tailored to behavioral experiments. This part will be complemented with an introduction/tutorial to both free and/or open source software commonly used in behavioral neuroscience studies (e.g. statistical power analyses, data extraction, estimation statistics)

**Part-3.** Students will be trained on a free software for machine learning and  data mining. Using data collected from a real behavioral experiments,  students will learn how to find the best data representation to perform  frame-by-frame behavior recognition using machine learning.

The overarching goal of this module is to move from traditional behavioral experiments where overall statistics of the behavior are collected (e.g. cumulative time spent in the center of an open arena zone) to more dynamic analyses where behavior is time-locked to neural signals.



## List of resources ##

## SESSION 1 - INTRODUCTION TO COGNITIVE & BEHAVIORAL SCIENCE (HISTORY & THEORIES) ##

#### Matching neural states and behavioral states in experimental neuroscience requires a top-down approach ####

* [Krakauer, J.W., Ghazanfar, A.A., Gomez-Marin, A., MacIver, M.A., and Poeppel, D. (2017). Neuroscience Needs Behavior: Correcting a Reductionist Bias. Neuron 93, 480–490.](https://www.sciencedirect.com/science/article/pii/S0896627316310406)

#### Proposed statement about modern systems neuroscience ####

* [The Modern Neuroscience Statement - Google Docs](https://docs.google.com/document/d/1Lo0rVNMUrW68tzo2KIpxYqNV9y_tmz6ipbF8cNwL4j8/)

#### Theory of mind imposes a limit to the inferences we make from observed / manifest behavior. The experiment of Heider and Simmel shows that we may attribute behavioral and mental states even to inanimate objects ####

* [Heider, F., and Simmel, M. (1944). An Experimental Study of Apparent Behavior. The American Journal of Psychology 57, 243.](https://www.jstor.org/stable/1416950) Watch the video here:  https://www.youtube.com/watch?v=76p64j3H1Ng

#### Introduction to the concept of mental representation - you need a strong stomach to digest these very dense pages ####

* [Pylyshyn, Z.W. (1989). Computation and cognition: toward a foundation for cognitive science (Cambridge, Mass.: MIT Press).](https://www.amazon.com/Computation-Cognition-Foundation-Cognitive-Science/dp/026266058X)

#### Introduction to cognitive science - Tracing the origin of the study of the mind #### 

* [Bermúdez, J.L. (2014). Cognitive science: an introduction to the science of the mind (Cambridge: Cambridge University Press).](https://www.amazon.com/Cognitive-Science-Introduction-Mind/dp/1107653355)

#### Behavior is supported by multiple, concurrent actions ####

* [Lashley, K.S. The Problem of Serial Order in Behavior.](http://www.s-f-walker.org.uk/pubsebooks/pdfs/The_Problem_of_Serial_Order_in_Behavior.pdf)

#### Cognitive revolution in the words of scientists that lived and contributed to it ####

* [Alan Baddeley on the cognitive revolution - YouTube](https://www.youtube.com/watch?v=wyfEETtWgCY)
* [Bower, G.H. (2008). The Evolution of a Cognitive Psychologist: A Journey from Simple Behaviors to Complex Mental Acts. Annual Review of Psychology 59, 1–27.](https://www.annualreviews.org/doi/abs/10.1146/annurev.psych.59.103006.093722)
* [Miller, G.A. (2003). The cognitive revolution: a historical perspective. Trends in Cognitive Sciences 7, 141–144.](https://www.cs.princeton.edu/~rit/geo/Miller.pdf)

#### Introduction to the fundamentals of cognitive psychology - interesting historical reading, I found particularly interesting the concept of "memory cell". Posner is not referring to an actual cell, but rather to a portion of space in a memory system. Influences from computer science and Hebb's ideas are particularly relevant #### 

* [Posner, M.I. (1973). Cognition: an introduction (Glenview, Ill: Scott, Foresman).](https://www.amazon.com/Cognition-Introduction-Foresman-Psychological-Concepts/dp/0673078604)

#### The concept of neural ensembles, interesting links to Lashley's ideas, and frictions between behaviorism, cognition, localizationism ####
_The original book can still be found on Amazon_

* [Hebb, Donald (1949). The Organization of Behavior. New York: Wiley & Sons.](https://www.amazon.com/Organization-Behavior-Neuropsychological-Theory/dp/0805843000)
* [Nadel, L., and Maurer, A.P. Recalling Lashley and Reconsolidating Hebb. Hippocampus 0.](https://onlinelibrary.wiley.com/doi/abs/10.1002/hipo.23027)

#### Merging levels of explanation in cognitive and neural science ####
_The original book is some kind of rarity. The new edition (2010) is available_

* [Marr, D. (1982). Vision: a computational investigation into the human representation and processing of visual information (Cambridge, Mass: MIT Press).](https://www.amazon.com/Vision-Computational-Investigation-Representation-Information/dp/0262514621)

#### A gentle and clever introduction to neural networks and the concept of representation in connectionist models - see chapter 4 ####

* [Gluck, M.A., and Myers, C.E. (2001). Gateway to memory: an introduction to neural network modeling of the hippocampus and learning (Cambridge, Mass: MIT Press).](https://www.amazon.com/Gateway-Memory-Introduction-Hippocampus-Neuropsychology/dp/0262571528)

#### Connectionism and PDP - very interesting read if you're interested in the origins of modern deep learning. Inspiring depictions of the network models show actual synapses connecting the units. Synergies between neuroscience and artificial neural networks ####

* [Rumelhart, D.E., and McClelland, J.L. (1986). Parallel distributed processing: explorations in the microstructure of cognition (Cambridge, Mass: MIT Press).](https://dl.acm.org/citation.cfm?id=104279)
* [Garson, J. (2018). Connectionism. In The Stanford Encyclopedia of Philosophy, E.N. Zalta, ed. (Metaphysics Research Lab, Stanford University)](

#### How the application of concepts derived from Deep learning (Objective function, Learning rule, and Architecture) may lead to novel discoveries in experimental neuroscience ####

* [A deep learning framework for neuroscience](https://www.nature.com/articles/s41593-019-0520-2)

#### What is connectionism?
* https://plato.stanford.edu/entries/connectionism/





## Session 2 - DEVELOPING SKILLS IN BEHAVIORAL NEUROSCIENCE ##

**Checklist of the careful experimenter:**

- Nobody has done what I am planning to do
- I have the best conditions to detect the effect size
- I am sure to measure what I plan to measure



#### Introduction to the concepts of Agent and Task environment ####

* [Web of Science](https://apps.webofknowledge.com/)

#### Exerting full control on stimulus delivery in the social domain ####

* [Atsumi, T., Ide, M., and Wada, M. (2018). Spontaneous Discriminative Response to the Biological Motion Displays Involving a Walking Conspecific in Mice. Front. Behav. Neurosci. 12.](https://www.frontiersin.org/articles/10.3389/fnbeh.2018.00263/full)
* S. Heath, et al. PiRat: An autonomous rat-sized robot as a social companion for studying social behavior in rats using real-time tracking. _Program No. 520.02. 2018 Neuroscience Meeting Planner. San Diego, CA: Society for Neuroscience, 2018. Online._

## Session 3.1 - REPRODUCIBILITY ##

#### Reproducibility in Science: a survey of 1500 scientists ####

* [Baker, M. (2016). 1,500 scientists lift the lid on reproducibility. Nature 533, 452–454.](https://www.nature.com/news/1-500-scientists-lift-the-lid-on-reproducibility-1.19970)

#### Is there a lack of quality in behavioral neuroscience research? ####

* [Bespalov, A., and Steckler, T. (2018). Lacking quality in research: Is behavioral neuroscience affected more than other areas of biomedical science? Journal of Neuroscience Methods 300, 4–9.](https://www.sciencedirect.com/science/article/pii/S0165027017303746)

#### Reproducibility in rodent behavioral neuroscience. A thorough analysis of a behavioral assay (Novel object recognition) reveals the pitfalls and possible solutions to extreme variability in test procedures ####

* [Gulinello, M., Mitchell, H.A., Chang, Q., Timothy O’Brien, W., Zhou, Z., Abel, T., Wang, L., Corbin, J.G., Veeraragavan, S., Samaco, R.C., et al. (2018). Rigor and reproducibility in rodent behavioral research. Neurobiology of Learning and Memory.](https://www.sciencedirect.com/science/article/pii/S1074742718300017)

#### Checklists for preparing and reporting your research project ####

* [PREPARE guidelines: the checklist](https://norecopa.no/media/7864/prepare_checklist_english.pdf)

* [ARRIVE guidelines: the checklist](https://www.nc3rs.org.uk/sites/default/files/documents/Guidelines/NC3Rs%20ARRIVE%20Guidelines%202013.pdf)

## Session 3.2 - STANDARDIZED BEHAVIORAL ASSAYS ##

* [Crabbe, J.C. (1999). Genetics of Mouse Behavior: Interactions with Laboratory Environment. Science 284, 1670–1672.](http://psych.colorado.edu/~carey/pdfFiles/MouseLab_Crabbe.pdf)

* [Touchscreen: equipment](https://campdeninstruments.com/products/bussey-saksida-touch-screen-chamber-mouse)

* [Touchscreen: video](https://www.youtube.com/watch?v=JBh5BJ-kUuA&t=2308s)

* [Phenotyper and Cogniton wall for cognitive flexibility studies](https://www.sylics.com/bioinformatics/cognitionwall/)

* [Intellicage: video](https://www.youtube.com/watch?v=fz6_nCbIs6Q)

* [Phenoworld](https://www.tse-systems.com/product-details/phenoworld)

* [Schaefer, A.T., and Claridge-Chang, A. (2012). The surveillance state of behavioral automation. Current Opinion in Neurobiology 22, 170–176.](https://www.sciencedirect.com/science/article/pii/S0959438811001942?via%3Dihub)

## Session 3.3 - SOFTWARES & APPROACHES FOR BEHAVIORAL DATA EXTRACTION + ANALYSIS ##

#### OpenBehavior: a website collecting resources for behavioral neuroscience research ####

* [OpenBehavior](https://edspace.american.edu/openbehavior/)

#### DeepLabCut - deep learning approach to markerless animal pose estimation ####

* [Mathis, A., Mamidanna, P., Cury, K.M., Abe, T., Murthy, V.N., Mathis, M.W., and Bethge, M. (2018). DeepLabCut: markerless pose estimation of user-defined body parts with deep learning. Nature Neuroscience.](https://www.nature.com/articles/s41593-018-0209-y)

* [GitHub page of DeepLabCut](https://github.com/AlexEMG/DeepLabCut)

* [Using DeepLabCut for 3D markerless pose estimation across species and behaviors](https://www.biorxiv.org/content/early/2018/11/24/476531)*

## Extra ##

#### The computational challenges we face everyday in our life and how algorithms help us cope with them. Do the study and application of these algorithms inform research on cognition? ####

* [Christian, B., and Griffiths, T. (2017). Algorithms to live by: the computer science of human decisions (London: William Collins).](https://www.amazon.com/Algorithms-Live-Computer-Science-Decisions/dp/1627790365)

#### Are animals capable of detecting statistical patterns in the environment? ####

* [Santolin, C., and Saffran, J.R. (2017). Constraints on Statistical Learning Across Species. Trends in Cognitive Sciences.](https://www.sciencedirect.com/science/article/pii/S1364661317302231)

#### Representations may not be necessary to develop intelligent systems ####

* [Brooks, R.A. (1991). Intelligence without representation. Artificial Intelligence 47, 139–159.](https://people.csail.mit.edu/brooks/papers/representation.pdf)

#### Another paper highlighting the synergies between biological and artificial neural networks - the paper is focused on learning in Drosophila circuits ####

* [Srinivasan, S., Greenspan, R.J., Stevens, C.F., and Grover, D. (2018). Deep(er) Learning. The Journal of Neuroscience 38, 7365–7374.](http://www.jneurosci.org/content/early/2018/07/13/JNEUROSCI.0153-18.2018)
