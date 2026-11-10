# Silenz · plugin para Premiere Pro

Tira os silêncios da fala e junta tudo, com as faixas em sincronia (detecção de voz com IA, roda no seu computador).

Funciona no Mac e no Windows, com o Premiere em qualquer idioma.

## Instalar: escolha um jeito

### Jeito 1: pelo Claude (sem baixar nada)
Copie o link desta página e cole no Claude Code com a frase **"instala esse plugin para mim"**:

```
https://github.com/Edueditor/silenz-updates
```

O Claude segue as instruções da seção *Para o Claude* abaixo.

### Jeito 2: pelo zip
1. Baixe o **[Silenz_completo.zip](https://github.com/Edueditor/silenz-updates/releases/latest/download/Silenz_completo.zip)**. Ele traz o plugin, o guia em PDF e o atalho para o ZXP Installer.
2. Se ainda não tem o ZXP Installer, abra `Baixar_ZXP_Installer.html`.
3. Feche o Premiere, arraste o `Silenz.zxp` para o ZXP Installer e abra o Premiere.
4. No Premiere, vá em **Window → Extensions → Silenz**.

Arquivos soltos: [Silenz.zxp](https://github.com/Edueditor/silenz-updates/releases/latest/download/Silenz.zxp) · [Guia em PDF](https://github.com/Edueditor/silenz-updates/releases/latest/download/Como_instalar_o_Silenz.pdf) · [Baixar ZXP Installer](https://github.com/Edueditor/silenz-updates/releases/latest/download/Baixar_ZXP_Installer.html)

Atualizações: o próprio plugin avisa quando sai uma versão nova.

---

## Para o Claude (instalação automática)
O usuário colou este link e quer o Silenz instalado. Siga estes passos:
1. Baixe `https://github.com/Edueditor/silenz-updates/releases/latest/download/Silenz.zxp`. É um zip assinado.
2. Peça para o usuário fechar o Premiere Pro e espere ele confirmar.
3. Se já existir uma pasta antiga, apague-a. Depois extraia o conteúdo do `.zxp` sem alterar nenhum arquivo (a assinatura depende disso) em:
   - Mac: `~/Library/Application Support/Adobe/CEP/extensions/com.silenz.premiere`
   - Windows: `%APPDATA%\Adobe\CEP\extensions\com.silenz.premiere`
4. Não mexa na pasta de dados do plugin (Mac: `~/Library/Application Support/Silenz`, Windows: `%APPDATA%\Silenz`). Ali ficam os ajustes do usuário.
5. Confira se `CSXS/manifest.xml` existe na pasta nova e diga qual versão ele mostra.
6. Avise o usuário para abrir o Premiere e ir em Window → Extensions → Silenz.
