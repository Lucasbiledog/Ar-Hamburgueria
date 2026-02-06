# Como Obter os Modelos 3D de Hambúrguer

## Opção 1: Poly.pizza (Recomendado - Gratuito, sem login)

Acesse cada link e clique em "Download" > "GLB":

| Modelo | Link |
|--------|------|
| Hambúrguer completo | https://poly.pizza/m/7ZLzqvaiFh7 |
| Cheeseburger | https://poly.pizza/m/eke7qcu_FR2 |
| Hambúrguer estilizado | https://poly.pizza/m/4BUVFQhihq |
| Pack de comidas | https://poly.pizza/bundle/Ultimate-Food-Pack-h3WC1gyRb4 |

Após baixar, renomeie os arquivos para:
- `smash.glb`
- `tradicional.glb`
- `duplo.glb`
- `bacon.glb`
- `monstro.glb`
- `compare.glb` (use um hambúrguer grande ou crie no Blender)

## Opção 2: Sketchfab (CC0 - Domínio Público)

1. Acesse: https://sketchfab.com/3d-models/cc0-hamburger-a6888a07938b4af4986cd05794961250
2. Clique em "Download 3D Model" (requer conta gratuita)
3. Selecione formato "glTF" ou "Original"
4. Renomeie para os nomes acima

## Opção 3: Criar no Blender (Avançado)

1. Baixe o Blender: https://www.blender.org
2. Crie ou importe modelos de hambúrguer
3. Exporte como GLB: File > Export > glTF 2.0 (.glb)

## Gerando arquivos USDZ para iOS

### Reality Converter (macOS)
1. Baixe: https://developer.apple.com/augmented-reality/tools/
2. Arraste o arquivo .glb
3. Exporte como .usdz

### Conversão Online
- https://products.aspose.app/3d/conversion/glb-to-usdz
- https://imagetostl.com/convert/file/glb/to/usdz

## Estrutura Final de Arquivos

```
burger-ar/
├── index.html
├── smash.glb
├── smash.usdz (opcional, para iOS)
├── tradicional.glb
├── tradicional.usdz
├── duplo.glb
├── duplo.usdz
├── bacon.glb
├── bacon.usdz
├── monstro.glb
├── monstro.usdz
├── compare.glb
└── compare.usdz
```

## Testando

1. Hospede em HTTPS (GitHub Pages, Netlify, Vercel)
2. Acesse pelo celular
3. Toque em "Ver em AR"

## Licenças

- **Poly.pizza**: CC0 / CC-BY (verificar cada modelo)
- **Sketchfab CC0**: Domínio público
- Sempre verifique a licença antes de uso comercial
