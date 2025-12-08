<div align="center">

  <img src="https://raw.githubusercontent.com/carlosvcl/yugen-files/main/assets/minecraft.png" alt="Logo YugenYumi" width="300" />

  # YugenYumi Client
  
  **A Nova Geração de Client PvP para Minecraft 1.8.9**
  
  [![Version](https://img.shields.io/badge/version-1.0.0%20Beta-ff4757?style=for-the-badge&logo=appveyor)](https://github.com/carlosvcl/yugenyumi-site/releases)
  [![Electron](https://img.shields.io/badge/Built%20With-Electron-47848F?style=for-the-badge&logo=electron)](https://www.electronjs.org/)
  [![Minecraft](https://img.shields.io/badge/Support-1.8.9-green?style=for-the-badge&logo=minecraft)](https://minecraft.net)
  [![Windows](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows)](https://microsoft.com)

  <p align="center">
    <a href="#-funcionalidades">Funcionalidades</a> •
    <a href="#-instalação">Instalação</a> •
    <a href="#-galeria">Galeria</a> •
    <a href="#-desenvolvimento">Desenvolvimento</a>
  </p>

</div>

---

## ⚡ Sobre o Projeto

**YugenYumi** é um Client focado em performance e estética para Minecraft 1.8.9. Diferente de outros launchers, ele automatiza a instalação do **Forge**, **OptiFine** e os melhores **Mods de PvP**, entregando uma experiência pronta para jogar com apenas um clique.

O design foi construído seguindo o conceito japonês *Yugen* (beleza misteriosa e profunda), com uma interface moderna, glassmorphism e animações fluidas.

## 🚀 Funcionalidades

### 🎮 Performance & PvP
* **FPS Boost:** Otimizações nativas via OptiFine e argumentos JVM personalizados.
* **Mods Inclusos:**
    * `KeystrokesMod` (Teclas na tela)
    * `ToggleSprint` (Correr automaticamente)
    * `OldAnimations` (Animações da 1.7 para PvP fluido)
    * `BlockOverlay` (Bordas de bloco RGB/Custom)
* **Conexão Direta:** Botões de acesso rápido para **MushMC** e **Hypixel**.

### 💻 Launcher Moderno
* **Sistema de Contas:** Suporte para Login Microsoft (Original) e Offline.
* **Auto-Update:** O launcher baixa e corrige arquivos do jogo automaticamente.
* **Custom Main Menu:** Menu principal do jogo totalmente redesenhado para combinar com o launcher.
* **Gerenciador de RAM:** Slider intuitivo para alocar memória.

---

## 📥 Instalação

1.  Acesse a aba **[Releases](../../releases)** deste repositório.
2.  Baixe o arquivo `YugenYumi Setup 1.0.0.exe`.
3.  Execute o instalador.
4.  Faça login e clique em **JOGAR**.
    * *Nota: Na primeira execução, o launcher pode demorar alguns minutos para baixar o Minecraft Vanilla e configurar o Forge.*

---

## 📸 Galeria

| Launcher Home | Menu In-Game |
|:---:|:---:|
| <img src="COLOQUE_LINK_DA_PRINT_DO_LAUNCHER_AQUI" width="400"> | <img src="COLOQUE_LINK_DA_PRINT_DO_MENU_AQUI" width="400"> |

| Seletor de Mods | Gerenciador de Contas |
|:---:|:---:|
| <img src="COLOQUE_LINK_DA_PRINT_DOS_MODS_AQUI" width="400"> | <img src="COLOQUE_LINK_DA_PRINT_DAS_CONTAS_AQUI" width="400"> |

---

## 🛠️ Desenvolvimento

Se você é desenvolvedor e quer compilar o código fonte:

```bash
# Clone este repositório
$ git clone [https://github.com/carlosvcl/yugenyumi-client](https://github.com/carlosvcl/yugenyumi-client)

# Instale as dependências
$ npm install

# Inicie em modo de desenvolvimento
$ npm start

# Gere o executável (.exe)
$ npm run dist
