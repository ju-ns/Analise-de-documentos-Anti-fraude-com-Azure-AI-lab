# Analise-de-documentos-Anti-fraude-com-Azure-AI-lab
Este projeto faz parte do Bootcamp da DIO e tem como objetivo demonstrar uma solução de análise automática de documentos para prevenção de fraude. Utilizando recursos de Azure AI Services, o sistema identifica informações relevantes em imagens enviadas pelo usuário, como possíveis dados de cartões ou documentos falsos, e retorna um relatório de validação.

A aplicação faz upload da imagem para um Azure Blob Storage, chama a API de Azure Document Intelligence para análise e exibe o resultado de forma simples e visual através de uma interface construída com Streamlit.
