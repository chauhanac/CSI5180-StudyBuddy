Data Extraction - This file checks for PDF files (course content) within a folder and extracts text and source URLs. Creates datasets further used for the QA system. (Requires a folder with all course PDFs)

Semantic Similarity Approach - This file utilizes the final_data.csv file. It uses text data divided into chunks and applies the semantic method to generate relevant answers for domain-specific questions.

Baseline Outputs-1 - This file implements the baseline TF-IDF approach for retrieval augmented QA.

final_data.csv - This file contains the text data divided into chunks of 300 words in the format: [text, chunk size, grammar score]
