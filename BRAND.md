# JAROD.SYSTEM · Manual de identidade

> Perfil autoral com referências à linguagem visual de terminais, thrillers tecnológicos e interfaces hacker cinematográficas. O projeto não usa marcas, logotipos ou elementos oficiais de produções audiovisuais.

## Conceito

**Precisão, contraste, silêncio visual.** A direção de arte utiliza superfícies pretas, linhas finas, grids quase invisíveis e vermelho como elemento de decisão. O monograma `J_` representa assinatura pessoal e cursor de terminal. A influência de *Mr. Robot* aparece no clima e na composição, preservando identidade própria.

### Tokens

| Uso | Cor |
| --- | --- |
| Fundo raiz | `#08090D` |
| Painel | `#13151C` |
| Bordas | `#34313A` |
| Texto principal | `#F4F5F7` |
| Texto secundário | `#A6ADB9` |
| Vermelho de ação | `#F12A48` |

Tipografia: `Inter, Segoe UI, Arial, sans-serif` para títulos e `JetBrains Mono, Consolas, Menlo, monospace` para metadados. Fontes são pilhas de fallback: nenhum serviço externo é carregado pelos SVGs.

## Mapa dos arquivos

```text
jarodofc/
├── README.md                    # Conteúdo semântico do perfil
├── BRAND.md                     # Este manual
├── hero-mr.svg                  # Identidade principal / console
├── services-mr.svg              # Painéis vetoriais de atuação
├── footer-mr.svg                # Chamada de contato
└── assets/
    └── brand/
        └── jarod-mark.svg      # Marca J_ isolada e reutilizável
```

## Regras de manutenção

1. **Tema preto fixo.** O mesmo conjunto visual deve ser visto no GitHub claro e escuro.
2. **Conteúdo em Markdown.** Nomes, contexto, projetos e endereços de contato devem continuar em texto e links clicáveis. SVG é apresentação e reforço, não única fonte de informação.
3. **Sem JavaScript embutido, imagens remotas ou animação contínua.** SVGs são autossuficientes, seguros para embedding por `<img>`.
4. **Acessibilidade.** Use `alt` no README, `title/desc` nos vetores e tamanhos legíveis em telas pequenas.
5. **Sem métricas artificiais.** Indicadores do terminal como `SESSION: ACTIVE` são decorativos. Nunca representar serviços externos como disponíveis sem verificação.
6. **Manutenção dos links.** A cada alteração de domínio ou repositório, sincronize os URLs do README.

## Projetos do perfil

- **zFORENSE · LÚMEN:** OSINT e investigação digital com ferramentas no navegador
- **ZentraCast:** IPTV web e integração com Web Video Caster
- **zTRADING · AETHER:** painel web para análise de mercados
- **zFLY · RotaClara:** comparador de voos com interface web

A identidade pode ser reutilizada em novas apresentações do autor sem imitar diretamente personagens, empresas ou marcas de terceiros.
