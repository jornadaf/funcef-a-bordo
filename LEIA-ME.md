# FUNCEF a Bordo · Portal do evento

Portal da Jornada da Liderança 2026, acessado pelo QR code do crachá.

## Arquivos

| Arquivo | Para que serve |
|---|---|
| `index.html` | O portal inteiro, com imagens e fontes embutidas. |
| `dados.json` | A data do evento. **Edite só este.** |
| `robots.txt` | Impede que buscadores indexem a página. |

## Como preencher a data do evento

1. No GitHub, abra `dados.json` e clique no lápis (Edit).
2. Preencha a data no formato ano-mês-dia, entre as aspas:

```json
{
  "data_evento": "2026-12-10"
}
```

No dia do evento, o portal mostra "Agora: …" na programação.

3. Clique em **Commit changes**. Em 1 a 2 minutos o portal está atualizado.
