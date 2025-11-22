

##  Prompt Optimization — Task Routing & Template Library


### 🎯 Overview
Designed and A/B tested prompt templates for intelligent intent routing across 6 conversation categories, improving customer service automation efficiency.

### 🏆 Key Results
- ✅ **28% improvement** in correct routing accuracy
- ✅ **50% reduction** in prompt authoring time
- ✅ **62.5% reduction** in hallucination rate
- ✅ Automated weekly performance reporting

### 📊 Technical Approach
- **Categories**: customer_support, sales_inquiry, technical_question, feedback_complaint, account_management, general_information
- **Template Library**: 20+ reusable prompt templates
- **Evaluation Metrics**: Precision, Recall, F1-Score, Hallucination Rate
- **A/B Testing**: Baseline vs Optimized prompt variants

### 🛠️ Technologies
```
Python 3.8+
pandas, numpy
scikit-learn (metrics)
matplotlib, seaborn
LLM APIs (OpenAI/Anthropic compatible)
```

### 📦 Installation
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 🚀 Usage
```bash
python prompt_optimization_routing.py
```

### 📤 Outputs Generated
1. **prompt_templates.json** - 20+ reusable templates
2. **ab_test_results.csv** - Comparative metrics
3. **template_performance.csv** - Individual template analysis
4. **time_savings.csv** - Efficiency improvements
5. **weekly_report.txt** - Automated performance summary
6. **ab_test_results.png** - Visualizations

### 📈 Sample Results
```
MODEL COMPARISON
Metric      Baseline  Optimized  Improvement
Accuracy      0.65      0.83       27.7%
Precision     0.64      0.82       28.1%
Recall        0.65      0.83       27.7%
F1-Score      0.64      0.82       28.1%
```

---
