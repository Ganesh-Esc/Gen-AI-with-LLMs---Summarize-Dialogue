# Gen-AI-with-LLMs---Summarize-Dialogue
# Dialogue Summarization with Generative AI 🤖

![Lab](https://img.shields.io/badge/Lab-Prompt%20Engineering-blue)

This lab explores the task of **dialogue summarization** using generative Large Language Models (LLMs). You will investigate how the structure and content of input text (prompts) affect the model's output.

The primary focus is on **prompt engineering**, where you will guide the model to perform the summarization task more effectively. By comparing zero-shot, one-shot, and few-shot inference techniques, you will learn foundational strategies to enhance and control the generative output of LLMs.

---


## 🚀 Key Concepts

### 1. Prompt Engineering

The art and science of designing effective inputs (prompts) to guide an LLM toward generating a desired output. This lab demonstrates how small changes in the prompt can lead to vastly different results.

### 2. Inference Techniques

You will experiment with the following methods to instruct the model:

* **Zero-Shot Inference:** You ask the model to perform a task without providing any prior examples. The model relies solely on its pre-existing knowledge.
    * **Example Prompt:** `Summarize the following conversation.`

* **One-Shot Inference:** You provide a single high-quality example of the task you want the model to perform. This helps the model understand the expected output format and style.
    * **Example Prompt:** `Summarize this dialogue in one sentence, like in this example: [Example Dialogue -> Example Summary]. Now, summarize this: [New Dialogue].`

* **Few-Shot Inference:** You provide several examples (typically 2-5) to give the model more context and a better understanding of the task's nuances. This is one of the most effective ways to steer a model's behavior.

---

## 🛠️ Lab Structure

This lab is structured to guide you through a hands-on comparison of the different prompting methods.

1.  **Task Definition:** Start by defining the dialogue summarization task and the dataset you will be working with.
2.  **Zero-Shot Summarization:** Run inference on a sample dialogue with a simple, direct prompt and analyze the output.
3.  **One-Shot Summarization:** Engineer a new prompt that includes one complete example (dialogue + summary) and observe the improvement.
4.  **Few-Shot Summarization:** Build a more robust prompt with multiple examples and compare its output against the previous methods.
5.  **Analysis & Conclusion:** Conclude by summarizing your findings on how prompt engineering enhances the quality of generative AI outputs.
