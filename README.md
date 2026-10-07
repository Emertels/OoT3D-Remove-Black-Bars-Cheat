<div align="center">

# Ocarina of Time 3D — Remover Barras Pretas

**Cheat para remover as tarjas pretas que aparecem ao mirar e ao usar itens.**

Criado com auxílio do **OpenAI Codex**, a pedido de **Emerson Teles (@Emertels)**.

</div>

---

## O que faz

Remove as barras pretas exibidas durante a mira e o uso de itens em *The Legend of Zelda: Ocarina of Time 3D*. Este é um cheat simples, não um mod de câmera livre nem um mod Single Screen.

## Compatibilidade conhecida

- **Citra Canary:** confirmado funcionando pelo autor no jogo da região North America, Rev. 1.
- **Azahar Plus:** usa o mesmo formato de arquivo de cheat. O arquivo está preparado para instalação, mas o funcionamento visual ainda precisa ser confirmado diretamente no Azahar.
- **ID do jogo visado:** `0004000000033500` (North America / USA).
- Outras regiões, revisões ou IDs de jogo não foram testados.

## Instalação manual

1. Feche o emulador.
2. Localize a pasta de dados do Citra ou Azahar. Em cópias portáteis, use a pasta `user` que fica junto aos arquivos do emulador.
3. Abra ou crie a pasta `user\cheats`.
4. Copie `0004000000033500.txt` para dentro de `user\cheats`.
5. Abra o jogo, entre nas propriedades do título, abra **Cheats** e marque o cheat para ativá-lo.
6. Inicie ou reinicie o jogo e teste mirando e usando um item.

O repositório também inclui a estrutura `user\cheats\0004000000033500.txt`, pronta para copiar a pasta `cheats` para dentro da pasta `user` do emulador.

## Código

```text
[Remover Barras Pretas - Mira e Uso de Itens]
D3000000 00000000
00330D98 1A00000F
D2000000 00000000
```

## Créditos e observações

O código foi preparado com auxílio do OpenAI Codex, a pedido de Emerson Teles. O nome *The Legend of Zelda* e os direitos do jogo pertencem à Nintendo. Este projeto é independente e não é afiliado à Nintendo, Citra ou Azahar. Nenhum jogo, ROM ou arquivo de jogo está incluído.

Se funcionar em outra revisão, região ou versão do emulador, informe essa combinação com detalhes para que a compatibilidade possa ser registrada corretamente.
