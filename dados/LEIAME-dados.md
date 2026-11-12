# Dados abertos do Painel de Vagas

Gerados a partir do mesmo banco do painel (https://projetoindustrial.github.io/vagas/). Leituras das vagas: 13 e 14/10/2026. Gerado em 2026-11-07.

| Arquivo | Conteúdo |
|---|---|
| `vagas.csv` | 4700 vagas, uma por linha (UTF-8, vírgula) |
| `vagas.jsonl` | as mesmas vagas, um objeto JSON por linha, com requisitos estimados e o texto da vaga (descrição, responsabilidades, requisitos) quando lido |
| `empresas.json` | 275 empresas com unidades, canais de candidatura e contagem de vagas |

Campos `nivel_estimado` e `area_estimada` vêm de palavras-chave do título e podem errar. `requisitos` (formação, ferramentas, normas, idiomas, experiência) vêm de regras de palavras-chave sobre o texto da vaga e existem só para vagas do Brasil lidas em detalhe. Fonte de cada vaga: página pública de carreiras da empresa (`url_oficial`). Projeto independente, sem vínculo com as empresas.
