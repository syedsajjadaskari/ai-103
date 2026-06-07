# ai-103

This repository contains the Translator tool assets from the `Foundry-Tools/Translator` workspace.

## Included files

- `Translator/foundry-translator.ipynb` - Jupyter notebook for Foundry Translator demo and deployment flow.
- `Translator/deploy-translator.json` - Foundry ARM template for deploying the Translator tool.
- `Translator/deploy-translator.parameters.json` - Parameters file for the Translator deployment.

## Setup

1. Copy `Translator/.env.example` to `Translator/.env`.
2. Fill in `TRANSLATOR_ENDPOINT` and `TRANSLATOR_REGION` with your Azure Translator/Foundry values.
3. Open `Translator/foundry-translator.ipynb` in Jupyter or VS Code.

## Notes

- `.env` is excluded from source control to keep credentials secure.
- Use the deployment template and parameters to deploy the Foundry Translator tool as needed.
