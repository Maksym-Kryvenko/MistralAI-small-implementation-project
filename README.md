# MistralAI-small-implementation-project
 Implementation and testing Mistral AI with a Small model.

## Task.
Achieve the best result in solving math tasks.

**Model 1:** [Mistral-small](https://docs.mistral.ai/api/)

**With hyperparameters:** 
* "temperature": 0.0, 
* "top_p": 1

**Model 2:** [GPT3.5Turbo](https://platform.openai.com/docs/models/gpt-3-5-turbo)

**With hyperparameters:** 
* "temperature": 0.0, 
* "top_p": 1

**Evaluation metric:** num_of_correct / 100

## Final results.
**Mistral Accuracy:** 
* 77% (77/100 correct) - with only user prompt
* 55% (55/100 correct) - with system prompt

Working history: prompt_history.jsonl

**GPT3.5-turbo Accuracy:**
* 80% (80/100 correct)

**Tuned GPT3.5-turbo Accuracy:**
* ?% (?/100 correct)

**GPT4 Accuracy:**
* 78% (78/100 correct) - with only answer
* 92% (92/100 correct) - if ask to explain the solution

As result of different methods and various prompts the best model can reach accuracy of 90%, however there are some questions that are still defined incorrectly. 

## Future prospects.
Further steps to improve the results:
* errors can be the results of model weakneses, so it can be replaced with another one to solve it;
* design better prompts, it can help to increase the accuracy;
* try to add extra chains to get extra solution or another validation step;
* add tools (calculator) to perform mathematical operations in outputs. 

