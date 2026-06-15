# Portfolio
---

## GAIA Agent
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/pierrebedu/GAIA_Agents) \
AI agent designed to automate business workflows by handling multi-step tasks across diverse data sources.
Extracts and processes information from documents, audio, video, and web data to enable use cases such as report generation, invoice data extraction, and competitive intelligence.
Reduces manual workload and improves productivity across operations, finance, and support teams.

Langfuse observability for performance evaluation on GAIA dataset and debugging.

## RAG/Agents architecture

Modular, scalable, and cloud-agnostic GenAI architecture with reusable components (Docker-based).
Includes robust tool-calling (retries, error handling) and gated CI/CD driven by performance improvements on benchmark datasets.
== work in progress ==

## QAmemBERT

[![View on Hugging Face](https://huggingface.co/datasets/huggingface/badges/resolve/main/model-on-hf-md.svg)](https://huggingface.co/CATIE-AQ/QAmembert)

QAmemBERT is simply the best performing QA model in French according to the benchmarks ! \
It is available in two sizes ([base](https://huggingface.co/CATIE-AQ/QAmembert) and [large](https://huggingface.co/CATIE-AQ/QAmembert-large))  and is freely available on Hugging Face. 

I gathered the data and build the scripts for training it, evaluated the results during the POC phase. It was developed in collaboration with [Loïck Bourdois](https://lbourdois.github.io/) and [Boris Albar](https://fr.linkedin.com/in/boris-albar).

---

## Multimodal RAG pipeline

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/catie-aq/multimodal_RAG_with_VLMs) \
This is my personnal take on multimodal RAG : modern method working on pdfs at the page level, no tedious document parsing !  Runs locally.

Script for fine tuning a Multimodal Langage Model (Idefics3) in French. \
Script for fine tuning a multimodal embedding model of type ColPali.



---
## Realtime object detection with a camera

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/pierrebedu/experiment_k) \
Code to run realtime object detection with a camera on cpu, FastAPI, unit test,exceptions , dataset creation, training... (docker or systemctl)


---

## Scoring app with explainability
Copy of a scoring app i made for a client. \
[app here!](https://scoring-app-km5j.onrender.com)\
Gradient boosting algorithms run in the backend to predict the probability of success/failure of a quotation.Shpa valuez for explainability of the prediction. \
Takes about 5 min to launch(free hosting), but works great.

--- 

## Quantization pipeline

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/catie-aq/infere-anything-FAST) \
Quantize any onnx model and run inference FAST ! 

fp16 or INT8 quantization 

---

## Efficient ML/DL presentation
[View the PDF presentation](https://github.com/pierrebedu/portfolio/blob/main/techintome_efficientML_public_version.pdf) \
Here is the link for an internal talk~workshop  I gave in 2023 to datascientists, data engineers and developers. \
Very little text, but a lot to tell and discuss! 

Include a guessing game to keep everyone attentive.

---

