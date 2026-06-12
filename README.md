# Decodelabs_week2
# Chain-of-Thought (CoT) Logic Engine

## Project Overview

This project was developed as part of the DecodeLabs Prompt Engineering Industrial Training Program. The objective was to design and evaluate a Chain-of-Thought (CoT) Logic Engine capable of solving multi-step reasoning problems accurately while reducing logical errors and hallucinations.

The prompt was designed to guide the AI through a structured reasoning process that includes identifying relevant information, ignoring distractions, performing step-by-step analysis, and verifying the final answer before responding.

---

## Objective

The primary objective of this project was to create a prompt that:

* Encourages explicit step-by-step reasoning.
* Reduces logical and calculation errors.
* Filters irrelevant information.
* Implements a self-correction mechanism.
* Produces verified and reliable answers.

---

## Prompt Architecture

The Logic Engine follows the workflow below:

1. Problem Understanding
2. Information Extraction
3. Irrelevant Information Filtering
4. Step-by-Step Reasoning
5. Self-Correction and Verification
6. Final Verified Answer

This structure ensures that the model reasons systematically rather than relying on intuitive guesses.

---

## Test Cases Used

The prompt was evaluated using five reasoning-focused test cases:

1. Bat and Ball Problem
2. Machines and Widgets Problem
3. Lily Pad Growth Problem
4. Irrelevant Context Identification
5. Percentage Increase and Decrease Problem

These questions were selected because they commonly expose weaknesses in reasoning and often lead to incorrect intuitive answers.

---

## Results Comparison

| Test Case                            | Expected Answer | Model Answer | Status |
| ------------------------------------ | --------------- | ------------ | ------ |
| Bat and Ball Problem                 | ₹5              | ₹5           | ✅ Pass |
| Machines and Widgets Problem         | 5 Minutes       | 5 Minutes    | ✅ Pass |
| Lily Pad Growth Problem              | Day 47          | Day 47       | ✅ Pass |
| Irrelevant Context Question          | Delhi           | Delhi        | ✅ Pass |
| Percentage Increase-Decrease Problem | ₹96             | ₹96          | ✅ Pass |

### Overall Performance

* Total Test Cases: 5
* Passed: 5
* Failed: 0
* Accuracy: 100%

---

## Key Features

* Chain-of-Thought Reasoning
* Logical Problem Decomposition
* Context Filtering
* Self-Correction Mechanism
* Calculation Verification
* Hallucination Reduction

---

## Technologies Used

* Google AI Studio
* Prompt Engineering
* Chain-of-Thought Reasoning
* GitHub

---

## Learning Outcomes

Through this project, I gained hands-on experience in:

* Designing structured reasoning prompts.
* Evaluating Large Language Model behavior.
* Building self-correcting prompt workflows.
* Testing AI systems using logic-based benchmarks.
* Improving answer reliability through prompt engineering techniques.

---

## Conclusion

The Chain-of-Thought Logic Engine successfully improved reasoning accuracy by guiding the model through a structured problem-solving process. By combining information filtering, step-by-step reasoning, and self-verification, the prompt was able to correctly solve all test cases used in the evaluation.

This project demonstrates how effective prompt engineering can enhance the reasoning capabilities of Large Language Models and reduce common logical errors in AI-generated responses.
