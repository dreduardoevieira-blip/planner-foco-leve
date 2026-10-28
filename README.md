# Planner Foco Leve: página de vendas

Página de vendas do **Planner Foco Leve**, um planner digital e para impressão, não datado, feito para quem tem TDAH ou vive com a cabeça cheia de abas abertas.

🔗 **Site no ar:** https://planner-foco-leve.vercel.app

🛒 **Comprar:** https://go.hotmart.com/B108131984S

---

## Sobre o produto

- **Planner Ano Completo:** 826 páginas, de janeiro a dezembro, já na ordem de impressão
- **Pacote do Mês:** 86 páginas para imprimir um mês por vez
- **Passo a passo** em 12 etapas e uma divisória com o roteiro do 1º dia de cada mês
- **Índice clicável**, para usar no GoodNotes, Notability, Xodo, Samsung Notes ou impresso
- Formato PDF, tamanho A4, pagamento único

## Estrutura do repositório

```
planner-foco-leve/
├── index.html        → a página de vendas (HTML e CSS em um só arquivo)
├── termos.html       → termos de uso
├── privacidade.html  → política de privacidade (LGPD)
├── img/              → imagens do site (inclui img/infografico.jpg)
└── README.md         → este arquivo
```

O site não precisa de instalação nem de build: é um HTML estático publicado pela Vercel.

## Como publicar (Vercel)

O site está conectado à Vercel. Cada envio para a branch `main` deste repositório gera um novo deploy automaticamente, em menos de 1 minuto.

- Projeto na Vercel: **planner-foco-leve**
- Framework Preset: **Other** (sem build command e sem output directory)
- Domínio: `planner-foco-leve.vercel.app`

## Como editar

Abra o `index.html` no GitHub, clique no lápis (**Edit**), faça a alteração e clique em **Commit changes**. A Vercel publica a nova versão sozinha em cerca de 1 minuto.

### Oferta atual

- Preço: **R$ 38,82** (de ~~R$ 57,90~~), em até 12x no cartão
- Garantia: **7 dias**

### Campos que ainda precisam ser preenchidos

| Campo | O que colocar |
|---|---|
| `[SEU NOME OU RAZÃO SOCIAL]` | Seu nome completo ou o nome da empresa (em `termos.html` e `privacidade.html`) |
| `[SEU CPF OU CNPJ]` | Seu CPF ou CNPJ |
| `[SEU E-MAIL DE CONTATO]` | E-mail para suporte e privacidade |

Os botões de compra ("Quero meu Foco Leve", no topo, no cartão de preço e no final da página) levam ao checkout da Hotmart.

## Cores e fontes

| Uso | Valor |
|---|---|
| Fundo | `#fffaf0` |
| Verde (botões e oferta) | `#2f5b45` |
| Amarelo (destaques) | `#ffd66b` |
| Texto | `#29251f` |
| Fonte | Inter / fonte do sistema |

## Aviso

O Planner Foco Leve é uma ferramenta de organização. Não é tratamento e não substitui avaliação ou acompanhamento com médico ou psicólogo.

---

© Planner Foco Leve. Todos os direitos reservados.
