## Build end-to-end ML/AI workflows with the AWS Step Functions Data Science SDK

This repository contains the sample notebook described in this AWS Machine Learning [blog post]().

## Overview

Building and deploying automated machine learning (ML) and artificial intelligence (AI) projects in production often requires provisioning and integrating a different set of functions separately for orchestrating the pipelines.

In modern cloud architectures, typically following DevOps or CI/CD practices, this means connecting the data-science and operational worlds through a set of different services for covering each step of the workflows, consuming time and effort to set up these independently on each service.

In this sample project, you will explore how you can **reduce and optimize the efforts** in these tasks by **orchestrating the infrastructure from the same place with the AWS Step Functions Data Science SDK**.

## Instructions

Open the [sample Jupyter notebook](https://github.com/aws-samples/amazon-sagemaker-end-to-end-workflows-with-data-science-sdk/blob/master/amazon-sagemaker-e2e-workflows-data-science-sdk.ipynb) and follow the instructions provided in it.

This example considers the following architecture, where the AWS Step Functions Data Science SDK allows the orchestration of the sample workflow directly from the notebook, interacting with Amazon SageMaker and some AWS Lambda functions.

<p align="center">
  <img src="images/sample_architecture.jpg" width="70%" height="70%">
</p>

## References

### Citations:

This sample project uses the Online Retail Data Set from the UCI Machine Learning Repository:

Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.

Daqing Chen, Sai Liang Sain, and Kun Guo, Data mining for the online retail industry: A case study of RFM model-based customer segmentation using data mining, Journal of Database Marketing and Customer Strategy Management, Vol. 19, No. 3, pp. 197-208, 2012 (Published online before print: 27 August 2012. doi: 10.1057/dbm.2012.17). [https://archive.ics.uci.edu/ml/datasets/Online+Retail].

### Some Links and Documentation:

- [AWS Step Functions Data Science Python SDK documentation](https://aws-step-functions-data-science-sdk.readthedocs.io/en/latest/index.html)
- [AWS Step Functions Data Science Python SDK GitHub repository](https://github.com/aws/aws-step-functions-data-science-sdk-python)
- [Introducing the AWS Step Functions Data Science SDK for Amazon SageMaker](https://aws.amazon.com/about-aws/whats-new/2019/11/introducing-aws-step-functions-data-science-sdk-amazon-sagemaker/?nc1=h_ls)
- [AWS Machine Learning Blog](https://aws.amazon.com/blogs/machine-learning/?nc1=h_ls)
- [AWS Machine Learning Overview](https://aws.amazon.com/machine-learning/?nc1=h_ls)

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

