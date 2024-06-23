
# Generative Ai: Prompt Engineering Basics 


# Task 1. Prompt Instructions and the Prompt


Difference Between Prompt Instructions and Prompt

Prompt Instructions are like rules for how the AI should talk to me. 

The Prompt is the actual question I ask the AI.

I could put the Prompt Instructions right before my question, but it looks nicer and cleaner if I keep them separate.

Neatness: Splitting them makes everything look tidy.

Consistency: The instructions apply to the whole chat without repeating.

Flexibility: If I want the instructions to apply to only one question, putting them right before the question works better.

Explanation

Prompt Instructions are rules for how the AI should talk. Here, I want the AI to be happy and excited.
Prompt is the question I ask. I want to know about five important people in computer science and their work.


![image](https://github.com/iahalkhatib/Prompt-Instructions-and-the-Prompt/assets/170050432/3e700523-67ec-48d6-9c06-baa143819298)

![image](https://github.com/iahalkhatib/Prompt-Instructions-and-the-Prompt/assets/170050432/b98c6355-479b-492c-af09-ab22311bb223)

![image](https://github.com/iahalkhatib/Prompt-Instructions-and-the-Prompt/assets/170050432/7199d3f9-8600-4388-96f8-8adfe6223432)



# Task 2. Experimenting with Prompts

Large language models (LLMs) are pre-trained on vast amounts of data to generate novel content, including text, images, and video. 

To generate the desired response, you should feed the input to a model as a prompt. It is important to provide a context-based, clear, and precise prompt to guide the model and get the desired output. The process of designing effective prompts to generate better and desired responses is called prompt engineering.

In this lab, I will learn the basics of prompt engineering and experiment with simple prompts to control how a model interprets and generates desired and coherent responses.

Learning Objectives
Design a prompt structure to write concise prompts based on requirements.
Write unambiguous and context-based prompts to generate the desired output.
Write prompts in different formats, such as questions, statements, and instructions.
Let's get started prompting and experimenting with foundation models.

Before You Start Prompting
Before beginning the exercise, I must set up the AI classroom and know the generative AI workspace.

# Step 1: Set Up the AI Classroom
Name the Chat: Give the chat a specific name for better organization.
Choose the Foundation Model: Select the appropriate model for the task.

# Step 2: Know Your Workspace
Use Prompt Instructions: Provide clear instructions to guide the AI.
Type Your Message: Enter the prompt in the input area.
Manage Your Chat: Keep track of the conversation history.
Delete the Chat from History: Remove unnecessary chat logs to keep the workspace clean.

# Step 3: Identify the Task
Before drafting a prompt, I should clearly understand the task that the model needs to perform. 
For example, do I want the model to generate a story or a social post, or do I want the model to summarize text or classify text by identifying sentiments?

# Step 4: Select the Model
Before designing prompts, it is important to understand the model I will leverage to accomplish the tasks. In this exercise, I will use the foundation model gpt-3.5-turbo to experiment with the prompts.

OpenAI's gpt-3.5-turbo is an advanced foundation large language model. 
As a powerful tool for generating coherent and contextually relevant text, the gpt-3.5-turbo foundation model can be used for various applications, including chatbots, virtual assistants, content generation, and more. It can be applied for translating languages, answering questions in an informative way, and completing tasks such as writing poems, code, scripts, musical pieces, emails, letters, and so on.

![image](https://github.com/iahalkhatib/Prompt-Instructions-and-the-Prompt/assets/170050432/0837e6a5-7088-4e40-9bbb-5f1f2d7df06f)


# Exercise 1: Prompt Structure

In this exercise, I will experiment to create a prompt structure for drafting prompts for converting the given text from English to Spanish.

Designing a Prompt Structure to Convert Text from English to Spanish

![image](https://github.com/iahalkhatib/Prompt-Instructions-and-the-Prompt/assets/170050432/f7d16f7f-b60c-4e74-866e-80c16e6fd519)


Let's propose a prompt structure that will help me write concise text prompts. Here’s how I can structure it:

Context: Provide a brief description of the task.

Instructions: Clearly state what needs to be done.

Example: Give an example to illustrate the instructions.

Prompt Structure

Context: I want to translate text from English to Spanish.

Instructions: Convert the following English text to Spanish.

Example:

English: "Hello, how are you?"
Spanish: "Hola, ¿cómo estás?"

![image](https://github.com/iahalkhatib/Prompt-Instructions-and-the-Prompt/assets/170050432/4001b68c-c041-4ef4-a3ce-1d313916fb00)

![image](https://github.com/iahalkhatib/Prompt-Instructions-and-the-Prompt/assets/170050432/a5fe3cac-8591-428e-9ba1-edecb8656b0c)

![image](https://github.com/iahalkhatib/Prompt-Instructions-and-the-Prompt/assets/170050432/3a0749f8-4cd6-4a29-84d4-1db85ec1c27d)



By following this prompt structure, I can create clear and concise prompts that help guide the AI to accurately convert English text to Spanish.
The context sets the task, the instructions tell the AI what to do, and the example provides a model for the desired output.


# Exercise 2: Unambiguous Prompts

Let's learn how adding context-specific input to the prompt influences the output.

Creating an Unambiguous Prompt
Setting Up the Chat:

I can create a new chat and name it according to the context, or I can reset an existing chat.

Initial Prompt:

![image](https://github.com/iahalkhatib/Prompt-Instructions-and-the-Prompt/assets/170050432/4d6d24a4-f670-4467-b7be-c1c273a48787)

Adding Context for Clarity:

To make the response more coherent, I can add context to the prompt.

![image](https://github.com/iahalkhatib/Prompt-Instructions-and-the-Prompt/assets/170050432/8c3b2751-85bb-4e42-bee2-bb0983546fcd)

Review and Compare

Initial Prompt Response: 

The response to the initial prompt "Why is generative AI useful in content marketing?" might be broad and general, providing an overview without specific details.

Modified Prompt Response: 

The response to the modified prompt "Discuss how generative AI can enhance the creation of blog posts and email newsletters in content marketing" is likely to be more focused, offering specific applications and their benefits in content marketing.

By reviewing and comparing these responses, I can see how adding context and specific input to the prompt leads to more precise and useful information.

By making the prompt more specific, I can guide the AI to generate a more coherent and detailed response, enhancing the quality of the information provided.



# Exercise 3: Prompts in Different Formats

Prompts can be presented in different formats, such as questions, statements, or instructions. 

Let's experiment with how prompts in different formats can yield different results.

Experimenting with Prompts in Different Formats

Setting Up the Chat:

I can create a new chat and name it according to the context, or reset an existing chat.

# Step 1: Question Format

First, I'll write a prompt in question format. 

![image](https://github.com/iahalkhatib/Prompt-Instructions-and-the-Prompt/assets/170050432/20ff8066-483d-4012-bb46-66c9cbff4a09)

# Step 2: Statement Format

Next, I'll write the prompt in statement format. 

![image](https://github.com/iahalkhatib/Prompt-Instructions-and-the-Prompt/assets/170050432/cd020786-5d43-43c7-901c-0b07a2457a5e)

# Step 3: Instruction Format

Further, I'll write the prompt in an instruction format.

![image](https://github.com/iahalkhatib/Prompt-Instructions-and-the-Prompt/assets/170050432/4daaca94-ba0e-4a7e-88b6-038aaa8cb0cd)


# I will review and analyze the response generated by each prompt to identify which prompt format works best to accomplish the desired task.

Question Format: Best for extracting specific information or details.

Statement Format: Suitable for text completion or elaboration on a topic.

Instruction Format: Effective for tasks like summarization or generating a list of items.


# Exercise 4: Limit the Output Length

For a few text generation tasks, such as generating tweets or text messages for a social media post, there are limitations on the number of words. 

Let's experiment with a prompt that instructs the model to generate a response with a specific number of words or to generate a specific number of statements.

Generating a Response of a Specific Number of Words/Statements

![image](https://github.com/iahalkhatib/Basics-of-Prompt-Engineering/assets/170050432/8302b7db-5bdb-4ec4-a0c1-f42a0722d3d9)


![image](https://github.com/iahalkhatib/Basics-of-Prompt-Engineering/assets/170050432/d2beeba4-8ca8-4835-b65f-b67d09fe46af)




# Conclusion: In this lab, I experimented with designing a prompt structure that helps to write concise prompts. 

I learned how to write a concise, unambiguous prompt to generate the desired response. 

I also experimented with different formats of prompts, such as questions, statements, and instructions. 

I learned to select the specific format based on the requirements and desired response.

