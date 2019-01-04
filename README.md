### CaseOLAP Workflow

The Context-aware Semantic Online Analytical Processing pipeline (CaseOLAP), was developed in 2016 by Fangbo Tao et.al. CaseOLAP successfully quantifies user-defined phrase-category relationships through analysis of textual data.

CaseOLAP workflow presents data preprocessing (i.e., downloading and parsing text documents), indexing and searching with Elasticsearch, creating a functional document structure called Text-Cube and quantifying phrase-category relationships using the core CaseOLAP algorithm.

Data preprocessing generates key-value pairs for all documents involved. As an example, a key may refer to the document PMID, while a value may refer to different document metadata. Preprocessed data is rearranged by indexing and searching for an entity count, which further facilitates the CaseOLAP score calculation. Obtained raw CaseOLAP results can be taken to integrative analysis including dimensionality reduction, clustering, temporal and geographical analysis, as well as the creation of a graphical database which enables semantic mapping of the documents .


Pipelines
Downloading and Data Extraction
Data Parsing Pipeline
Indexing and Search with Elasticsearch
Text-Cube Creation
Entity Count
CaseOLAP Calculation
Data Samples
Extracted Data Sample
Parsed Data Sample
Age group CaseOLAP score Sample
PMID to entity count mapping Sample
