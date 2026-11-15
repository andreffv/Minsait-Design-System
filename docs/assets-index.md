# Índice de assets

## Fontes — `assets/fonts/`

Família **ForFutureSans**, 5 pesos × normal/itálico:

| Peso | Ficheiro base |
|---|---|
| Light (300) | `ForFutureSans-Light`, `-LightItalic` |
| Regular (400) | `ForFutureSans-Regular`, `-RegularItalic` |
| Medium (500) | `ForFutureSans-Medium`, `-MediumItalic` |
| Bold (700) | `ForFutureSans-Bold`, `-BoldItalic` |
| Black (900) | `ForFutureSans-Black`, `-BlackItalic` |

Formatos: `Desktop Fonts/*.otf`, `Web Fonts/WOFF/*.woff`, `Web Fonts/WOFF2/*.woff2`.
Para web, preferir WOFF2 com WOFF como *fallback*.

## Logótipos — `assets/logos/minsait/`

Convenção `AF_MINSAIT_<TIPO>_<VARIANTE>`:

- **Tipo:** `LOG` = logótipo completo; `SIM` = símbolo.
- **Variante:** `POS` = positivo (para fundos claros); `NEG` = negativo (para fundos escuros).

Cada combinação tem um PNG de pré-visualização e uma pasta `… attachments/` com os formatos de
origem: `.ai`, `.eps`, `.svg`, `.png`, `.tif`, em `RGB` (ecrã) e `CMYK` (impressão).
Para web usar o `.svg` RGB.

## Pictogramas — `assets/pictograms/`

- `color/` – 288 SVG a cores
- `white/` – 288 SVG brancos (para fundos escuros ou de cor)

Os nomes estão em espanhol (ex.: `Acuerdo.svg`, `Almacén.svg`, `Altavoz.svg`).

## Ilustrações — `assets/illustrations/`

50 ficheiros (JPG/PNG). Dois grupos de nomes:

- `*_Minsait_Ilustracion_IA.jpg` – ilustrações oficiais geradas com IA (ciberseguridad, satélite, smart city, oficinas…)
- `img N.png` e nomes descritivos (`citizens.jpeg`, `urban1.jpg`, `VRvision.jpg`…)

## Imagens — `assets/images/`

30 ficheiros (23 JPG, 6 PNG, 1 TIF). Famílias por prefixo:

| Prefixo | Descrição |
|---|---|
| `GettyImages-<id>` | Fotografia de banco (Getty). Sufixo `_M` = formato médio, `_Baja` = baixa resolução |
| `BF_IA_*` | Imagens IA por tema (naturaleza, proyecciones, VR, tablet…) |
| `EL_IA_NN-*` | Imagens IA (global, medioambiente) |
| `iStock-*` | Fotografia de banco (iStock) |

## Pastas vazias

- `assets/icons/` – por preencher.
