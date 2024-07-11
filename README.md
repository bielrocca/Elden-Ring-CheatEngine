## Último lançamento

[![Download](https://img.shields.io/badge/dynamic/json.svg?label=download&url=https://api.github.com/repos/The-Grand-Archives/Elden-Ring-CT-TGA/releases/latest&query=$.assets[0].name&style=for-the-badge)](https://github.com/bielrocca/Elden-Ring-CheatEngine/releases/tag/v1.13.0)  
[Changelog](/CHANGELOG.md)

### Requisitos

Cheat Engine: [7.4](https://github.com/cheat-engine/cheat-engine/releases)  
Game: App ver. 1.12

## Como usar

### Informações

Esta table não se destina a ser usada online e você provavelmente será banido se tentar fazê-lo.

### Cheat Table (Windows)

1. Baixe e instale o Cheat Engine no [Github](https://github.com/cheat-engine/cheat-engine/releases) ou no [website](https://cheatengine.org/)
2. Baixe a [Tabela de dicas](https://github.com/The-Grand-Archives/Elden-Ring-CT-TGA/releases)
3. Descompacte o arquivo .CT em qualquer lugar, uma recomendação seria sua pasta **My Cheat Tables** (por exemplo, `%USERPROFILE%\Documents\My Cheat Tables`)
4. Desative o EasyAntiCheat e execute o jogo, consulte [Desativar o EasyAntiCheat](#disabling-easyantiCheat)
5. Carregue o arquivo .CT diretamente clicando duas vezes ou selecionando-o e pressionando Enter, ou inicie o Cheat Engine e carregue o arquivo .CT via Arquivo-> Carregar ou clicando no ícone da pasta
6. Ative o script "Abrir" marcando sua caixa

### Cheat Table (Linux)

Espero que você já tenha Steam, Wine, Proton e o jogo instalados

1. Inicie o jogo pelo menos uma vez via Steam para configurar seu prefixo de vinho
2. Instale [protonhax](https://github.com/jcnils/protonhax) (No Arch você deve pegar [protonhax-git](https://aur.archlinux.org/packages/protonhax-git))
3. Baixe e instale a versão **Windows** do Cheat Engine no [Github](https://github.com/cheat-engine/cheat-engine/releases) ou no [site](https://cheatengine .org/) usando **Wine**
4. Baixe a [Tabela de dicas](https://github.com/The-Grand-Archives/Elden-Ring-CT-TGA/releases)
5. Descompacte o arquivo .CT em qualquer lugar, uma recomendação seria algum lugar que você possa encontrar facilmente dentro do prefixo wine criado para o jogo (por exemplo, `~/.steam/steam/steamapps/compatdata/1245620/pfx/drive_c/`)
6. No Steam, defina as opções de inicialização do jogo para `protonhax init %command%`
7. Execute o jogo via Steam ([Desativar EasyAntiCheat](#disabling-easyanticheat) é opcional)
8. Execute o Cheat Engine via `protonhax run 1245620 /path/to/Cheat\ Engine.exe` no terminal de sua escolha ou coloque-o em um script de shell (substitua `/path/to/` pelo caminho real para onde você instalou CE)
9. Carregue o arquivo .CT via Arquivo -> Carregar ou clicando no ícone da pasta
10. Ative o script "Abrir" marcando sua caixa

### Desativando EasyAntiCheat

#### Método 1 - Recomendado

1. Descompacte `steam_appid.txt` da [versão mais recente](https://github.com/The-Grand-Archives/Elden-Ring-CT-TGA/releases/latest)
2. Localize sua pasta Elden Ring (por exemplo, `C:\Program Files\Steam\steamapps\common\ELDEN RING\Game` ou `~/.steam/steam/steamapps/common/ELDEN RING/Game/`)
3. Mova `steam_appid.txt` para a mesma pasta do executável Elden Ring (`eldenring.exe`)
4.
   - Windows: execute o jogo via `eldenring.exe`
   - Linux: adicione `eldenring.exe` como um aplicativo não Steam e execute-o


#### Método 2 - Compatibilidade

1. Baixe o iniciador offline de LukeYui em [Nexusmods](https://www.nexusmods.com/eldenring/mods/98) ou [Github](https://github.com/LukeYui/launch_modded_eldenring)
2. Localize sua pasta Elden Ring (por exemplo, `C:\Program Files\Steam\steamapps\common\ELDEN RING\Game` ou `~/.steam/steam/steamapps/common/ELDEN RING/Game/`)
3. Mova o arquivo .exe baixado para a mesma pasta do executável Elden Ring (`eldenring.exe`)
4.
   - Windows: execute o jogo através do **Iniciador offline**
   - Linux: adicione o **Offline Launcher** ao Steam como um aplicativo não Steam e execute-o

#### Método 3 - Legado

1. Localize sua pasta Elden Ring (por exemplo, `C:\Program Files\Steam\steamapps\common\ELDEN RING\Game` ou `~/.steam/steam/steamapps/common/ELDEN RING/Game/`)
2. Renomeie `start_protected_game.exe` para outro nome (por exemplo, `start_protected_game.exe.bak`)
3. Renomeie `eldenring.exe` para `start_protected_game.exe`
4. Execute o jogo via Steam ou `start_protected_game.exe`

## Créditos

The Grand Archives | Reason
------------- | ---------------------
Ametalão | Contribuições de tabela (DS3)
Apricus | Sinalizadores de evento, MassItemGib
Esper descuidado | Nomes de identificação de graça
[Coinsworth](https://github.com/LukeYui/) | Contribuições de mesa, conselhos
Dalvik | Conselhos, ideias
[Dasaav](https://github.com/Dasaav-dsv) | Retrabalhos e adições de funcionalidades
[hery](https://github.com/heryoff) | Nomes de identificação de graça
[Igromanru](https://github.com/igromanru) | Param Patcher, conselho
[inuNorii](https://github.com/inuNorii) | Portando, mantendo, pesquisando
Jouta Kujo | Scripts de parâmetros
RBT | Scripts de parâmetros, sinalizadores de eventos
Abandonado001 | Contribuições de mesa
[sfix](https://github.com/garyttierney) | Contribuições de tabela, param dumps, conselhos
Silêncio | Planilha
O-Chefe do Raid | Adições de MassItemGib
[tremwil](https://github.com/tremwil/) | CParamUtils e mais contribuições de tabela


Github | Reason
------------- | ---------------------
[Mar-Veloz](https://github.com/Mar-Veloz) | Dê a todos os materiais de artesanato x999
[qwelias](https://github.com/qwelias) | Ponteiro ReinforceLv

Comunidade PvP perfeita | Reason
------------- | ---------------------
Jacky Dima | Contribuições de roteiro
Jouta Kujo | Contribuições de roteiro
Laranja | Contribuições de roteiro

Others | Reason
------------- | ---------------------
AssassinXMod | Unlock all Summoning Pools
Pav | Free Camera
