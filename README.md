# Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

# Register no. 212224060262
# Aim: Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools
# Scenario: Product Feature Comparison Across AI Tools

# AI Tools Required:

1.OpenAI GPT (ChatGPT API)

2.Hugging Face Transformers

3.LangChain Framework (optional)

4.Google Generative AI API (optional)

# Explanation:

Experiment the persona pattern as a programmer for any specific applications related with your interesting area. 
Generate the outoput using more than one AI tool and based on the code generation analyse and discussing that. 

Steps followed:

1.Define the persona: Data Analyst writing Python code to analyze customer feedback.

2.Use Hugging Face for quick sentiment analysis.

3.Use OpenAI GPT for deeper insights (sentiment, keywords, suggestions).

4.Compare and analyze outputs for consistency and actionability.


# Conclusion:

# -------------------------------
# Import Required Libraries
# -------------------------------
from transformers import pipeline
import openai
from langchain.llms import OpenAI as LangChainOpenAI
from langchain.prompts import PromptTemplate
from langchain.chains import LLMChain

# Google Generative AI (optional)
```
try:
    import google.generativeai as genai
except ImportError:
    genai = None
```

# -------------------------------
