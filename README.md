# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm
1. Input Preparation:

  Select the source text: a 500-word article “The Basics of Blockchain Technology”.
  
  Define evaluation criteria: accuracy, coherence, simplicity, speed, UX.

2. Prompting Setup:

  Zero-shot: “Summarize the following article in simple terms for undergraduates.”
  
  Few-shot: Provide 2–3 examples of good summaries, then the target text.
  
  Chain-of-thought: “Think step by step. Identify key concepts, then form a short summary.”
  
  Role-based: “You are an educator preparing content for undergraduates. Summarize clearly and simply.”

3. Platform Testing:

  Run each prompting technique across ChatGPT, Gemini, Claude, Copilot.
  
  Record response quality, time taken, and interaction ease.

4. Evaluation:

  Form a rubric (1–5 scale) for each criterion.
  
  Ask 2–3 independent reviewers (or your team) to rate each output.
  
  Collect average scores.

5. Analysis:

  Compare results across platforms and prompting strategies.
  
  Identify top-performing combinations.

<img width="1186" height="467" alt="image" src="https://github.com/user-attachments/assets/f569f29d-b7c0-4d24-99b9-dd04f2ca6771" />

## Result
1. Observation:

  Few-shot + ChatGPT produced highly accurate and coherent summaries.
  
  Role-based + Claude gave the most student-friendly (simple, clear) outputs.
  
  Chain-of-thought + Gemini ensured logical structuring but was slower.
  
  Zero-shot + Copilot was the fastest but less accurate.

2. Conclusion:

  The best balance of accuracy, coherence, and simplicity was achieved with Role-based prompting on Claude.
  
  For speed-critical tasks, Zero-shot on Copilot is preferable.
  
  For detailed accuracy, Few-shot on ChatGPT is recommended

