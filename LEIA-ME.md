# FUNCEF a Bordo · Portal do evento

Portal da Jornada da Liderança 2026, acessado pelo QR code do crachá.

## Arquivos

| Arquivo | Para que serve |
|---|---|
| `index.html` | O portal inteiro, com imagens e fontes embutidas. Não precisa mexer. |
| `dados.json` | O que muda perto do evento: data e links das fotos. **Edite só este.** |
| `robots.txt` | Impede que o Google e outros buscadores indexem a página. |

## Como atualizar a data e os links das fotos

1. No GitHub, abra o arquivo `dados.json` e clique no lápis (Edit).
2. Preencha entre as aspas, sem apagar as vírgulas nem as chaves:

```json
{
  "data_evento": "2026-12-10",
  "link_ver_fotos": "https://link-da-pasta-para-ver",
  "link_enviar_fotos": "https://link-para-enviar-fotos"
}
```

- `data_evento`: no formato ano-mês-dia. No dia do evento, o portal mostra "Agora: …" na programação.
- `link_ver_fotos`: o link para ver a pasta de fotos.
- `link_enviar_fotos`: o link para enviar fotos. Se for o mesmo, repita o link ou deixe em branco, e o botão usa o link de ver.
- Os links precisam começar com `https://`.

3. Clique em **Commit changes**. Em 1 a 2 minutos o portal está atualizado.
