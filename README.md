**TL;DR:** This repo hosts a paper regarding a ML project I completed to detect security "hotspots" in code. These hotspots are valuable to security engineers, developers, and security compliance programs at scale.

## Abstract
This paper demonstrates an application of specialized machine learning models that reliably
identify security-sensitive operations in code and deliver meaningful cost and operational utility
advantages compared to LLM alternatives while maintaining classification performance. The
models achieve 74.6% precision, 77.5% recall, and 80.1% accuracy in human-labeled experiments
as well as a 95.42% precision rate in modified usage during real-world testing, enabling reliable
detection of privileged operations in previously unseen codebases. This subjective task has
applications for developers implementing security improvements, security engineers reviewing
unseen codebases, and organizational security efforts at scale. I start by constructing a labeled
dataset using AST-derived representations and a multi-pass LLM pipeline, then train and
evaluate multiple machine learning model architectures individually and in ensembles. Finally,
I validate real-world applicability by conducting a human-labeled alignment experiment and
demonstrating generalization and operational value. The results show that building custom
models is an efficient and practical method to identify security-sensitive code that significantly
outperforms LLMs in terms of cost and operational utility, and provides a mechanism that
materially improves security implementation and review workflows at scale.

---
This work was performed in late 2024 and 2025; Approved for public sharing in late 2026.

---

This paper is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). Commercial use is not permitted without prior written permission from the author.
