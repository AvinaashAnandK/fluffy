# Fluffy
![]()

Since the project is actively in exploration and development, there are a lot of winding codepaths, experiments, and
dead ends in the codebase. It is not production-grade yet for ANY definition of production.

🚧 <img src="https://img.shields.io/badge/under%20construction-FF8C00" /></a> <img src="https://img.shields.io/badge/under%20construction-FF8C00" /> </a><img src="https://img.shields.io/badge/under%20construction-FF8C00" /> </a><img src="https://img.shields.io/badge/under%20construction-FF8C00" /></a>
🚧

<p align="center"><img src="https://github.com/AvinaashAnandK/fluffy/blob/main/Fluffy_wb.png" width="400" height="400" /></p>

Fluffy aims to simplify the development process by reducing boilerplate code & infrastructure setup that devs need to handle while integrating open-source AI models into their applications to address problems they encounter while solving for their core business logic. 

## Context:
- [X] Current platforms like 'Papers with Code' or 'Hugging Face' primarily cater to Data Scientists and ML engineers. They are excellent at training, optimizing, and deploying models. 
- [X] However, for engineers, Product Managers, or technical founders, the process of finding, understanding, and quickly deploying the right models can be quite challenging.
    + Try searching for PAN number extraction from PAN card image on Google / Bing or Hugging Face, you would find it incredibly difficult to arrive at named entity recognition + OCR as one of the approaches for the question at hand
- [X] This need for efficient model deployment is common, both in early-stage startups & in larger orgs.
    + In early-stage startups engineers might lack specific data science experience
    + In larger companies certain data science initiatives might be deprioritized due to the organization's broader focus.

## Work so far:

- [X] Understand the data: Created a database of open source models from [HuggingFace](https://huggingface.co/), [Papers With Code](https://paperswithcode.com/) and other research labs such as [AI4Bharat](https://github.com/AI4Bharat)
- [X] Use semantic search to match business use-cases to Open Source models
    + 
- [X] [Deep dive on embeddings](https://vickiboykis.com/what_are_embeddings/)
  and [LaTeX Resource](https://vickiboykis.com/latex_resources/)
- [x] Deploy the baseline model to "prod" (aka a single server) and test it out. Word2Vec Demo:

https://user-images.githubusercontent.com/3837836/230725711-62d7b203-e4c3-4188-a9fd-14ea74db876e.mov

- [ ] Build a model [using BERT](https://github.com/veekaybee/viberary/tree/bert) and also deploy that and evaluate them
  against each other. In progress on the main branch.

https://github.com/veekaybee/viberary/assets/3837836/e25e2fee-a2bb-4c09-897c-10d672410dd1
