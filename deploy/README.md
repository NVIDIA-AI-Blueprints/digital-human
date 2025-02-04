# Deployment

**Persona needed**: Devops Engineer

For this guide, we will deploy the Digital human avatar and the Retrieval Augmented Generation pipeline on separate instances. 
NOTE:  Here detail a way to deploy the digital human pipeline agnostic of a cloud provider. The deployment specific to a cloud provider can be found [here](https://docs.nvidia.com/ace/latest/workflows/tokkio/text/deployment/AWS_CSP_Setup_Guide_automated.html). 

The digital avatar deployment uses cloud native stack deployment script that automates and abstracts out complexities setup and deployment of our application on a virtual or a physical machine with a GPU.  


## Digital Human Pipeline Deployment

For this workflow, we will be leveraging [NVIDIA ACE](https://developer.nvidia.com/ace) - a suite of technologies for bringing digital humans to life with generative AI.

Follow the setup guide [here](https://docs.nvidia.com/ace/latest/workflows/tokkio/text/deployment/BareMetal-setup.html#setup-guide) to deploy the out of box **Ben** digital human on your virtual or physical machine.

## RAG Pipeline Deployment

Follow the steps [here](https://github.com/NVIDIA/GenerativeAIExamples/tree/main/RAG/examples/basic_rag/langchain) to set up the RAG pipeline on a different instance.

Note: For connecting the DH pipeline to RAG, please take a look at the customization(../customize/) section of this guide
