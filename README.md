# News Summarization with Large Language Models

This repository contains a Jupyter notebook that demonstrates how to fetch the latest news articles and summarize them using Large Language Models (LLM). By leveraging the power of LLM, you can quickly extract key information from news articles and generate concise summaries.

## Overview

The notebook `NewsScrapper.ipynb` provides a step-by-step guide on fetching news articles from reliable sources using APIs and then utilizing LLM to generate summaries. It showcases how LLM can effectively process and condense large amounts of text into concise and meaningful summaries.

This project utilizes a combination of powerful technologies and tools to create an efficient news summarization system. The key components involved in the development process include:

- LangChain Agents: Leveraging the capabilities of LangChain Agents to facilitate efficient communication and coordination between different components.
- OpenAI-Functions: Harnessing the functionalities provided by OpenAI-Functions to automatically detect when a function should be called and respond with the inputs that should be passed to the function.
- ChatGPT: Utilizing ChatGPT, a cutting-edge language model developed by OpenAI, to generate high-quality summaries.
- Prompt-Engineering: Employing prompt engineering techniques to optimize the input prompts and improve the quality of generated summaries.
- NewsData API: Utilizing the NewsData API to fetch the latest news articles for summarization.
- Python: Implementing the entire system using the Python programming language, enabling flexibility, ease of use, and a vast ecosystem of libraries and tools.

By combining these technologies and tools, we have developed a robust and efficient news summarization solution that showcases the power of language models and enables users to extract key information from news articles effectively.

## Prerequisites

To run the notebook, you need the following dependencies:

- Python 3.10
- Jupyter Notebook
- Required Python packages (specified in `requirements.txt`)

## Getting Started

1. Clone this repository to your local machine.
2. Install the required dependencies by running the following command:
   ```
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook and open the `NewsScrapper.ipynb` notebook.
4. Follow the instructions provided in the notebook to fetch news articles and generate summaries using LLM.

## Limitations

Currently, the word restriction functionality does not work accuratley in terms of word limit. While the overall summarization process functions smoothly, the word limit for the generated summaries may not be accurately enforced.

We encourage you to contribute to this project and help improve the word restriction functionality. By addressing this limitation, we can enhance the accuracy and usefulness of the generated summaries.

Your contributions and insights are greatly appreciated as we work together to enhance the capabilities of news summarization using Large Language Models.


## Contributing

Contributions to this repository are welcome! If you have any ideas, improvements, or bug fixes, feel free to submit a pull request. Please ensure that your contributions align with the project's coding style and guidelines.

## License

This repository is licensed under the [MIT License](LICENSE). Feel free to use the code and modify it according to your needs.

## Acknowledgments

We would like to thank the contributors and developers of the libraries and tools used in this project. Their valuable work makes projects like this possible.