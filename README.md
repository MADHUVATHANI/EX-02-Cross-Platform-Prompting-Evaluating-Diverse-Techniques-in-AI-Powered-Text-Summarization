# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization
### Name : MADHUVATHANI V
### Reg.No : 212223040107
## AIM

To evaluate and compare the effectiveness of different **prompting techniques**—**Zero-shot**, **Few-shot**, **Chain-of-Thought**, and **Role-based prompting**—across multiple **AI platforms** such as ChatGPT, Gemini, Claude, and Copilot for the task of **technical text summarization**.

The evaluation focuses on identifying the best **prompt + platform combination** based on:

* Accuracy
* Coherence
* Simplicity
* Speed
* User Experience



## **SCENARIO**

You are part of a **content curation team** for an educational platform that provides **quick, easy-to-understand summaries of research papers** to undergraduate students.

A **500-word technical article** titled **“The Basics of Blockchain Technology”** is provided as input.
The same article is summarized using **different prompting strategies** on **different AI platforms**.

The generated summaries are then compared to understand how prompting styles and platforms affect output quality.


## **PROMPTING TECHNIQUES USED**

1. **Zero-Shot Prompting**

   * No examples provided
   * Direct instruction to summarize

2. **Few-Shot Prompting**

   * One or two example summaries provided
   * Model learns the pattern before summarizing

3. **Chain-of-Thought Prompting**

   * Model is instructed to think step-by-step
   * Encourages logical flow and completeness

4. **Role-Based Prompting**

   * Model is assigned a role (e.g., “You are a professor teaching undergraduates”)
   * Improves tone and simplicity



## **AI PLATFORMS USED**

* ChatGPT
* Gemini
* Claude
* Copilot



## **ALGORITHM**

1. Select a **500-word technical article** on *The Basics of Blockchain Technology*.
2. Choose one **AI platform**.
3. Apply a **specific prompting technique** (Zero-shot / Few-shot / Chain-of-Thought / Role-based).
4. Generate the summary.
5. Measure the output based on:

   * Accuracy of technical content
   * Coherence and logical flow
   * Simplicity for undergraduate students
   * Speed of response
   * Overall user experience
6. Repeat steps 2–5 for **all platforms and prompting techniques**.
7. Record observations in a **comparison table**.
8. Analyze results to determine the **best-performing combination**.



## **EXPERIMENTAL OBSERVATION TABLE**

| AI Platform | Prompting Technique | Accuracy  | Coherence | Simplicity | Speed     | User Experience |
| ----------- | ------------------- | --------- | --------- | ---------- | --------- | --------------- |
| ChatGPT     | Zero-shot           | High      | Good      | Moderate   | Very Fast | Good            |
| ChatGPT     | Few-shot            | Very High | Very Good | High       | Fast      | Very Good       |
| ChatGPT     | Chain-of-Thought    | Very High | Excellent | Moderate   | Medium    | Good            |
| ChatGPT     | Role-based          | High      | Very Good | Excellent  | Fast      | Excellent       |
| Gemini      | Zero-shot           | Medium    | Good      | Moderate   | Very Fast | Good            |
| Gemini      | Few-shot            | High      | Good      | High       | Fast      | Good            |
| Claude      | Chain-of-Thought    | Very High | Excellent | High       | Medium    | Very Good       |
| Copilot     | Zero-shot           | Medium    | Average   | Low        | Very Fast | Average         |



## **RESULT**

From the experiment, the following observations were made:

* **Few-shot prompting** consistently improved **accuracy and structure** across platforms.
* **Chain-of-Thought prompting** produced the most **logically coherent** summaries but sometimes included unnecessary technical depth.
* **Role-based prompting** generated the **simplest and most student-friendly summaries**, making it ideal for undergraduate learners.
* **ChatGPT with Role-based and Few-shot prompting** offered the **best balance** of:

  * Accuracy
  * Clarity
  * Readability
  * User experience
* **Gemini and Copilot** performed well in speed but lacked consistency in simplicity.
* **Claude** excelled in coherence and depth but was slightly slower.


