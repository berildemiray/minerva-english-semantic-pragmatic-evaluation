[README_llm_prompt_comparative_evaluation.md](https://github.com/user-attachments/files/27553265/README_llm_prompt_comparative_evaluation.md)
# Prompt-based Comparative Evaluation of the Minerva and Gemini Outputs
Conducted by: Tutku Beril Demiray

## Project title
**Prompt-based Comparative Evaluation of the Semantic and Pragmatic Competence of Minerva and Gemini**

## Research Aim
This project comparatively evaluates the semantic and pragmatic competence of the LLMs Minerva and Gemini with regard to semantic ambiguity, pragmatic inference, figurative meaning and register-sensitive language. The main aim is to test Minerva’s English-language competence, given that its primary functional language is Italian. The project aims to identify and analyse semantic and pragmatic failures or limitations of Minerva in order to contribute to its improvement in the English context.

## Research Question
When compared to Gemini, to what extent does Minerva correctly interpret meaning beyond literal sentence form in English, especially in cases involving ambiguity, implicature, metaphor and register adaptation?

## Significance of the Project
This project is significant because such a bilingual AI LLM model should produce responses in English that are nearly as accurate, semantically and pragmatically competent as those generated in Italian.

## Dataset
The dataset contains 40 English prompts divided into four categories:
1. Semantic ambiguity
2. Pragmatics
3. Metaphor / figurative meaning
4. Register / style

Each prompt includes:
- linguistic phenomenon
- concept tested
- prompt text
- expected strong answer
- success criterion

## Tested Models
- Minerva
- Gemini

## Methodology
Each prompt was manually tested on both models. Responses were evaluated using the following rubric:
- 0 = incorrect
- 1 = partially correct
- 2 = fully correct

## Main Findings
Minerva consistently underperformed Gemini in:
- contextual interpretation
- pragmatic inference
- figurative language understanding
- register adaptation

Minerva demonstrated stronger literal processing tendencies and weaker semantic and pragmatic reasoning.

## Limitations
- Small dataset
- Subjective manual scoring
- No automatic evalutation metrics
- Output variability across sessions

## Files
- `llm_prompt_based_comparative_evaluation_project.xlsx`: full project with mini introduction, prompts, rubric, evaluation and results.
- `prompts_dataset.csv`: prompt dataset only.

## Notes
This project has been independently conducted by the author for academic and research purposes. The project does not claim ownership over any evaluated AI systems or their generated outputs and is intended solely for educational, analytical and non-commercial research purposes.
