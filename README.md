# UoW_Data_Engineering
 Week 9 added:

# Tutorial Weeks 7–9: Unstructured Data Exploration, Preprocessing, and Storage

This repository contains materials and solutions for Weeks 7, 8, and 9 of the 5DATA005C Data Engineering module. These tutorials cover the exploration, preprocessing, and storage of unstructured data, specifically image and text data, using Python, MongoDB, and Google Colab.

## Week 7: Unstructured Data Exploration

### Topics Covered
1. Image Data Exploration:
   - Investigate basic image properties (format, size, and mode).
   - Extract metadata using EXIF.
   - Visualize pixel distributions through histograms.
   - Compute image statistics (mean, median, mode).
   - Perform extra exercises involving analysis of multiple images.

2. Text Data Exploration:
   - Examine textual properties (length, word count, specific content).
   - Visualize word distributions using word count and word clouds.
   - Additional exercises for analyzing and visualizing multiple documents.

## Week 8: Unstructured Data Preprocessing

### Topics Covered
1. Image Preprocessing:
   - Transformations: Resize, rotate, and denoise images individually and in sequence.
   - Feature Extraction:
     - Mean and norm intensity.
     - Shape features (area, perimeter, centroid, bounding box).
     - Combine extracted features into metadata files.
   - Annotation: Save metadata as JSON for image features.

2. Text Preprocessing:
   - Preprocessing Techniques:
     - Text normalization, tokenization, punctuation removal, stop word removal.
     - Stemming and lemmatization.
   - Vectorization:
     - Represent text numerically using Bag of Words (BoW) and TF-IDF.
   - Metadata Creation:
     - Explain vectorization and label processed text data.
     - Save metadata as a JSON file.

## Week 9: Unstructured Data Storage

### Topics Covered
1. **MongoDB Basics**:
   - Set up MongoDB Atlas, create clusters, and configure access.
   - Use `pymongo` to connect to MongoDB from Google Colab.

2. Image Data Storage:
   - Create a `CBIR` database with collections for:
     - Processed images.
     - Image metadata.
   - Store and query image metadata and processed images.

3. Text Data Storage:
   - Create an `NLP` database with collections for:
     - Processed documents.
     - Document metadata.
   - Store and query text metadata and processed documents.

4. Extra Activities:
   - Extend texture extraction techniques from Week 8 (e.g., GLCM features like contrast and dissimilarity).


## Repository Structure

1. /Week7_Images:  
   - Image files for Week 7 tasks.

2. /Week7_TextData:  
   - Text files for Week 7 tasks.

3. /Week8_Images:  
   - Image files for Week 8 preprocessing tasks.

4. /Week8_TextData:  
   - Text files for Week 8 preprocessing tasks.

5. /Week9_MongoDB:  
   - Connection strings, metadata files, and scripts for Week 9 MongoDB tasks.

6. /Notebooks:  
   - Python notebooks for step-by-step solutions for Weeks 7–9 tasks.

7. /Outputs:  
   - Generated outputs, including histograms, word clouds, processed metadata, and database query results.


---

### Instructions for Use
1. Open the provided notebooks in Google Colab.
2. Download and extract the relevant folders for Weeks 7–9 from this repository.
3. Follow the step-by-step instructions in the notebooks to complete tasks and exercises.

