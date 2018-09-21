## Personality Chat Datasets
The small talk datasets for the 100+ scenarios include responses and some sample queries. 

|Dataset file      |Contents |
|---------|-----|
|scenario_responses_the_professional.tsv<br>scenario_responses_the_friend.tsv<br>scenario_responses_the_comic.tsv|Small talk responses for each persona|
|qna_chitchat_the_professional.tsv<br>qna_chitchat_the_friend.tsv<br>qna_chitchat_the_comic.tsv|Small talk query-answer pairs that can be imported directly into QnAMaker cognitive service|

## Small talk using QnAMaker
If your chatbot is already using [QnAMaker cognitive service](https://qnamaker.ai) for powering a knowledge base of question-answers, you can import the small talk query dataset *Queries_Responses_QnAMaker.tsv*. Note that since QnAMaker does not support multiple answers for a single query i.e. randomized responses, this dataset picks one small talk response for each scenario. You can edit the responses directly in the [QnAMaker management portal.](https://qnamaker.ai)

Learn more about [how to create a new knowledge base](https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/home) or [update an existing knowledge base](https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/home) in QnAMaker


