# An AI doctors without borders
shreyasl@stanford.edu

### Abstract
This research work focuses on building and evaluating a practical healthcare agent 
that can help patients in need, especially in low resource settings. We do this by
taking an existing large language model (LLM) and fine-tuning it on a dataset that
consists of healthcare questions that consumers often have. The model is then 
evaluated by comparing answers it provides to model answers. The model is further 
evaluated qualitatively by examining specific responses to prompts in the test-set
to assess hallucination. We find that although fine-tuning significantly improves
model performance, the model's practical use in low resource settings is 
limited by the nature of its hallucination and the slow speed of inference.

### About the code
The base directory contains code for 3 things
- Input processing and dataset shaping
- Output processing: making sense of the outputs
- Creating visualizations and statistics for the report

#### Fine-tuning, inference and zero shot results
This code exists in the corresponding directories in `runpod/`
