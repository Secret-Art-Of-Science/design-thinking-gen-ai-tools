# Design Thinking Toolkit Prototypes
This just a bit of experimentation in mostly Jupyter Notebooks with using LangChain to conduct Design Thinking sessions
using a Panel of Experts using targeted vectorized information to build the right panel and giving it some basic tooling
to do them.  It's a blast!  It's not software engineering, it is prompt engineering! Or is it?  I am confused :-)

Have fun!  This isn't a project about the code, it is about the possibilities.

## Getting Started
Right now this just uses simple .env files to load up the API Keys for the OpenAI GPT Model.  You can switch the LLM 
easily but make sure you set the right variables or add code to get it right.  For OpenAI, you only need two pieces of 
information:

```shell
OPENAI_API_KEY="<Your Key>"
OPENAI_ORGANIZATION="<Your Org>"
```

You only need the `OPENAI_ORGANIZATION` if you use multiple Organizations in with your Open AI Key.  You can also set a 
default in your account.

That's it.  

## About the Design Thinking Session Types
The Agent will choose between a Six Thinking Hats Design Session, used when critiquing or providing feedback on something,
 and a "Yes And" Session which limits the panel of experts to only additive, constructive and positive ideas.  

## Future Ideas to Work On
* Building the panel of experts based on specific unstructured data sources
* Add retrieval of structured data
* Chaining Design Thinking Session types into a Design Thinking Workshop
* Simple UI Mockups applying a Semantic Design Language
