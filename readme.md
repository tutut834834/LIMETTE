# LIMETTE - Local Interpretable Model Explanation with Trust and Transparency Enhancements for Defensive Protection Against Adversarial Attacks

Code for our paper, "LIMETTE - Local Interpretable Model Explanation with Trust and Transparency Enhancements for Defensive Protection Against Adversarial Attacks". Here, we 
provide an extended defensive mechanism against scaffolding-based adversarial attacks on
perturbation-based explainers. 

**Abstract**:

In the realm of recent machine learning developments, the deployment of black box models in sensitive
domains demands robust, trustworthy, and auditable explanation techniques capable of combating a wide
range of adversarial attacks. Recent critiques have highlighted potential vulnerabilities in perturbation-based
post hoc explanation methods such as LIME and SHAP, revealing that these methods can be manipulated to
produce deceptive explanations, potentially thwarting audits. In this thesis, we introduce LIMETTE (Local
Interpretable Model Explanation with Trust and Transparency Enhancements)1, a novel defensive algorithm
demonstrating particular effectiveness when used in conjunction with LIME and designed to guard against
adversarial manipulation attacks. LIMETTE incorporates extended robustness checks and adversarial detec-
tion mechanisms, ensuring the reliability and transparency of explanations. Our approach prevents adversaries
from redirecting explanations to unrelated portions of the input, thus uncovering false trails. This defensive
framework integrates several advanced mechanisms: threshold dynamics to adjust explanation sensitivity, dy-
namic ARIMA and GARCH structures to capture volatility clustering and temporal dependencies, a Lipschitz
adjustment and an account for differential privacy. Hereby, we introduce a trust score metric that quantifies
the reliability of generated explanations, enabling auditors to assess the likelihood of adversarial interference.
Through extensive experiments involving six real-world scenarios, we demonstrate that LIMETTE effectively
resists a range of novel adversarial attacks, providing reliable and transparent insights into model behavior.
Our findings reaffirm the utility of LIMETTE in fostering trust and accountability in vulnerable machine
learning applications, particularly in high-stake environments prone to profiling.

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
The LIMETTE framework can be executed directly via the provided Python scripts:
![image](https://github.com/user-attachments/assets/ca70a0e4-6956-4c65-81a8-151564adb56c)
Before running the script, ensure that all dependencies listed in requirements.txt are installed in your environment. You can install them using pip.



## How to Cite This Work

([link](https://arxiv.org/))
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
