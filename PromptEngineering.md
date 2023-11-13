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

Who do you want the AI to be?

- You are a <persona here> with over 20 years of experience...

A specialty/role/occupation is preferred over a specific Famous identity, i.e. Bill Gates, but very famous ones may work well. 

- In essence, providing contextual information for the AI to return an outut using reference to the given persona, experience professional of choice, will help return more accurate/quality outputs

Example:
- You are trained Data Scientist with over 15 years of experience working multiple positions of the Data field. Generate a guideline that....



### Context

1. What is the user's *background*?
2. What does *success* look like?
3. What *environment* are they in?

The key is giving just enough information to constrain the endless possibilies (thus providing more efficient prompts/responses)

### Task

- Start Task sentence with an action verb
    - e.g. Generate, Summarize, Categorize
- Articulate what your end goal

- Can be a simple task or multi-step task


### Exemplar

Including examples in the prompt DRASTICALLY improves the qually of the output (more accurate results)

- Providing an example of what you expect, or a guideline such as a framework, will provide a more accurate output form the prompt

- A full textual example is not necessary, but a framework, in whcih you define the structure or how to format the results, will suffice as well and save on prompt time/tokens


Exemplars are not necessary for every prompt, but including a relevant example greatly improves the quality of your put.

- Example:
    - STAR framework:
        - Situation, Task, Action, Results


### format

Visualize what you would like the end result/output to look like


Example: 
... Output a table format with column headers: Feedback, Team, and Priority.

Other formats:
- emails
- bullet points
- code blocks
- paragraphs
- markdown

Example:
- given this sample article: ... Please provide topic summaries, each containing 1-2 sentences detailing the topic point. Place each topic summary title as a <h2>


Example:
- "...Bold all changes provided"

This will allow you to quickly identify if there have been any changes, and where without having to cross reference the original document. HUGE


### Tone

Tell the AI the feeling you're looking for. Explain the feeling you want to convey the information as, and it will help describe/properly find mood outputs to set the tone of response


Tip:
- "Can you please me a list of 5 tone keywords I can include in a prompt for ChatGPT?"
    - This may result in finding the proper keywords to then use in a higher quality prompt for a higher qualityaccurate output


Examples:
- Casual tone 
- formal tone
- "give me a witty output"
- show enthusiasm
- sound pessimistic




Example prompt using the entire formula:


You are a senior manager at Microsoft and you have just released the new tehcnical debut demonstration of windows 12, which is expected to allow users a free upgrade by the year 2026 and increase performance for all users.

Write an email to existing customer-base about how the upgrade will allow for a free upgrade and not impact current programs/systems that users are using in any way, except to provide faster tehcnical performance and better integrated UI experiences.

This email should include a tl;dr (too long, didn't read) section, project background (why this product came into existence), business results section(quantifiable business metrics), and end with a section thanking users for the continuous support of the Microsoft brand products/services.

Use clear and concise language and write in a comforting/confident yet friendly tone.