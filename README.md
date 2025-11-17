# Análise de Redes Sociais com Python

Este projeto utiliza algoritmos de Teoria dos Grafos para analisar a estrutura de redes sociais, identificar influenciadores-chave e detectar comunidades. 
A análise é aplicada em dois datasets: o clássico "Zachary's Karate Club" (para validação) e o "Ego-Facebook" da Stanford (para um caso de uso real).

Os principais algoritmos implementados e utilizados são:
* Centralidade de Grau
* Centralidade de Proximidade (usando BFS)
* Centralidade de Intermediação
* PageRank
* Detecção de Comunidade (Método de Louvain)

## Como Executar o Projeto

Este projeto foi feito para ser executado no ambiente do **Google Colab**.
[Link Colab](https://colab.research.google.com/drive/1fudmuBiWFsOvIUXhk0KNAPx0ezrHh0Mb?usp=sharing)


### 1. O Dataset (Passo Essencial)

Para que a **Parte 2 (Análise do Facebook)** funcione, o script precisa do arquivo `facebook_combined.txt`.

> **Importante:** O script **não** vai funcionar se este arquivo não for carregado no ambiente do Colab.

Siga este passo:
1.  **Baixe o dataset** a partir deste link:
    * [Link do Google Drive: facebook_combined.txt](https://drive.google.com/file/d/1w5rRvtczcTHGk4eM3GyKaDwkmr0kfSTQ/view?usp=sharing)


### 2. Executando a Análise

1.  Abra o arquivo `.ipynb` deste repositório no [Google Colab](https://colab.research.google.com/drive/1fudmuBiWFsOvIUXhk0KNAPx0ezrHh0Mb?usp=sharing).
2.  No menu lateral esquerdo do Colab, clique no ícone de **Arquivos** (pasta).
3.  Clique em **"Fazer upload"** e selecione o arquivo `facebook_combined.txt` que você baixou.
4.  Aguarde o upload ser concluído. Você deve ver o arquivo listado no painel.
5.  No menu superior, clique em **Ambiente de execução** > **Executar tudo**.

##  Resultados Esperados

Ao executar o notebook, você verá:
* A análise de centralidade e comunidade do "Karate Club".
* A geração de dois arquivos de visualização: `karate_club_interactive.html` e `karate_club_static.png`.
* A análise completa da sub-rede do Facebook.
* A impressão da "Análise Estratégica de Marketing" no final.
* A criação do arquivo `facebook_network_com_metricas.gexf`, que pode ser aberto em softwares como o [Gephi](https://gephi.org/) para uma visualização mais detalhada.

## Integrantes
- Beatriz Brito
- Mariana Paiva
- Othon Sales
