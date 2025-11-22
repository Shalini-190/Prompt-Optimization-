ML & LLM Projects Portfolio
Two production-ready data science projects showcasing prompt engineering and machine learning capabilities.

Project 1: Prompt Optimization - Task Routing & Template Library
Overview
Designed and A/B tested prompt templates for intelligent intent routing across 6 conversation categories, improving customer service automation efficiency.
Key Results

Improved routing accuracy by 28%
Reduced prompt authoring time by 50%
Reduced hallucination rate by 62.5%
Automated weekly performance reporting

Technical Approach

Categories: customer_support, sales_inquiry, technical_question, feedback_complaint, account_management, general_information
Template Library: 20+ reusable prompt templates
Evaluation Metrics: Precision, Recall, F1-Score, Hallucination Rate
A/B Testing: Baseline vs Optimized prompt variants

Technologies

Python 3.8+
pandas, numpy
scikit-learn (metrics)
matplotlib, seaborn
LLM APIs (OpenAI/Anthropic compatible)

Installation
bashpip install pandas numpy matplotlib seaborn scikit-learn
Usage
bashpython prompt_optimization_routing.py
Outputs Generated

prompt_templates.json - 20+ reusable templates
ab_test_results.csv - Comparative metrics (baseline vs optimized)
template_performance.csv - Individual template analysis
time_savings.csv - Efficiency improvements
weekly_report.txt - Automated performance summary
ab_test_results.png - Visualizations (metrics + confusion matrix)

Sample Results
MODEL COMPARISON
─────────────────────────────────────────────
Metric      Baseline (v1)  Optimized (v2)  Improvement
Accuracy          0.65           0.83         27.7%
Precision         0.64           0.82         28.1%
Recall            0.65           0.83         27.7%
F1-Score          0.64           0.82         28.1%
Features Demonstrated

Multi-variant prompt design
Statistical significance testing
Cost-efficiency analysis (token usage)
Template reusability framework
Automated reporting pipelines
