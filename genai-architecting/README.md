## Functional Requirements
We will aim to host the selected model locally. This is so that we will be able to reduce latency, fine tune the model for better translation capabilities in order to supercharge learning outcomes. This will allow for cost-savings in the longer term. Further optimisations to the caching strategy will be required. We are aiming to have a user-base from regional locations that may amount to >1000 students as Chinese is a very desirable language for business.

## Data Strategy
Store user progress and preferences locally
Voice data processed in real-time, temporary storage only
User conversations not saved unless perhaps explicitly requested
Language models updated monthly with new content
Analytics collected anonymously for model improvements

## Assumptions
We assume that caching both responses and inputs will help to improve latency and compute costs over the long term as more students interact with similar language learning paths and common sentences. 
We assume that hosting a small ai server will be able to handle the expected student base.
We assume that there will be model-side guardrails for profanities, and we do not need to handle this at the onset.

## Consideration
We are considering DeepSeek as it is a Chinese model and should be able to handle chinese translation and learning well. We will need to fine tune the prompting to ensure that the model serves as an assistant without providing the answers or too advanced language for the learners.