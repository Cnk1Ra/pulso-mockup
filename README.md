# Pulso — Mockup de validação

Protótipo navegável (HTML/Tailwind) da plataforma **Pulso**, SaaS multi-tenant que gera, via IA, todos os ativos digitais de uma campanha política brasileira (identidade visual, jingle, áudios, posts, site, bot de WhatsApp, material gráfico) em até 72 horas.

Mockup construído para validação com sócios do candidato piloto antes do desenvolvimento da plataforma real.

## Telas

| Arquivo | Tela | Propósito |
|---|---|---|
| `index.html` | Landing comercial | Hero, como funciona, planos (Plus R$ 4.997 / Pro R$ 9.997), exemplos, FAQ |
| `onboarding.html` | Briefing estratégico | Etapa 4/7 do onboarding — propostas, adjetivos, tom de voz, referências regionais |
| `gerando.html` | Dashboard de geração | Progresso em tempo real das 47 peças sendo produzidas pela IA |
| `kit.html` | Kit pronto | Galeria de entrega com identidade, jingle, posts, gráfico, site, bot |

Candidato fictício usado no mockup: **Rafael Costa**, Dep. Estadual MG, MDB, número 15.789, base regional Vale do Aço.

## Stack do mockup

- HTML estático puro
- Tailwind CSS via CDN
- Google Fonts (Inter + Playfair Display)
- Sem build step — abre direto no navegador

## Stack pretendido para a plataforma real

Ver `CLAUDE.md` no repositório do projeto principal: Next.js 15 + Supabase + Pagar.me + Trigger.dev v3 + integrações de IA (Claude, Suno, ElevenLabs, Recraft, Bannerbear).

## Compliance

Todas as peças exibidas no mockup já indicam a **rotulagem obrigatória prevista pela Resolução TSE 23.732/2024** para conteúdo gerado por IA.
