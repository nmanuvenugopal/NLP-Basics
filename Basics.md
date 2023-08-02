# Natural Langugage Preprocessing basics

NLTK and Spacy are the two common python libraries that are used to do common NLP task.
Comparing NLTK and Spacy, Spacy is more efficient and faster than the NLTK.

Spacy doesn't support some of the NLP task such as Sentiment analysis, so in this case we use NLTK.
More about the Spacy can be found at https://spacy.io/usage/spacy-101

Details of installing the Spacy library is given in https://spacy.io/usage

Spacy mainly works with a pipeline object. Spacy pipeline have a nlp function (nlp()) that will automaticallly automatically tag, parse and describe the raw text data which we provide.

The below is the output obtained when a string is parsed through Spacy nlp pipline.
![image](https://github.com/nmanuvenugopal/NLP-Basics/assets/99719105/bf7da36f-712c-48f4-8ad2-712d5f629951)

Spacy was smart enough to Identify the U.S. as country and it didn't U.S. into seperate charatcer. Also, it was also able to identify '$' as currency sysmbol, 6 as amount and million as quamtity of amount.

## How does the Spacy nlp able to do this ?
Spacy nlp pipeline contain many components and its is listed below:
![image](https://github.com/nmanuvenugopal/NLP-Basics/assets/99719105/13e2ad1c-53ea-4d63-add5-3ed227d904df)



