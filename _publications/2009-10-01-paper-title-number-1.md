---
title: "A Dataset for Evaluating LLMs Vulnerability Repair Performance in Android Applications"
collection: publications
category: manuscripts
date: 4-6 June 2025
venue: 'Proceedings of the 5th ACM Conference on Data and Application Security and Privacy (CODASPY 2025), 4-6 June 2025, Pittsburgh, USA'
paperurl: 'https://dl.acm.org/doi/10.1145/3714393.3726486'
---
Automated Program Repair (APR) is a well-established research area that enhances software reliability and security by automatically fixing bugs, reducing manual effort, and accelerating debugging. Despite progress in publishing benchmarks to evaluate APR tools, datasets specifically targeting Android are lacking.
To address this gap, we introduce a dataset of 272 real-world violations of Google's Android Security Best Practices, identified by statically analyzing 113 real-world Android apps. In addition to the faulty code, we manually crafted repairs based on Google's guidelines, covering 176 Java-based and 96 XML-based violations from Android Java classes and Manifest files, respectively. Additionally, we leveraged our novel dataset to evaluate Large Language Models (LLMs) as they are the latest promising APR tools. In particular, we evaluated GPT-4o, Gemini 1.5 Flash and Gemini in Android Studio and we found that GPT-4o outperforms Google's models, demonstrating higher accuracy and robustness across a range of violations types. Hence, with this dataset, we aim to provide valuable insights for advancing APR research and improving tools for Android security.

