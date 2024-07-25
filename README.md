# Classification-of-DNA-Sequences
This repository contains the code and documentation for a mini-project aimed at classifying deoxyribonucleic acid (DNA) sequences using Support Vector Machine (SVM) and Logistic Regression algorithms. The project leverages Google Collaboratory for development and experimentation.
### Algorithms Used
1. **Support Vector Machine (SVM)**
2. **Logistic Regression**
## Theory
### DNA Basics
DNA, or deoxyribonucleic acid, is the hereditary material in humans and almost all other organisms. Nearly every cell in a person’s body has the same DNA. Most DNA is located in the cell nucleus (where it is called nuclear DNA), but a small amount of DNA can also be found in the mitochondria. Mitochondria are structures within cells that convert the energy from food into a form that cells can use. The information in DNA is stored as a code made up of four chemical bases: adenine (A), guanine (G), cytosine (C), and thymine (T). Human DNA consists of about 3 billion bases, and more than 99 percent of those bases are the same in all people. The order, or sequence, of these bases, determines the information available for building and maintaining an organism, similar to the way in which letters of the alphabet appear in a certain order to form words and sentences. DNA bases pair up with each other, A with T and C with G, to form units called base pairs. Each base is also attached to a sugar molecule and a phosphate molecule. Together, a base, sugar, and phosphate are called a nucleotide. Nucleotides are arranged in two long strands forming a double helix spiral.
### DNA Sequence Encoding Methods
1. **Sequence Coding:** The coding region of a gene, also known as the coding sequence (CDS), is the portion of a gene's DNA or RNA that codes for protein. Studying the length, composition, regulation, splicing, structures, and functions of coding regions compared to non-coding regions over different species and time periods can provide significant information regarding gene organization and evolution of prokaryotes and eukaryotes.

2. **One-Hot Encoding:** One-hot encoding is a way to represent categorical data as binary vectors. Machine learning algorithms cannot work with categorical data directly. Instead, we use character-level one-hot encoding to represent the categorical data (for us DNA). This method transforms each DNA base into a binary vector, facilitating the input of DNA sequences into machine learning models.

3. **K-mer Coding:** K-mer-based analysis and comparison methods have become standard tools for analyzing large DNA sequences such as chromosomes, whole genomes, or even metagenomes. The advantage of K-mer-based methods over alignment-based methods (like NCBI BLAST) is shorter computation times. In K-mer coding, a DNA sequence is broken down into shorter, overlapping sequences (k-mers), which are then analyzed. For example, the sequence "ATGCATGCA" can be broken down into k-mers of length 6: 'ATGCAT', 'TGCATG', 'GCATGC', 'CATGCA'. This method helps in identifying similarities between sequences by comparing k-mer counts.
## Machine Learning Algorithms 
1. **Logistic Regression:** Used for binary classification problems, utilizing a sigmoid function to convert predicted values into probabilities.
2. **Support Vector Machine (SVM):** Utilized for both classification and regression tasks, it finds the decision boundary that maximizes the margin between different classes.
## Count Vectorizer
A method to convert text data into numerical data, essential for processing DNA sequences in machine learning models.
## Results
- **Accuracy, Precision, Recall, and F1 Score** were used to evaluate model performance.
- **Logistic Regression:** Accuracy = 0.926, Precision = 0.938, Recall = 0.8851, F1 Score = 0.927.
- **SVM Model:** Accuracy = 0.8851, Precision = 0.9154, Recall = 0.8851, F1 Score = 0.883.
