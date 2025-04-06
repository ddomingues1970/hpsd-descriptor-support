# HPE Service Director Descriptors

Este plugin fornece realce de sintaxe e suporte básico para arquivos `.dsd`, `.hds`, `.dsc`, `.svc`, `.knd`, `.tpl`, `.hpsd` e `.yaml` utilizados no HPE Service Director (HPSD/HEAT).

## Recursos

- **Realce de Sintaxe**: Suporte para os seguintes tipos de arquivo:
  - `.dsd` (Dynamic Service Descriptor)
  - `.hds`
  - `.dsc`
  - `.svc`
  - `.knd`
  - `.tpl`
  - `.hpsd`
  - `.yaml`

- **Snippets**: Trechos de código pré-definidos para facilitar a escrita e reduzir erros comuns.

- **Configuração de Linguagem**: Definições específicas para comentários, pares de fechamento automático e colchetes correspondentes.

## Instalação

1. **Empacotamento**: No diretório raiz do projeto, execute:
   ```bash
   vsce package
   code --install-extension hpsd-descriptor-support-0.0.1.vsix

