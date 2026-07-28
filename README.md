# 📊 Extraindo Insights de Feedbacks Bancários com IA

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio **“Extraindo Insights do Feedback de Clientes Bancários”**, da trilha **Bradesco - Dados, Cibersegurança e GenAI**, na plataforma DIO.

O objetivo é utilizar Inteligência Artificial para analisar comentários de clientes sobre os serviços digitais de um banco fictício chamado **DIOBANK**.

A análise busca identificar reclamações frequentes, elogios, padrões de comportamento e oportunidades de melhoria nos seguintes serviços:

- Assistente virtual;
- PIX;
- Estabilidade do aplicativo;
- Investimentos.

---

## 🎯 Objetivo

Transformar comentários de clientes em informações úteis para apoiar:

- Desenvolvedores responsáveis por melhorias no aplicativo;
- Equipes de atendimento e experiência do cliente;
- Profissionais envolvidos na melhoria contínua dos serviços digitais;
- Priorização de correções e novas implementações.

---

## 👥 Público-alvo

Os resultados poderão ser utilizados por:

- Desenvolvedores freelancers responsáveis por testes e melhorias;
- Equipes de tecnologia;
- Equipes de experiência do cliente;
- Gestores de produtos digitais;
- Clientes do banco, beneficiados pelas melhorias realizadas.

---

## 📂 Estrutura do Projeto

```text
FEEDBACK-DIOBANK/
├── README.md
├── docs/
│   ├── 01-contexto-e-objetivos.md
│   ├── 02-criterios-de-analise.md
│   └── 03-metodologia.md
├── prompts/
│   └── prompt-analise-feedbacks.md
├── data/
│   └── modelo-feedbacks.csv
└── resultados/
    └── modelo-resultado.md
```

---

## 🗃️ Dados Utilizados

A base de dados deve conter os seguintes campos:

| Campo | Descrição |
|---|---|
| Data do comentário | Data em que o feedback foi registrado |
| Localidade | Cidade, estado ou região do cliente |
| Avaliação | Nota de 1 a 5 |
| Texto do feedback | Comentário enviado pelo cliente |
| Serviço citado | Assistente virtual, PIX, estabilidade do app ou investimentos |

> O arquivo disponibilizado neste repositório é apenas um modelo de estrutura. A análise real deve utilizar somente os comentários fornecidos para o desafio.

---

## 🔎 Critérios de Análise

Cada feedback deverá ser classificado por:

### Urgência

- **Alta:** problema crítico, indisponibilidade, falha grave ou risco elevado de perda do cliente;
- **Média:** problema relevante que prejudica a experiência, mas não impede totalmente o uso;
- **Baixa:** sugestão, elogio, dúvida simples ou melhoria não crítica.

### Impacto no relacionamento com o cliente

- **Alto:** pode causar abandono do serviço, perda de confiança ou insatisfação intensa;
- **Médio:** gera atrito ou frustração, mas permite continuidade do relacionamento;
- **Baixo:** possui efeito limitado ou representa uma oportunidade de aprimoramento.

---

## 🤖 Papel da Inteligência Artificial

A IA deve atuar como consultora de experiência do cliente e melhoria contínua de processos.

Ela deverá:

1. Classificar os feedbacks por urgência e impacto;
2. Agrupar comentários semelhantes;
3. Identificar reclamações recorrentes;
4. Identificar elogios;
5. Apontar oportunidades de melhoria;
6. Apresentar evidências com base nos comentários;
7. Recomendar ações práticas;
8. Informar limitações quando os dados forem insuficientes.

---

## 📦 Entrega Esperada

A resposta da IA deverá conter:

- Resumo executivo de até cinco linhas;
- Tabela com os principais temas;
- Frequência ou recorrência observada;
- Nível de urgência;
- Impacto no relacionamento;
- Exemplos de comentários;
- Recomendações práticas;
- Lista de prioridades;
- Estimativa qualitativa de complexidade, quando possível.

> Custos e prazos não devem ser inventados. Caso não existam dados técnicos suficientes, a IA deverá informar que não é possível realizar uma estimativa confiável.

---

## ⚠️ Restrições

- Utilizar somente os dados fornecidos;
- Não inventar números, causas ou conclusões;
- Não expor dados pessoais ou sensíveis;
- Não realizar estimativas de custo ou prazo sem informações suficientes;
- Informar as limitações da análise;
- Utilizar linguagem simples, direta e profissional.

---

## ✅ Critérios de Sucesso

O resultado será considerado adequado quando:

- For claro e organizado;
- Estiver baseado nos comentários fornecidos;
- Apresentar evidências;
- Identificar padrões relevantes;
- Apoiar a priorização de melhorias;
- Não incluir informações inventadas.

---

## 🛠️ Tecnologias e Conceitos Aplicados

- Inteligência Artificial Generativa;
- Engenharia de Prompts;
- Análise de sentimentos;
- Experiência do Cliente;
- Melhoria contínua de processos;
- Análise e classificação de feedbacks;
- Documentação com Markdown;
- Git e GitHub.

---

## 📚 Documentação

- [Contexto e objetivos](docs/01-contexto-e-objetivos.md)
- [Critérios de análise](docs/02-criterios-de-analise.md)
- [Metodologia](docs/03-metodologia.md)
- [Prompt principal](prompts/prompt-analise-feedbacks.md)
- [Modelo de resultado](resultados/modelo-resultado.md)

---

## 👨‍💻 Autor

**Lucas Mafra Camargo**

Projeto desenvolvido para fins educacionais como parte da formação na plataforma DIO.
