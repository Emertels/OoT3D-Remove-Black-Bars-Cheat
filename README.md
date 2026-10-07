<div align="center">

# Ocarina of Time 3D — Remover Barras Pretas

**Cheat para remover as tarjas pretas ao mirar e usar itens.**

[![Citra](https://img.shields.io/badge/Citra-Confirmado-2EA44F?style=for-the-badge)](#compatibilidade)
[![Azahar](https://img.shields.io/badge/Azahar-Confirmado-2EA44F?style=for-the-badge)](#compatibilidade)
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

## Sobre Emerson Teles

Desenvolvedor, profissional de automação inteligente, engenharia reversa, tradução técnica e localização PT-BR. Apaixonado pela cultura gamer retrô e moderna, Emerson cria ferramentas, automações e projetos de localização para resolver problemas práticos e ajudar comunidades de usuários.



### Outros projetos

| Projeto | Descrição | Repositório |
| :--- | :--- | :---: |
| **Silent Hill: Homecoming PT-BR** | Tradução e revisão em Português do Brasil. | [Acessar](https://github.com/Emertels/Silent-Hill-Homecoming-Traducao-PTBR) |
| **PSBBN Translator** | Tradução e localização automatizada para o PSBBN Definitive Project. | [Acessar](https://github.com/Emertels/PSBBN-Translator) |
| **Suíte de Emuladores** | Ferramentas PowerShell para emuladores e frontends. | [Acessar](https://github.com/Emertels/Suite-Emuladores) |
| **AI-Chat-Vault** | Backup e recuperação de conversas locais de ferramentas de IA. | [Acessar](https://github.com/Emertels/AI-Chat-Vault) |
| **Microsoft Photos Fix** | Correções para inicialização rápida e papéis de parede no app Fotos. | [Acessar](https://github.com/Emertels/Microsoft-Photos-Fix) |
| **Roccat Syn Pro Air Fix** | Ferramentas de estabilização e áudio para o headset. | [Acessar](https://github.com/Emertels/Roccat-Syn-Pro-Air-Fix) |
| **Cursor Tradução PT-BR** | Localização do Cursor AI para Português do Brasil. | [Acessar](https://github.com/Emertels/Cursor-Traducao-PTBR) |
| **Google Antigravity Tradução PT-BR** | Localização do Google Antigravity Desktop. | [Acessar](https://github.com/Emertels/Antigravity-Traducao-PTBR) |
| **ZCode Tradução PT-BR** | Localização do ZCode Desktop. | [Acessar](https://github.com/Emertels/ZCode-Traducao-PTBR) |
| **Portal Oficial** | Portal de ferramentas, projetos e canais da comunidade. | [Acessar](https://github.com/Emertels/emertels.github.io) |

[Ver todos os repositórios de Emerson Teles no GitHub](https://github.com/Emertels?tab=repositories)

---

## Encontre-me

### Encontre-me

[![Website](https://img.shields.io/badge/Website-emertels.github.io-0070F3?style=for-the-badge&logo=googlechrome&logoColor=white)](https://emertels.github.io)
[![Discord](https://img.shields.io/badge/Discord-Comunidade%20Oficial-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://emertels.github.io/discord)
[![YouTube](https://img.shields.io/badge/YouTube-@emersonteles2379-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@emersonteles2379)
[![Telegram](https://img.shields.io/badge/Telegram-Aplicativos%20Mods-24A1DE?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/apksmodsandroid)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Apoiar%20Projetos-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white)](https://ko-fi.com/emertels)
[![X](https://img.shields.io/badge/X-@emertels-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/emertels)
