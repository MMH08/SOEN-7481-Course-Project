# Vote Variance Factors Analysis of Similar Stack Overflow Posts (Q&A)
Abstract—Duplicate codes from online sources are code frag- ments which are copied from the same online sources such as Stack Overflow. Stack Overflow is a popular online Q&A website where developers discuss coding problems and share code examples for seeking and providing answers. Due to the popularity of this technical questions and answering website, developers are frequently re-using the code snippets for asking questions and answering the questions within the Stack Overflow. In this paper, we conduct a case study only with java posts (i.e., questions and answers) on Stack Overflow, to investigate i) similar Q&A in terms of cloned code snippets ii) vote differences among the cloned Q&A iii) accountable factors that affects vote differences between cloned Q&A through mixed modeling. For cloned questions, we found 20% (i.e., 60,079) java questions that are cloned to each other from 291,427 java questions. In terms of cloned answers, we found 12.24% (i.e., 16,316) java accepted answers that are cloned to each other from 133,243 java accepted answers. Furthermore, we collect around 45 potential factors for both questions and answers; build mixed-model to finding out most responsible factors that contribute more to the vote differences. Finally, we found 25 responsible factors that affected vote differences of those cloned questions and answers. So, this study reveals that developers commonly use Stack Overflow for posting Q&A and use code snippets repeatedly as an example, but before voting users consider 25 factors that makes vote differences among cloned questions or answers.

# Data Processing approach
<img width="905" alt="image" src="https://user-images.githubusercontent.com/45977153/120518799-f4404080-c39f-11eb-9acf-dd26a07925ed.png">

# Result: Responsible factors of cloned questions and answers from Mixed Model in Stack Overflow(SO)
<img width="1048" alt="image" src="https://user-images.githubusercontent.com/45977153/120525393-18068500-c3a6-11eb-95b3-d0ac38274419.png">

# Requirements
- R Studio
- NiCad clone detection tool

# Research questions
- RQ1: What are the factors that affects the vote differences of each cloned Questions (i.e., cloned in terms of code snippets)?
- RQ2: What are the factors that affects the votes differences of each cloned Answers (i.e., cloned in terms of code snippets)?

# Data source
- Stack Exchange data dump: https://archive.org/details/stackexchange
- NiCad tool: http://www.txl.ca/nicaddownload.html

# Filtered Q&A in number with calculation
https://docs.google.com/spreadsheets/d/1h_VrUWL-gvabVPyXS61s3pFNrOb80IouSP5Zwc3mOew/edit#gid=2100088724

# For any questions
Please send email to manik.ruet08@gmail.com
