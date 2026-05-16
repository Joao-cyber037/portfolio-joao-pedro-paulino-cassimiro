# Teachable Machine - Classificação de Imagens

## Descrição do Projeto
Desenvolvimento e treinamento prático de um modelo de Inteligência Artificial voltado para o reconhecimento visual e classificação supervisionada de itens de vestuário. O foco principal, além da implementação prática, centrou-se na análise matemática do comportamento do modelo em cenários de dados limitados.

## Tecnologias Utilizadas
* ***Plataforma de Desenvolvimento:*** Teachable Machine por Google
* ***Paradigma de Aprendizado:*** Aprendizado Supervisionado (Supervised Learning) para Classificação de Imagens
* ***Hiperparâmetros de Treino:***
    * *Epochs:* 50
    * *Batch Size:* 16
    * *Learning Rate:* 0.001

## Resultados e Aprendizados
* ***Mecanismo de Viés:*** O modelo foi alimentado com um conjunto customizado de dados (11 amostras claras e 10 escuras). Identificou-se que modelos operando em ambientes muito restritos sofrem com problemas severos de generalização, tratando variações comuns (como roupas estampadas ou mudanças de iluminação) como erros estruturais de predição.
* ***Mitigação Prática:*** Para contornar falhas operacionais e quedas de confiança em sistemas de larga escala, estabeleceu-se a necessidade da implementação da arquitetura *Human-in-the-loop*, que integra a curadoria humana contínua para auditoria das decisões automatizadas e expansão iterativa das bases de dados.

* https://drive.google.com/file/d/1lnN-zltBNq3DsjeumvDkpu1advNI88Sd/view?usp=sharing

[Voltar ao início](../README.md)
