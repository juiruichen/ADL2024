# ADL Homework

## HW1 - Chinese Extractive Question Answering (QA) Task

### Task Overview

The task of **Chinese Extractive Question Answering** involves determining the correct answer to a given question from a set of paragraphs by performing the following two steps:

1. **Paragraph Selection**:  
   The objective in this step is to identify which paragraph among several candidates contains the relevant information needed to answer the given question.  
   - **Input**: A set of paragraphs and a question.
   - **Model**: A **Multiple Choice Model** that evaluates each paragraph's relevance to the question.
   - **Output**: The correct paragraph that is most relevant to the question.

2. **Span Selection**:  
   After the relevant paragraph is identified, the next step is to pinpoint the exact answer within the selected paragraph.  
   - **Input**: The correct paragraph and the question.
   - **Model**: An **Extractive QA Model** that locates the start and end positions of the answer span within the paragraph.
   - **Output**: The specific text span that constitutes the answer.  
   
   *Note: The answer is always a continuous span of text within the correct paragraph.*

### Applications
This task is widely used in real-world applications such as:
- Reading comprehension systems
- AI-based customer service
- Automated question answering systems for large document corpora
