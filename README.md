# SLANGCASTIC: Evaluating Human-LLM Alignment on Sarcasm and Sentiment in Generation Z Slang
This repository serves as a complete archive of the data, code, and methodology used to investigate how well Large Language Models (LLMs) detect and interpret Generation Z sarcastic slang compared to human baselines in sarcasm detection and sentiment analysis tasks.

What's Included in This Repository:
1. **Code folder:** Python scripts used to interface with the LLMs;
2. **Slangcastic Dataset:** 200 sarcastic and non-sarcastic tweets;
3. **Slangcastic Dataset and Annotations:** 200 sarcastic and non-sarcastic tweets with LLMs' side-by-side outputs and human annotations;
4. **Human Annotation Questionnaire folder:**  Online Google Form used to gather the human baseline data. This includes the evaluation rubric and the samplers used to ensure consistent grading among participants, and notes that the questionnaire is separated into two PDFs. Please download the PDF if the preview is not available.

**Abstract:**
Large language models (LLMs) have become increasingly capable of processing informal language, yet their interpretation and alignment of sarcastic slang with humans remain underexplored. This study introduces SLANGCASTIC, a fine-grained English dataset comprising 200 tweets embedded with Generation Z sarcastic and non-sarcastic slang, annotated by eight human raters for sarcasm and sentiment. We evaluate six LLMs (GPT-4.1, GPT-5.1, GPT-OSS-20B, GPT-OSS-120B, Gemini-2.5-Flash, and Gemini-2.5-Pro) and compare their ratings with those of human annotators. Findings reveal that while newer models, such as GPT-5.1, show high overall agreement with humans, they all systematically over-annotate sarcasm and assign more negative sentiment. Qualitative analysis suggests this discrepancy arises because LLMs tend to over-reason and overanalyze semantic details. In contrast, human annotators rely on holistic, pragmatic reasoning to infer the speaker’s true intent. Therefore, the findings suggest that LLM-based moderation systems should account for cultural and contextual understanding when interpreting slang rather than relying solely on surface-level cues.

This paper is in press in the *Proceedings of the 5th Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics and the 15th International Joint Conference on Natural Language Processing: Student Research Workshop (AACL-IJCNLP)*.
