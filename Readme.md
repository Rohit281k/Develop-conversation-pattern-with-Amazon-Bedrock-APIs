# Developing Generative AI Applications on AWS v2.x - Lab 3: Develop conversation pattern with Amazon Bedrock APIs an hour

In this lab, you explore how to use the Amazon Nova Lite model through Amazon Bedrock API for intelligent question answering. You first examine the limitations of zero-shot prompting, and then learn how to enhance response accuracy by providing relevant context. This lab demonstrates both complete and streaming response generation methods, simulating a simplified version of Retrieval-Augmented Generation (RAG) for enterprise-level question answering systems.

# Lab overview

AnyCompany aims to provide accurate and context-aware responses to customer queries about their vehicle maintenance procedures, particularly regarding tire-related issues. However, they face a challenge where general-purpose language models often provide generic responses that may not align with their specific vehicle specifications. To address this, they want to leverage Amazon Bedrock’s question-answering capabilities with context augmentation to ensure accurate, model-specific responses.

In this lab, you explore how to use the Amazon Nova Lite model through Amazon Bedrock API for intelligent question answering. You first examine the limitations of zero-shot prompting, and then learn how to enhance response accuracy by providing relevant context. This lab demonstrates both complete and streaming response generation methods, simulating a simplified version of Retrieval-Augmented Generation (RAG) for enterprise-level question answering systems.

# Objectives

By the end of this lab, you should be able to do the following:

Implement zero-shot prompting for basic question answering.
Enhance model responses using context augmentation.
Develop streaming responses for improved user experience.
