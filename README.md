# Fox17 — landing page

Página estática “em construção” da Fox17 (empresa de engenharia), publicada em [fox17.com.br](https://fox17.com.br/) via GitHub Pages. O repositório contém apenas HTML/CSS estático, `CNAME`, `robots.txt` e o workflow de deploy.

## DNS (domínio apex)

Aponte o apex `fox17.com.br` e o `www` para o GitHub Pages deste repositório:

| Tipo | Nome | Valor |
|------|------|--------|
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| AAAA | `@` | `2606:50c0:8000::153` |
| AAAA | `@` | `2606:50c0:8001::153` |
| AAAA | `@` | `2606:50c0:8002::153` |
| AAAA | `@` | `2606:50c0:8003::153` |
| CNAME | `www` | `fox17-br.github.io` |

No Cloudflare, deixe os registros em DNS only (nuvem cinza) até o GitHub emitir o certificado HTTPS; depois pode ativar o proxy se quiser.
