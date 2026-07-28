# Gustavo Gomes


Fundador do [Payroll](https://payrollia.com.br), SaaS de educação financeira via WhatsApp, em produção. Antes disso, mercado financeiro (XP e Safra) e Marinha do Brasil. Estudante de Análise e Desenvolvimento de Sistemas na FIAP, último ano.

## O que eu faço

Passei anos do lado de quem vende e decide no mercado financeiro. Depois construí um produto financeiro do zero: backend, banco, pagamentos, compliance. Hoje meu foco é o próximo passo lógico dessa cadeia: analisar os dados que esses sistemas geram.

## Payroll

O projeto que melhor me representa tecnicamente. Algumas decisões de arquitetura:

```
- Cálculos financeiros 100% determinísticos em código puro.
  O LLM nunca faz matemática, apenas conversa.
- Memória financeira em tabela dedicada, não em JSONB.
  Direito ao esquecimento (LGPD) vira um DELETE cirúrgico.
- Webhooks com validação HMAC-SHA256 e comparação timing-safe.
- Rate limiting, bcrypt, lockout de força bruta, CORS restrito.
- Stack: Node.js, PostgreSQL, Redis, WhatsApp Business API.
```

O código é proprietário, mas o produto está no ar e a arquitetura eu discuto com prazer.

## Stack

```
dados        python, pandas, scikit-learn, jupyter, sql
bancos       postgresql, oracle, redis
backend      java, spring boot, node.js
infra        docker, git, railway
```

## Repositórios

| repo | descrição |
|------|-----------|
| [pizzas-ml](https://github.com/gustavogomes-dv/pizzas-ml) | Análise exploratória e modelagem preditiva em Python |
| [esg-compliance-api](https://github.com/gustavogomes-dv/esg-compliance-api) | API REST de compliance ambiental. Spring Boot, JWT, Flyway, Oracle, Docker |

## Contato

[LinkedIn](https://www.linkedin.com/in/gustavogomesoliv) · [payrollia.com.br](https://payrollia.com.br)
