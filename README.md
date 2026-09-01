# FoodFast — LGPD e APIs de pagamento

Material de apoio da apresentação do **Grupo 5** na disciplina de Compliance (FAMINAS),
sobre o cenário fictício *FoodFast — o delivery universitário*.

**Cartão surpresa do grupo:** terceirização e APIs de pagamento — como a arquitetura
de microsserviços isola o risco de dados de cartão de crédito.

## Páginas

| Arquivo | O que é |
|---|---|
| `index.html` | A explicação sem palavra difícil — guarda-volumes, gavetas separadas, Ctrl+Z. É o que abre pelo QR code. |
| `tecnico.html` | A versão técnica: fluxo detalhado, schema do banco, artigos da LGPD e PCI-DSS. |

As duas páginas têm dois simuladores que rodam no navegador, sem servidor:
o **vazamento do banco de dados** (comparando as duas arquiteturas) e a
**falha de TLS** (mostrando o rollback).

## Rodando local

Site estático, sem build. Basta abrir o `index.html` no navegador, ou:

```bash
npx serve .
```

## Referências

- Lei nº 13.709/2018 (LGPD)
- PCI-DSS v4.0
