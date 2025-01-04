# Fine-Tuned BERT for Named-Entity Recognition (NER) using Transformers and PyTorch

In this notebook, the process of fine-tuning a pre-trained **BERT-based model** (**DistilBERT**) for the task of **Named-Entity Recognition (NER)** will be explored. NER is a fundamental task in **Natural Language Processing (NLP)** that involves identifying entities such as persons, locations, and organizations in text.

## Why Fine-Tune BERT for NER?

Pre-trained models like **BERT** and **DistilBERT** are general-purpose language models trained on vast amounts of text data. However, for domain-specific tasks like NER, fine-tuning is essential to adapt the model to the specific task requirements and dataset. This enables the model to achieve higher accuracy by leveraging task-specific labeled data.

## How to Fine-Tune BERT?

This notebook demonstrates two approaches to fine-tuning:

1. **Trainer API from the Transformers Library**  
   The first method utilizes the **Trainer API** provided by the **Transformers** library, which simplifies the fine-tuning process.
   
2. **Custom Training Loop with PyTorch**  
   The second method involves implementing a custom training loop using **PyTorch** for greater flexibility and control.

Both models will be trained and evaluated, followed by predictions using the trained models.

## Steps

0. **Install the basic libraries**  
   - Transformers, Datasets, and Evaluate libraries.

1. **Load and understand the dataset**  
   - Gain insights into the data used for the NER task.

2. **Preprocess the data**  
   - Transform the data to make it compatible with the model.

3. **Fine-tune the model using the Trainer API**  
   - Fine-tune the model with the built-in Trainer API for simplicity.

4. **Fine-tune the model using a custom PyTorch implementation**  
   - Implement a custom training loop for more control over the training process.

5. **Make predictions using the pipeline API on the Trainer API fine-tuned model**  
   - Use the trained model with the pipeline API to make predictions.

6. **Make predictions using the PyTorch fine-tuned model**  
   - Similarly, use the PyTorch fine-tuned model to make predictions.

## Model Availability

The model is saved on my account of HuggingFace. It can be imported and used in your own projects. For example, see Step 5 for instructions on how to load and use the model.

- [Wencho/distilledbert-finetuned-ner](https://huggingface.co/Wencho/distilledbert-finetuned-ner)


