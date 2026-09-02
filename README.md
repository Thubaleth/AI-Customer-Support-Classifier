

AI Customer Support Classifier built with LangChain and OpenAI. Uses few-shot prompting to classify customer messages into categories such as Billing, Shipping, Returns, Account, and Technical Support.

README introduction
Writing
AI Customer Support Classifier

An AI-powered customer support message classifier built with LangChain and OpenAI.

The project uses few-shot prompting to teach an LLM how to classify customer messages into predefined support categories such as:

Shipping
Billing
Returns
Technical Support
Account
How It Works

The application provides the LLM with example question-and-answer pairs using LangChain's FewShotPromptTemplate. When a new customer message is provided, the model uses the examples to determine the appropriate category.

Example

Input:

I haven't received my refund yet.

Output:

Billing

Technologies
Python
LangChain
LangChain OpenAI
OpenAI API
python-dotenv
Concepts Practiced
PromptTemplate
FewShotPromptTemplate
Few-shot prompting
Prompt formatting
LangChain chains
LLM invocation
Environment variables
AIMessage.content
Example Flow
Customer Message
       ↓
Few-Shot Prompt
       ↓
LangChain
       ↓
OpenAI LLM
       ↓
Support Category


