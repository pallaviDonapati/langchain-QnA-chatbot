# llm-Q-A-application

This project demonstrates the use of **LangChain** to integrate multiple language models, including OpenAI and Hugging Face, for building text-based applications. It covers essential functionalities such as creating prompt templates, chaining tasks, and developing a simple chatbot using Streamlit.

### Project Overview

1. **Language Model Integration**  
   - The project uses OpenAI's GPT-based models and Hugging Face's models for various tasks, such as answering questions and generating creative text. 

2. **Prompt Design**  
   - Prompts are customized to interact with language models effectively. For instance, users can input a country name, and the system will fetch its capital and suggest notable places to visit.

3. **Chaining Functions**  
   - Tasks are linked in sequential workflows, where one model output becomes the input for the next. For example, the capital of a country is identified first, followed by recommendations for popular tourist destinations in that capital.

4. **Streamlit Interface**  
   - A simple web application lets users input questions and receive responses from OpenAI models. It makes interacting with the project easy and user-friendly.

5. **Custom Output Parsers**  
   - Includes examples of parsing outputs, like splitting synonyms into a list format.

6. **Demonstrating Creativity**  
   - The models generate poems and even deliver jokes, showcasing their ability to handle creative tasks.

### Features
- Combine models for question answering, poetry, and chain-based logic.
- Use of deprecation handling for smoother migration to updated packages.
- Simple sequential chains and chatbot creation.

This project highlights how to use AI tools practically for solving real-world text-processing tasks. It provides a great starting point for developers interested in building language-driven applications.
