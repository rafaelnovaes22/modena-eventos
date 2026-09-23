# Modena Eventos

A trilha do sim, ao vivo. Site da banda para casamentos em São Paulo (desde 2008) em arquivo único (`index.html`): serviços, formações, repertório com filtros por momento e estilo, salvos, pedido com envio no WhatsApp, depoimentos, FAQ e assistente.

Produção: https://rafaelnovaes22.github.io/modena-eventos/

Deploy: GitHub Pages via GitHub Actions (`.github/workflows/deploy-pages.yml`). Railway com trial expirado em 2026-09-22: migrar de volta quando o plano for reativado (Dockerfile nginx na porta 8080 mantido).

```powershell
python -m http.server 8000
```
