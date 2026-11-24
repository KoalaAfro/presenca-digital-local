<div align="center">

# 📍 presenca-digital-local

**Uma skill para o Claude planejar a presença digital de negócios locais de serviço no Brasil.**

Do diagnóstico à proposta comercial, em português, sem receita pronta de "growth hacking".

![Licença MIT](https://img.shields.io/badge/licen%C3%A7a-MIT-green)
![Idioma](https://img.shields.io/badge/idioma-pt--BR-009c3b)
![Claude Skill](https://img.shields.io/badge/Claude-Skill-d97757)
![Meta Ads](https://img.shields.io/badge/Meta%20Ads-leads-1877f2)

[O que faz](#-o-que-a-skill-faz) · [Instalação](#-instalação) · [Exemplos](#-exemplos-de-pedido) · [Estrutura](#-estrutura) · [Contribuir](#-contribuindo)

</div>

---

## 🎯 Para quem é

Agências e freelancers que vendem marketing para **negócios locais que fecham por conversa ou agendamento**:

| 🏥 Clínicas e consultórios | 💇 Salões e estúdios | 🏫 Escolas e cursos | 👤 Especialistas (marca pessoal) |
|---|---|---|---|

O foco é gerar **contato qualificado**, não curtida.

## 🧭 O que a skill faz

Ela segue um caminho em sete etapas. Se você já tem parte pronta (briefing, campanha rodando, resultados), o Claude começa na etapa certa.

| # | Etapa | O que você recebe | Referência |
|---|---|---|---|
| 1 | **Diagnóstico** | Cliente ideal, maior vazamento de contato e 3 ações para 30 dias | [`diagnostico.md`](skills/presenca-digital-local/references/diagnostico.md) |
| 2 | **Oferta e posicionamento** | Promessa em uma frase, bio do Instagram e pilares de conteúdo | [`oferta-e-posicionamento.md`](skills/presenca-digital-local/references/oferta-e-posicionamento.md) |
| 3 | **Campanha de leads (Meta Ads)** | Estrutura de campanha, conjuntos, destinos e o que medir | [`campanha-meta-leads.md`](skills/presenca-digital-local/references/campanha-meta-leads.md) |
| 4 | **Copy** | Variações A/B prontas para colar e mensagem inicial de WhatsApp | [`copy.md`](skills/presenca-digital-local/references/copy.md) |
| 5 | **Relatório de resultados** | Relatório de uma página que o cliente entende | [`relatorio-resultados.md`](skills/presenca-digital-local/references/relatorio-resultados.md) |
| 6 | **Proposta comercial** | Proposta de leitura rápida, com escopo e investimento claros | [`proposta-comercial.md`](skills/presenca-digital-local/references/proposta-comercial.md) |
| 7 | **Setores regulados** | Cuidados para saúde, educação, jurídico e finanças | [`setores-regulados.md`](skills/presenca-digital-local/references/setores-regulados.md) |

## 📦 Instalação

1. Baixe o repositório (**Code → Download ZIP**) ou clone:
   ```bash
   git clone https://github.com/KoalaAfro/presenca-digital-local.git
   ```
2. Use a pasta `skills/presenca-digital-local`:
   - **Claude Code:** copie a pasta para `~/.claude/skills/` (ou para `.claude/skills/` dentro do seu projeto).
   - **Claude (app):** compacte a pasta `presenca-digital-local` em `.zip` e envie como skill nas configurações do Claude.
3. Peça normalmente. O Claude carrega a skill quando o pedido for sobre estratégia, campanha, copy, relatório ou proposta para negócio local.

## 💬 Exemplos de pedido

```text
Faça o diagnóstico deste salão: [dados do negócio]
Monte a estrutura de campanha de leads para esta clínica em [bairro]
Escreva duas variações de anúncio para [negócio] em [bairro]
Monte o relatório do mês com estes números: [dados]
Prepare uma proposta em duas fases para [negócio]
```

## 📁 Estrutura

```
skills/presenca-digital-local/
├── SKILL.md                         # instruções principais da skill
└── references/
    ├── diagnostico.md               # perguntas e checagem de 15 minutos
    ├── oferta-e-posicionamento.md   # promessa, bio, pilares, alto padrão
    ├── campanha-meta-leads.md       # estrutura, destinos, orçamento, medição
    ├── copy.md                      # anúncios, A/B e WhatsApp
    ├── relatorio-resultados.md      # relatório para o cliente
    ├── proposta-comercial.md        # proposta e modelo em duas fases
    └── setores-regulados.md         # cuidados por setor
```

## ✅ Princípios

- **Um objetivo por campanha** e **um teste por vez**.
- **Medir o que dá para medir** e dizer o que não dá (clique no WhatsApp não é lead confirmado).
- **Sem promessa de resultado.** Metas e acompanhamento, sim; garantia, não.
- **Nada de dados de cliente** em material público.

## ⚠️ Limites

- O conteúdo é um ponto de partida e reflete práticas gerais. Plataformas e normas profissionais mudam: confira sempre a regra atual.
- Não é orientação jurídica.

## 🤝 Contribuindo

Sugestões e correções são bem-vindas, principalmente novos setores locais e ajustes quando uma plataforma mudar. Abra uma issue (sem dados de clientes) ou envie um pull request. Veja o [`CONTRIBUTING.md`](CONTRIBUTING.md).

## 📄 Licença

[MIT](LICENSE) © 2026 João Victor Freitas
