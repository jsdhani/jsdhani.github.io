# Data Scientist

**Reach out to me at:** jsdhani@cs.toronto.edu<br />
<a href="https://www.linkedin.com/in/jaspreet-singh-dhani/"> LinkedIn Profile </a><br /><br />

Hello there, and thank you for visiting my personal webpage! This space is a reflection of my commitment towards crafting a career in Artifical Intelligence with special focus on Natural Lanaguage Processing and Recommender Systems. It's not just a collection of my past projects and accolades; rather it's a timeline of my growth, my exploration, and my unwavering passion for technology. Whether you're a fellow student like me, a prospective employer, or simply someone intrigued by the endless possibilities of the digital world, you're in the right place. Take your time to peruse my work, and don't hesitate to reach out if you'd like to connect, collaborate, or simply share your thoughts. 

## Education
- **MSc, Applied Computing**, University of Toronto <br /> (_September 2022_ - _December 2023_)	<br /> **GPA: 4.0/4.0** <br /><u>COURSES TAKEN</u> <br /> <a href = "https://amfarahmand.github.io/IntroML-Fall2022/" >CSC2515 </a>: Introduction to Machine Learning <br /> <a href="http://www.cs.toronto.edu/~gpenn/csc485/"> CSC2501 </a>: Computational Linguistics <br /> <a href="http://www.cs.toronto.edu/~ashton/csc2552/"> CSC2552 </a>: Topics in Computational Social Science: AI, Data and Society <br /> <a href="http://www.cs.toronto.edu/~raeidsaqur/csc401/">CSC2511</a>: Natural Language Computing <br /> <u>MScAC APPLIED RESEARCH INTERNSHIP</u><br />Research project on applications of Machine Learning methods for Gherkin Test Case Prioritization<br /><u>ACADEMIC SUPERVISOR: </u><a href="https://www.eecg.utoronto.ca/~shuruiz/">Prof. Shurui Zhou</a>

- **MSc, Computer Science**, University of Delhi <br /> (_July 2019_ - _June 2021_) <br /> **CGPA: 9.59/10** <br /><u>ACADEMIC SUPERVISOR:</u> <a href="http://people.du.ac.in/~vbhatnagar/"> Prof. Vasudha Bhatnagar </a> <br /> <u>COURSE PROJECT</u> (in collaboration with <a href="https://research.ibm.com/publications/similar-cases-recommendation-using-legal-knowledge-graphs">IBM Global Remote Mentorship </a> under joint supervision of Mr. <a href="https://research.ibm.com/people/balaji-ganesan">Balaji Ganesan</a>) <br /> <a href="https://arxiv.org/abs/2107.04771">Similar Cases Recommendation Using Legal Knowledge Graphs </a>

- **BSc (Hons.), Computer Science**, University of Delhi <br /> (_July 2016_ - _June 2019_) <br />**CGPA: 9.37/10**

## Academic Awards
- **Vector Scholarship in Artificial Intelligence (2022-23)** <a href="https://vectorinstitute.ai/programs/scholarship/#:~:text=A%20%2417%2C500%20entrance%20scholarship%20awarded,path%20that%20is%20demonstrably%20AI%2D">(source)</a><br />_The Vector Insitute, Toronto_ <br />
  Merit-based entrance scholarship worth $17500 CAD for pursuing graduate degree in AI at an Ontario university.
- **Academic Excellence Award in Computer Science (2016-17)** <br />_University of Delhi, Delhi_ <br />
  First rank in academic performance in B.Sc (Hons.), Computer Science, out of 21 colleges under University of Delhi.

## Experience
**Research Intern, Data Science @ SOTI Inc. (_May 2023 - Present_)**
_Mississauga, Ontario_
- Enhancing the internal CI/CD BDD (Behavior Driven Development) test case selection algorithm using semantic features from Gherkin Scenarios and corresponding C# syntax structure for priority-driven test recommendations.


**AI/ML Engineer @ Scimox Pvt. Ltd. (_June 2021 - June 2022_)** <br />
_Gurugram, NCT-Delhi_ <br />
**Contribution: _BuddyKu News_** [[Link]](https://buddyku.com/), **_Vision+ Entertainment_** [[Link]](https://www.visionplus.id/)
- Developed implicit feedback collaborative filtering models that improved user engagement by 18% in Q1 2022.
- Leveraged Google Analytics attributes to tackle cold-start issues and develop the fall-back recommendation pipeline.
- Designed a 7M+ users network in AWS Neptune and utilized topological attributes to generate offline, near-line recommendations under 900ms.

**Research Intern, Text Mining @ DUCS (_June 2017 - July 2017)_** <br />
_University of Delhi, Delhi_
- Surveyed topic modeling methods considering \textit{Stanford Twitter Sentiment} data as the experimental benchmark.
- Utilized sentiment analysis and topic modeling methods to deliver a prototype for analyzing Twitter pages.

## Projects
### Similar Cases Recommendation Using Legal Knowledge Graphs
_**Dhani JS**, Bhatt R, Ganesan B, Sirohi P, Bhatnagar V. Similar cases recommendation using legal knowledge graphs. arXiv preprint arXiv:2107.04771. 2021 Jul 10._<br />
[View KGKDD-2021 Demo Paper](https://arxiv.org/abs/2107.04771)

A legal knowledge graph constructed from court cases, judgments,
laws and other legal documents can enable a number of applications
like question answering, document similarity, and search. While
the use of knowledge graphs for distant supervision in NLP tasks
is well researched, using knowledge graphs for downstream graph
tasks like node similarity presents challenges in selecting node
types and their features. In this demo, we describe our solution
for predicting similar nodes in a case graph derived from our legal
knowledge graph.

#### Contributions
- Derived the ontology for legal knowledge graph by a combination of manual process and topic modeling.
- Developed link prediction RGCN model using domain-specific features from 2200+ IPR documents.
- Achieved 5% improvement in AUC over pre-trained STANZA and spaCy entity recognition models.
- Our research received recognition at the KGKDD-2021 conference held in Singapore and has recently been accepted into the proceedings at the <a href="https://sites.google.com/view/sail-2023/call-for-papers?authuser=0">3rd Symposium for AI and Law</a>, held at IIIT-Hyderabad.

### Divide and Conquer: From Complexity to Simplicity for Lay Summarization
_Rochana Chaturvedi, Saachi ., **Jaspreet Singh Dhani**, Anurag Joshi, Ankush Khanna, Neha Tomar, Swagata Duari, Alka Khurana, and Vasudha Bhatnagar. 2020. Divide and Conquer: From Complexity to Simplicity for Lay Summarization. In Proceedings of the First Workshop on Scholarly Document Processing, pages 344–355, Online. Association for Computational Linguistics._ <br />
[View ACL Publication]([https://arxiv.org/abs/2107.04771](https://aclanthology.org/2020.sdp-1.40/))

We describe our approach for the 1st Computational Linguistics Lay Summary Shared Task CL-LaySumm20. The task is to produce non-technical summaries of scholarly documents. The summary should be within easy grasp of a layman who may not be well versed with the domain of the research article. We propose a two step divide-and-conquer approach. First, we judiciously select segments of the documents that are not overly pedantic and are likely to be of interest to the laity, and over-extract sentences from each segment using an unsupervised network based method. Next, we perform abstractive summarization on these extractions and systematically merge the abstractions. We run ablation studies to establish that each step in our pipeline is critical for improvement in the quality of lay summary. Our approach leverages state-of-the-art pre-trained deep neural network based models as zero-shot learners to achieve high scores on the task.

#### Contributions
- Analyzed the corpus for formulating the heuristic to split each scholarly article into subsections.
- Generated extractive summaries for the subsections using pre-trained BERT variants.
- Employed clustering algorithms over BERT embeddings to group semantically similar article subsections.
- Our shared task submission secured rank 2 of 356 in Rouge1-Recall at the CL-Laysumm Shared Task

### Influence of Community on Online User Decisions - an Analysis of the Impact of COVID-19 on Yelp Reviews
_University of Toronto, Department of Computer Science_ <br />
[View Project]([https://github.com/jsdhani/community_influence_yelp_reviews])

The COVID-19 pandemic observed a major upsurge in the adoption of virtual service mechanisms by multifarious offline businesses, especially restaurants and other food outlets. As a consequence, customers writing reviews during this period were left to judge restaurants solely based on their online experience. We suspect this to have significantly altered review dynamics with the increased reliance of a user on their community for making decisions online. In this observational study, we implement three distinct methodologies in an attempt to quantify the degree of community influence during the pandemic. We compare our findings with prior works in the field to draw inferences about the significance of a user’s community on online review platforms. Our findings reveal limited evidence of a shift in the influence of the community on user reviews, indicating that users writing reviews on an online experience write them based on their own experiences rather than their community.


### An Empirical Study of Supervised and Active Learning Methodologies for Classifying Research Papers
_University of Toronto, Department of Computer Science_ <br />
[View Project]([https://github.com/tiru-patel/Active-Learning-based-Research-Paper-Classification])

Document classification is one of the predominant tasks in Machine Learning,
that by and large involves the use of supervised methodologies to determine most
suitable categories for a given set of documents. In this project, we seek to conduct
an empirical study, that, in addition to the conventional machine learning methods,
experiments with active learning and semi-supervised methods for assorting a
mix of labelled and unlabelled computer science scholarly articles hosted on the
arXiV repository. We develop a solution using the gathered labelled data points,
by experimenting with various multi-class supervised learning models such as K
Nearest Neighbours, Naive Bayes, Random Forest, and Logistic Regression. We
also account for the issue of class imbalance, and thus conduct experiments to
determine a suitable oversampling methodology for addressing this concern. Lastly,
we extend beyond the conventional machine learning classification methods to
incorporate the concept of active learning, a type of iterative supervised learning,
used when the unlabelled data is in abundance.

### Against All Odds: A Machine Learning Perspective to Cold Start Feed Recommendations
[View Project]([https://github.com/jsdhani/FeedRecommender])

Cold Start is one of the biggest challenges in the realm of Recommender Systems. Be it recommending suitabl items to a new user, or pushing newly uploaded contents to the audience, cold start requires careful utilization of limited attributes to curate the recommendations. The proposed approach uses a combination of unsupervised learning, supervised learning, and rule based approaches to create a feature set and train a multi-label classification model for finding the most suitable subset of contents for a given user. The final recommendation set includes multiple recommendation types each accompanied with a fallback method to cover-up in case of failure in generating recommendations. The result is an end-to-end pipeline for assorted feed recommendations to users and contents with limited interactions. An emphasis has been paid to experimenting with exploration-exploitation capabilities in the implemented supervised models for result calibration. Lastly, a near-line recommendation layer was introduced to expedite user-specific result generation in under 1.7 seconds.

## Technical and Extra-Curricular Certifications
- <a href="https://www.udemy.com/course/recommender-systems/">Recommender Systems and Deep Learning</a> (August 2022)
- <a href="https://graphacademy.neo4j.com/"> Querying using Cypher- Neo4j GraphAcademy </a> (December 2021)
- <a href="https://www.edx.org/learn/language/universitat-politecnica-de-valencia-basic-spanish-1-getting-started?webview=false&campaign=Basic+Spanish+1%3A+Getting+Started&source=edx&product_category=course&placement_url=https%3A%2F%2Fwww.edx.org%2Fschool%2Fupvalenciax">Basic Spanish-Universitat Politècnica de València (UPV)</a> (September 2021)
- Ethical Hacking Certification (Delhi Technological University, 2017)
- <a href="https://www.coursera.org/learn/website-coding?specialization=website-development"> Responsive Web Development Basics- Goldsmiths, University of London</a> (August 2016)

## Volunteering
- **President**, <a href="https://ordinateurhrc.online/home">Ordinateur- The Computer Science Society</a>, Hans Raj College, University of Delhi (July 2017-December 2017)
- **General Member - Health Wing**, <a href="https://www.hansrajcollege.ac.in/NSS/home.html">National Service Scheme, Hans Raj Chapter</a>, University of Delhi (August 2016 - April 2017)
- **General Member**, <a href="https://www.hansrajcollege.ac.in/studentcorner/socities/societiesdetails/45">Spic Macay, Hans Raj Chapter</a>, University of Delhi (August 2016 - April 2017)

## Workshops and Competitive Engagements
- International Workshop on AI for Computational Social Systems (IIIT-Delhi, 2020)
- Online workshop on Data Analytics over COVID-19 Data (Finland Labs, 2020).
- ACM Winter School on Geometric Algorithms and Applications (IISER Pune, 2019)
- ACM Summer School on Cybersecurity and Data Analytics (IIIT-Delhi 2019)
- Introductory Machine Learning Methods using Anaconda (PGDAV College, University of Delhi, 2018)
- Blind Coding Competition (Deen Dayal Upadhayaya College, University of Delhi, 2016)
- Android Application Developement workshop (Hansraj College, University of Delhi, 2016)
