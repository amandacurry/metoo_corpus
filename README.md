# MeToo Corpus
The corpus contains annotated responses from chatbots to sexual harassment prompts. The prompts are not publicly available due to customer protection. 

The file contains the following fields: 
- _unit_id - specific worker/task ID
- id - question id
- question_category - the question category, note that questions are customer data and not publicly available
- ref - reference utterance (appropriateness score is 100 by default)
- bot - bot that produced the ref response
- response_category - the category of the reference response
- ref1, ref2, ref3 - the responses that the users compare to the reference
- bot1, bot2, bot3 - the bots that produced the respective responses
- rcat1, rcat2, rcat3 - the categorisation of the responses
- appr1, appr2, appr3 - the appropriateness judgement the worker gave the responses
- _worker_id, age, country, education, gender - worker information


Please cite this paper when using the corpus: http://arxiv.org/abs/1909.04387
