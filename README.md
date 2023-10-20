# SecurityNet
This is the official repository for our USENIX Security Symposium 2024 paper ["SecurityNet: Assessing Machine Learning Vulnerabilities on Public Models"](https://arxiv.org/abs/2310.12665).

## Introduction  

While advanced machine learning (ML) models are deployed in numerous real-world applications, previous works demonstrate these models have security and privacy vulnerabilities.
Various empirical research has been done in this field.
However, most of the experiments are performed on target ML models trained by the security researchers themselves.
Due to the high computational resource requirement for training advanced models with complex architectures, researchers generally choose to train a few target models using relatively simple architectures on typical experiment datasets.
We argue that to understand ML models' vulnerabilities comprehensively, experiments should be performed on a large set of models trained with various purposes (not just the purpose of evaluating ML attacks and defenses).
To this end, we propose using publicly available models with weights from the Internet (public models) for evaluating attacks and defenses on ML models.
We establish a database, namely SecurityNet, containing 910 annotated image classification models.
We then analyze the effectiveness of several representative attacks/defenses, including model stealing attacks, membership inference attacks, and backdoor detection on these public models.
Our evaluation empirically shows the performance of these attacks/defenses can vary significantly on public models compared to self-trained models.
We advocate researchers to perform experiments on public models to better demonstrate their proposed methods' effectiveness in the future.

![SecurityNet Statistics](./figures/SecurityNet.png)

## Code and database coming soon
