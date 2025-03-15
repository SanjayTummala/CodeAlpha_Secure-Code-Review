Overview
This project introduces an automated code review system that combines Static Analysis and Generative AI to improve the efficiency and effectiveness of code reviews in large-scale software projects. The system leverages static analysis tools and advanced AI models to identify potential issues and provide insightful summaries, reducing the burden on human reviewers.

Key Features
Static Analysis Integration: Uses tools like Semgrep to scan codebases and identify relevant code segments.

Generative AI for Code Analysis: Employs OpenAI's GPT models to analyze and summarize code, providing detailed insights.

Scalable and Efficient: Automates the code review process, enabling faster and more comprehensive reviews at scale.

Customizable Rulesets: Allows for tailored static analysis rules to focus on specific code patterns or security concerns.

How It Works
Static Analysis: The system scans code using Semgrep to identify code segments of interest.

SARIF Parsing: Results from Semgrep are parsed using a custom Python script.

AI-Powered Analysis: The parsed code is sent to OpenAI's GPT models for detailed analysis and summarization.

Results Generation: The system outputs insights and recommendations in a structured format (e.g., JSON or CSV).

Example Use Case
Scenario: Analyzing Regex Usage in C# Code
Code File: StringExtensions.cs

Static Analysis: Semgrep identifies regex patterns in the code.

AI Analysis: GPT-4 analyzes the regex usage and flags potential security risks.

Output: JSON summary with risk levels, usage details, and recommendations for improvement.

Results
Efficiency: The system significantly reduces the time required for code reviews.

Accuracy: Identifies issues that may be overlooked in manual reviews.

Scalability: Successfully analyzed over 10,000 API consumers in less than a week.

