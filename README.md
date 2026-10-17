# DARKVIWS — AI Video Studio

Interface inicial Cyberpunk para Windows, em Electron. O código inclui gerenciamento local de projetos e navegação. **Esta versão não gera vídeos nem vozes com IA**; o motor de IA será conectado futuramente.

## Como obter o instalador Windows

1. Abra a aba **Actions** no repositório.
2. Selecione a execução mais recente de **DARKVIWS Windows Installer** e aguarde o status verde **Success**.
3. Na página da execução, procure **Artifacts** e clique em **DARKVIWS-Windows-Setup** para baixar um ZIP.
4. No Windows, clique com o botão direito no ZIP e escolha **Extrair tudo**.
5. Abra a pasta extraída e execute `DARKVIWS-Setup-1.0.0.exe`.

O GitHub não mostra um botão “Instalar” diretamente na página do workflow. O instalador é baixado como artifact ZIP e executado localmente.

A cada commit em `main`, o GitHub Actions compila o instalador NSIS em um runner Windows. O computador que instalar o aplicativo não precisa ter Node.js nem usar PowerShell.

Esta versão inicial ainda não inclui geração de vídeo/voz por IA e precisa de integração posterior para essas funções.
