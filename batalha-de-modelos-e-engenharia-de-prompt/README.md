# Batalha de Modelos & Engenharia de Prompt (XML)

## Descrição do Projeto
Construção e validação de um Prompt Estruturado utilizando marcações XML com o objetivo de gerar uma aplicação web de página única (Single Page Application) funcional para comercialização de pacotes de voos. O foco do estudo consistiu em avaliar o nível de aderência estrutural de sete modelos de IA de grande porte.

## Tecnologias Utilizadas
* ***Linguagens de Saída:*** HTML5, CSS3 integrado
* ***Estruturação do Input:*** Tags customizadas em formato XML (`<tarefa>`, `<diretrizes_design>`, `<obrigatoriedades_tecnicas>`)
* ***Modelos Avaliados:*** ChatGPT, Gemini, DeepSeek, Qwen, Grok, Maritaca e Claude.

## Resultados e Aprendizados
O desempenho de cada modelo foi catalogado de acordo com critérios rigorosos de conformidade técnica:

| Critérios de Avaliação | GPT | Gemini | DeepSeek | Qwen | Grok | Maritaca | Claude |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Precisão do HTML** | Baixíssima | Fraca | Boa | Nenhuma | Alta | Baixíssima | Altíssima |
| **Erros de Sintaxe (Bugs)** | Página não funciona | Erro no carrinho | Sem bugs | Todos | Sem bugs | Erro no carrinho | Sem bugs |
| **Tokens Gastos** | 1.300 | 1.750 | 4.100 | 3.200 | 6.820 | 1.200 | 9.200 |

***Modelo de Destaque:*** O Claude demonstrou a melhor interpretação das tags XML. O modelo enriqueceu o ambiente visual e manteve a integridade estrutural do código sem apresentar falhas de execução, consolidando-se como a ferramenta ideal para o desenvolvimento de códigos complexos e prototipagem robusta.

https://drive.google.com/file/d/1vz9489RdR-HwvYvI7WjZiHyd73OVqIDG/view?usp=sharing

[Voltar ao início](../README.md)
