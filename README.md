# Agency Delivery OS Marketplace

> Marketplace público (MIT) para o Claude Code listando o framework
> [Agency Delivery OS](https://github.com/giuseppe-commits/agency-delivery-os)
> e plugins relacionados.

## Como instalar

No Claude Code (CLI ou desktop), uma vez na vida:

```text
/plugin marketplace add giuseppe-commits/agency-delivery-os-marketplace
```

Depois, pra instalar o plugin:

```text
/plugin install agency-delivery-os
```

As 28+ skills (`/ag-*`) ficam disponíveis automaticamente em qualquer
projeto onde abras Claude Code — sem necessidade de clonar o repo do
framework ou de flags `--add-dir`.

Para consultar a documentação canônica (PRD/ARCHITECTURE/ROADMAP)
após instalação, use a skill `/ag-docs`.

## Atualizar

```text
/plugin install agency-delivery-os
```

A reinstalação resolve a tag mais recente referenciada no
`marketplace.json` deste repo.

## Plugins listados

### agency-delivery-os (v3.1.0)

Framework de multi-agentes de IA para agências boutique de marketing
digital. Skills cobrem onboarding de cliente, calendário de conteúdo,
copy de anúncios, landing pages, sequências de email, planos de
campanha, relatórios, briefings criativos, auditoria de mídia,
pesquisa de concorrência e perfis de audiência — além de critics
determinísticos pra validação automática de output.

- **Repo:** [giuseppe-commits/agency-delivery-os](https://github.com/giuseppe-commits/agency-delivery-os)
- **Versão atual:** v3.1.0
- **Licença:** MIT
- **Idioma:** Português brasileiro

## Sobre este marketplace

Este repo serve apenas pra discovery — o código de cada plugin vive
no repo próprio (campo `source` em `marketplace.json`). Forks são
bem-vindos.

## Adicionar um plugin

Se queres adicionar um plugin teu ao marketplace, abre um PR
modificando `marketplace.json`. Critérios:

- O plugin tem `.claude-plugin/plugin.json` válido na raiz do repo
- Licença permite redistribuição
- README explica claramente quando usar e como instalar
- Versionamento segue semver

Reservo o direito de não aceitar plugins que não façam sentido
no contexto do marketplace, sem necessidade de justificativa
detalhada.

## Mantenedor

Giuseppe Lira (giuseppe@modernista.digital)
