# NLTK-Tokenization

This Python code demonstrates how to use the Natural Language Toolkit (NLTK) library to tokenize text into individual words and calculate the frequency of each token in the text. This command installs the NLTK library if it’s not already installed. NLTK is a powerful library for text processing and is widely used in Natural Language Processing (NLP). Here, we import:

//word_tokenize: A function that breaks down text into words.

//FreqDist: A function that helps in calculating the frequency of each token.

//nltk.download('punkt'): This command downloads the model, which is essential for NLTK's tokenizers to handle punctuation and identify word boundaries accurately. This only needs to be done once.

A sample text paragraph of four sentences is defined. This text will be used to demonstrate tokenization and frequency analysis.

The word_tokenize function splits the text paragraph into individual words (tokens) and stores them in a list called tokens. Each word and punctuation mark becomes an element in this list.

//print("Tokens:", tokens) : This line prints the tokens list, allowing us to see the individual words and punctuation that the word_tokenize function has generated.

//num_tokens = len(tokens)
//print("Total number of tokens:", num_tokens) : This step calculates the total number of tokens (words and punctuation) in the text by using the len function. It then prints this count, which provides a quick overview of the text’s size.

Using FreqDist, this line creates a frequency distribution of the tokens, which shows how often each word or punctuation mark appears in the text. This frequency distribution is stored in frequency_dist.

Finally, this loop iterates through each unique token and its frequency in frequency_dist, printing each token alongside its frequency count. This gives us insight into the most and least common tokens in the text.

Summary
This code is a basic NLP workflow:

Tokenizing text into individual words.
Calculating and displaying the frequency of each word. This process is useful in tasks such as analyzing word patterns, creating word clouds, and further NLP applications like sentiment analysis.
