# LIMETTE - Local Interpretable Model Explanation with Trust and Transparency Enhancements for Defensive Protection Against Adversarial Attacks

Code for our paper, "[Unfooling Perturbation-Based Post Hoc Explainers](https://arxiv.org/abs/2205.14772)." Here, we 
provide an extended defensive mechanism against scaffolding-based adversarial attacks on
perturbation-based explainers. We propose a novel dynamic trustable treshold, ensembler extensions and ARIMA extensions.

**Abstract**:

> In the realm of machine learning developments, the deployment of black box models in sensitive domains demands robust, trustworthy, and auditable explanation techniques capable of combating adversarial attacks. Recent critiques have highlighted potential vulnerabilities in perturbation-based post hoc explanation methods like LIME and SHAP, revealing that these methods can be manipulated to produce deceptive explanations, potentially thwarting audits. In this thesis, we introduce LIMETTE (Local Interpretable Model Explanation with Trust and Transparency Enhancements), a novel defensive algorithm for LIME and SHAP designed to guard against adversarial manipulation attacks. LIMETTE incorporates robustness checks and adversarial detection mechanisms, ensuring the reliability and transparency of explanations. Our approach prevents adversaries from redirecting explanations to unrelated portions of the input, thus uncovering false trails. LIMETTE integrates several advanced mechanisms: threshold dynamics to adjust explanation sensitivity, dynamic ARIMA models for time series anomaly detection, and ensemble methods to learn form a wide range of existing attacks, enhancing robustness. Additionally, we introduce a trust score metric that quantifies the reliability of generated explanations, enabling auditors to assess the likelihood of adversarial interference. Through extensive experiments, including both synthetic and six real-world scenarios, we demonstrate that LIMETTE effectively resists a range of novel adversarial attacks, providing reliable and transparent insights into model behavior. Our findings reaffirm the utility of LIMETTE in fostering trust and accountability in vulnerable machine learning applications, particularly in high-stakes environments.

**Note**: We adapt the "unfooling" portion of the code from [Unfooling-LIME-SHAP](https://github.com/craymichael/unfooling)
in this repository.

## Installation
All required packages are listed in `requirements.txt`. This can be installed
in a virtual environment using tools, such as `virtualenv` or `conda`.

Example of installation via `pip`:

```shell
pip install -r requirements.txt
```

## Run Instructions
The LIMETTE framework can be executed directly via the provided Python script run.py. Before running the script, ensure that all dependencies listed in requirements.txt are installed in your environment. You can install them using pip.



## How to Cite This Work

([link](https://arxiv.org/abs/2205.14772))
Kiel A. "LIMETTE"
Erasmus University Rotterdam, 2024.

**BibTeX**:

```text
@inproceedings{LIMETTE2024,
  title     = {LIMETTE - Local Interpretable Model Explanation with Trust and Transparency Enhancements for Defensive Protection Against Adversarial Attacks,
  author    = (Kiel, Alexander},
  year      = 2024,
  booktitle = {},
  publisher = {Erasmus University},
}
```
