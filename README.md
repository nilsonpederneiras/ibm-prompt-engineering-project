# 🤖 IBM Skills Build: Engenharia de Prompt e Otimização de LLMs

> 📄 **Documentação Oficial:** [Roteiro do Laboratório (PDF)](./lt4-lab1.pdf)

Este repositório documenta a conclusão do laboratório prático da **IBM Skills Network**, focado em técnicas avançadas para guiar modelos de linguagem (LLMs) na geração de resultados estruturados e profissionais.

## 📋 Cenário do Lab
O desafio consistiu em transformar informações brutas de um projeto em um relatório de atualização de status para stakeholders, utilizando o modelo **Llama-2-70b**.

> **Nota de Agradecimento:** Um agradecimento especial à **IBM** e ao **IBM Granite** por fornecerem o voucher que possibilitou a utilização da API no Replicate durante este laboratório.

## 🛠️ Tecnologias Utilizadas
- **Modelagem:** Llama-2-70b via Replicate API.
- **Ambiente de Desenvolvimento:** Google Colab (Python).
- **Framework:** LangChain (para invocação do modelo).

## 🧪 Desenvolvimento Técnico (Prompt Engineering)
O laboratório seguiu uma evolução de 4 etapas para atingir a precisão máxima:
1. **Baseline Prompt:** Teste inicial com instruções simples.
2. **Refinamento de Tarefa:** Adição de detalhes específicos do projeto.
3. **Refinamento de Contexto:** Inclusão de informações adicionais para evitar ambiguidades.
4. **Advanced Prompting:** Implementação de **Role** (Papel), **Tone** (Tom) e **Output Format** (Formato de Saída).

---

## 🖼️ Evidências de Execução

| Construção do Prompt Avançado | Resposta Estruturada da IA |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/bfb2b5e2-ec18-4160-bc18-c74b2312f250" width="450"> | <img src="https://github.com/user-attachments/assets/a6ca7789-e38f-42c7-a132-8a937a3b19a9" width="450"> |
| *Definição de Role, Context e Format no Python* | *Saída polida com Status, Riscos e Próximos Passos* |

---

## 💡 Aprendizados Principais
- **Componentes de um Prompt:** Um prompt eficaz deve conter Descrição da Tarefa, Contexto, Formato de Saída, Persona (Role) e Tom.
- **Estruturação de Dados:** Forçar a IA a responder em tópicos específicos: Status Atual, Tarefas Concluídas, Riscos e Próximos Passos.
- **Automação com Python:** Desenvolvimento de funções para criar prompts dinâmicos reutilizáveis.

---
🚀 *Projeto realizado para aprimorar habilidades em IA Generativa, Elaboração de Prompts e Desenvolvimento Cloud.*
