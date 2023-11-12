# ChatGPT and Prompt Engineering

This is a set of notes to help further understanding and effiency of prompts when utilizins ChatGPT and other AI language models

## Tables of contents

[Six Topics of Improving Prompts](#six-topics-of-improving-prompts)

[Zero-shot and Few-Shot Prompting](#zero-shot-and-few-shot-prompting)

[AI Hallucinations](#ai-hallucinations)

[Prompt Formulas](#prompt-formulas)


## Six Topics of Improving Prompts

### Clear Instructions

### Adopt a Persona

### Specify the Format

### Avoid Leading the Answer

### Limit the Scope



## Zero-shot and Few-Shot Prompting

<u> Zero Shot Prompting </u>

Leverages an AI language model's understanding of words and concept relationships without further training


- A query is made to the model without any training/specificity for the task/prompt


- A Model performs a task without having seen any examples of that task during its training

- This is in the context of machine learning, not just prompting an AI language model.



<u> Few Shot Prompting </u>

Enhances the model with training exampels of the prompt via the prompt avoiding retraining


- Data is required for some answers/reponses to be either valid or more accurate

- Providing data for a model in the prompt allows for specifity and quality of responses
    - This both increases response quality and efficiency



## AI Hallucinations

This term refers to the instance when a LLM (Large Language Model) generates false information

- Not exclusive to a more visual medium of imagery, text/data may also be interpretted incorrectly in a LLM

- If a LLM incorrectly interprets data/patterns in a response, it may use a method that is 'creative' to fill in the blanks for a response and return false information

## Vector/Text Embeddings

Association of words/context is done using text embeddings.

An example is similar words to food:

- human response examples: burger, pizza, tacos
- machine response: foot, fool


It is important that text embeddings are used to allocate more descriptiveness that the LLM may search through to find contextual similarities






## Prompt Formulas

Order of elements to include in prompts for efficiency/quality:

- Persona
- Context
- Task
- Exemplar
- Format
- Tone


Simple prompt efficiency:

- Context
- Task
- Exemplar
- Tone




### Persona




### Context




### Task




### Exemplar




### format




### Tone