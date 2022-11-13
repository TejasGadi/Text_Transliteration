# Text_Transliteration
### LSTM based Encoder Decoder model for Transliteratin of English , and Indic language query

##Steps followed(Flow):
1. Importing the data from GitHub (Using !wget)
2. Reading the data (Using Pandas)
3. Checking if the data has any Nan values.
4. Converting the text into Lower case
5. Adding Starting and Ending token to the target data.
6. Tokenization.
7. Checking the max length of both the types of sentences.
8. Padding the sentences.
9. Splitting the dataset into Training and Testing.
10. Building the Model (Encoder and Decoder)
11. Making a predict function.
