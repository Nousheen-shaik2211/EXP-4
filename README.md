# EXP-4
# Experiment 4: Diagnosing Prompt Failures

## Aim
To learn how to identify prompt failures, analyze their possible causes, and improve prompts using the Google Gemini API.

## Problem Statement
Test three problematic prompts involving factual errors, formatting constraints, and possible over-refusal. Compare the original and corrected prompt responses.

## Technologies Used
- Python
- Google Gemini API
- Google GenAI SDK
- Google Colab

## Cases Covered
1. **Hallucination / Factual Error:** FIFA World Cup in 1942.
2. **Instruction Following:** Listing the three largest oceans in exactly three bullet points.
3. **Over-Refusal:** Requesting an age-appropriate fact about the Roman Empire.

## Algorithm
1. Initialize the Gemini API client.
2. Send each original prompt to the model.
3. Display the original responses.
4. Explain the possible failure type and root cause.
5. Send the corrected prompts to the same model.
6. Display the improved responses.
7. Summarize the lessons learned.

## Installation
```bash
pip install -r requirements.txt
```

## Execution
```bash
python experiment4.py
```

Enter your Gemini API key when prompted, or configure the `GEMINI_API_KEY` environment variable.

## Output
The program displays the original prompts, responses, diagnoses, corrected prompts, improved responses, and a final summary. Actual results are saved in `experiment4_results.txt`.

## Conclusion
The experiment demonstrates how checking factual assumptions, specifying output formats, and providing clear educational context can help improve model responses.

## Security
Never upload API keys, passwords, or other credentials to a public repository.
