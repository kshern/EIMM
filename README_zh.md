# EIMM 项目

本项目基于万物皆模型，每天引入一个新思维模型，将思维模型转成prompt


## 用法

1.  **选择模型：** 从 `models/` 目录中选择您想要使用的模型（例如 `models/1.Opportunity_Cost_Model/`）。
2.  **复制模型提示：** 在所选模型的目录中，打开对应语言的提示文件（例如中文选择 `zh.txt`，英文选择 `en.txt`）。复制该文件的全部内容。
3.  **更新基础提示：**
    *   打开 `prompts/` 目录中对应的基础提示文件（中文为 `prompts/base_prompts_zh.txt`，英文为 `prompts/base_prompts_en.txt`）。
    *   导航到第 48 行（或指定的整合位置）。
    *   将复制的模型提示内容粘贴到此处。
4.  **交互：** 使用更新后的基础提示文件（`prompts/base_prompts_zh.txt` 或 `prompts/base_prompts_en.txt`）作为与 AI 交互的输入。

## 目录结构：

*   `models/`: 包含不同的 AI 模型定义，每个模型通常包含特定语言的提示文件（`zh.txt`, `en.txt` 等）。
*   `prompts/`: 包含基础提示文件（`base_prompts_zh.txt`, `base_prompts_en.txt`），用于整合特定模型的提示。
*   `README.md`: 本文件（英文版）。
*   `README_zh.md`: 本文件的中文版本。

## 模型列表

*   [`1.Opportunity_Cost_Model`](models/1.Opportunity_Cost_Model/README_zh.md): 机会成本思维模型
