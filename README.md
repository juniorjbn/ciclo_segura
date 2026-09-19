# Ciclo Segura

![Ciclo Segura — segurança, saúde, ciência e mobilidade ativa. Uma iniciativa da NEUROPSI.io](img/og.jpg)

## Segurança, saúde, ciência e mobilidade ativa

Landing page da Ciclo Segura, iniciativa social idealizada e coordenada pela NEUROPSI.io que conecta comunidade, saúde, ciência e políticas públicas para construir uma cultura permanente de segurança na mobilidade ativa, a partir da Ciclo Rio Pinheiros, em São Paulo.

**Acesse:** https://juniorjbn.github.io/ciclo_segura/

## Como funciona

Página estática de arquivo único, sem build e sem dependências externas. `index.html` carrega CSS, JavaScript e a fonte Bricolage Grotesque (embutida em base64) inline — nenhuma requisição sai para CDN, o que mantém o carregamento rápido e a página funcionando offline.

Publicação por GitHub Pages direto da branch, com a raiz do repositório como origem. Para editar, altere `index.html` e faça push.

```
index.html   página completa (marcação, estilos, scripts e fonte)
img/         logo, favicons e imagem de compartilhamento
```

## Paleta

Extraída por amostragem de pixels do logo oficial.

| Papel | Hex | Origem no logo |
|---|---|---|
| `--navy` | `#03496a` | wordmark "CICLO", ciclista e bicicleta |
| `--navy-deep` | `#022f45` | variação escura para seções de contraste |
| `--blue` | `#05688a` | variação para texto sobre fundo claro |
| `--cyan` | `#0490be` | arco esquerdo e swoosh |
| `--amber` | `#fdb71b` | wordmark "SEGURA", arco direito e pontos |

Todas as combinações de texto e fundo usadas na página passam no contraste mínimo AA da WCAG 2.1. O âmbar é sempre aplicado com texto em `--navy-deep`, nunca em branco.

## Estrutura da página

Origem do projeto · manifesto · o que é a iniciativa · sete dimensões · os sete componentes do ecossistema · jornada do participante · o que acontece no dia a dia · ciência e políticas públicas · o que a iniciativa não é · Programa Membro · formas de apoiar e rede de parceiros · perguntas frequentes · contato.

## Contato

- **Instagram:** [@ciclosegura](https://www.instagram.com/ciclosegura)
- **E-mail:** dricardoso@usp.br
- **NEUROPSI.io:** https://neuropsi.io
