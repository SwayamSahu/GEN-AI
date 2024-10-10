1) **Fine-Tuning Techniques**: 
   - **Standard Fine-Tuning**: Involves training a pre-trained model on a domain-specific dataset to adapt it for specific tasks[1][2].
   - **Feature-Based Fine-Tuning**: Utilizes the features of a pre-trained model as inputs for a new model, keeping most layers unchanged to save computational resources[1].
   - **Parameter-Based Fine-Tuning**: Updates the model's weights, either fully or selectively, enhancing adaptability but requiring more resources[1][3].
   - **Adapter-Based Fine-Tuning**: Introduces small modules within the model, allowing efficient training of additional parameters while keeping the rest fixed[1][4].
   - **Few-Shot and Zero-Shot Learning**: Adapts models with minimal or no task-specific data, relying on existing knowledge[2][5].

2) **Extracting Data from Structured Documents**: 
   - Use Optical Character Recognition (OCR) to convert scanned documents into text.
   - Implement regular expressions or parsing libraries (like `pandas` for tables) to identify and extract relevant fields such as invoice numbers, dates, and amounts.
   - Leverage Natural Language Processing (NLP) techniques to understand context and relationships between extracted data points.

3) **Chunking Strategies**:
   - **Fixed-Size Chunking**: Divides text into equal segments, useful for uniform data.
   - **Semantic Chunking**: Breaks text based on meaning or context, ideal for narrative data.
   - For semi-structured data like invoices, use semantic chunking to maintain the relationship between fields (e.g., grouping line items with their respective totals).

4) **Automation of Web Form-Filling**:
   - Utilize tools like Selenium or Puppeteer to automate browser interactions.
   - Write scripts that navigate to web forms, input data programmatically, and submit forms.
   - Implement error handling and logging to manage any issues during the automation process.

5) **Platforms for Deploying Python Code**:
   - **Cloud Platforms**: AWS Lambda, Google Cloud Functions, Microsoft Azure.
   - **Web Frameworks**: Flask, Django for building web applications.
   - **Containerization Tools**: Docker for creating portable applications.

6) **Tech/Tools/Framework Proficiencies**:
   - Familiar with machine learning libraries like TensorFlow and PyTorch.
   - Experienced in data manipulation with `pandas` and `NumPy`.
   - Proficient in web scraping tools like BeautifulSoup and Scrapy.

7) **Favorite AI Tool**:
   - Hugging Face Transformers is often favored for its extensive library of pre-trained models and ease of use in fine-tuning large language models.

Citations:
[1] https://labelyourdata.com/articles/llm-fine-tuning/llm-fine-tuning-methods
[2] https://www.datacamp.com/tutorial/fine-tuning-large-language-models
[3] https://www.ibm.com/topics/fine-tuning
[4] https://en.wikipedia.org/wiki/Fine-tuning_(deep_learning)
[5] https://www.superannotate.com/blog/llm-fine-tuning
[6] https://www.lakera.ai/blog/llm-fine-tuning-guide
[7] https://www.turing.com/resources/finetuning-large-language-models
