# Objective

Wouldn't it be wonderful to have a magical drive that would autonomously create the content of documents based on their name?


# How It Works<a name="how-it-works"></a>

1. It mounts Virtual Drive
2. When empty file is created, it reads EXTENSION and FILENAME
3. Select best plugin to serve EXTENSION
4. DOCX - it will send FILENAME to OpenAI, to generate document based on FILENAME

[![Pierwszy test](http://img.youtube.com/vi/bHabB_6NGrA/0.jpg)](https://youtu.be/bHabB_6NGrA "Pierwszy test")

#  Roadmap

- ✔️ First public commit
- ❌ Creating Images .jpg .png from filename
- ❌ Configuration portal
- ❌ Database integration
- ❌ Magic folders ex. Split PDFs, Cut background from image




# Supported Models<a name="supported-models"></a>

This script works with all OpenAI models. Default model is **gpt-3.5-turbo**. To use a different model, specify it through LLM_MODEL or use the command line.

## Llama

❌ TODO

# Contribution

Needless to say, Vector Drive is still in its alpha and thus we are still determining its direction and the steps to get there. To maintain this simplicity, we kindly request that you adhere to the following guidelines when submitting PRs:

- Focus on small, modular modifications rather than extensive refactoring.
- When introducing new features, provide a detailed description of the specific use case you are addressing.

# License

Vector Drive is distributed on a GPL License.
