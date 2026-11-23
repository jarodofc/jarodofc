# JAROD.SYSTEM | Identidade visual 3.0

Perfil GitHub com uma única composição visual contínua e identidade hacker original, inspirada em interfaces de terminais e design tecnológico. Não utiliza símbolos, marcas ou imagens protegidas da série *Mr. Robot*.

## Arquitetura da interface

- **Um painel único:** `assets/visual/profile-dark.svg` e `profile-light.svg` reúnem identidade, resumo, serviços, projetos e contato, com uma linha vertical contínua de navegação.
- **Duas aparências:** modo escuro (*Crimson Console*) e modo claro (*Paper Terminal*), ativados automaticamente pelo `<picture>` e `prefers-color-scheme` do navegador/GitHub.
- **Microanimação:** cursor intermitente, luz do status e linha de varredura em CSS SVG. São decorativas, podem variar por navegador/renderização e respeitam `prefers-reduced-motion`. Sem JavaScript, bibliotecas ou fontes remotas.
- **Navegação clicável:** os quatro cartões de link são imagens SVG separadas envoltas em links HTML. As partes do painel único são visuais, pois um SVG dentro de `<img>` não oferece links independentes.
- **Conteúdo acessível:** um bloco `<details>` reproduz os dados essenciais em texto com links reais.

## Paleta

| Papel | Dark | Light |
| --- | --- | --- |
| Fundo | `#080A0E` | `#F8F6F6` |
| Superfície | `#13171C` | `#FFFFFF` |
| Borda | `#333941` | `#CFC8CD` |
| Texto | `#F7F8FA` | `#242229` |
| Texto secundário | `#B8C0CA` | `#55535D` |
| Acento vermelho | `#F03C55` | `#B52240` |

Tipografia com fallback local: Inter / Segoe UI / Arial, e JetBrains Mono / Consolas / Menlo para comandos. O perfil permanece legível se essas famílias não estiverem instaladas.

## Estrutura

```text
jarodofc/
├── README.md
├── BRAND.md
└── assets/
    ├── brand/jarod-mark.svg
    └── visual/
        ├── profile-dark.svg
        ├── profile-light.svg
        ├── link-forense-dark.svg
        ├── link-forense-light.svg
        ├── link-zentracast-dark.svg
        ├── link-zentracast-light.svg
        ├── link-trading-dark.svg
        ├── link-trading-light.svg
        ├── link-fly-dark.svg
        └── link-fly-light.svg
```

## Manutenção

Evite seções duplicadas ou cards de estilos diferentes fora do painel. Mantenha uma só fonte de cores para todos os vetores, preserve textos e links no README, teste visualmente claro/escuro e valide que os oito cartões de link tenham seus URLs funcionais. Indicadores visuais como `SESSION READY` são elementos ilustrativos e não status real de serviços.
