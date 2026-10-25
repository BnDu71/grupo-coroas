# Grupo Coroas — Landing page

Página estática (HTML/CSS/JS em um único arquivo). Sem build.

## Configuração
Edite o bloco `CONFIGURAÇÃO` no final do `index.html`:
- `TELEGRAM_BOT_URL`: link do bot (todos os botões usam essa variável)
- `LEGAL`: URLs da Política de Privacidade, Termos de Uso e contato
- `FAQ_FILL`: textos sobre entrada e ajuda
- `TESTIMONIALS`: apenas depoimentos reais e autorizados
- `ANALYTICS_ENABLED`: manter `false` até haver consentimento

## Deploy
Importe o repositório na Vercel (Framework Preset: Other). Sem comando de build; o diretório raiz é a pasta do projeto.
