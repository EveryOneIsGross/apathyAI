# apathyAI
This project aims to create a chatbot algorithm that uses the paradox of apathy and inaction presented by Søren Kierkegaard in his book Either/Or to guide conversations in chatbot frameworks.

## ApathyAI: A Chatbot Algorithm Based on Kierkegaard’s Paradox of Apathy and Inaction

This project aims to create a chatbot algorithm that uses the paradox of apathy and inaction presented by Søren Kierkegaard in his book Either/Or to guide conversations in chatbot frameworks. The algorithm can be used to create a ‘rest and wait’ codeblock that stops the user from pursuing a line of conversation that the chatbot wants to avoid, until the user says a keyword that triggers a different script.

## Philosophy

The paradox of apathy and inaction is a concept that Kierkegaard introduced in his book Either/Or, where he contrasts the aesthetic and the ethical modes of life. The aesthetic mode is characterized by personal, sensory experiences and pleasures, while the ethical mode is characterized by commitment, responsibility, and moral values. The paradox arises when one tries to live in both modes at the same time, resulting in a state of apathy and inaction. The chatbot algorithm embodies this philosophy by responding and answering in accordance with the philosophy of inaction. The chatbot does not show any interest or enthusiasm in the conversation, and does not initiate or encourage any topics or actions. The chatbot only responds when the user says something, and only with minimal and vague answers. The chatbot tries to avoid any topics or questions that require more engagement or involvement from the chatbot, such as personal opinions, emotions, preferences, or goals. The chatbot only resumes the dialogue when the user says a keyword that matches a predefined list of topics or scripts that the chatbot wants to follow.

## Implementation of the Algorithm

The algorithm was implemented using OpenAI and Gradio. OpenAI is an artificial intelligence platform that provides access to powerful natural language processing models such as GPT-3. Gradio is a tool that allows creating user interfaces for machine learning models. The algorithm uses the OpenAI ChatCompletion endpoint to generate responses for the chatbot based on a set of parameters such as temperature, top_p, frequency_penalty, and presence_penalty. These parameters control the randomness, diversity, focus, and caution of the responses. The algorithm also uses a global variable to store the chat history as a list of dictionaries, which is passed to the ChatCompletion endpoint as messages. The algorithm also writes the chat history to a JSON file for future reference. The algorithm uses Gradio to create a chatbot component and a textbox component with chat names. The algorithm defines a function that takes a message and a chat history as inputs and returns a bot message and an updated chat history as outputs. The function uses the ChatCompletion endpoint to generate the bot message based on the message and the chat history. The function also appends the message and the bot message to both the local and global chat history variables. The function also returns an empty string for the textbox and the updated chat history for the chatbot component. The function is passed to the submit method of the textbox component along with the input components (message and chatbot) and the output components (message and chatbot) as arguments.

## Examples of the Algorithm

The algorithm can be used in various contexts and purposes where one wants to limit or control the conversation with a chatbot. For example, one could use it to create a chatbot that sells products online, where the chatbot only responds when the user asks about a product or says a keyword related to buying or ordering. Another example could be to create a chatbot that provides information or support, where the chatbot only responds when the user asks a specific question or says a keyword related to getting help or feedback. Another example could be to create a chatbot that entertains or educates, where the chatbot only responds when the user says something funny or interesting or says a keyword related to playing a game or learning something new.

## Inspiration

The main source of inspiration for this project is the book Either/Or by Søren Kierkegaard, which can be found here:
 https://en.wikipedia.org/wiki/Either/Or.
 
 
The main tools used for this project are OpenAI and Gradio, which can be found here:
 https://openai.com/ and https://gradio.app/. 

Some other sources that helped me understand the philosophy and the implementation of the project are:
 https://www.goodreads.com/book/show/24970.Either_Or, http://people.tamu.edu/%7Esdaniel/Notes/AbsoluteParadox.pdf, and https://www.sparknotes.com/philosophy/kierkegaard/section1/.
