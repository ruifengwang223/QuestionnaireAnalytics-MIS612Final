## Introduction ##
This is course project in the form of 4 -student group in MIS-612, Aligning Information Systems and Business Strategies. The professor shared the datasets in Drexel Co-op feedback questionnaires from 2014 to 2019 and asked us to select 3-4 questions to solve based on analyzing datasets. The group leader requested each of group member to solve one of the questions. Therefore, I decided to select the question: "Strength mentioned: personality characteristics, skills, or academic knowledge?". I used Python and Excel to output conclusions.
## Dataset ##
The datasets are prvided by professor, include questionnaires from employers, students, and faculty. The variables include work term, students' major, Co-op period, comments on strengths. Th data is only available for students who enrolled MIS-612, so I can not uplod it here.
## Analysis ##
I used text analysis coding from Pandas and NLTK libraries to preprocess text data, also conduct tokenization and lemmatization on questionnaire's comments. Then made statistics on unigram and bigram, classified them into three categories: personality characteristics, skills, or academic knowledge.
## Result ##
Based on visualizations, the strength mentioned are: Personal characteristics > Skills > Academic knowledge
