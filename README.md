# b2bfull-cadastro-web

Página pública estática (HTML puro, sem build) de auto-cadastro do B2BFull.
Envia os dados para o microserviço `b2bfull-cadastro`
(`https://b2bfull-cadastro-frqkw.ondigitalocean.app/register`).

Feita em HTML/CSS/JS puro de propósito: deploy como site estático no
DigitalOcean App Platform é gratuito (até 3 apps só-estáticos por conta),
sem necessidade de build step.

## Deploy

App Platform → Create App → GitHub → este repositório → Static Site
(detecta sozinho, sem build command). Depois associar domínio próprio
(ex.: `cadastro.b2bfull.com.br`) em Networking.
