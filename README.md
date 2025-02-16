# Bem-vindo ao **LLM_Lab**!

Este repositório é dedicado ao estudo e desenvolvimento de Modelos de Linguagem Grande (LLMs). Aqui você encontrará recursos, implementações e tutoriais para aprofundar seu conhecimento e habilidades na área de Processamento de Linguagem Natural (PLN).

![Descrição da Imagem](https://github.com/profamar/LLM_Lab/blob/main/Design%20sem%20nome%20(16).png)


## Introdução

Os Modelos de Linguagem Grande são modelos de aprendizado profundo que conseguem entender e gerar texto humano com alta precisão. Eles são amplamente usados em várias aplicações, como chatbots, tradutores automáticos, assistentes virtuais e mais.

## Objetivos

- Explorar as principais arquiteturas de LLMs
- Implementar e treinar modelos utilizando frameworks populares
- Analisar e comparar o desempenho de diferentes abordagens
- Compartilhar recursos educacionais e tutoriais

# Comparação de Capacidade de Contexto (Free) entre as LLMs

## O que é Contexto em LLMs?  
O **contexto** refere-se à quantidade de tokens (palavras, frases ou código) que um modelo pode "lembrar" dentro de uma única interação. Isso inclui tanto a entrada (input) do usuário quanto a saída (output) gerada pelo modelo. Quanto maior o contexto, mais informações a IA pode processar de uma vez, permitindo respostas mais coerentes e contextualizadas em interações longas.  

## Comparação entre Modelos Gratuitos  

| Modelo   | Contexto (K) | Máximo de saída (tokens) | Tokens/s (Input) | Pontos Positivos | Pontos Negativos |
|----------|-------------|--------------------------|------------------|------------------|------------------|
| **GPT-3.5 (Free)** | ~16K | ~4K | Moderado | Bom para tarefas gerais, resposta rápida | Limite de contexto menor que versões pagas |
| **GPT-4 (Free - GPT-4-turbo no ChatGPT Free)** | ~4K | ~2K | Moderado | Melhor qualidade que GPT-3.5 | Contexto muito reduzido na versão gratuita |
| **Claude (Free - Claude 3 Haiku)** | ~200K (trecho analisado pode ser menor) | ~4K | Rápido | Excelente capacidade de contexto | Controle limitado na versão gratuita |
| **Gemini 1.5 (Free)** | ~1M (limitado no free) | ~8K | Alto | Maior capacidade de contexto | Restrições na versão gratuita |

> **Nota:** As versões gratuitas dessas LLMs possuem limitações variáveis conforme o uso.  
> Modelos pagos geralmente oferecem maior capacidade de contexto e saída.

---

**Tabela Final (Exemplo Visual)**

| Nome           | Desenvolvedor     | Características Principais                                                                                                                                              |
| :------------- | :---------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **GPT-4**      | OpenAI           | Multimodal (texto/imagem), raciocínio avançado, melhor segurança e alinhamento.                                                                                           |
| **GPT-3.5**    | OpenAI           | Eficiência aprimorada, mais coerência nas respostas, usado em chatbots.                                                                                                  |
| **PaLM 2**     | Google DeepMind  | Suporte a múltiplos idiomas e código, melhor desempenho matemático e lógico.                                                                                              |
| **Gemini 1.5** | Google DeepMind  | Multimodal avançado, integração com Google Docs e Sheets.                                                                                                                |
| **LLaMA 2**    | Meta             | Código aberto, eficiente para hardware limitado, disponível em diferentes tamanhos.                                                                                        |
| **Claude 2 & 3**| Anthropic        | Foco em segurança, IA constitucional, melhor em raciocínio de longo prazo.                                                                                                |
| **Mistral & Mixtral**| Mistral AI      | Mistral 7B: leve e open-source; Mixtral: arquitetura MoE para eficiência.                                                                                                |
| **Command R**  | Cohere           | Recuperação aumentada por IA (RAG), ideal para consultas em bases de conhecimento.                                                                                      |

Essa tabela no Google Sheets estará formatada para facilitar a leitura e visualização dos dados sobre os LLMs.  Você pode adicionar bordas (selecionando as células e usando o botão "Bordas"), cores de preenchimento e outros elementos de formatação para personalizá-la ainda mais.

---
 ## Comparativo dos Principais Modelos de Linguagem (LLMs) e suas Características

| Modelo          | Desenvolvedor        | Características                                                                                                                   |
|-----------------|----------------------|---------------------------------------------------------------------------------------------------------------------------------|
| GPT-4           | OpenAI               | Multimodal (texto e imagens), melhor compreensão contextual, raciocínio lógico, criatividade, redução de viés, respostas seguras. |
| GPT-3.5         | OpenAI               | Melhor eficiência computacional, coerência e precisão aprimoradas.                                                                 |
| PaLM 2          | Google DeepMind      | Treinado em múltiplos idiomas e código, melhor desempenho em tarefas matemáticas, lógicas e científicas.                          |
| Gemini 1.5      | Google DeepMind      | Multimodal (vídeos, áudio e texto), integração com ferramentas do Google.                                                           |
| LLaMA 2         | Meta (Facebook)      | Código aberto, disponível em diferentes tamanhos, eficiência para execução em hardware acessível.                                 |
| Claude 2/3      | Anthropic            | Focado em segurança e alinhamento ético, melhor desempenho em raciocínio de longo prazo, IA constitucional.                       |
| Mistral/Mixtral | Mistral AI           | Mistral 7B (leve e open-source), Mixtral (arquitetura MoE para eficiência).                                                      |
| Command R       | Cohere               | Focado em recuperação aumentada por IA (RAG), alta eficiência para consultas em bancos de dados de conhecimento.                 |
