# Natural-Language-Processing
Natural Language Processing 
**Resource:** [Ultimate Guide to Understand and Implement Natural Language Processing](https://www.analyticsvidhya.com/blog/2017/01/ultimate-guide-to-understand-implement-natural-language-processing-codes-in-python/)

**Natural Language Processing (NLP)** is defined as the branch of Artificial Intelligence that provides computers with the capability of understanding text and spoken words in the same way a human being can. 
It incorporates machine learning models, statistics, and deep learning models into computational linguistics i.e. rule-based modeling of human language to allow computers to understand text, spoken words 
and understands human language, intent, and sentiment.


### Applications of NLP

- Informational retrieval
- Information extraction
- Question Answering
- Machine Translation
- Summarization
- Auto Completion
- Spell Correction

### **NLP Ambiguities**

There are different types of ambiguities present in natural language:

- **Lexical Ambiguity**
    - It is defined as the ambiguity associated with the meaning of a single word. A single word can have different meanings. Also, a single word can be a noun, adjective, or verb.
    - For example, The word “bank” can have different meanings. It can be a financial bank or a riverbank. Similarly, the word “clean” can be a noun, adverb, adjective, or verb.
- **Syntactic Ambiguity**
    - It is defined as the ambiguity associated with the way the words are parsed.
    - For example, The sentence “Visiting relatives can be boring.” This sentence can have two different meanings. One is that visiting a relative’s house can be boring. The second is that visiting relatives at your place can be boring
- **Semantic Ambiguity**
    - It is defined as ambiguity when the meaning of the words themselves can be ambiguous.
    - For example, The sentence “Mary knows a little french.” In this sentence the word “little french” is ambiguous. As we don’t know whether it is about the language french or a person.
 
      ### NLP Systems

- **Natural language understanding**
    - Extract information (e.g. about entities or events) from text
    - Translate raw text into a meaning representation
    - Reason about information given in text
    - Execute NL instructions
- **Natural language generation and summarization**
    - Translate database entries or meaning representations to raw natural language text
    - Produce (appropriate) utterances/responses in a dialog
    - Summarize (newspaper or scientific) articles, describe images
- **Natural language translation**
    - Translate one natural language to another
 
  ### Common NLP Tasks

- **Tokenization**
    - the process of breaking down a text into individual units called tokens
    - Tokens are typically words, but can also be phrases or even individual characters, depending on the application.
    - Tokenization is a crucial step in natural language processing tasks such as machine translation, sentiment analysis, and named entity recognition.
    - **Resource:** [Tokenization Techniques in NLP](https://heartbeat.comet.ml/tokenization-techniques-in-nlp-561e277b6090)
    - **Resource:** [OpenAI GPT-3 Tokenizer](https://platform.openai.com/tokenizer)
- **POS tagging**
    - POS stands for **Part-of-Speech,** which is a linguistic term used to describe the grammatical category of a word in a sentence.
    - POS tagging is the process of assigning each word in a text with its corresponding POS category, such as noun, verb, adjective, or adverb.
    - POS tagging is a critical component in various natural language processing tasks, including text-to-speech conversion, information retrieval, and machine translation.
- **Word sense disambiguation**
    - Word sense disambiguation is the process of identifying the correct meaning of a word with multiple possible meanings based on the context in which it appears.
    - This is a crucial task in natural language processing because words often have different meanings depending on the context in which they are used.
    - Word sense disambiguation is used in various applications, including information retrieval, machine translation, and question answering systems.
- **Dependency parsing**
    - Dependency parsing is the process of analyzing the grammatical structure of a sentence by identifying the relationships between words in a sentence.
    - It involves identifying the subject, object, and other dependent clauses and phrases, and representing them as a tree-like structure known as a dependency tree.
    - Dependency parsing is used in various natural language processing applications, including sentiment analysis, named entity recognition, and machine translatio
- **Syntactic parsing**
    - Syntactic parsing is the process of analyzing the grammatical structure of a sentence to determine its syntactic components, such as nouns, verbs, adjectives, and adverbs.
    - It involves identifying the parts of speech of each word in the sentence and grouping them together into phrases and clauses based on their syntactic relationships.
    - Syntactic parsing is used in various natural language processing applications, including text-to-speech conversion, machine translation, and information retrieval.
    - POS Tagging Vs. Syntactic parsing
        - POS tagging is the process of labeling individual words in a sentence with their part of speech, such as noun, verb, adjective, or adverb, while syntactic parsing involves analyzing the relationships between the words to determine the overall grammatical structure of the sentence.
        - For example, consider the sentence "John eats pizza." POS tagging would label "John" as a proper noun and "eats" as a verb, while syntactic parsing would identify "John" as the subject of the verb "eats" and "pizza" as the object of the verb.
        - In short, POS tagging is concerned with the individual words, while syntactic parsing focuses on the overall sentence structure.
- **Semantic analysis**
    - Semantic analysis is the process of extracting the meaning of a text by analyzing the relationships between words and phrases in a sentence.
    - It involves identifying the underlying concepts and ideas conveyed by the text and representing them in a structured form, such as a knowledge graph or ontology.
    - Semantic analysis is used in various natural language processing applications, including question answering, information retrieval, and chatbots, to enable more accurate and intelligent responses.
    - **Resources**
        - [How is Semantic Search Different from Keyword Search?](https://www.traindex.io/blog/how-is-semantic-search-different-from-keyword-search-578d/)
        - [Hamza's "Travelle" website](https://traversaal.com/travelle/)
- **Conference resolution**
    - Coreference resolution is the task of identifying all the expressions (e.g., pronouns, names) in a text that refer to the same entity, and linking them together.
    - It is a crucial task in natural language processing as it enables a system to maintain a consistent representation of entities throughout a document, enabling more accurate information extraction and text understanding
- **Named Entity Recognition (NER)**
    - Named entity recognition (NER) is the process of identifying and categorizing named entities in a text, such as people, organizations, locations, and dates.
- **Text representation**
    - Text representation is the process of converting unstructured text data into a structured format that can be used for natural language processing tasks.
    - It involves selecting a suitable representation scheme, such as bag-of-words, word embeddings, or topic models, to capture the key features and characteristics of the text data in a numerical form that can be processed by machine learning algorithms.
- **Text classification**
    - Text classification is the process of categorizing text into organized groups.
        
        ![ 2023-07-08 at 4.02.47 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0a41cf94-5cd8-44d7-8757-be5707511c0a/_2023-07-08_at_4.02.47_PM.png)
        
- **Natural language generation**
    
    Natural language generation, NLG, technology can be used for a variety of purposes, including creating automated customer service responses, filling out online forms, and creating intelligent chatbots.
    
    **Resource:** [What is Natural Language Generation?](https://www.aidataanalytics.network/data-science-ai/articles/what-is-natural-language-generation)
    
- **Multimodal NLP**
    - Multimodal NLP combines data from multiple modes, such as text, speech, images, and videos, to gain a deeper understanding of the data.
    - Multimodal NLP is used in a variety of applications, such as video captioning, speech recognition, and image captioning.
    - Resource:  [MUM: A new AI milestone for understanding information](https://blog.google/products/search/introducing-mum/)


  ### SpaCy Package

- **Resource:**  [How to Train NER with Custom training data using spaCy](https://manivannan-ai.medium.com/how-to-train-ner-with-custom-training-data-using-spacy-188e0e508c6)
- spaCy is an open-source library used for natural language processing in python. It is extremely popular for processing a large amount of unstructured data generated at a vast scale in the industry and generate useful and meaningful insights from the data.
- spaCy NLP pipeline



- [Ultimate Guide to Understand and Implement Natural Language Processing](https://www.analyticsvidhya.com/blog/2017/01/ultimate-guide-to-understand-implement-natural-language-processing-codes-in-python/)
- [NLP Zero to One: Full Course](https://medium.com/nerd-for-tech/nlp-zero-to-one-full-course-4f8e1902c379)
- [OpenAI GPT-3 Tokenizer](https://platform.openai.com/tokenizer)
- [How is Semantic Search Different from Keyword Search?](https://www.traindex.io/blog/how-is-semantic-search-different-from-keyword-search-578d/)
- [Hamza's "Travelle" website](https://traversaal.com/travelle/)
- [MUM: A new AI milestone for understanding information](https://blog.google/products/search/introducing-mum/)
- [How to Train NER with Custom training data using spaCy](https://manivannan-ai.medium.com/how-to-train-ner-with-custom-training-data-using-spacy-188e0e508c6)
