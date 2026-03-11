# An evaluation of automated knowledge graph population from unstructured task descriptions using LangExtract.
## Potential RQ's
1. Can LangExtract be used effectively with unstructured text to populate an existing KG? 

2. What are the shortfalls of using LangExtract for this use case?

3. What is the performance varation between LLM models for this use case? 
## Introduction
## Background
## Merit
## Novely 
## Timeliness
## Impact
## Proposed work
1. Analyze NIST taskboard instruction files and create an expected output used for evaluation. 
2. Convert unstructured NIST taskboard instruction files into plain text.
3. Use LangExtract to extract entities from the plain text, aligned to the task-goal module of the ontology. 
  **Note**: LangExtract requires one to few examples to be effective. 
4. Map entities and attributes to their respective classes. (not sure the best way to do this. Another LLM?)
5. Populate KG via a SPARQL query (INSERT?). 
6. Evaluate the success of the output vs expected output. 
7. Repeat steps 3 through 6 for each model. 

## Timeline
# References
[Youtube - LangExtract for NLP](https://www.youtube.com/watch?v=t-53fouKqWI)
[Github - LangExtract](https://github.com/google/langextract?tab=readme-ov-file#introduction)