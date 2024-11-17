# README: LLM Agent for Summarizing a 10K Documents

## Overview
- This Jupyter Notebook showcases a LLM (Large Language Model) agent to summarize 10K documents effectively.
- In this example, Colgate Coprporation 10-K document is used as a proof of concept.
- The final output of summary can be seen at the end of the Jupyter notebook.

## Goal
- The goal is to facilitate and reduce the time spent on reading 10-K documents which are known to be quite lengthy.
- The prompt offers quick insights to:
  - Key Financial Metrics
  - Major Risks
  - Management Insights
  - Significant Events

## Summarisation Method
- The method used to summarise the document is using "Best Representation Vectors".
- Essentially, creates a summary of summaries, capturing key sentences and grouping semantically similar sentences.
- This way we reduce significantly the number of tokens, and create a cost effective OpenAI API calls.

