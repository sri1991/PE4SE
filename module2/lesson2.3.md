# Lesson 2.3: Common Prompting Mistakes

Welcome to the third lesson of Module 2: Fundamentals of Prompting. In this lesson, we'll explore common mistakes that developers make when crafting prompts for AI coding assistants, and learn how to avoid them.

## Introduction

Even with a good understanding of prompt structure and key elements, it's easy to fall into certain pitfalls when writing prompts. Recognizing and avoiding these common mistakes will help you get more accurate and useful responses from AI tools.

## 1. Being Too Vague

One of the most common mistakes is not providing enough specific information in the prompt.

### Example:
Poor: "Fix this code."
Better: "Debug the following Python function that's supposed to calculate the factorial of a number but is returning incorrect results for inputs greater than 5."

### How to Avoid:
- Always include specific details about the task or problem.
- Mention the programming language, framework, or libraries involved.
- Describe the expected behavior and the current (incorrect) behavior.

## 2. Overloading the Prompt

Trying to ask too many questions or request too many tasks in a single prompt can lead to incomplete or confusing responses.

### Example:
Poor: "Write a function to sort an array, explain how quicksort works, and compare its performance to bubble sort."
Better: Break this into three separate prompts, one for each task.

### How to Avoid:
- Stick to one main task or question per prompt.
- For complex tasks, break them down into a series of simpler prompts.
- Use follow-up prompts to build on previous responses.

## 3. Neglecting to Provide Context

Failing to provide relevant context can lead to responses that don't fit your specific situation.

### Example:
Poor: "How do I implement authentication?"
Better: "I'm building a Node.js REST API using Express and MongoDB. How can I implement JWT-based authentication for user login?"

### How to Avoid:
- Always provide context about your project, including technologies used.
- Mention any relevant constraints or requirements.
- If applicable, briefly explain the purpose or goal of the task.

## 4. Using Ambiguous Language

Ambiguous or imprecise language can lead to misinterpretations and irrelevant responses.

### Example:
Poor: "Make this code faster."
Better: "Optimize the following Python function for time complexity. It currently has O(n^2) complexity, and I need to improve it to at least O(n log n)."

### How to Avoid:
- Use precise technical terms.
- Be specific about what you mean by terms like "better", "faster", or "improve".
- Provide measurable criteria when asking for optimizations or improvements.

## 5. Forgetting to Specify Output Format

Not specifying the desired format of the response can result in answers that are difficult to use or integrate into your workflow.

### Example:
Poor: "Explain how to use async/await in JavaScript."
Better: "Provide a brief explanation of async/await in JavaScript, followed by a simple code example demonstrating its use in a function that fetches data from an API."

### How to Avoid:
- Clearly state how you want the information presented (e.g., code snippets, step-by-step instructions, bullet points).
- If you need code, specify whether you want complete functions, pseudo-code, or code fragments.
- For explanations, indicate the level of detail you're looking for.

## 6. Assuming Too Much Knowledge

AI models have broad knowledge, but they don't know the specifics of your project or codebase unless you provide that information.

### Example:
Poor: "Update the user model to include email verification."
Better: "I have a User model in a Django application. Here's the current model code: [insert code]. I need to add an email verification field and a method to handle the verification process. Please provide the updated model code and explain the changes."

### How to Avoid:
- Don't assume the AI knows about your specific project structure or custom implementations.
- Provide relevant code snippets or descriptions of your current implementation.
- Explain any non-standard or custom elements in your project.

## Conclusion

By avoiding these common mistakes, you'll be able to craft more effective prompts and get more useful responses from AI coding assistants. Remember, effective prompting is a skill that improves with practice. Don't be afraid to iterate on your prompts if you don't get the desired response on the first try.

In the next module, we'll dive into practical applications of prompt engineering for code generation.

Next up: [Module 3: Prompting for Code Generation](../module3/lesson3.1.md)