# Fluffy
![]()
🚧  <img src="https://img.shields.io/badge/under%20construction-FF8C00" /></a>  🚧

<p align="center"><img src="https://github.com/AvinaashAnandK/fluffy/blob/main/Fluffy_wb.png" width="200" height="200" /></p>

Fluffy aims to simplify the development process by reducing boilerplate code & infrastructure setup that devs need to handle while integrating open-source ML models into their applications to address problems they encounter while solving for their core business logic. 

Fluffy allows you treat open-source models like legos, mix-and-match to achieve the desired outcome, without worrying about the ops side of things!

## Context:
- Current platforms like 'Papers with Code' or 'Hugging Face' primarily cater to Data Scientists and ML engineers. They are excellent at training, optimizing, and deploying models. 
- However, for engineers, Product Managers, or technical founders, the process of finding, understanding, and quickly deploying the right models can be quite challenging and time consuming.
    + Try searching for PAN number extraction from PAN card image on Google / Bing or Hugging Face, you would find it incredibly difficult to arrive at named entity recognition + OCR as one of the approaches for the question at hand
- This need for efficient model deployment is common, both in early-stage startups & in larger orgs.
    + In early-stage startups, engineers might lack specific data science experience
    + In larger companies, certain data science initiatives might be deprioritized due to the organization's broader focus.

## Work so far:

- [X] Understand the data: Created a database of open-source models from [HuggingFace](https://huggingface.co/), [Papers With Code](https://paperswithcode.com/) and other research labs such as [AI4Bharat](https://github.com/AI4Bharat)
- [X] Build a semantic search model [using SBERT](https://www.sbert.net/) to match business use-cases to open Source models
    + Was unable to throw relevant results for search terms like "Detect blured images in documents", "Compress heavy audio files to support upload from low latency networks" and 'Identify profanity in hinglish texts' from the alpha test users. 
- [X] Refine the retrival model using [Generative Pseudo Labelling](https://github.com/AvinaashAnandK/GPL-Walkthrough) on a corpus of relevant text (e.g. articles from Towards Data Science and other blogs on data science) and evaluate against baseline model
    + Showed little to no improvement on the baseline model
- [X] Use Retrieval Augmented Generation (RAG) to provide users with relevant search results
    + Showed a significant improvement over baseline for alpha test users.
- [X] Test the feasibility of a python decorator package that wraps input functions to perform the desired task
    + Succesfully built a prototype for text extraction & machine translation tasks for an input function which takes in text / image as user input

## Coming soon:
- [ ] [In Progress] Use [Skeleton-of-Thought](https://arxiv.org/abs/2307.15337) approach to piece together base models that can be sequentially connected to address a user's business problem
- [ ] Dynamically create decorators that abstracts the deployment and connects the identified base models 
