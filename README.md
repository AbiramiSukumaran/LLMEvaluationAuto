# LLMEvaluationAuto
This lab evaluates a foundation model and fine tuned model based on Automatic Metrics of model results on the evaluation data and you will use the following Google Cloud products:  Vertex AI Pipelines Vertex AI Evaluation Services Vertex AI Model Registry Vertex AI Endpoints

# Model Evaluation with Vertex AI
LLMOps, or Large Language Model Operations, is an important methodology as organizations increasingly adopt large language models (LLMs) for a wide range of applications. LLMOps is the set of tools, processes, and best practices for managing the lifecycle of LLMs, from development and deployment to monitoring and maintenance. Vertex AI offers services to manage LLMOps pipelines as also mechanisms to evaluate the new models quality after every pipeline execution that you run.

In the realm of Generative AI, evaluation is a critical aspect of assessing the quality and relevance of the generated text. It involves examining the output from a generative language model to determine its coherence, accuracy, and alignment with the provided prompt. Model evaluation helps identify areas for improvement, optimize model performance, and ensure that the generated text meets the desired standards for quality and usefulness. Read more about it in the official [documentation]([url](https://cloud.google.com/vertex-ai/docs/generative-ai/models/evaluate-models)).

# Objective

This lab teaches you how to evaluate a foundation model or a fine tuned model based on Automatic Metrics of model results on the evaluation data and you will use the following Google Cloud products:

Vertex AI Pipelines
Vertex AI Evaluation Services
Vertex AI Model Registry
Vertex AI Endpoints

# Use Case & Dataset

Using Generative AI we will evaluate a model that generates a suitable TITLE for a news BODY from BBC FULLTEXT DATA (Sourced from BigQuery Public Dataset bigquery-public-data.bbc_news.fulltext). The evaluation will cover both foundation (text-bison@002) and fine tuned (called "bbc-news-summary-tuned") models with the automatic metrics method. The sample evaluation dataset is published in this repo as a JSONL file.

# Steps

Prepare data

Load Fine Tuned Model

Evaluate Fine Tuned Model

Load Base Model

Evaluate Base Model

Compare

Visualize in Google Cloud Console and in Cloud Storage Bucket
