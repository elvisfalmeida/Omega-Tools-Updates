# Omega Tools Updates

Repositório público de distribuição do **Omega Tools**.

Este repositório contém apenas:

- `version.json` (manifesto de atualização)
- Releases com o binário `Omega_Tools.exe`

> O código-fonte permanece no repositório privado.

## Como funciona

O aplicativo consulta este repositório para:

1. Verificar nova versão via `version.json`
2. Baixar o executável da release correspondente

## Estrutura esperada

- `version.json`
- Releases `vX.Y.Z` com o arquivo `Omega_Tools.exe`

## Exemplo de version.json

```json
{
  "version": "1.1.3",
  "download_url": "https://github.com/elvisfalmeida/Omega-Tools-Updates/releases/download/v1.1.3/Omega_Tools.exe",
  "changelog": "Correções de estabilidade no updater, melhorias visuais e ajuste do fluxo de validação de Java."
}
