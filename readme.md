## Visual Data Interpretation and Analysis with LLM Integration

### Description
This collaborative notebook aims to advance the automated analysis of data visualizations, including bar charts, pie charts, and time series plots. By leveraging the Huggingface library and Google's [DePlot](https://huggingface.co/google/deplot), visual data is translated into linearized tables. This structured data is then processed using Microsoft's pretrained Small Language Model ([Phi-3](https://huggingface.co/microsoft/Phi-3-mini-4k-instruct-gguf/blob/main/Phi-3-mini-4k-instruct-q4.gguf)), which utilizes its few-shot reasoning capabilities for generating accurate summaries and answering user queries. Additionally, the LangChain framework is employed for prompt tuning and optimizing text generation tasks, ensuring precise and relevant output from the language model.

You can use any valid input data visual image for text summarization and question answering tasks. This integration streamlines the interpretation of complex data visualizations and facilitates interactive user engagement with the visual data through question-answering functionalities.

### Tech Stack Used
Huggingface Library, Google's DePlot, Microsoft's Small Language Model (Phi-3), LangChain Framework, Python
