# VitaSense DRE Visual — Deploy na Vercel

Passos rápidos para publicar este projeto (site estático) na Vercel.

Opção A — Importar pelo dashboard (mais simples)
- Vá para https://vercel.com/new
- Arraste a pasta `vitasense-dre-visual` (ou conecte o repositório Git) e importe.
- Configure o framework detection como `Static` se necessário. Build command: vazio. Output directory: `/`.

Opção B — Usando Vercel CLI
- Instale o CLI: `npm i -g vercel`
- No terminal, entre na pasta do projeto e rode:

```bash
cd vitasense-dre-visual
vercel
```

Aceite as opções padrão (deploy público). O `vercel.json` já força `index.html` como entrada.

Observações
- Se houver assets (imagens, CSS externos) em outras pastas, coloque-os dentro desta pasta antes do deploy.
- Para usar um domínio próprio, configure via dashboard da Vercel.
