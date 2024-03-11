## Research Topic Recommender System
### Abstract
With exponentially growing literature amounts, it has become increasingly impractical to create a complete literature review. This necessitates the need for automated search for relevant information with regards to modern research. The designed system is able to generate relevant and related topics from a given seed topic enabling the researcher to explore these in more detail. Moreover a functionality has been provided to automatically extract relevant keywords from the provided abstract. Finally, an internet based user interface is created for easy access and retrieval of information.

### Dataset Description
<img width="284" alt="image" src="https://github.com/RiddhiTripathi/topic-recommender-system/assets/36181595/4d47619a-dd67-4103-ad4e-b95915c87a7b">
<img width="280" alt="image" src="https://github.com/RiddhiTripathi/topic-recommender-system/assets/36181595/366cf1fe-097c-4400-a54b-85945b9feb23">


### Expected Input :
• Research Topic
• Research paper abstract

### Software & Hardware :
• Windows 7 Workstation with 16GB of RAM
• DBLP-Citation-network V11 Dataset from Aminer.org
• MongoDB
• Python
• SciKit Learn
• MLxtend
• Flask

### Assumptions & Constraints :
• The topic search is limited by the topics recorded within the particular database.
• A subsample of about 1,00,000 papers was taken from the original database to apply the keyword
prediction from the abstract and FP-Growth based search due to practical time limit constraint.

### System Workflow
#### Normal Search

<img width="284" alt="image" src="https://github.com/RiddhiTripathi/topic-recommender-system/assets/36181595/181d6696-8e37-4f8a-a157-712f8706dfb3">

#### Advance Search
<img width="277" alt="image" src="https://github.com/RiddhiTripathi/topic-recommender-system/assets/36181595/0d4eeb87-5fc2-45bc-bafd-2fdff1a33777">

#### Abstract Based Topic Search
<img width="281" alt="image" src="https://github.com/RiddhiTripathi/topic-recommender-system/assets/36181595/47824eb1-b1a8-44a6-a21d-e8354a5d29a1">

#### Conclusion
Thus we can say that, the designed system fulfills the objective of research topic recommendation
by involving multiple strategies like node degree and edge weight or the FP-Growth algorithm. Another tool
provided to recommend topics based on abstract data is also included which has a good accuracy. Although
there are multiple avenues for improvement such as increasing data size, query coverage, more structured
web app, etc we believe that this system will be able to provide good value for it's users.

#### Links and References
• https://www.aminer.cn/citation
• https://clarivate.com/webofsciencegroup/solutions/web-of-science/
• https://www.citnetexplorer.nl/
• https://www.microsoft.com/en-us/research/project/microsoft-academic-graph/
• https://en.wikipedia.org/wiki/Centrality
• https://en.wikipedia.org/wiki/Association_rule_learning#FP-growth_algorithm
• https://scikit-learn.org/stable/
• http://rasbt.github.io/mlxtend/
• https://www.palletsprojects.com/p/flask/



