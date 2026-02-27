# Engenharia de Prompts (Sequência de Construção)

Este arquivo detalha a sequência exata de comandos utilizada no **Google NotebookLM** para extrair e organizar o conhecimento das 46 fontes sobre a metodologia de Benjamin Graham.

## 1. Configuração do Contexto (Prompt Inicial)
> **Prompt:** "Crie um segundo cérebro, baseado nos ensinamentos de Benjamin Graham, e sua metodologia de investimentos."

---

## 2. Mineração de Dados (Glossário Técnico)
> **Prompt:** "Com base em todas as fontes fornecidas, identifique os 10 termos técnicos e conceitos mais recorrentes na metodologia de Benjamin Graham. Para cada termo, forneça: 1) Uma definição clara, 2) Como ele se diferencia da visão de mercado comum e 3) Em qual fonte (vídeo ou texto) ele é explicado com mais profundidade."

---

## 3. Extração de Lógica Matemática (Fórmulas)
> **Prompt:** "Crie um guia passo a passo para calcular o Valor Intrínseco de uma ação usando a 'Fórmula de Graham'. Explique o significado dos multiplicadores 15 e 1,5 (e o produto 22,5). Use as fontes para listar as limitações dessa fórmula em empresas de crescimento rápido, conforme mencionado nos vídeos e no artigo da Toro."

---

## 4. Análise Crítica e Contextualização (Brasil)
> **Prompt:** "Compare a aplicação da metodologia de Graham no mercado dos EUA (conforme a Investopedia) com a realidade brasileira discutida no artigo do Congresso USP e nos vídeos. Quais são os 3 maiores desafios de adaptar o Value Investing para o Brasil? Formule 5 perguntas que um investidor deve fazer antes de decidir se uma ação brasileira é 'Graham-compliant'."

---

## 5. Criação de Ferramenta Reutilizável (Prompt Mestre)
> **Prompt:** "Com base nas lições extraídas deste caderno, elabore um 'Prompt Mestre' que possa ser usado no futuro para analisar o balanço de qualquer empresa. Esse prompt deve instruir a IA a verificar: Margem de Segurança, Relação P/L, Endividamento e Estabilidade de Lucros, citando sempre as métricas ideais defendidas por Graham nestas fontes."

---

## 6. Consolidação e Verificação (Guia de Estudo)
> **Prompt:** "Com base em todas as minhas fontes, gere um Guia de Estudo completo que inclua um resumo executivo, uma lista de termos-chave e 5 perguntas de múltipla escolha para testar meus conhecimentos sobre Benjamin Graham."
