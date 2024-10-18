# Evaluative-AI

This code serves as a base implementation for generating local SHAP feature importance, which is crucial for building an evaluative AI framework. You can learn more about evaluative AI from: https://dl.acm.org/doi/abs/10.1145/3593013.3594001.

Our main objective is to measure human subjects' trust in the XAI model. To do this, we conducted a user study where participants were divided into two groups: one exposed to the traditional XAI framework displaying local SHAP feature importance, and the other using the evaluative AI approach.

The code generates local SHAP feature importance using an IF-THEN scenario, where we modify specific features to observe changes in both the model's predictions and SHAP values. This allows us to evaluate how explanations influence trust in AI systems.

Further details will be shared upon acceptance of our paper.
