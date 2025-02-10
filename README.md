# Playing DeepSeek Examples

This repository contains practical examples showcasing interactions with various DeepSeek models, including different distilled versions of the DeepSeek-R1 models on Hugging Face. Ideal for developers looking to explore and utilize DeepSeek models in their projects.

* [Loading_DeepSeek_R1_Example_1.ipynb](https://github.com/easonlai/deepseek_examples/blob/main/Loading_DeepSeek_R1_Example_1.ipynb) - Sample of using the Transformers library to load the [DeepSeek-R1-Distill-Llama-8B](https://huggingface.co/deepseek-ai/DeepSeek-R1-Distill-Llama-8B) model from Hugging Face. And use the Transformers library to generate the response to the question.
* [Loading_DeepSeek_R1_Example_2.ipynb](https://github.com/easonlai/deepseek_examples/blob/main/Loading_DeepSeek_R1_Example_2.ipynb) - Sample of using the Transformers library to load the [DeepSeek-R1-Distill-Llama-8B](https://huggingface.co/deepseek-ai/DeepSeek-R1-Distill-Llama-8B) model from Hugging Face. And use the HuggingFacePipeline class from the LangChain-HuggingFace library to generate the question response with chain.
* [Fine_Tuning_DeepSeek-R1_Example_3.ipynb](https://github.com/easonlai/deepseek_examples/blob/main/Fine_Tuning_DeepSeek_R1_Example_3.ipynb) - Sample of using the Transformers library to load the [DeepSeek-R1-Distill-Llama-8B](https://huggingface.co/deepseek-ai/DeepSeek-R1-Distill-Llama-8B) model from Hugging Face for model fine-tuning with PEFT library by LoRa method. It used the sample dataset on HuggingFace ([easonlai/medical-common-diseases-reasoning-SFT](https://huggingface.co/datasets/easonlai/medical-common-diseases-reasoning-SFT)), a common disease reasoning COT dataset in traditional Chinese.

Enjoy!
