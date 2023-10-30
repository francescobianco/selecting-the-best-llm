# Selecting the best LLM

Today, having access to one or more Large Language Models (LLMs) for your projects is essential. The case of the [Cheshire Cat](https://github.com/cheshire-cat-ai/core) project highlights the potential to build highly advanced features when you have access to an LLM. That said, understanding which LLM is the best fit for your needs is crucial. In this repository, we present a grid to help you make an informed choice based on your skills, budget, ambitions, and more.

## LLM Metrics

| Service                        | Service Cost | Hardware Cost | Tech Skill | ML Skill | Maintenance |
|--------------------------------|--------------|---------------|------------|----------|-------------|
| Self-hosted llama-cpp-python   | 3            | 3             | 4          | 4        | 4           |
| OpenAI ChatGPT                 | 3            | 0             | 3          | 3        | 2           |
| OpenAI GPT-3                   | 4            | 0             | 4          | 4        | 2           |
| Cohere                         | 2            | 0             | 2          | 2        | 1           |
| HuggingFace Hub                | 1            | 0             | 2          | 2        | 1           |
| HuggingFace Endpoint           | 2            | 0             | 3          | 3        | 2           |
| HuggingFace TextGen Inference  | 2            | 0             | 3          | 3        | 2           |
| Azure OpenAI Completion models | 3            | 3             | 3          | 4        | 3           |
| Azure OpenAI Chat Models       | 3            | 3             | 3          | 4        | 3           |
| Anthropic                      | 4            | 2             | 4          | 4        | 3           |
| Google PaLM                    | 4            | 3             | 4          | 4        | 3           |
| Custom LLM                     | 4            | 2             | 3          | 4        | 3           |

| Metrics          | "0" Means                           | "1" Means               | "2" Means            | "3" Means             | "4" Means                | 
|------------------|-------------------------------------|-------------------------|----------------------|-----------------------|--------------------------|
| Service Cost     | No montly or annual payments        | Less than 50$/year      | Less than 100$/year  | Less than 200$/year   | More than 500$/year      |
| Hardware Cost    | No dedicated hardware are needed    | Only CPUs               | Mush have a good GPU | Hosted GPU in Cloud   | Advanced Cloud           |
| Tech Skill       | No programming skill or sys admin   | Just python             | Pro python developer | Basic DevOps and IaC  | Pro DevOps and IaC       |
| ML Skill         | No ML skills needed                 | Just manage model files | Work with training   | Pro ML skills         | Pro ML and Domain Espert |
| Maintenance      | No maintenance needed               | Just update software    | Soft tuning on scale | Hard tuning on scale  | Human supervisor needed  |

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
