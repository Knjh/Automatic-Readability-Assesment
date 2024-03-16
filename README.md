# Automatic Readability Assessment 

## Overview
The Readability Assessment is a Python-based application designed to evaluate the readability of text passages. It incorporates various readability metrics and semantic features to provide insights into the complexity of educational content. This  is particularly useful for educators and content creators to ensure that text materials are appropriately tailored to the target audience's reading level.

## Features
- **Readability Assessment:** Calculate readability metrics such as Flesch Reading Ease score, Automated Readability Index (ARI), Flesch-Kincaid Grade Level, etc.
- **Subject-wise Analysis:** Analyze text passages based on different subjects (English, Science, Biology, Social Science).
- **Class-wise Analysis:** Categorize text passages according to academic classes (Class 6, Class 7, etc.).
- **Semantic and Syntactic Features:** Utilize advanced linguistic features like average word count per sentence, average syllables per word, type-token ratio (TTR), and average parse tree height for comprehensive readability analysis.
- **Dataset Creation:** Includes a detailed process for creating the dataset used for model training and evaluation, involving data extraction from NCERT books and organization into a structured format.

## Dataset Creation
The dataset used for training and evaluation is created from NCERT books for classes 6 to 12. The process involves the following steps:
- Extract text data from NCERT books for English, Science, Biology, and Social Science subjects.
- Split the extracted text into sentences.
- Organize the sentences into separate files for each class and subject.
- Merge the separate files into a single dataframe for further processing.
