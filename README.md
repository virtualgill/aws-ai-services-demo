# AWS AI Services Demos

The code samples here are the ones walked through in AWS Power Hour: Machine Learning | S1 E1 | Intro to ML: https://m.twitch.tv/videos/688752443

## To set up a SageMaker Notebook
Open the Amazon SageMaker console at https://console.aws.amazon.com/sagemaker/.

Choose Notebook instances, then choose Create notebook instance.

On the Create notebook instance page, provide the following information (if a field is not mentioned, leave the default values):
 - For Notebook instance name, type a name for your notebook instance.
 - For Instance type, choose ml.t2.medium. This is the least expensive instance type that notebook instances support.
 - For IAM role, choose Create a new role, then choose Create role.

Choose Create notebook instance.

In a few minutes, Amazon SageMaker launches an ML compute instance—in this case, a notebook instance—and attaches an ML storage volume to it. The notebook instance has a preconfigured Jupyter notebook server and a set of Anaconda libraries.

NOTE: You are charged while your SageMaker Notebook Instance is running. Make sure to familarise yourself with the pricing and always remember to Stop your Instance when you aren't using it.
https://aws.amazon.com/sagemaker/pricing/


## Copying the Juypter Notebooks to your SageMaker Instance
Once your instance is running choose "Open Jupyter". From here you have two options:

1. Use the Upload button to manually copy up the Jupyter Notebooks (.ipynb) files

or 2. Use the New button to open a terminal window and run the following commands to navigate to the correct location and clone this repo: 

```cd SageMaker```

```git clone https://github.com/virtualgill/aws-ai-services-demo.git```


## Adding in the Lex Bot
Navigate to the Lex Console at https://console.aws.amazon.com/lex

Choose Actions -> Import

Upload [coffee_and_cover_bot_Export.zip](coffee_and_cover_bot_Export.zip) included in this repo

Select the Bot and click navigate to the Editor page

Select "Build"

Once built choose "Publish" and choose an alias of "*test*" (you can select a different name, but be sure to update any notebooks that use this bot too)
