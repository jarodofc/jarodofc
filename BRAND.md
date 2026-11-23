# Identidade visual | Jarod

Este repositório é o perfil público do GitHub de **Jarod M. M. Jr.**. O README foi pensado para comunicar de forma clara a atuação profissional, projetos e canais de contato.

## Direção de arte

- **Conceito:** precisão digital, superfícies suaves e minimalismo funcional, com referências discretas a interfaces de terminal, Material UX e Liquid Glass.
- **Marca:** monograma geométrico `J_`, construído em vetores no cabeçalho.
- **Paleta escura:** fundo `#090E19`, superfície `#182440`, texto `#F7FAFF`.
- **Paleta clara:** fundo `#F8FAFF`, superfície `#EAF0FB`, texto `#17223B`.
- **Acentos:** coral `#FF5579` e azul `#7BA8FF`. O tema claro utiliza variantes com contraste reforçado.
- **Tipografia:** pilha de fontes de sistema com preferência por Inter; Consolas/Menlo nas microetiquetas técnicas. Nenhuma fonte remota é necessária.
- **Ícones:** SVGs vetoriais locais, com traço arredondado e espessura consistente.

## Arquivos de interface

| Arquivo | Função |
| --- | --- |
| `readme.md` | Conteúdo semântico, cartões, links e navegação do perfil |
| `hero-mr.svg` | Banner principal no tema escuro |
| `hero-light.svg` | Banner principal no tema claro |
| `footer-mr.svg` | Chamada de contato no tema escuro |
| `footer-light.svg` | Chamada de contato no tema claro |
| `assets/icons/*.svg` | Ícones vetoriais dos quatro serviços |
| `services-mr.svg` | Composição original preservada como referência histórica |

## Boas práticas

1. Preserve títulos, textos e links importantes como Markdown ou HTML semântico; não esconda informações críticas somente em SVG.
2. Para elementos ilustrativos, crie as duas variantes de tema e use `<picture>` com `prefers-color-scheme`.
3. Teste a leitura em larguras pequenas; evite concentrar parágrafos inteiros dentro de imagens.
4. Não adicione rastreadores, scripts, animações contínuas ou fontes externas ao perfil.
5. Mantenha as URLs e descrições dos projetos consistentes com seus respectivos repositórios.
