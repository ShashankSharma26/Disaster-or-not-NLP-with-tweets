# Data Cleaning

It is imperative to clean the dataset before it is used for modelling. The following processes/changes were made to the data at this stage:

1. Standardization: All text was changed to lower case. 
2. Removing incosistencies and irrelavent information such as punctuations, words with numbers, website links, special characters etc.
3. Tokenizing: Splitting text into minimal meaninful units (individual words)
4. Removing stopwords: Getting rid of words which are used extensively and do not add contextual walue to the sentence.
5. Part-of-Speech Tagging: Assiging special label assigned to each word(token) in corpus to indicate the part-of-speech the belong to such as noun, verb etc.
6. Lemmatizing: Grouping different inflected forms of a word that essentially mean the same example: car, cars, car's become car

The above processes were performed on both training and testing data and the result were saved as csv to be used for exploratory data analysis and data modelling.
 
