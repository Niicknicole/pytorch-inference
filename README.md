# High-Precision Batch Image Inference with Swin Transformer V2

Este repositório contém uma aplicação prática de Visão Computacional e Deep Learning focada em batch inference. O projeto foi desenvolvido como prática de estudos em arquiteturas modernas de redes neurais e ecossistema PyTorch.

## Tecnologias
* **PyTorch & Torchvision**
* **Swin Transformer V2**
* **Batch Inference**

## Estrutura do Projeto
* `batch_inference_swin.ipynb`: Jupyter Notebook principal contendo todo o pipeline de carregamento, inferência e exibição dos resultados.
* `data/`: Diretório contendo as imagens de teste utilizadas na validação do modelo.
* `requirements.txt`: Arquivo de dependências.

## Melhorias Futuras

* **Automação do Pipeline de Dados:** Implementar um script automatizado para ingestão de dados em lote, permitindo ler imagens diretamente de um bucket S3 (AWS) ou realizar downloads automáticos via consumo de APIs externas.
* **Interface do Usuário (UI):** Desenvolver uma interface gráfica web simples e intuitiva utilizando **Gradio** ou **Streamlit**.
