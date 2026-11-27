# FUNCEF a Bordo · Portal do evento

Portal da Jornada da Liderança 2026, acessado pelo QR code do crachá.

## Arquivos

| Arquivo | Para que serve |
|---|---|
| `index.html` | O portal inteiro, com imagens e fontes embutidas. |
| `dados.json` | A data do evento e o link da pasta de fotos. **Edite só este.** |
| `robots.txt` | Impede que buscadores indexem a página. |

## Como preencher a data e o link das fotos

1. No GitHub, abra `dados.json` e clique no lápis (Edit).
2. Preencha entre as aspas, sem apagar as vírgulas nem as chaves:

```json
{
  "data_evento": "2026-12-10",
  "link_fotos": "https://funcef.sharepoint.com/..."
}
```

- `data_evento`: formato ano-mês-dia. No dia do evento, o portal mostra "Agora: …" na programação.
- `link_fotos`: link da pasta de fotos (somente visualização, com login corporativo). Precisa começar com `https://`. Enquanto estiver vazio, o botão aparece desativado com "liberado em breve".

3. Clique em **Commit changes**. Em 1 a 2 minutos o portal está atualizado.
