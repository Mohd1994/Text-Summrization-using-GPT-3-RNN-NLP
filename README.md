# Text-Summrization-using-GPT-3-RNN-NLP
This paper presents a survey of the current state-of-the-art in text summarization, focusing on  the challenges and advances in the field. The goal of text summarization is to condense long  documents and extract key information while retaining the most relevant facts or topics. 

# Abstract
This paper presents a survey of the current state-of-the-art in text summarization, focusing on 
the challenges and advances in the field. The goal of text summarization is to condense long 
documents and extract key information while retaining the most relevant facts or topics. The rapid 
development of emerging technologies poses new challenges that still need to be solved. The 
survey provides an overview of the past, present, and future directions of text summarization, 
highlighting the main advances achieved and outlining remaining limitations. Additionally, this 
paper introduces the GPT-3 model, developed by OpenAI, which achieves competitive or better 
performance on short documents with higher memory and compute efficiency, compared to full 
attention transformers, and state-of–the-art performance on a wide range of long document 
summarization benchmarks.

# RNN (Recurrent Neural Network)
is a type of neural network that is able to process sequential
data. RNNs can be used in text summarization by maintaining a hidden state that can be used to
process sequences of inputs, allowing for the modelling of complex dependencies between inputs.
This allows RNNs to understand the context and meaning of the text and generate a summary that
captures the most important information. RNNs have been widely used in natural language
processing tasks such as text generation, language translation and summarization.
In terms of performance, GPT-3 is considered to be a state-of-the-art language processing model,
achieving competitive or better performance on short documents with higher memory and compute
efficiency, compared to full attention transformers and state-of-the-art performance on a wide
range of long document summarization benchmarks. While RNNs have also been widely used in
natural language processing tasks and can achieve good performance in text summarization, GPT3 currently has the edge in terms of overall performance

# Introduction
Text summarization is the process of generating a concise and coherent summary of a 
longer text document. The summary is meant to capture the main points and key information
from theoriginal text while reducing its length and complexity. Text summarization can be 
performed using a variety of techniques, including natural language processing (NLP) 
algorithms, rule- based systems, and extractive or abstractive approaches.
Extractive summarization involves selecting and condensing important information from 
the original text, while abstractive summarization involves generating new phrases and 
sentencesthat capture the main ideas of the text. Abstractive summarization is often seen as 
more challenging, as it requires the ability to understand and interpret the meaning of the text,
ratherthan just identifying and extracting key phrases.
Text summarization has numerous applications, including improving the efficiency of
information retrieval, condensing long documents for easier reading, and providing quick
overviews of news articles or other texts. It is also used in a variety of fields, including
journalism, business, and education.
The purpose of Text Summarization isto provide a large, high-quality work for researchers
touse in developing and evaluating text summarization models. It is a widely used dataset in
thefield of natural language processing and has been used in many research papers and projects.

![maxresdefault](https://user-images.githubusercontent.com/118799603/215291454-dce12090-7253-4745-aabf-eb2ecd603cde.jpg)

# Why was the text summarization created?
I. Usually, in our daily lives, we may read texts and articles that interest us, but in the end,
we do not realize whether we have fully understood them or not, because usually long
articles consist of difficult-to-understand sentences or from unaware goals, so we do not
understand their purpose, and we move on to read something else and suffer from The same
problem is that we do not get our goal from reading, and sometimes we may understand
simple things, but the information is complex and there is no desired and intended benefit
in it. On the other hand, some jobs require the employee to read articles and understand
their texts and summarize them by hand so that he can deliver the correct information to
the employer, but it is a very traditional and tiring method that takes an infinitely slow time.
Hence, new and modern ideas have arisen that why is there no tool that helps us summarize
texts in a way that is easy to understand and read, and it may classify information for us in
a correct way and take the most important ideas to be reached without reading thousands
of lines and without benefit.
II. Text summarization is a natural language processing (NLP) task that involves generating
a concise and coherent summary of a longer text document. It is often used to condense
large amounts of information into a more digestible form, allowing people to quickly
understand the main points and concepts contained in the original text.
III. Text summarization was invented to address the problem of information overload, which
has become increasingly prevalent in our digital age. With the proliferation of online
content and the availability of vast amounts of information, it can be difficult for people to
sift through and find the information they need. Text summarization helps to alleviate this
problem by providing a concise and comprehensive summary of a text document, making
it easier for people to quickly grasp the main points and concepts.

# Aims and objectives

# The aim of this project
Is to build a Summarization and forecasting Model to provide a brief concise and coherent
summary of a text that accurately captures the key points and main ideas of the original
document, while reducing the length and complexity of the text and preserving the
important information and main points of the original text.

# The objectives of this project
• Reduction of the text length: The primary objective of text summarization is to produce 
a shorter version of the original text while maintaining its meaning and key points. This 
can be useful for saving time and making it easier to digest large amounts of 
information.
• Preservation of important information: It is important that text summarization systems
retain the key points and important information from the original text. A good summary
should accurately represent the main ideas and content of the original text.
• Coherence: The summary should be a cohesive and coherent text, rather than a random
collection of sentences or phrases.
• Fluency: The summary should be written in a clear and natural language that is easy to
understand.
• Relevance: The summary should cover only the most important and relevant 
information from the original text.
Text summarization can be useful for a variety of applications, such as information 
retrieval, content management, and news filtering. It can help people quickly process and 
understand large amounts of information and stay updated on the latest developments in their 
fields of interest.

# Methodology
To achieve the proposed work, this section provides a brief flow of the steps that are
thoroughlyexamined and studied to confirm the contribution of the proposed work in terms of
understanding the data and extracting the results.

# Dataset understanding
The CNN / Daily Mail Dataset is an English-language dataset containing just over 300k unique 
news articles written by journalists at CNN and the Daily Mail. The current version supports both 
extractive and abstractive summarization, though the original version was created for machinereading and comprehension and abstractive question answering.
The CNN Daily Mail News Test Summarization Training Dataset consists of three columns: id,
article, and highlights. Each row in the dataset represents a single text sample and itscorresponding
summary.

• ID column
• Article column
• Highlights column

![image](https://user-images.githubusercontent.com/118799603/215291787-927d47bb-a540-47c7-9494-26f6500a002e.png)
