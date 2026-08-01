# Gustavo Gomes

**Dados e engenharia aplicados a finanças e setor público.**
Fundador do [Payroll](https://payrollia.com.br), SaaS de educação financeira via WhatsApp, em produção com usuários pagantes. Antes: mercado financeiro (XP e Safra) e Marinha do Brasil. Último ano de Análise e Desenvolvimento de Sistemas na FIAP.

## O que eu faço

Passei anos do lado de quem vende e decide no mercado financeiro. Depois construí um produto financeiro do zero — backend, banco, pagamentos, compliance — e hoje aplico esse mesmo rigor a dados: transformar sistemas e bases públicas em decisões defensáveis.

## Projetos em destaque

| Projeto | O que é | Stack |
|---|---|---|
| [auditoria-ml](https://github.com/gustavogomes-dv/auditoria-ml) | Detecção de fraude em licitações federais: Lei de Benford, grafos de conluio e Isolation Forest sobre dados da CGU | Python, pandas, scikit-learn, networkx |
| [payroll.ia-showcase](https://github.com/gustavogomes-dv/payroll.ia-showcase) | Vitrine técnica do meu SaaS em produção: arquitetura, compliance CVM/LGPD e módulos reais | Node.js, PostgreSQL, Redis, Claude |
| [esg-compliance-api](https://github.com/gustavogomes-dv/esg-compliance-api) | API REST de compliance ambiental com autenticação e migrations | Java, Spring Boot, JWT, Oracle, Docker |

## Payroll — decisões de arquitetura

- Cálculos financeiros 100% determinísticos em código puro. O LLM nunca faz matemática, apenas conversa.
- Memória financeira em tabela dedicada. Direito ao esquecimento (LGPD) vira um DELETE cirúrgico com ON DELETE CASCADE.
- Webhooks validados por HMAC-SHA256 com comparação timing-safe.
- Rate limiting, bcrypt, lockout de força bruta, CORS restrito.

O código de produção é proprietário, mas o produto está no ar e a arquitetura eu discuto com prazer.

## Stack

**Dados** · Python, pandas, scikit-learn, networkx, Jupyter, SQL
**Bancos** · PostgreSQL, Oracle, Redis
**Backend** · Node.js, Java, Spring Boot
**Infra** · Docker, Git, Railway

## Contato

[LinkedIn](SEU_LINK_LINKEDIN) · [payrollia.com.br](https://payrollia.com.br)
