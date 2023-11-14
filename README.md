# Azure Open AI Example Scenarios

## Getting Started

### Set environment variables

To use the Azure Open AI Endpoint you need to set an API key. To set this API key you will need to run the following CLI command before executing the notebooks.

```bash
export OPENAI_API_KEY=<your-api-key>
```

These environment variables are used to connect to your Azure OpenAI resource. You can find the values for these variables in the Azure portal.

### Run the Notebooks

Open the jupyter notebooks and run the notebook. Ensure you run this notebook in the conda environment you created earlier. Consider running the notebooks in the following order:

- [`00-aoai-parameters.ipynb`](core/00-aoai-parameters.ipynb)
- [`01-word-embeddings.ipynb`](core/01-word-embeddings.ipynb)
- [`02-prompt-engineering-best-practices.ipynb`](core/02-prompt-engineering-best-practices.ipynb)
- [`03-prompt-engineering.ipynb`](core/03-prompt-engineering.ipynb)

## Resources

- [Azure OpenAI Documentation](https://learn.microsoft.com/azure/cognitive-services/openai/overview/)
