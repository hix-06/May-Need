# Basic AI Prompts for Developers: Practical Examples for Everyday Tasks

## Overview
This guide provides ready-to-use AI prompts that developers can integrate into their daily workflows to improve productivity. The prompts have been tested using Portkey's Prompt Engineering Studio and utilize techniques like zero-shot, few-shot, chain-of-thought prompting, retrieval-augmented generation (RAG), and structured queries.

## 1. Code Generation Prompts

### Basic Code Generation (Zero-Shot Prompting)
```
You are an expert [programming language] developer. Write a function that [describe the task]. Ensure the function is:
- Well-documented: Add clear comments explaining each step.
- Optimized for performance: Use efficient data structures and algorithms where applicable.
- Robust: Handle edge cases such as empty inputs, incorrect data types, and large datasets.
- Modular: Keep the function reusable and avoid hardcoded values.
```

### Optimized Code Generation (Few-Shot Prompting)
```
Here's a basic implementation of [algorithm/function] in [programming language]:
[code snippet]
Now, improve this implementation by optimizing it using [optimization technique, e.g., memoization, dynamic programming, vectorization]. Explain:
- Why the optimized version is better in performance and efficiency.
- Time complexity improvements compared to the original.
- Any trade-offs
```

### Code Translation (Cross-Language Prompting)
```
Convert the following [source language] function into [target language]. Ensure that you:
- Maintain equivalent functionality in the new language.
- Explain key differences in syntax and behavior between the two languages.
- Highlight any necessary modifications due to differences in data types, function definitions, or execution models.
```

## 2. Debugging and Error Resolution

### Error Explanation and Fixes
```
I'm seeing this error in my [programming language] code:
[error message]
Explain:
- Why is this error occurring
- How to fix it - provide one or more solutions.
- Best practices to prevent similar errors in the future.
```

### Bug Identification
```
Here's a function that isn't returning the expected output:
[code snippet]
Describe:
- Why the function is failing and identify the root cause
- How to fix it,
- Best practices to avoid similar bugs in the future
```

### Performance Optimization
```
Analyze the following [programming language] function and suggest optimizations to improve its [performance/memory usage/time complexity]:
[code snippet]
Provide:
- An explanation of the current inefficiencies and why they impact performance.
- A step-by-step optimization strategy, including specific improvements.
- A revised version of the function with the applied optimizations.
- A comparison of time complexity before and after optimization
```

## 3. Code Review and Best Practices

### Code Review for Best Practices
```
Review the following [programming language] function and suggest improvements for Readability, Performance, and Security
[code snippet]
```

### Security Vulnerability Detection
```
Analyze the following SQL query and identify potential security risks:
[SQL query]
Provide a safer alternative and explain why it's secure.
```

## 4. Documentation and Explanation

### Generating Docstrings
```
Write a detailed docstring for the following [programming language] function:
[code snippet]
Make sure the docstring includes:
- A brief description of what the function does.
- Parameters with expected data types and descriptions.
- Return value with its type and meaning.
- Edge cases or exceptions the function may handle.
- Usage example (optional) to demonstrate correct usage.
```

## 5. AI for DevOps and Automation

### Dockerfile Generation
```
Generate a Dockerfile to containerize a [technology/framework] application with the following requirements:
- Use a lightweight and optimized base image.
- Ensure all required dependencies are copied and installed efficiently.
- Expose the necessary ports for the application.
- Use an appropriate CMD or ENTRYPOINT to start the application.
- Keep the image size minimal and follow best practices for security and performance.
```

### CI/CD Pipeline Configuration
```
Write a [CI/CD tool] workflow to automate the deployment of a [technology/framework] application to [deployment platform] with the following requirements:
- Runs on specific events (e.g., code push to main).
- Installs necessary dependencies and prepares the application for deployment.
- Deploy the application to [target platform] efficiently.
- Ensures minimal permissions, caching, and optimized build processes.
- Provides logging and alerts for failures.
```

## 6. Data Processing and Analysis

### Data Cleaning with Pandas
```
Write a Pandas script to clean and preprocess a dataset with the following steps:
- Remove duplicate rows efficiently.
- Fill missing values using an appropriate strategy (e.g., mean, median, or interpolation).
- Convert all column names to a consistent format (e.g., lowercase, snake_case).
- Save the processed DataFrame in a specified format (e.g., CSV, Parquet).
```

### SQL Query Optimization
```
Optimize the following SQL query for faster execution on a large dataset:
[SQL query]
Provide:
- Inefficiencies in the current query
- Optimized version of the query
- Explanation of performance improvements
- Best practices for writing efficient SQL queries on large dataset
```

## Conclusion
By using structured and optimized AI prompts, developers can speed up coding, automate repetitive tasks, debug efficiently, and improve overall code quality. Experiment with different techniques to get the most out of AI-powered development tools.

For developers managing large-scale AI workflows, tools like Portkey.ai can help optimize prompt execution, version control, and response evaluation, ensuring more reliable and efficient AI interactions.
