---
title: "How Does a Deep Learning Model Architecture Impact Its Privacy? A Comprehensive Study of Privacy Attacks on CNNs and Transformers"
date: 2024-08-01
publishDate: 2024-08-01
authors: ["Guangsheng Zhang", "Bo Liu", "Huan Tian", "Tianqing Zhu", "Ming Ding", "and Wanlei Zhou"]
publication_types: ["1"]
abstract: "As a booming research area in the past decade, deep learning technologies have been driven by big data collected and processed on an unprecedented scale. However, privacy concerns arise due to the potential leakage of sensitive information from the training data. Recent research has revealed that deep learning models are vulnerable to various privacy attacks, including membership inference attacks, attribute inference attacks, and gradient inversion attacks. Notably, the efficacy of these attacks varies from model to model. In this paper, we answer a fundamental question: Does model architecture affect model privacy? By investigating representative model architectures from convolutional neural networks (CNNs) to Transformers, we demonstrate that Transformers generally exhibit higher vulnerability to privacy attacks than CNNs. Additionally, we identify the micro design of activation layers, stem layers, and LN layers, as major factors contributing to the resilience of CNNs against privacy attacks, while the presence of attention modules is another main factor that exacerbates the privacy vulnerability of Transformers. Our discovery reveals valuable insights for deep learning models to defend against privacy attacks and inspires the research community to develop privacy-friendly model architectures."
featured: true
publication: "*33rd USENIX Security Symposium (USENIX Security 24)*"
tags: ["Privacy Attacks", "CNNs", "Transformers"]
doi: ""
url_pdf: https://www.usenix.org/system/files/usenixsecurity24-zhang-guangsheng.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false
---