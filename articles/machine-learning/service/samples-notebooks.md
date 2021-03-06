---
title: Example Jupyter notebooks
titleSuffix: Azure Machine Learning service
description: Find and use example Jupyter notebooks to explore the Azure Machine Learning service in Python. 
services: machine-learning
ms.service: machine-learning
ms.subservice: core
ms.topic: sample

author: sdgilley
ms.author: sgilley
ms.reviewer: sgilley
ms.date: 12/04/2018
ms.custom: seodec18
#Customer intent: As a professional data scientist, I can build an image classification model with Azure Machine Learning using Python in a Jupyter notebook.
---

# Use Jupyter notebooks to explore Azure Machine Learning service

For your convenience, we have developed a series of Jupyter Python notebooks you can use to explore the Azure Machine Learning service. 

Learn how to use the service with the documentation on this site and use these notebooks to customize them to your situation. 

Use one of the paths below to run a notebook server with these sample notebooks.  Once the server is running, find tutorial notebooks in **tutorials** folder, or explore different features in **how-to-use-azureml** folder.

## A managed cloud notebook server

It's easy to get started with your own cloud-based notebook server. The sample notebook and the [Azure Machine Learning SDK for Python](https://aka.ms/aml-sdk) are already installed and configured for you once you create this cloud resource.  

[!INCLUDE [aml-azure-notebooks](../../../includes/aml-azure-notebooks.md)]

* The samples are available on the notebook webpage.

## A Data Science Virtual Machine (DSVM)

The [Azure Machine Learning SDK for Python](https://aka.ms/aml-sdk) and notebook server are already installed and configured for you on a DSVM. 

After you [create a DSVM](how-to-configure-environment.md#dsvm), use these steps on the DSVM to run the notebooks.

[!INCLUDE [aml-dsvm-server](../../../includes/aml-dsvm-server.md)]

## Your own Jupyter Notebook server

Use these steps to create a local Jupyter Notebook server on your computer.

[!INCLUDE [aml-your-server](../../../includes/aml-your-server.md)]

The setup instructions will install the packages you need to run the quickstart and tutorial notebooks.  Other sample notebooks may require installation of additional components.  For more information about these components, see [Install the Azure Machine Learning SDK for Python](https://docs.microsoft.com/python/api/overview/azure/ml/install).

## Azure Notebooks

The sample notebooks and the [Azure Machine Learning SDK for Python](https://aka.ms/aml-sdk) are already installed and configured for you on [Azure Notebooks](https://notebooks.azure.com/). The installation and future updates are automatically managed via Azure services.

Use the [Azure portal](https://portal.azure.com) to get started with Azure Notebooks.  Open your workspace and from the  **Overview** section, select **Get Started in Azure Notebooks**.

## Next steps

+ Explore the sample notebooks for Azure Machine Learning service in this GitHub repository: https://aka.ms/aml-notebooks

Try these tutorials:
+ [Train and deploy an image classification model with MNIST](tutorial-train-models-with-aml.md)

+ [Prepare data and use automated machine learning to train a regression model with the NYC taxi data set](tutorial-data-prep.md)