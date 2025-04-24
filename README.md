# EIMM Project

This project facilitates interaction with different AI models by managing prompts.

## Usage

1.  **Select a Model:** Choose the desired model from the `models/` directory (e.g., `models/1.Opportunity_Cost_Model/`).
2.  **Copy Model Prompt:** Open the prompt file for your selected language within the model's directory (e.g., `zh.txt` for Chinese, `en.txt` for English). Copy the entire content of this file.
3.  **Update Base Prompt:**
    *   Open the corresponding base prompt file in the `prompts/` directory (`prompts/base_prompts_zh.txt` for Chinese, `prompts/base_prompts_en.txt` for English).
    *   Navigate to line 48 (or the designated integration point).
    *   Paste the copied model prompt content at this location.
4.  **Interact:** Use the updated base prompt file (`prompts/base_prompts_zh.txt` or `prompts/base_prompts_en.txt`) as input for your AI interaction.

## Directory Structure:

*   `models/`: Contains different AI model definitions, each typically with language-specific prompt files (`zh.txt`, `en.txt`, etc.).
*   `prompts/`: Contains the base prompt files (`base_prompts_zh.txt`, `base_prompts_en.txt`) where model-specific prompts are integrated.
*   `README.md`: This file.
*   `README_zh.md`: Chinese version of this README.

## Base Prompts

*   [`base_prompts_zh.txt`](prompts/base_prompts_zh.txt): Base prompts in Chinese.
*   [`base_prompts_en.txt`](prompts/base_prompts_en.txt): Base prompts in English.

## Model List

*   [`1.Opportunity_Cost_Model`](models/1.Opportunity_Cost_Model/README.md): Opportunity Cost Mental Model
