This project contains the Concept-based Integer Linear Programming (ILP) single-document summarization system described in the paper [1].
	
The release includes code for:

	1. Reading the articles from the CNN corpus described at [2]:
				
	2. Pre-Processing the textual documents using the Stanford CoreNLP (https://stanfordnlp.github.io/CoreNLP/).
	
	3. Extracting bigrams as the notion of concepts.
	
	3. Measuring the concepts weighing using the proposed method described at [1].
	
	5. Applying the Entity Graph model [3]. We use the implementation made available by Karin Sim (https://github.com/karins/CoherenceFramework).
	
	5. Modeling the sentence selection process as an optimization process using an ILP model.

Setup

	The project was develop using the Eclipse IDE and Java version 10. All dependencies are included in the project.
	
	It is possible to run a predefined example of the system using the ConceptILPSingleSummarizerAppTestTxt.
	
	Besides, it is possible to run the ConceptILPSingleSummarizerAppTest to summarize articles from the CNN corpus. It is required to change the directory path where the CNN XML articles are stored and the directory where the summaries will be saved.
	
References

	[1] H. Oliveira, R. Lima, R. D. Lins, F. Freitas, M. Riss, and S. J. Simske. A concept-based integer linear programming approach for single-document summarization. In: 5th Brazilian Conference on Intelligent Systems, BRACIS 2016, Recife, Brazil, October 2016, pp. 403–408.

	[2] LINS, R. D.; OLIVEIRA, H. T. A.; CABRAL, L. S.; ANTUNES, J. B.; Mello, R. F. L.; SILVA, G. F. P. E.; LIMA, R. J.; SIMSKE, S. J. The CNN-Corpus: A Large Textual Corpus for Single-Document Extractive Summarization. In: ACM Symposium on Document Engineering, 2019, Berlin. The 19th ACM Symposium on Document Engineering, 2019. (To appear).

	[3] C. Guinaudeau and M. Strube. Graph-based local coherence modeling. In: 51st Annual Meeting of the Association for Computational Linguistics, August 2013, pp. 93–103.