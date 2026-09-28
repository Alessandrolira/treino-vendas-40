# Treino de Vendas — Plano de Saúde

Plugin de treinamento para times de vendas de planos de saúde (Porto, SulAmérica, Amil e Bradesco).

## O que faz

O Claude assume o papel de um **cliente simulado** e conversa por WhatsApp com o vendedor, como se fosse um lead real. Cada treino tem:

- Um **perfil de cliente sorteado** (tipo de contratação, motivação, personalidade, operadora).
- Um **nível de dificuldade oculto** (fácil, médio ou difícil) que só é revelado no final.
- Uma **regra central**: o cliente nunca revela quanto paga hoje no plano atual — isso testa a técnica do vendedor.

No fim da conversa (venda ganha, venda perdida, ou quando o vendedor digita `ENCERRAR`), o Claude sai do personagem e entrega um **relatório de desempenho** com nota por competência e melhorias prioritárias.

## Como usar

1. Instale o plugin.
2. Peça algo como *"vamos treinar vendas"* ou chame a skill pelo nome.
3. Informe seu nome e comece a conversa como vendedor.
4. Ao terminar, leia o relatório.

## Componentes

- **Skill:** `treino-vendas-plano-saude` — conduz o roleplay e gera o relatório.
