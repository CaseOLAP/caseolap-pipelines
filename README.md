### CaseOLAP Workflow

The Context-aware Semantic Online Analytical Processing pipeline (CaseOLAP), was developed in 2016 by Fangbo Tao et.al. CaseOLAP successfully quantifies user-defined phrase-category relationships through analysis of textual data.

CaseOLAP workflow presents data preprocessing (i.e., downloading and parsing text documents), indexing and searching with Elasticsearch, creating a functional document structure called Text-Cube and quantifying phrase-category relationships using the core CaseOLAP algorithm.

Data preprocessing generates key-value pairs for all documents involved. As an example, a key may refer to the document PMID, while a value may refer to different document metadata. Preprocessed data is rearranged by indexing and searching for an entity count, which further facilitates the CaseOLAP score calculation. Obtained raw CaseOLAP results can be taken to integrative analysis including dimensionality reduction, clustering, temporal and geographical analysis, as well as the creation of a graphical database which enables semantic mapping of the documents .

<h2>Pipelines</h2>

<ul>
                    <li> <a href="pipelines/Download.html" target="_blank"> Downloading and Data Extraction </a> </li>
                    <li> <a href="pipelines/Parsing.html" target="_blank"> Data Parsing Pipeline </a> </li>
                    <li> <a href="pipelines/Indexing.html" target="_blank"> Indexing and Search with Elasticsearch</a></li>
                    <li> <a href="pipelines/TextCube.html" target="_blank"> Text-Cube Creation </a></li>
                    <li> <a href="pipelines/EntityCount.html" target="_blank"> Entity Count </a></li>
                    <li> <a href="pipelines/CaseOLAP.html" target="_blank"> CaseOLAP Calculation </a> </li>
                </ul>
                <h2>Data Samples</h2>
                <ul>
                    <li> <a href="data/extracted-data-sample.xml" target="_blank"> Extracted Data Sample </a> </li>
                    <li> <a href="data/parsed-data-sample.json" target="_blank"> Parsed Data Sample </a> </li>
                    <li> <a href="data/age-group-sample.csv" target="_blank"> Age group CaseOLAP score Sample </a> </li>
                    <li> <a href="data/PMID-to-entity-count-mapping-sample.txt" target="_blank"> PMID to entity count mapping Sample </a> </li>
                </ul>
