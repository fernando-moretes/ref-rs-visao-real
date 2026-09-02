# ref-rs-visao-real

Public Fernando Moretes repository connected to the broader architecture and engineering portfolio.

**Tipo:** Arquitetura de referência · **Stack:** Python · **Temas:** `brazil`, `emergency-response`, `gis`, `moretes`, `open-source`, `portfolio`, `python`, `rio-grande-do-sul`, `satellite-imagery`

## Como rodar

```bash
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## Estrutura

```
src/
tests/
```

## Contribuindo

Este repositório segue as convenções de [`fernandofatech/platform`](https://github.com/fernandofatech/platform):

- Branch: `<tipo>/<escopo>` — `feat/`, `fix/`, `chore/`, `docs/`
- Commit e título de PR: [Conventional Commits](https://www.conventionalcommits.org)
- A versão sai dos commits; ninguém escreve número de versão à mão

A pipeline (`pr-lint`, CI, segurança e release) vem dos workflows reutilizáveis do `platform` — corrigir a régua é mudar um arquivo lá, não aqui.
