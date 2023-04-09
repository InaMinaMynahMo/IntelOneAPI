# IntelOneAPI 
DAKSH '23 @ SASTRA

# INSPIRATION:  <img src = "Inspiration.png" /> <br>
A codon, in biology, is the basic genetic unit of life that acts as the template for the amino acid synthesis required for protein expression. All the information required for life is stored in the genes and protein expression is the modality through which information encoded on the genes is expressed. Thus, the codon acts as an essential genetic unit of life. Until the development of bioinformatics, the only way to locate genes and research on them was to study their behavior in the organism or isolate the DNA and study it in a test tube. Bioinformatics allows scientists to make educated guesses about genes simply by analyzing sequence data using a computer. In light of this, the inspiration for the DNA Kingdom Prediction machine learning model is to surpass the first stage of the research i.e., to identify which kingdom the organism belong to. Ultimately, this project has the potential to play a significant role in gene and it's characteristics.

# PROBLEM STATEMENT: <br>
The problem statement is to efficiently analyse which kingdom of biology do the specified organism belong to using the codon.

# WHAT IT DOES? <img src = "How does it work.png"/> <br>
The DNA Kingdom Prediction application is a cutting-edge tool that helps the scientists to predict which kingdom of biology do the species belong to given the codon of the respective species. A codon is a specific sequence of nucleotides on a DNA or RNA that corresponds to a specific amino acid or to a stop signal during protein translation. A nucleotide is made up of a nucleobase, a sugar, and a phosphate group. A sequence of three nucleotides constitutes a codon. By inputting the codon values such as UUU, UCA, CUC, AUU, etc.. i.e., the combinations of A, U, G, C which stands for Adenine, Uracil, Guanine and Cytosine respectively, the user can identify which kingdom of species do the organism belong to. This helps the bioscientists to proceed their study in a successful manner. The DNA Kingdom Prediction tool is a valuable tool for the scientists looking to ease and optimize their research.

# HOW I BUILT IT? <img src = "How I built it.png" /> <br>
1. IMPORT THE LIBRARIES: The necessary packages and libraries are imported into the python notebook.
2. PREPROCESSING THE DATA: The provided data is understood and preprocessed according to the requirements.
3. TRANSFORMATION OF DATA: Includes replacements of cells in the data for better understanding.
4. PREPARATION OF MODEL: Testing different models and finding the best out of it. The machine learning algorithms used here are                       
                         1. DECISION TREE CLASSIFIER which provided an accuracy of 77.27. <br>
                         2. RANDOM FOREST CLASSIFIER which provided an accuracy of 90.45.
5. INTEL ONE API: Training the model using IntelOneAPI to get better results and faster computation.<br>
                  BUILDING THE MODEL USING COLAB took 2 minutes and 43 seconds.<br>
                  BUILDING THE MODEL USING INTEL ONE API took 55 seconds.
6. SAVE THE MODEL: The accuracy of the respective models and the results from the dataset are stored.
7. DEPLOY THE MODEL: The model is deployed using Streamlit application package in python.

# DEPLOYMENT:
The machine learning model was deployed into a web application with the help of Streamlit application package in python.

# WHAT I LEARNT? <img src = "What I learnt.png" />
1. BUILDING APPLICATION USING INTEL ONE API: The Intel OneAPI Toolkit contributes to build and deploy high-performance, data-centric applications across diverse                                                    architectures with a core set of tools and libraries. The toolkit ensures better results and faster computation.
2. Building a DNA Kingdom Prediction model involves a significant amount of research and development. During this process, I likely learned a number of things,        
   including:
    1. BIOINFORMATICS: I gained a deep knowledge of codon and genes and the factors responsible for the prediction of it's characteristics.
    2. MACHINE LEARNING: I learned about different machine learning algorithms and how they can be applied on biological data to predict the kingdom of species.
    3. DATA ANALYSIS: I likely gained experience in collecting and analyzing large amounts of data, processing it and feeding it into the models.
    4. BIOLOGICAL TRENDS: I likely gained insight into current trends in biological field with respect to technology and various applications of computer domains in                             the field of biological research.

# FUTURE ENHANCEMENTS:
After identifying the kingdom of specified species it can be improvised for identifying, <br>
    1. The characteristics of the species provided the codon. <br>
    2. The DNA sequence of the species. <br>
    3. The characteristics of genes that will be reflected in future generation of the respective species.

# REFERENCES:
1. MACHINE LEARNING MODELS TO PREDICT THE GENOMIC AND EVOLUTIONARY TRAITS OF DNA KINGDOMS : nature.com
2. CODON USAGE IS A STOCHASTIC PROCESS ACROSS GENETIC CODES OF KINGDOMS OF LIFE : biorxiv.org
3. THE CODON USAGE OF LOWLY EXPRESSED GENES IS SUBJECT TO NATURAL SELECTION : academic.oup.com
