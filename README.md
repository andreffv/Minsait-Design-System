# Minsait Design System

Repositório partilhado de recursos de marca (fontes, logótipos, pictogramas, imagens e
ilustrações) e tokens para projetos ligados à Minsait.

> **Estado:** os assets de marca já estão carregados e a tipografia usa a ForFutureSans.
> As cores e o espaçamento em `tokens/` continuam `PROVISÓRIO` e `assets/icons/` está vazia.

## Estrutura

| Pasta | Conteúdo | Ficheiros |
|---|---|---|
| `assets/fonts/` | Família **ForFutureSans** (10 estilos): `Desktop Fonts/` (OTF), `Web Fonts/WOFF` e `Web Fonts/WOFF2` | 30 |
| `assets/logos/minsait/` | Logótipo e símbolo, versões positiva e negativa, com formatos de origem (AI, EPS, SVG, PNG, TIF; RGB e CMYK) | 4 PNG + 4 pastas `attachments` |
| `assets/pictograms/` | Pictogramas SVG em `color/` e `white/` | 288 + 288 |
| `assets/illustrations/` | Ilustrações (muitas geradas com IA) | 50 |
| `assets/images/` | Fotografia e imagens IA (Getty, iStock, banco interno) | 30 |
| `assets/icons/` | Vazia | 0 |
| `tokens/` | `typography.css` (ForFutureSans via `@font-face`), `colors.css` e `spacing.css` (provisórios) | 3 |
| `docs/` | Documentação e style guide | – |

O índice detalhado, com convenções de nomes, está em [`docs/assets-index.md`](docs/assets-index.md).

## Notas importantes

- **Licenças:** `assets/images/` contém imagens Getty Images e iStock. Confirmar
  que a licença cobre o uso previsto antes de as reutilizar num projeto.
- **Tamanho:** o repositório ocupa cerca de 590 MB (`assets/images/` ≈ 370 MB e `assets/illustrations/` ≈ 136 MB). Os
  logótipos têm 83 MB por incluírem os formatos de origem. Considerar Git LFS se continuar a crescer.
- **Variantes `_Baja`:** 6 imagens têm uma versão de baixa resolução com sufixo `_Baja`; as restantes
  só existem numa versão.
- **Nomes de ficheiro** contêm espaços, acentos e mistura de espanhol, inglês e italiano. Ao
  referenciar em código, usar caminhos com *encoding* correto.

## Próximos passos

1. Substituir os tokens provisórios de cores e espaçamento pelos valores do manual de marca
2. Confirmar a licença da ForFutureSans para os usos previstos
3. Preencher `assets/icons/` ou decidir usar apenas os pictogramas
4. Normalizar nomes de ficheiros e decidir sobre Git LFS
5. Definir componentes conforme a stack dos projetos consumidores
