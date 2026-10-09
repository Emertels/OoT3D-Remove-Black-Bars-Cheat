<div align="center">



# Ocarina of Time 3D — Remover Barras Pretas

**Cheat para remover as tarjas pretas ao mirar e usar itens.**

[![Português (Brasil)](https://img.shields.io/badge/Portugu%C3%AAs%20(Brasil)-PT--BR-009739?style=for-the-badge)](README.md)
[![English](https://img.shields.io/badge/English-EN-1F4E79?style=for-the-badge)](README.en.md)

[![Citra](https://img.shields.io/badge/Citra-Confirmado-2EA44F?style=for-the-badge)](#compatibilidade-confirmada-pelo-autor)
[![Azahar](https://img.shields.io/badge/Azahar-Confirmado-2EA44F?style=for-the-badge)](#compatibilidade-confirmada-pelo-autor)
[![Release](https://img.shields.io/github/v/release/Emertels/OoT3D-Remove-Black-Bars-Cheat?style=for-the-badge)](https://github.com/Emertels/OoT3D-Remove-Black-Bars-Cheat/releases)

**Contribuição original de Emerson Teles (@Emertels), com o código desenvolvido pelo OpenAI Codex a pedido do autor.**

</div>

---

## O que faz

Remove as tarjas pretas que aparecem durante a mira e o uso de itens em *The Legend of Zelda: Ocarina of Time 3D*. É um cheat pequeno e independente: não altera a câmera livre, o layout Single Screen nem outros elementos do jogo.

## Uma contribuição específica para OoT3D

O cheat foi criado para resolver esse comportamento específico na versão 3DS de *Ocarina of Time*. Nas pesquisas feitas para publicar este projeto, não encontramos outra publicação do mesmo código com esta finalidade e suporte documentado a Citra/Azahar. Existem outros patches que tratam barras pretas em OoT3D de outras maneiras; este repositório documenta esta solução de cheat, sua instalação e os testes feitos pelo autor.

## Compatibilidade confirmada pelo autor

- **Citra Canary:** funcionando no jogo North America / USA, Rev. 1.
- **Azahar Plus:** funcionando no jogo North America / USA, Rev. 1.
- **ID do jogo:** `0004000000033500`.
- O autor relata funcionamento normal nos dois emuladores.
- Outras regiões, revisões e IDs de jogo não foram testados.

## Instalação manual

1. Feche o emulador.
2. Encontre a pasta de dados do Citra ou Azahar. Em uma cópia portátil, é a pasta `user` ao lado do executável.
3. Dentro de `user`, abra ou crie a pasta `cheats`.
4. Copie o arquivo `0004000000033500.txt` deste repositório para `user\cheats`.
5. Abra o jogo e entre nas propriedades de *Ocarina of Time 3D*.
6. Na seção **Cheats**, marque **Remover Barras Pretas - Mira e Uso de Itens**.
7. Inicie ou reinicie o jogo e teste ao mirar e usar itens.

O repositório inclui o caminho pronto `user\cheats\0004000000033500.txt`. Você também pode baixar o ZIP da página de [Releases](https://github.com/Emertels/OoT3D-Remove-Black-Bars-Cheat/releases) e copiar a pasta `cheats` para dentro da pasta `user` do emulador.

## Código do cheat

```text
[Remover Barras Pretas - Mira e Uso de Itens]
D3000000 00000000
00330D98 1A00000F
D2000000 00000000
```

## Créditos e observações

O projeto foi organizado e publicado por **Emerson Teles (@Emertels)**. O código foi elaborado com auxílio do **OpenAI Codex**, a pedido de Emerson, e testado pelo autor em Citra Canary e Azahar Plus.

*The Legend of Zelda* é uma marca da Nintendo. Este projeto é independente e não é afiliado à Nintendo, Citra ou Azahar. Nenhum jogo, ROM ou arquivo de jogo é distribuído aqui.

---

## 👨‍💻 Sobre o Autor

Desenvolvido e mantido por **Emerson Teles** (conhecido na comunidade como **Emertels**).

Entusiasta de tecnologia, informática, jogos, manutenção de sistemas e tradução/localização de softwares para Português do Brasil (PT-BR). Desenvolvedor focado em utilitários práticos, ferramentas de produtividade, automação inteligente em PowerShell e soluções completas de localização técnica que aproximam ferramentas modernas do público brasileiro.

### 🛠️ Projetos & Contribuições

- [AI-Chat-Vault](https://github.com/Emertels/AI-Chat-Vault) — Backup portátil e recuperação de conversas locais de 20+ ferramentas e assistentes de IA.
- [Antigravity — Tradução PT-BR](https://github.com/Emertels/Antigravity-Traducao-PTBR) — Localização completa do Google Antigravity Desktop para Português do Brasil.
- [Codex Router — Tradução PT-BR](https://github.com/Emertels/CodexRouter-Traducao-PTBR) — Pacote de tradução e localização do Codex Router Control Center em PT-BR.
- [Cursor AI — Tradução PT-BR](https://github.com/Emertels/Cursor-Traducao-PTBR) — Localização completa e profunda do Cursor AI para Português do Brasil.
- [GPU Tweak III — Tradução PT-BR](https://github.com/Emertels/GPU-Tweak-III-Traducao-PTBR) — Tradução em português brasileiro e instalador automatizado para ASUS GPU Tweak III.
- [Microsoft Photos Fix](https://github.com/Emertels/Microsoft-Photos-Fix) — Solução definitiva em PowerShell e C# para rota de inicialização rápida e visualização no app Fotos do Windows.
- [PSBBN-Translator](https://github.com/Emertels/PSBBN-Translator) — Suíte corporativa de tradução e localização para o PSBBN Definitive Project (PlayStation 2) em 40 idiomas.
- [Silent Hill: Homecoming — Tradução PT-BR](https://github.com/Emertels/Silent-Hill-Homecoming-Traducao-PTBR) — Tradução e revisão completa do jogo para PC em português brasileiro.
- [Suite-Emuladores](https://github.com/Emertels/Suite-Emuladores) — Suíte inteligente em PowerShell para download e atualização autônoma de 56 emuladores e frontends no Windows.
- [ZCode — Tradução PT-BR](https://github.com/Emertels/ZCode-Traducao-PTBR) — Tradução e localização completa do ZCode Desktop para Português do Brasil.

### 🌐 Conecte-se comigo & Comunidades Oficiais

<div align="left">

[![GitHub](https://img.shields.io/badge/GitHub-Emertels-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/emertels)
[![Website](https://img.shields.io/badge/Website-Emerson_Teles-0070F3?style=for-the-badge&logo=googlechrome&logoColor=white)](https://emertels.github.io)
[![Discord](https://img.shields.io/badge/Discord-Emertels%20Server-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://emertels.github.io/discord)
[![X / Twitter](https://img.shields.io/badge/X_Twitter-@emertels-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/emertels)
[![YouTube](https://img.shields.io/badge/YouTube-Emerson_Teles-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@emersonteles2379)
[![Telegram](https://img.shields.io/badge/Telegram-Aplicativos%20Mods-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/apksmodsandroid)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Apoiar%20Projeto-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white)](https://ko-fi.com/emertels)

</div>
