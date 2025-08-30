# My AWS Notebooks Repository
This repository contains Jupyter notebooks demonstrating how to interact with Amazon Web Services (AWS) using the **Boto3** library, the official AWS SDK for Python. The notebooks are designed to help you understand and automate common AWS tasks for **EC2** and **S3**.

## Table of Contents

  - [Notebooks]
      - [AWS EC2 with Boto 3](./Notebooks/AWS%20EC2%20With%20Boto%203.ipynb)
      - [AWS S3 with Boto ](./Notebooks/AWS%20S3%20With%20Boto%203.ipynb)

-----

## Prerequisites

To run these notebooks, you will need:

  * **Python 3.6+**
  * **Jupyter Notebook** or **JupyterLab**
  * **Boto3** library: `pip install boto3`
  * **AWS CLI** configured with your credentials: `aws configure`

You must have an AWS account with the necessary permissions to create and manage EC2 instances and S3 buckets.

-----

## Notebooks

### AWS EC2 with Boto3

This notebook, `ec2_with_boto3.ipynb`, covers the fundamental operations for managing **Amazon EC2** instances. It provides practical examples of:

  * **Launching** a new EC2 instance from an AMI.
  * **Listing** your existing instances.
  * **Starting** and **stopping** instances.
  * **Terminating** instances to avoid ongoing charges.

### AWS S3 with Boto3

The `s3_with_boto3.ipynb` notebook focuses on **Amazon S3** (Simple Storage Service). It walks you through common S3 tasks, including:

  * **Creating** and **deleting** buckets.
  * **Uploading**, **downloading**, and **listing** objects (files).
  * **Deleting** objects from a bucket.

-----

## Configuration

Ensure your AWS credentials are set up correctly. Boto3 automatically looks for credentials in several locations, including the `~/.aws/credentials` file. The easiest way to configure this is by running:

```bash
aws configure
```

You will be prompted to enter your AWS Access Key ID, Secret Access Key, region, and output format.