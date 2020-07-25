# AWS AI Services Demos

## To set up a SageMaker Notebook
Open the Amazon SageMaker console at https://console.aws.amazon.com/sagemaker/.

Choose Notebook instances, then choose Create notebook instance.

On the Create notebook instance page, provide the following information (if a field is not mentioned, leave the default values):
 - For Notebook instance name, type a name for your notebook instance.
 - For Instance type, choose ml.t2.medium. This is the least expensive instance type that notebook instances support.
 - For IAM role, choose Create a new role, then choose Create role.

Choose Create notebook instance.

In a few minutes, Amazon SageMaker launches an ML compute instance—in this case, a notebook instance—and attaches an ML storage volume to it. The notebook instance has a preconfigured Jupyter notebook server and a set of Anaconda libraries.

